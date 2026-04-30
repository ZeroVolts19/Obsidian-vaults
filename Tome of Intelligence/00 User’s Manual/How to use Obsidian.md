# Introduction to Obsidian

An Obsidian Vault is well organized when

1. Adding new information takes very little time
2. Finding the right information when you need it takes as little time as possible.

Obsidian is very well-equipped for information storage and retrieval.

Within Obsidian, there are three primary ways to organize your information:

- Storing files in certain folders
- Using links
- Using tags

Some people prefer to only use one of the three, or they opt to specifically avoid tags for instance. For most people, the best approach is to use a mix of the three.

## Storing information

### Links are meant to represent _relationships_ between two things

Take a meeting for example, in a meeting you have people who're attending, you have previous and following meetings, etc.

Who's present in this meeting? `[[people/legal/Jane]]`, `[[people/teachers/Damian]]`, ..

When was my last meeting? `[[meetings/meeting-about-...-27-08-2023]]`.

### Folders organize things that strictly belong together

Images are images, store images in a folder named `/img`, not in your base folder. People are always people regardless of who they are or what they do, store them in `/people`. Same goes for organizations, projects, topics, whatever makes sense for your work.

Here's an example of what a vault's folder structure can look like:

- **_meta** (used to store files and information "about" Obsidian)
- **_meta/img** all images that were pasted into the vault
- **@person** one note per person
- **Books** one note per book
- Daily notes
- **Projects** One folder per project
- **Projects/project-name** One primary note per project and other related stuff all goes in this folder

## Tags are for everything else

Tags are useful for many things. One obvious use-case is to group related things. For instance, Jane is from Legal, a meeting is about revising our teacher contracts and "that random thought I had" that I put in my daily notes is also about "legal".

They're all "about" legal, so you can tag all of them with `#legal`.

Here are some examples of tags that can be useful

- project
- project/PROJECT_NAME (a link could work equally well here)
- software-engineering
- philosophy
- biology
- psychology
- article
- video
- tweet
- thought
- idea
- status:read
- status:unread
- important
- later

As you can see most of them are strictly for grouping information into a certain bin.

However, there are some more at the end. Tags can be used as a kind of mark of importance: `#important`, `#not-important`; as a status `#status-read`, `#status-unread`; as a way to inform your behavior in the future: `#to-read`

### Combine them!

Of course, when actually working in your vault you won't be using either of the three exclusively. It's better to over-use than to under-use them!

A daily note can look like

> # Today

> #legal #status-unread #article maybe tell [[@person/legal/Jane]] about this? [relevant article](https://legal-site.cool/relevant-article)

In text this doesn't look amazing, but Obsidian will make it look readable :)

---

Links, folders and tags are the basis of your organization; links for relationships, folders to enforce a structure and tags to add fluid relationships.

## Retrieving information

Of course you won't spend all day "storing" information in your vault, because then you wouldn't be doing any _actual_ work.

By using links, folders and notes while writing notes you've made many paths you can traverse to go from one starting point to the next.

If you need to refer to a certain meeting, you can find the meeting in the meetings folder. Looking for a person? Go to the people folder. Looking for all meeting with that one person in 2021? Well... uhm..

That's where search comes in. Obsidian has a very powerful built-in search tool. Just press CTRL-SHIFT-F (or equivalent on Mac) or find the search icon in your left sidebar.

Here you can type in search terms. Type in text and Obsidian will look through all of your files to find the text you looked for. You can go further though with specific "queries". This is how we're going to find those meetings in 2021.

Okay. So, who's that person? Jane. Alright. When? 2021. Alright. What kind of notes are we looking for? Meetings.

Obsidian's search lets you look for patterns in files. For instance you can say "find all files with this tag". Or, "find all files in this folder". "Find all files with this text". And more importantly, it lets you combine them so you can ask specific questions such as "Find all meetings in 2021 where Jane was present".

How? Easy! Just use the right keywords in your search, Obsidian will show most available keywords as you are searching. Here are the previous questions reformulated using Obsidian's search tool

- Find all files with this tag: `tag:Legal`
- Find all files in this folder: `path:meetings/`
- Find all files with this text: `my text`
- Find all meetings in 2021 where Jane was present: `path:meetings file:2021 [[people/legal/jane]]`

Refer to the [Obsidian search help article](https://help.obsidian.md/Plugins/Search) to learn more about search. For most use-cases I find search to be sufficient. If you ever feel the need to create even more intricate search patterns you can look into the [Obsidian Dataview plugin](https://github.com/blacksmithgu/obsidian-dataview).

## Synthesizing information

Synthesizing information is a combination of retrieval and storage. You'll be searching and navigating through your vault while taking notes. Again, Obsidian gives you multiple tools here.

Of course, you can create a note to work in. Obsidian also offers an additional really useful tool that can aid in synthesis: the canvas! This is basically a whiteboard, useful for larger projects, work where you have to reference many different related articles, etc.

The canvas allows you to work on a whiteboard-like space. You can create cards, group cards, you can put existing notes on the canvas, you can add images and even websites and videos. The visual workspace of the canvas is a nice alternative perspective to the one-dimensional nature of the text-based note.

Besides that, use Obsidian's UI to your advantage. You can split the workspace vertically or horizontally to have multiple notes open at the same time, you can use tabs in a similar way as your browser.

## Learning Obsidian

This post mostly outlined guiding principles with which you can achieve your work. Of course Obsidian is a tool and a complex one at that. Not only is it a tool, it's a toolbox filled with tools many of which are meant to solve similar problems.

This post doesn't help you "use" Obsidian to its fullest potential. Only time can do that.

The best way to learn obsidian is to start using it for what you want to achieve and learn as you go. With this approach it's important to know where to go if you don't know something:

- Play with the UI, hover over icons to see their names. Click on things to see what happens
- Press ctrl+shift+p to open the command palette, this shows **all** commands available in Obsidian, including ones installed by plugins
- The [ObsidianMD reddit community](https://reddit.com/r/ObsidianMD)
- [The official Obsidian documentation](https://help.obsidian.md/)
- [The official Obsidian forum](https://forum.obsidian.md/)

When you see an advanced user use Obsidian, their vault might look unrecognizable to you. It's almost always pointless to try and emulate someone else's vault. Your vault reflects your life and goals in one way or another, and therefore its structure will differ depending on your preferred way to do things.

Your vault will grow with use, whenever you hit a wall you can read the documentation, go through the settings, ask for help or even look through the plugins page to see if there's something specific out there to solve your problem.

Over time your vault's structure will expand, you will have modified your theme and you are using your specific set of Plugins. Now you are one of those people newcomers are looking at to emulate :)

## Recommended plugins to start with

- Calendar
- Find a theme that you like, makes your vault feel "yours"
- Kanban if post-its feel like second nature to you
- I strongly recommend paying for Obsidian Sync if you use Obsidian on multiple computers
- Excalidraw is a painting/drawing application that you can also use within your Obsidian vault. Useful for sketches, literal whiteboarding and more.
- Homepage lets you set one note to show every time you open up Obsidian. I really like this one.

More advanced:

- Periodic notes is great if you need more structure than what the built-in daily notes plugin provides
- Obsidian dataview is for advanced to insanely advanced querying of your vault, most people use this but I recommend staying away from it until you find yourself hitting a wall with Obsidian search

Other:

- **Book search** is great if you read many books. It lets you find books via Google books and it creates a note with author, release date, ISBN and more. You can link to this note for book notes as well as to reference to books in other notes
- **Zotero** plugin for those using Zotero for reference management
- **Copilot** With ChatGPT's recent success everyone wants AI in Obsidian. Sometimes it's useful to let it criticize your writing, find grammar mistakes, summarize large pieces of text, etc. This can be very useful but might require some tinkering.