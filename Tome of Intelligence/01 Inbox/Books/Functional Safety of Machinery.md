# Functional Safety of Machinery

![rw-book-cover](https://m.media-amazon.com/images/I/61ltb8R5eOL._SY160.jpg)

## Metadata
- Author:: [[Marco Tacchini]]
- Full Title: Functional Safety of Machinery
- Category: #books

## Highlights
#### Before You Start Reading this Book
#### 1 The Basics of Reliability Engineering
```text
"IEC 62061 uses the RBD method and it assumes the systems (Architectures) as non‐repairable. ISO 13849‐1 uses Markov Chains and it assumes the systems (Categories) as repairable; please refer to § 6.2.5. That seems a major difference that makes the two approaches irreconcilable. In reality that is not the case and the reason is that in high demand, normally, the safety control system is the ultimate safety layer: that is the assumption in both ISO 13849‐1 and IEC 62061. Where a safety‐related control system is working in high demand or in continuous mode, and it is the ultimate safety layer then, the overall safety‐related control system failure will lead directly to a potentially hazardous situation, regardless if it is considered repairable or non‐repairable. In case the safety‐related control system is the ultimate safety layer w(t) = f(t); that means:"
```
([Location 2072](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2072))


##### 1.11 Weibull Distribution
```text
"in Functional Safety, the failure rate of any component has to be constant:"
```
([Location 2095](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2095))


```text
"Please notice that when β = 1, the Weibull becomes the Exponential distribution,"
```
([Location 2110](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2110))


```text
"Manufacturers conduct production process control, production acceptance tests, “burn‐in,” or reliability stress screening (RSS) to prevent early failures before delivery to customers. Therefore, shape parameters of less than one indicate the following: lack of adequate process control; inadequate burn‐in or stress screening; production problems, dis‐assembly, poor quality control; overhaul problems; mixture of populations; run‐in or wear‐in. Many electronic components during their useful life show a decreasing instantaneous failure rate, thus featuring shape parameters less than 1. Preventive maintenance on such a component is not appropriate, as old parts are better than new."
```
([Location 2148](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2148))


```text
"Figure 1.42 Weibull and the bathtub."
```
([Location 2156](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2156))


- **Zettel:** THIS LIVES RENT FREE IN MY HEAD

```text
"1.11.4 The Mean Time to Failure"
```
([Location 2168](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2168))

- Tags: [[h4]] 


##### 1.12 B10D and the Importance of T
```text
"Once a Safety‐related block diagram has been defined, for each safety‐related system, the technique used to calculate the probability of hardware failure is based upon specific Markovian formulae obtained from Taylor’s series and slightly conservative underlying hypotheses, among which a constant failure rate"
```
([Location 2227](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2227))


```text
"B10Dis the mean number of cycles until 10% of the components failed dangerously and is used for components having mechanical wear."
```
([Location 2246](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2246))


```text
"Linked to B10 is the number of operations a component does in a year: n"
```
([Location 2255](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2255))


```text
"1.12.2 How λD and MTTFD are Derived from B"
```
([Location 2282](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2282))

- Tags: [[h4]] 


```text
"B10Dis used to indicate the Reliability of components that do not have a constant failure rate."
```
([Location 2286](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2286))


```text
"the usage of the component will be limited to when it reaches the B10Dnumber of operation"
```
([Location 2290](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2290))


```text
"Therefore, the following is the formula to be used to calculate the MTTFD from B10D: [Equation 1.12.2]"
```
([Location 2314](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2314))


```text
"1.12.3 The Importance of the Parameter T"
```
([Location 2318](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2318))

- Tags: [[h4]] 


```text
"If a component has a B10D, that means its failure rate is not constant over time. The B10D was chosen not by chance! It can be demonstrated that by limiting the product life to T10D, there is no significant error in the estimation of the PFHD by assuming a constant failure rate, compared to the use of a Weibull distribution."
```
([Location 2319](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2319))


#### 2 What is Functional Safety
```text
"In the 1990s, IEC started writing what later became the IEC 61508 [4] series of standards that officially defined the term Functional Safety. Since IEC 61508 series only consider electrical/electronic/programmable electronic (E/E/PE) safety‐related systems, this is its definition of Functional Safety."
```
([Location 2564](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2564))


```text
"[IEC 61508‐4] 3 Definitions and abbreviations 3.1.12 Functional Safety. Part of the overall safety relating to the EUC and the EUC control system that depends on the correct functioning of the E/E/PE safety‐related systems and other risk reduction measures"
```
([Location 2568](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2568))


```text
"However, Functional Safety can be achieved with other technologies, like Pneumatic or Hydraulic; therefore, this is another definition [1]: [Electropedia] Functional Safety: part of the overall safety that depends on functional and physical units operating correctly in response to their inputs"
```
([Location 2577](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=2577))


##### 2.4 CE Marking, OSHA Compliance, and Functional Safety
```text
"the “New Approach” was developed in 1985, which restricts the content of legislation to “essential requirements,” leaving the technical details to European harmonized standards."
```
([Location 3684](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3684))


```text
"not all goods require a CE marking to be considered safe. There are 27 European Directives that require a CE Mark."
```
([Location 3686](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3686))


```text
"The presence of the CE mark on a product means that it is safe to use."
```
([Location 3695](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3695))


```text
"The power of the CE marking is precisely that:"
```
([Location 3698](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3698))


```text
"by placing the CE mark on a product, the manufacturer is stating that the product complies with all the applicable EHSRs of all the applicable European Directives."
```
([Location 3698](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3698))


```text
"regulating the goods sold within the EEA since 1985."
```
([Location 3702](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3702))


```text
"Most Products that require a CE Mark do not need third‐party testing. For example, a circuit breaker can be sold in the European Market without having had any third‐party testing nor certification, since the Low Voltage Directive (2014/35/EU) does not require the involvement of notified bodies or third‐party laboratories."
```
([Location 3704](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3704))


```text
"For more information about CE Marking, please refer to the Blue Guide [49]."
```
([Location 3715](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3715))


```text
"For example, the PE cable (protection earth or grounding cable) was green in some European countries and yellow in others. CENELEC harmonized standards (for example, EN 60204‐1) states that the PE cable has to be GREEN‐AND‐YELLOW. That is an example of a compromise"
```
([Location 3726](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3726))


```text
"Type‐A standards or basis standards. They give the basic safety concepts, principles for design, and general aspects that can be applied to machinery. ISO 12100 is a Type A standard."
```
([Location 3750](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3750))

- Tags: [[favorite]] 


```text
"Type‐B standards or generic safety standards. They deal with one or more safety aspects or with one or more types of safeguards that can be used across a wide range of machinery: Type‐B1 standards deal with particular safety aspects: for example safety distances (ISO 13855), surface temperatures (ISO 13732‐x), and Functional Safety (ISO 13849‐1): they give indications, in the form of data or methodology, how those particular safety aspects can be addressed. Type‐B2 standards provide the performance requirements for the design and construction of particular safeguards: for example two‐hands controls (ISO 13851), interlocking devices (ISO 14119), pressure‐sensitive devices (ISO 13856‐x), and guards (ISO 14120). Type‐C standards They deal with detailed safety requirements for a particular machine or group of machines: for example Stationary Grinding Machines (ISO 16089)."
```
([Location 3752](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3752))


```text
"Basic Safety Publication (BSP). Publication on a specific safety‐related matter. A BSP is primarily intended for use by Technical Committees"
```
([Location 3762](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3762))


```text
"An Example is IEC 60446 (Basic and safety principles for man‐machine interface, marking and identification – Identification of conductors by colors or alphanumerics)"
```
([Location 3764](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3764))


```text
"IEC 61508‐1 [5] to ‐4 [8] are also BSP."
```
([Location 3766](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3766))


```text
"Group Safety Publication (GSP). Publications covering all safety aspects of a specific group of products within the scope of two or more product TCs."
```
([Location 3767](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3767))


```text
"Product Safety Standard. Standard covering all safety aspects of one or more products within the scope of a single product TC. Product includes equipment, software, installation, and service. IEC 62061 is an example of a product safety standard."
```
([Location 3770](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3770))


```text
"Both EN ISO 13849‐1 and EN IEC 62061 standards are harmonized to the Machinery Directive, and therefore they both give the presumption of conformity for the aspects they deal with. For example, compliance with one of the two standards gives a presumption of conformity to the EHSR (Essential Health and Safety Requirement) 1.2.1 stated by the Machinery Directive 2006/42/EC in annex I:"
```
([Location 3782](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3782))


```text
"That is the reason why Functional Safety is important for CE Marking."
```
([Location 3797](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3797))


```text
"2.4.4 Functional Safety in North America"
```
([Location 3800](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3800))

- Tags: [[h4]] 


```text
"The OSH Act places the responsibility on both the employer and the employee."
```
([Location 3805](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3805))


```text
"new machines, the US legal system (non‐regulatory, products liability) provides a strong incentive for machine builders to provide safeguarding."
```
([Location 3808](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3808))


```text
"manufacturers mainly refer to Technical Standards in order to design safe machinery, because the requirements are kept up to date."
```
([Location 3811](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3811))


```text
"ANSI B11 series of machinery safety standards and technical reports are the predominant and most important for machinery."
```
([Location 3813](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3813))


```text
"Hazard Control Hierarchy."
```
([Location 3816](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3816))


```text
"should be applied in the order of hierarchy as they appear below."
```
([Location 3817](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3817))


```text
"Control reliable. Control reliable safety circuitry shall be designed, constructed and applied such that any single component failure shall not prevent the stopping action of the robot."
```
([Location 3843](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3843))


```text
"The issue with the concepts described, like Control Reliable, is that there is no specific standard (Type B, in ISO language) that defines them: in other words, considering we are in the 1990s and early 2000s, there is nothing equivalent to EN 954‐1 in US voluntary or regulatory standards."
```
([Location 3852](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3852))


```text
"as familiarity and understanding of ISO 13849‐1 and IEC 62061 grows in North America, their voluntary consensus standards are beginning to informatively, and sometimes even normatively, reference those standards, not only in Canada but even in the United States."
```
([Location 3855](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3855))


```text
"2.4.4.2 Functional Safety in the United States"
```
([Location 3865](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3865))

- Tags: [[h5]] 


```text
"The B11 Functional Safety standard is ANSI B11.26 [47]. It is a Guideline for the Design of SCS using ISO 13849‐1."
```
([Location 3866](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3866))


```text
"Informative Note 3: Control reliability: is one of the design strategies that may be used to meet these requirements; cannot prevent a repeat cycle in the event of a major mechanical failure or in the presence of multiple simultaneous component failures; is not provided by simple redundancy; must have monitoring to confirm that redundancy is maintained."
```
([Location 3882](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3882))


```text
"complying with Category 3 or 4 and/or Performance Level “d” or “e”, at a minimum, will satisfy the requirements of control reliability."
```
([Location 3889](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3889))


```text
"The primary objectives of the 2018 edition of ANSI B11.26 standard"
```
([Location 3891](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3891))


```text
"The ANSI B11 series of (Type‐C) standards will reference ANSI B11.26, as they get revised."
```
([Location 3896](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3896))


```text
"It is also worth mentioning how OSHA is embracing ISO 13849‐1 and ISO 13849‐2 as the functional safety standard for Robots, as indicated in section IV, chapter 4"
```
([Location 3897](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3897))


```text
"A failure rate is typically represented by the lower case Greek letter lambda (λ), and it has units of inverse time."
```
([Location 3907](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3907))


- **Zettel:** Inverse time: the higher the value the shorter the duration

```text
"Please consider that if a component has a FIT of 1, that is not to say that the device has a lifetime of 1 billion years but rather that, if you have 1 million components running for 1000 hours, you can expect one failure due to random hardware failure issues."
```
([Location 3911](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3911))


```text
"According to IEC 61508, there are four types of Failures: Safe failures; Dangerous failures; No Effect failures; and No Part failures."
```
([Location 3913](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3913))


```text
"Prevents a safety function from operating when required (demand mode)"
```
([Location 3920](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3920))


```text
"causes a safety function to fail (continuous mode) such that the EUC is put into a hazardous or potentially hazardous state;"
```
([Location 3921](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3921))


```text
"3.6.8 Safe Failure. Failure of an element and/or subsystem and/or system that"
```
([Location 3924](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3924))


```text
"Results in the spurious operation of the safety function to put the EUC (or part thereof) into a safe state"
```
([Location 3926](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3926))


```text
"Increases the probability of the spurious operation of the safety function to put the EUC (or part thereof) into a safe state or"
```
([Location 3927](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3927))


```text
"is not relevant for the opening of the guard door safety function, and it has an influence only on the Availability of the machine. That means it is a no effect failure λNE, as previously defined, and not a safe failure."
```
([Location 3993](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=3993))


```text
"That means, also in this case, λS ≈ 0 and therefore SFF = DC. That reasoning is valid for the majority of electromechanical components. Those components would be defined as Type A, according"
```
([Location 4055](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=4055))


```text
"if you work in Machinery safety, you are used to the fact that the diagnostic coverage depends upon the way the component is cabled to the Logic Solver and the way the logic solver is programmed."
```
([Location 4276](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=4276))


```text
"Annex D “Failure modes of electrical/electronic components” of the previous edition of IEC 62061 was written to help in this aspect. The new edition of the standard has removed that approach and replaced it with the more pragmatic approach of ISO 13849‐1, detailed in its annex E."
```
([Location 4296](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=4296))


```text
"However, in case of a single electromechanical component, that has no electronics and therefore no possibility of self‐diagnostics, that is not possible, due to the lack of diagnostic coverage."
```
([Location 4307](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=4307))


```text
"When we analyze the Reliability of an input signal, we should look at two possible faults: the Sensor; and the connection between the Sensor and the Logic Solver."
```
([Location 4315](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=4315))


```text
"Moreover, Systematic failures should be considered for the connection between the sensor and the process."
```
([Location 4317](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=4317))


```text
"the use of 4–20 mA signal allows a certain amount of diagnostics, like component failure, to be communicated by driving the signal to out of range, as indicated in Figure 3.7. A German Standard called Namur NE43 recommends that values ≤3.6 mA or ≥21 mA be used to communicate a component failure."
```
([Location 4319](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=4319))


```text
"(Type B component)."
```
([Location 4327](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=4327))


```text
"The risks that cannot be eliminated, or reduced with Safeguarding, have to be managed by informing the operator: Instruction manuals, Awareness Means on the machine, Procedures, and Training can all be used for this purpose. This third step is defined as Information for use in ISO 12100 language or Administrative Controls in North American B11.19 or CSA Z432 language."
```
([Location 5919](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5919))


```text
"Often, the second step, Safeguarding, requires the implementation of a safety function."
```
([Location 5926](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5926))


```text
"In case the machine can be connected and somehow operated remotely, it is important to adopt precautions that prevent affecting the safety system and therefore creating a dangerous situation. Several standards deal with the subject: IEC 62443 series, ISO/TR 22100‐4 [40], and IEC/TR 63074."
```
([Location 5948](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5948))


```text
"[New Machinery Regulation] Annex III: 1.1.9. Protection against corruption The machinery or related product shall be designed and constructed so that the connection to it of another device, via any feature of the connected device itself or via any remote device that communicates with the machinery or related product does not lead to a hazardous situation."
```
([Location 5953](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5953))


```text
"In general, Risk Reduction happens through both Preventive measures, which reduce the frequency, and mitigating or Protective measures, which"
```
([Location 5970](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5970))


```text
"reduce the severity, as shown in Figure 4.2."
```
([Location 5972](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5972))


```text
"The operation of cutting trees in a forest is an example of a Preventive measure since it prevents fires to spread. On the other hand, a fire detector is an example of a Protective measure since it cannot reduce the frequency at which a fire occurs, but it can reduce the severity of consequences by initiating a sprinkler system."
```
([Location 5973](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5973))


```text
"Figure 4.2 The risk analysis as required by ISO 12100."
```
([Location 5976](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5976))


```text
"Preventive measures reduce the likelihood of a dangerous event, while protective measures reduce the severity of the damage."
```
([Location 5980](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5980))


```text
"The use of glycolic water in Forging Presses is another example of a preventive measure since it reduces the likelihood of fires."
```
([Location 5981](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5981))


```text
"The creation of a safeguarded space with an interlocked door can be seen as a protective measure; however, it only reduces the likelihood of the accident to happen and not the severity of the damage. For that reason, it is an example of a preventive and not of a protective measure."
```
([Location 5983](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5983))


```text
"The issue is that ISO 12100 has never made a distinction between Protective and Preventive Measures and that generated confusion during the risk reduction process, whereby a safeguarded space reduced the severity of the damage, which is not correct. Experts in ISO/TC 199 technical committees are now using the term Risk Reduction Measures instead of Protective Measures in order to eliminate possible ambiguities."
```
([Location 5994](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5994))


```text
"used in the new edition of ISO 12100 as well as in this book. Risk Reduction Measures are means to eliminate hazards or reduce risks."
```
([Location 5997](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5997))


```text
"Therefore, glycolic water in Forging Presses is a type of Risk Reduction by Inherently Safe Design, while a safeguarded space with an interlocked door is a type of Risk Reduction by Safeguarding."
```
([Location 5998](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=5998))


```text
"the damage in case it starts unexpectedly does not change,"
```
([Location 6001](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6001))


- **Zettel:** since the original risk reduction measure didn't reduce the severity anyways.

```text
"However, since the SCS that keeps the robot in a “Safety‐Related Stop” when a gate is open, has a low probability of failure, the likelihood that a person gets injured is reduced, even if it is not impossible."
```
([Location 6001](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6001))


```text
"Therefore, the use of an SCS reduces the probability of the event, but not its Severity. That is valid for most of the Risk Reduction Measures applied in Machinery Safety."
```
([Location 6003](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6003))


- **Zettel:** what are some exceptions can I come up with?

```text
"At the end of the Analysis, a Risk Evaluation has to be done,"
```
([Location 6010](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6010))


```text
"Functional Safety plays a role mainly in STEP 2 of the risk reduction activity."
```
([Location 6013](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6013))


```text
"every time I need to reduce a risk by using an SCS, I need to follow the prescriptions of one of the two Functional Safety Standards previously mentioned, supposing the safety loops operate in high‐demand mode. A similar approach is valid in the United States. Table 4.1"
```
([Location 6023](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6023))


```text
"When doing a risk assessment of Machinery, regardless of whether ISO 12100 or B11.0 is used, it is good to keep in mind the concept of the Naked Machinery. If you are assessing a machine that is already in operation, you need to imagine it without any safeguard."
```
([Location 6060](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6060))


```text
"for example, ask yourself the question: “How often do I need to open that guard?”. If it is once a day, then that guard is not correct since an interlocked guard needs to be installed. Without this approach, you would not have assessed the risk of that specific mechanical movement. That is clearly stated in an informative note of B11.0:"
```
([Location 6063](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6063))


```text
"The machine should not be considered harmless as shipped and guarded."
```
([Location 6071](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6071))


```text
"If a thorough risk assessment is delivered with the machine, it may be used as a starting point for the user's risk assessment."
```
([Location 6076](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6076))


```text
"The parts of the machinery control system that provide safety functions are defined by ISO 13849‐1 as SRP/CS, while IEC 62061 defines them as SCS."
```
([Location 6080](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6080))


```text
"Both standards decompose a Safety‐related part of the control System or SRP/CS into Subsystems,"
```
([Location 6101](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6101))


```text
"Both an SRP/CS and an SCS are the “physical” aspect of a Safety Function:"
```
([Location 6113](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6113))


```text
"a clear example is an AOPD that detects the entering of a person in a safeguarded area and stops a dangerous movement by de‐energizing a motor contactor."
```
([Location 6114](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6114))


```text
"This definition differs from ISO 12100 because this document addresses risk reduction performed by SCS."
```
([Location 6132](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6132))


```text
"Therefore, there are two levels: A Logical or Functional one: the Safety Function A Physical one: the SCS The equivalent of a subsystem for the safety function is a Sub‐function. [ISO 13849‐1] 3.1 Terms and definitions 3.1.28 Sub‐function. Part of a safety function whose failure results in a failure of the safety function. The approach of IEC 62061 in a graphical representation is shown in Figure 4.5."
```
([Location 6137](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=6137))


- **Zettel:** "functional channel" is an extremely common term in functional safety because its follows the points of failure outside of just hardware objects, but also logical aspects and objects too, and logic is essentially metaphysical.

```text
"As detailed in IEC 61508 series, everything starts with a proper activity plan, that includes how modifications to the safety system, once it has been validated, are made. That is organized in a Functional Safety Plan (FSP) that is detailed in annex I of IEC 62061 and annex G of ISO 13849‐1."
```
([Location 7539](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=7539))


```text
"modifications with an impact on the SCS should initiate a return to an appropriate design phase for its hardware and/or for its software, including the validation of the modified safety system. The Management of Changes is a key aspect of the FSP."
```
([Location 7556](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=7556))


```text
"Once I was told, by an engineer who designed a control panel with a 10 A contactor protected by a 100 A motor protection (self‐protected combination motor controller, in north American language), that the solution was acceptable, since the contactor status was monitored. His idea was: “if the contactor gets stuck, I immediately notice it and I can take immediate counter measures.” The monitoring of a Final Element is required in Architecture 1oo2D of IEC 62061, for example, or in Category 4 of ISO 13849‐1. That is needed in order to claim a certain level of Diagnostic Coverage (DC). However, if I do not properly protect the contactor (the final element) from short circuit or even overload, I cannot even claim that I designed a Safety Function, since it lacks a Basic Safety Principle."
```
([Location 7569](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=7569))


```text
"If Fault Masking takes place, the capability of the system to detect faults is limited or completely lost. When calculating the parameters in accordance with ISO 13849‐1 or IEC 62061, the effect of fault masking on the DC and therefore on the PL and SIL, must be taken into account. The implication is that the possibility of Fault Masking has a direct impact on the value of DC of the Safety Subsystem, and therefore it has an impact on the PL or SIL of the safety function."
```
([Location 7627](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=7627))


```text
"Note: the symbol ⇑ means that the contact B1.2 is shown in its actuated position: when the movable guard is closed,"
```
([Location 7650](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=7650))


```text
"Guard B1 is opened again and there is a fault on one of the interlock devices. Now, there are two undetected faults and the safety function is lost: therefore, when B1 opens, movements inside the area are not stopped."
```
([Location 7719](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=7719))


```text
"Annex A of ISO 13849‐1 contains a method that can be used for the determination of the PLr of a safety function performed by the SRP/CS. Annex A of IEC 62061 could also be used as an alternative. In general, any such method will show a variance because of the subjective nature of the evaluation criteria. The required performance level corresponds to the required risk reduction to be provided by the safety function: the greater the contribution to the risk reduction, the higher the required safety performance. The performance levels of safety functions are defined in terms of Average probability of dangerous failure per hour."
```
([Location 8936](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8936))


```text
"probabilistic approach"
```
([Location 8954](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8954))


```text
"One of the differences between EN 954‐1 and ISO 13849‐1 is that, in the former, the categories were associated to the entire SRP/CS, while in the latter, they are used to represent subsystems."
```
([Location 8955](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8955))


```text
"it is improper to describe an SRP/CS in terms of a Category: a safety system has a PFHD and a Performance Level (or a SIL, if IEC 62061 is used) but, necessarily, no Category (nor Architecture)."
```
([Location 8970](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8970))


```text
"In Chapter 4 of ISO 13849‐1, a new Figure 2 clarifies that ISO‐13849‐1, and that is valid for IEC 62061 as well, is applicable only when the risk reduction is achieved with the use of a safety‐related control system."
```
([Location 8973](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8973))


```text
"A new chapter 7 was added, to be read together with annex N, dealing with software development and how to avoid systematic failures in software. Please refer to § 5.6 of the book."
```
([Location 8979](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8979))


```text
"IEC 61511 has the concept of Management of Functional Safety."
```
([Location 8985](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8985))


```text
"A functional safety plan should be drawn up and documented for each SRP/CS design project and should be updated as necessary. Please refer to § 4.13.1 of the book."
```
([Location 8988](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8988))


```text
"The numerical quantification of the probability of failure of a subsystem can never be attained exactly, but only by approximation with the aid of statistical methods or other estimations are possible."
```
([Location 8991](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8991))

- Tags: [[favorite]] 


```text
"Any validated and recognized method can be used for this purpose. Such methods include reliability block diagrams (used in IEC 62061), fault tree analysis, Markov modeling (used in ISO 13849‐1) or Petri nets."
```
([Location 8993](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=8993))


```text
"they show a logical representation of the subsystem structure, which may differ from its physical one."
```
([Location 9014](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=9014))


```text
"not all parts are necessarily physically redundant but there are redundant means of assuring that a single fault cannot lead to the loss of the sub‐function."
```
([Location 9020](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=9020))


```text
"in mechanical devices with a single channel Architecture, the detection of faults by the control system may not be possible in certain situations, or its cost would be unjustifiable. However, it is important that all probable faults are evaluated by the interlocking device manufacturer"
```
([Location 9028](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=9028))


```text
"and that any dangerous failure mode is either eliminated or proven to be technically improbable"
```
([Location 9031](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=9031))


```text
"over‐dimensioning critical parts of the device and subsequently testing them."
```
([Location 9032](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=9032))


```text
"where mechanical faults are proved to be technically improbable, continued performance of the safety function in the presence of a single fault is assumed."
```
([Location 9035](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=9035))


```text
"Any such fault exclusions shall be justified and documented (see Note 2)."
```
([Location 9045](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=9045))


```text
"however, each category is applicable to a subsystem: either an Input subsystem or an output subsystem, for example. Therefore, do not be confused by the figure: it shows a subsystem and not necessarily a Safety‐related control system."
```
([Location 9113](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=9113))


```text
"In low demand mode, components are classified as Type A or Type B, and there are two different tables to be used to decide what is the maximum SIL that a Safety Subsystem can reach. In IEC 62061, one table only is defined for all types of components, and its content is similar to the one used for Type B components."
```
([Location 10787](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=10787))


```text
"according to ISO 13849‐1, it is possible to use a general purpose PLC to implement a Safety System: the maximum PL reachable is PL b. That is not allowed by IEC 62061, neither with a single channel (Architecture A) nor with a redundant channel without diagnostics (Architecture B). Please also refer to § 5.1.4.5."
```
([Location 10819](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=10819))


```text
"IEC 62061 uses the acronym PFH but that is exactly the same parameter as the PFHD used in ISO 13849‐1 (§ 4.5.1). The reason is to be in line with IEC 61508 series."
```
([Location 10902](https://readwise.io/to_kindle?action=open&asin=B0BY5WNGLN&location=10902))


