# Workflow copy & Chat GPT Conversation:
 https://chatgpt.com/share/6a407269-50dc-83ea-859e-2a30a7baeef3
## The overall workflow (ISO 13849-1)

The calculation is really three separate calculations.

```
          Safety Function

    Input SB
  (E-stop button)
        │
        ▼
    Logic SB
 (Safety Relay)
        │
        ▼
    Output SB
 (2 Contactors)

Step 1  Calculate each subsystem
        ↓
Step 2  Convert each subsystem to PFHd
        ↓
Step 3  Add the PFHd together
        ↓
Overall PFHd
        ↓
Determine PL
```

Notice something?

You **do not calculate the entire safety function directly.**

You calculate each **Subsystem (SB)** first.

---

## STEP 1 — Determine the architecture of each subsystem

ISO 13849-1 Clause 6

For your example:

### Input SB

Dual-channel E-stop

Category 3 or 4 depending on implementation.

Need:

- Architecture
    
- MTTFd
    
- DCavg
    
- CCF
    

---

### Logic SB

Safety relay UF6925

Manufacturer already states

- PL e
    
- Cat 4
    
- PFHd = 8.3E-11/hr
    

So...

**Done.**

Nothing else to calculate.

This is an encapsulated subsystem.

---

### Output SB

Two monitored contactors

Need to determine

Category 3 or 4

Need

- MTTFd
    
- DCavg
    
- CCF
    

---

## STEP 2 — Calculate MTTFd for Input and Output

ISO 13849-1 Annexes C and D

For electromechanical devices

Use

[  
MTTF_d=\frac{B10_d}{0.1 \times nop}  
]

where

[  
nop=  
\frac{\text{operations/year} \times years}{8760}  
]

(or use the ISO equations)

---

Example

E-stop

B10d = 100,000

Suppose

10 operations/day

250 days/year

20 years

Then

operations

 [  
10\times250\times20

50,000  
]

and ISO converts that into hours.

Eventually you obtain something like

MTTFd = 180 years

(or whatever the math gives.)

---

Do the exact same thing for the contactors.

---

## STEP 3 — Determine subsystem MTTFd

If there are multiple components

ISO Annex K

Use

 [  
\frac1{MTTF_{d,total}}

\sum  
\frac1{MTTF_{d,i}}  
]

This is just adding failure rates.

---

## STEP 4 — Determine DCavg

ISO Annex E

Input

Does the relay detect

- shorts?
    
- opens?
    
- discrepancy?
    

Maybe

DC = High

99%

or

Medium

depending on wiring.

---

Output

External Device Monitoring

(monitored NC contacts)

usually gives High DC.

---

## STEP 5 — Verify CCF

Annex F

Score

≥65 points

Done.

---

## STEP 6 — Determine subsystem PL/PFH

This is where people think there's an equation.

There isn't.

You use

Table 5

and

Figure 5

(or SISTEMA does it)

using

```
Category

MTTFd

DCavg

CCF
```

↓

Obtain

```
PFHd

PL
```

for that subsystem.

---

 At this point suppose you have

Input

PFHd

[  
2.0\times10^{-8}  
]

Logic

Manufacturer

[  
8.3\times10^{-11}  
]

Output

[  
5.0\times10^{-9}  
]

---

## STEP 7 — Add subsystem PFHd

THIS is the overall PFHd equation.

ISO 13849-1 Clause 6

 [  
PFH_D

PFH_{Input}  
+  
PFH_{Logic}  
+  
PFH_{Output}  
]

Literally just add them.

So

[  
2.0E-8  
+  
8.3E-11  
+  
5.0E-9  
]

=

[  
2.5083E-8  
]

---

## STEP 8 — Convert PFHd to PL

Use Table 3

|PFHd|PL|
|---|---|
|≥10⁻⁵|c|
|3×10⁻⁶|d|
|10⁻⁶–10⁻⁷|e|
|etc||

If

[  
PFHd=2.5\times10^{-8}  
]

then

PL e

---

 Notice something interesting

The safety relay contributes almost nothing.

Input

[  
2E-8  
]

Logic

[  
8E-11  
]

Output

[  
5E-9  
]

The relay contributes

less than half a percent.

This is extremely common.

Most PFHd comes from

- switches
    
- contactors
    
- valves
    

not from certified safety PLCs or safety relays.

---

 The standards map almost perfectly

|Step|ISO 13849-1 Section|
|---|---|
|Define safety function|Clause 4|
|Divide into subsystems|Clause 6|
|Determine Category|Clause 6|
|Calculate MTTFd|Annexes C & D|
|Determine DCavg|Annex E|
|Verify CCF|Annex F|
|Calculate subsystem PFHd|Clause 6, Figure 5, Table 5|
|Sum subsystem PFHd|Clause 6|
|Assign PL|Table 3|

 One thing I would add

Given the kinds of questions you've been asking lately (ISO 12100, block diagrams, SISTEMA modeling, encapsulated subsystems), I think the next logical exercise is to **work this exact E-stop example completely by hand**—without SISTEMA.

We'd start with your actual components (the E22 E-stop, DOLD UF6925 relay, and the two CWBS25 contactors), calculate the MTTFd for the input and output using realistic mission time and operation frequency, determine the subsystem PFH values, add them to the relay's published PFH of **8.3 × 10⁻¹¹/h**, and then compare our hand calculation to what SISTEMA reports. By the end, you'll understand what every number in the SISTEMA report means instead of treating it as a black box.

I think that's one of the best ways to become genuinely fluent with ISO 13849 rather than just proficient with the software.
# Desmos Calculations: 

![[Pasted image 20260627210219.png|479]] 
![[Pasted image 20260627210228.png|481]]


# Notebook 1-pager: 
![[Pasted image 20260627210326.png|697]]
# Safety BOM
![[Pasted image 20260627211245.png]]