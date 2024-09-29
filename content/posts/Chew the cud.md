---
up: 
related: 
prev: 
down: 
aliases:
  - Information Architecture
AutoNoteMover: disable
created: 2024-04-04T14:29:39.000-04:00
id: e1e4ca48-df26-4fc1-add8-52646cc960db
tags: 
title: Chew the cud
updated: 2024-09-27T20:15:55.200-04:00
draft: true
---
  
# Chew the Cud  
  
## References  
  
We keep it simple here, theres no need for complex metadatafying, just the interconnected-ness of main sources/MOCs/related ideas is enough.  
  
#source/book in-line metadata:  
  
```  
up:: [[author (sources/people)]]  
status:: #state/process, #source  
down: : [[MOCs]], [[related note or type/hole note]]  
```  
  
#source/video in-line metadata:  
  
```  
up:: [[author, youtuber (sources/people)]]  
status:: #state/process, #source  
down: : [[MOCs]], [[related note or type/hole note]]  
```  
  
the `next` and `previous` can be used in the inline-metadata if the note is part of a series of notes, perhaps subsequent notes from a course or anything that has structure.  
  
## A Bit about the Tagging Method  
  
> Tags are doors and links are corridors. Tags are how you enter a building, and links are how you navigate around once you're in. So you'll in general have few tags and not every note will have a tag. But you'll want many links. [^1]  
  
> Tags are an easy way to relate heterogeneous items, but they’re quite a low-signal way of describing relationships. [^2]  
  
Keeping [Karl Voit's Tagging Rules](../../Karl%20Voit's%20Tagging%20Rules.md) in mind: Ontology of the Various Note Types and States.  
  
| Purpose                                                                                                                                                                                                                                                                     | Tag                |  
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |  
| Seed Idea - Initial thoughts or questions, basically a fleeting note                                                                                                                                                                                                        | `state/seeds`      |  
| In Process - Ideas being actively developed (rely on a project, MOC note type) require further exploration, research, or contemplation before deciding whether to actively develop them or move them to the incubating state; ultimate goal is to make them permanent notes | `state/process`    |  
| State Reference Materials - Supporting information and data, this tag is not that serious its really just a parent tag for the references(which includes anything meant for cold storage, everything is a reference to _something_)                                         | `source`           |  
| State Incubating - Ideas that are temporarily dormant but have potential for future growth(into permanent notes). This generally happens after a periodic review, previous states are usually state/process or type/holes; may revisit them later.                          | `state/incubating` |  
| Project - Notes associated with specific projects or actionable goals or anything that is being developed in the [Now](../../Now.md)                                                                                                                                 | `projects`         |  
| Reference Type Video                                                                                                                                                                                                                                                        | `sources/videos`   |  
| Reference Type Article                                                                                                                                                                                                                                                      | `sources/articles` |  
| Reference Type Quotes                                                                                                                                                                                                                                                       | `sources/quotes`   |  
| Reference Type People                                                                                                                                                                                                                                                       | `sources/people`   |  
| Reference Type Podcasts                                                                                                                                                                                                                                                     | `sources/podcasts` |  
| Reference Type Books                                                                                                                                                                                                                                                        | `sources/books`    |  
| Reference Type Poetry                                                                                                                                                                                                                                                       | `sources/poetry`   |  
| Reference Type Tweets                                                                                                                                                                                                                                                       | `sources/tweet`    |  
| Permanent Note - Well-developed, interconnected ideas                                                                                                                                                                                                                       | `type/Ref`         |  
| Rabbit hole - Ideas that pique curiosity and allows of going down the rabbit hole                                                                                                                                                                                           | `type/holes`       |  
| MOCs Note Type - Don’t feel shy, have as many topic notes as you want.                                                                                                                                                                                                      | `type/MOCs`        |  
| Journal Note Type                                                                                                                                                                                                                                                           | `type/journals`    |  
| Private Note Type                                                                                                                                                                                                                                                           | `type/private`     |  
| Devlog Note Type                                                                                                                                                                                                                                                            | `type/devlog`      |  
  
## How Do I Use This?  
  
- ==All notes are relative to me==: All notes are primarily written for my own use, capturing what I know about a topic.  
- In the interest of time, I avoid over-explaining in my notes unless necessary, since these notes serve my personal understanding and relate to my existing knowledge of the subject.  
- There may be times when I choose not to document certain information if it's already part of my mental framework and doesn't require explicit noting; I may revisit and potentially add this previously omitted information at my discretion.  
- **“Strong opinions, loosely held”** — Opinions are fine as long as I have strong epistemic confidence in the given opinion.[^3]  
- ==Gotta capture 'em all==: Hog whatever information tickles your pickle([anything that gratifies one's intellectual curiosity](https://news.ycombinator.com/newsguidelines.html)).  
- There's a subtle difference between References like books, articles, podcasts, and videos, and what I call Swipes. Swipes are pithy or valuable snippets of information, like `#quotes` (which I've recently begun to compile in the extensive [All Quotes](../../All%20Quotes.md) note), `#excerpts`, `#sayings`, and `#phrases`. They are essentially ideas or opinions I've picked up from various `#people`.  
- Make no distinction between "your" ideas and ideas of "others"; if you vibe(resonate) with an idea; it's already yours ([Steal Like an Artist](../../Steal%20Like%20an%20Artist.md)).  
- But also remember **"If you've time to consume, you've time to produce."**.  
- ==Don't force evolution==: Let your second brain evolve at it's own pace.  
- The structure should never be _too_ rigid because its meant to take form by itself.  
- ==Noise to signal==: While capturing ideas left and right is recommended, make sure you're not harming your periods of focus.  
- Have impenetrable focus periods where you only care about the work at hand and nothing else.  
- ==Why do any of this?==: Given that I can't remember everything; there's a lot of information around that interests me and there isn't enough working memory installed in me.  
- Thus, I make notes — _**to remember, to create, to meditate(reflect), to ponder**_.  
- A bodybuilder's portfolio is their body - my portfolio is my wiki (an egoistical notion but I’ll allow it).  
- By taking notes on what I learn or come across, I'm not just materializing this knowledge; I know exactly where to look for forgotten information as I have tangible references to it.  
- I am at the beginning of my learning adventures. When I look back at it, I will know where I came from and how my thoughts evolved over time.  
- Plus, its really fun to nerd out.  
  
## High Level Overview  
  
The folder structure of my notes means little to me as I prefer to use tags over traditional folder structures (tags also enable backwards compatibility). I categorize my notes using three main classifications:  
  
**First Classification**: This pertains to their role within my Personal Knowledge Management (PKM) system, essentially indicating the 'physical' folder where they are stored, although this is more a technicality since I use an Auto Note Mover plugin to organize notes based on this classification. Tags like source, indexes(or state/permanent), initiative, journals, state/archived are used here, which aligns with the PARA method.  
  
States reflects a note’s current state which in turn informs my epistemic confidence in the ideas they contain. This helps me gauge how well I understand the concept, my feelings towards it, and its development stage.  
  
**Second Classification**: Each note is placed within a hierarchy, showing its relation to other notes and linking back to a central topic or Map of Concept (MOC) note. To connect a note with its main topic, I use inline metadata `up:: [[<topic>]]` format.  
  
The indexes function as gateways or portals; they are essentially notes that highlight a particular area of interest or research topic. Topics are essentially **Map of Concept** or an **Area of Interest/Responsibility** note. [^4] ==While all topics are permanent notes, not all permanent notes are topics==. I prefer to elevate a topic to a permanent note after evaluating its significance, its completeness, rather than assigning it by default.  
  
I've recently recognized the value in organizing topics in a manner similar to [Nikita Voloboev's](https://wiki.nikiv.dev/) approach, albeit with heavy usage of transclusion and back-linking.  
  
Reference notes serve as reference points and can be assigned various states, such as `#state/process` or `#source`, depending on their developmental stage. These references notes can evolve into or have their content be transmuted to their designated permanent/topic note; which is essentially a summary of your understanding, crafted in your own words, and typically derived from literature notes.  
  
Reference notes are further organized by type, with each note tagged as `source` in addition to its specific type. The types can include `sources/videos`, `sources/articles` etc.  
  
Additionally, I use the devlog tag for notes related to technology, inspired by [Bryan Jenks](https://www.bryanjenks.dev/)  
  
A notes tagged with `#state/seed`, `#state/question` captures spontaneous thoughts or ideas. These can be expanded upon later using references like books, eventually transforming into literature notes. These are essentially fleeting notes.  
  
Notes in the `#state/archived` are in 'cold storage'. They're available when needed but aren't scheduled for regular review. These are notes with fewer connections, often just one ('orphan notes'). These could include facts or 'Today I Learned' (TIL) and tidbits of information and may or may not always be linked to a specific topic.  
  
I maintain an inbox folder connected to my Telegram bot, primarily used for collecting various items such as tweets, quotes, vocabulary, and more. This folder serves as an initial sorting ground. By default, all items that land in the Inbox are considered unqualified references awaiting evaluation and categorization. They stay in the inbox until I find the time and opportunity to review and organize them.  
  
My objective is to decrease inbox clutter by concentrating on utilizing existing reference notes, such as books, courses, and articles, into permanent notes. Instead of continually accumulating more information in my inbox, my ultimate goal is to make or improve permanent notes from existing references.  
  
type/incubating needs to be processed: compiling the reflective questions and actually reflecting. The ghost backlinks can also be used to go down rabbit holes. The state can change to permanent note once its processed when it is processed. I think rabbit holes and state question are quite related.  
  
The “Reflective questions” are supposed to be prompts and the genAI ones that can be found in some state inprocess notes are just to get me going can often become seeds and of course they have to be personally reflective, they need to be reflected upon in perhaps your journals and they can be part of [Shadow Work Progress](Shadow%20Work%20Progress.md) project too.  
  
While I have retired the note type archive(type/arhive) over the combination of "source" tag, along with the various "sources/" tags, serves as a cold storage for notes that may not be actively relevant but still valuable for future reference. There could be various refTypes or I could cheat and create a generic references.  
  
state incubating are ideas that you are not actively processing, the ideas that are stale in the hierarchy of things you’re actively working on. Say a course, a project, for example learning about [ADHD](../../ADHD.md) by doing a course on it would keep on giving notes to process but if you’ve moved on from the course, you could make them into state incubating as this will help you review the notes on a regular basis and you don’t need a separate tag to identify the ones to to review and you’d have a consolidated view with the process tag alone. Of course the state/project tag is adhoc and these notes are tracked in the [Now](../../Now.md) and there can never be more than \_\_ (need to decide a good number of projects one can actively work on). ==These can be MOCs or even a Rabbit hole note if its decidedly worthy :).==  
  
the "seed" state is the starting point for new ideas, capturing initial thoughts, questions, and inspirations that have not yet been actively processed. Seed notes can often originate from the reflective questions generated during the processing of notes in the "in process" state. These questions serve as prompts for further exploration and can be captured as seed notes for future development. Or they can also be discarded as fleeting notes(no hard feelings).  
  
The state/hole - "Rabbit hole" note type represents ideas or questions that have captured my interest and invites further exploration, or contemplation before deciding whether to actively develop them(proceeds state/process) or move them to the incubating state. They should really be referencing existing ideas, concepts, any kind of phenomenon, occurrence that has been discovered, discussed.  
  
There could be the aspect of gamification with the integration of Habitica task/reward flow. Reward for promoting inprocess notes to other states.  
  
All MOCs are permanent notes but not all permanent notes are MOCs, MOC tag is assigned to create more distinction its mostly utility purpose than about the methodology.  
  
I have:  
  
- Maps  
- Efforts  
  - Projects  
- Eggs - view to quickly intake Eggs, Thoughts, Ideas  
- Incubating - prompted growth of an egg, source/lit note  
- Insights - final churned wisdom, permanent note  
  
## Note Types  
  
## Complimentary Tools  
  
- [NattyNote: Take time-stamped YouTube notes](https://github.com/ahmedelq/NattyNote)  
- [calibre - E-book management](https://calibre-ebook.com/)  
- [KOReader](https://koreader.rocks/)  
- [Omnivore.app](https://omnivore.app/)  
- [Raindrop.io — All-in-one bookmark manager](https://raindrop.io/)  
- [markdownload: A browser extension to clip websites and download them into a readable markdown file.](https://github.com/deathau/markdownload)  
- [send-to-telegram: A browser extension to send selected text, link, and images on web pages to Telegram via Telegram Bot API.](https://github.com/ridvan/send-to-telegram)  
- [obsidian-telegram-sync: Transfer messages and files from Telegram to Obsidian](https://github.com/soberhacker/obsidian-telegram-sync)  
- [ActivityWatch - Open-source time tracker](https://activitywatch.net/)  
  
---  
  
# Zettelkasten Information Model  
  
## General Note Structure  
  
All notes will have the following basic structure in their YAML frontmatter:  
  
```yaml  
---  
fileClass: [class name]  
up:  
related:  
prev:  
down:  
created: YYYY-MM-DD  
updated: YYYY-MM-DD  
tags:  
  - type/[actual-type]  
  - [additional-tags]  
---  
```  
  
## Note Types and Their Structures  
  
1. Fleeting Note 2. Literature Note (Incubating) 3. Permanent Note (Insight)  
  
```yaml  
---  
fileClass: note  
up:  
related:  
prev:  
down:  
created: YYYY-MM-DD  
updated: YYYY-MM-DD  
tags:  
  - [type/fleeting, type/insight, type/incubating, type/source, type/MOC, type/calendar, type/definition, type/effort, type/initiative]  
---  
```  
  
1. Source Note (Eg: Book)  
  
```yaml  
---  
fileClass: book  
up:  
related:  
prev:  
down:  
id: {{DATE:YYYYMMDDHHmmss}}  
title: "{{title}}"  
subtitle: "{{subtitle}}"  
author: "[[<%= book.authors.map(author => author.split(' ').map(word => word.charAt(0).toUpperCase() + word.slice(1).toLowerCase()).join(' ')).join(', ') %>]]"  
cover: "{{coverUrl}}"  
isbn: "{{isbn10}} {{isbn13}}"  
publisher: "{{publisher}}"  
publish: "{{publishDate}}"  
publishYear: "{{publishDate}}"  
total: 0  
created: {{DATE:YYYY-MM-DDTHH:mm:ss.SSSZ}}  
updated:  
started: {{DATE:YYYY-MM-DD}}  
finished:  
genres: "[[{{categories}}]]"  
status: queue  
rate:  
volume: {{totalPage}}  
timestamp: 0  
units: pages  
tags:  
  - type/source  
  - sources/books  
aliases:  
---  
```  
  
1. Effort  
  
```yaml  
---  
up:  
related:  
prev:  
down:  
title: {{VALUE:Effort Name}}  
fileClass: Effort  
description: {{VALUE:Effort Description}}  
type: {{VALUE:On,Ongoing,Simmering,Sleeping}}  
created: {{DATE:YYYY-MM-DD}}  
updated: {{DATE:YYYY-MM-DD}}  
rank: {{VALUE:1,2,3,4,5}}  
eol: false  
tags:  
  - type/effort  
---  
```  
  
1. Daily Note  
  
```yaml  
---  
fileClass: Calendar, Daily  
title: {{note_name}}  
created:  
updated:  
journal: {{ journal_name }}  
journal-start-date: {{ start_date:YYYY-MM-DD }}  
journal-end-date: {{ start_date:YYYY-MM-DD }}  
journal-section: day  
date: {{ start_date:YYYY-MM-DD }}  
tags:  
  - type/calendar  
  - Calendar/daily  
cssclasses:  
---  
```  
  
1. Initiative  
  
```yaml  
---  
title: {{VALUE:Initiative Name}}  
description: {{VALUE:Initiative Description}}  
fileClass: Initiative  
effort: {{VALUE:On,Ongoing,Simmering,Sleeping}}  
created: {{DATE:YYYY-MM-DD}}  
updated: {{DATE:YYYY-MM-DD}}  
dueDate: {{DATE:YYYY-MM-DD}}  
status: {{VALUE: 🟥 Backlog, 🟨 Active, 🟩 Finished}}  
eol: false  
tags:  
  - type/initiative  
---  
```  
  
1. Definition Note  
  
```yaml  
---  
fileClass: dfn  
up:  
related:  
prev:  
down:  
created: YYYY-MM-DD  
updated: YYYY-MM-DD  
def-type: [atomic,consolidated]  
aliases:  
tags:  
  - type/definition  
  - definition/atomic  
---  
```  
  
## Connections and Organization  
  
1. Use the `up`, `related`, `prev`, and `down` fields to create connections between notes.  
  
   - `up`: Link to broader topics or MOCs  
   - `related`: Link to related concepts or notes  
   - `prev`: Link to predecessors in a sequence of thoughts  
   - `down`: Link to more specific subtopics or examples  
  
2. Use `[[backlinks]]` within the content of notes to reference other notes, definitions, or MOCs.  
3. Create MOC (Map of Content) notes to organize and structure your knowledge areas.  
4. Use the `fileClass` field for categorization and to leverage the Metadata Menu plugin.  
5. Maintain a consistent tagging system using `type/[actual-type]` and additional tags as needed.  
  
## Workflow  
  
1. Capture fleeting notes quickly, using the fleeting note structure.  
2. Process fleeting notes into literature notes when reading or studying sources.  
3. Develop literature notes into permanent notes (insights), making connections to existing notes.  
4. Create and update MOCs to organize your permanent notes and provide entry points to your knowledge.  
5. Use daily notes for regular reflections and to capture new ideas.  
6. Create project notes for specific endeavors or areas of focus.  
7. Maintain definition notes for key terms, linking them to relevant permanent notes and MOCs.  
  
## Implementation in Obsidian  
  
1. Create templates for each note type with the predefined YAML structure.  
2. Use the Templater plugin to automatically fill in creation and update dates.  
3. Utilize the Metadata Menu plugin for easier management of the `fileClass` and other metadata fields.  
4. Set up Dataview queries to generate dynamic lists of notes based on `fileClass`, tags, or other metadata.  
5. Use the Graph View to visualize connections between notes based on the `up`, `related`, `prev`, and `down` links.  
6. Regularly review and update your MOCs to ensure your knowledge structure remains organized and accessible.  
  
# Zettelkasten Flow in Obsidian  
  
## Note Types and Their Roles  
  
1. **Fleeting Notes** (fileClass: note)  
  
   - Quick capture of ideas, thoughts, and observations  
   - Temporary by nature, waiting to be processed  
  
2. **Literature Notes** (fileClass: note)  
  
   - Processed notes from sources  
   - Contain key ideas, quotes, and your initial thoughts  
  
3. **Source Notes** (fileClass: note) + (fileClass: book, article, etc.)  
  
   - Reference materials  
   - Contain metadata about the source and your overall impressions  
  
4. **Insight Notes** (fileClass: note) + type/moc  
  
   - Well-developed, permanent notes  
   - Contain your own thoughts and connections  
  
5. **MOC Notes** (fileClass: note)  
  
   - Index notes that organize and structure your knowledge  
   - Each MOC has a corresponding Canvas file for visual organization  
  
6. **Definition Notes** (fileClass: definition)  
   - Concise explanations of key terms and concepts  
   - Can be individual files or consolidated for specific domains  
  
## Workflow  
  
1. **Capture**:  
  
   - Create Fleeting Notes to quickly capture ideas  
   - Use the fleeting note template with minimal metadata  
  
2. **Process Sources**:  
  
   - Create a Source Note for each book, article, or other reference  
   - While reading, create Literature Notes linked to the Source Note  
   - Use the `up` field in Literature Notes to link to the Source Note  
  
3. **Develop Insights**:  
  
   - Review and develop Literature Notes into Insight Notes  
   - Make connections using the `up`, `related`, `prev`, and `down` fields  
   - Link to Definition Notes for key terms using `[[backlinks]]`  
  
4. **Organize Knowledge**:  
  
   - Create and update MOC Notes to structure your knowledge  
   - Use the `up` field in Insight Notes to link to relevant MOCs  
   - Create corresponding Canvas files for visual organization  
  
5. **Define Terms**:  
  
   - Create individual Definition Notes for key concepts  
   - For domain-specific terms, use consolidated Definition Notes  
   - Link definitions to relevant Insight Notes and MOCs  
  
6. **Review and Refine**:  
   - Regularly review MOCs and update connections  
   - Process remaining Fleeting Notes into Literature or Insight Notes  
   - Update Canvas files to visualize and discover new connections  
  
## Tags Used  
  
#source/book  
  
## Example Flow  
  
1. While reading "Thinking, Fast and Slow" by Daniel Kahneman:  
  
   Create a Source Note:  
  
   ```yaml  
   ---  
   fileClass: book  
   up: "[[Psychology MOC]]"  
   related:  
   prev:  
   down:  
   author: "[[Daniel Kahneman]]"  
   year: 2011  
   isbn: 978-0374275631  
   publisher: Farrar, Straus and Giroux  
   total_pages: 499  
   created: 2023-09-23  
   updated: 2023-09-23  
   tags:  
     - type/source  
     - source/book  
   ---  
   # Thinking, Fast and Slow  
  
   [Your overall impressions and summary]  
   ```  
  
2. Create Literature Notes while reading:  
  
   ```yaml  
   ---  
   fileClass: literature  
   up: "[[Thinking, Fast and Slow]]"  
   related:  
   prev:  
   down:  
   source: "[[Thinking, Fast and Slow]]"  
   created: 2023-09-23  
   updated: 2023-09-23  
   tags:  
     - type/literature  
   ---  
  
   # System 1 and System 2  
  
   Kahneman introduces two systems of thinking:  
   - System 1: Fast, intuitive, and emotional  
   - System 2: Slower, more deliberative, and more logical  
  
   [Your notes and initial thoughts]  
   ```  
  
3. Develop an Insight Note:  
  
   ```yaml  
   ---  
   fileClass: insight  
   up: "[[Cognitive Psychology MOC]]"  
   related: "[[Decision Making]]", "[[Behavioral Economics]]"  
   prev: "[[Heuristics and Biases]]"  
   down: "[[Anchoring Effect]]", "[[Availability Heuristic]]"  
   created: 2023-09-24  
   updated: 2023-09-24  
   tags:  
     - type/permanent  
   ---  
  
   # Dual Process Theory in Decision Making  
  
   The concept of two systems in thinking, as proposed by [[Daniel Kahneman]] in [[Thinking, Fast and Slow]], offers a framework for understanding human decision making.  
  
   [[System 1]] operates automatically and quickly, with little or no effort and no sense of voluntary control. It's our intuitive, gut-reaction system.  
  
   [[System 2]] allocates attention to the effortful mental activities that demand it, including complex computations. It's often associated with the subjective experience of agency, choice, and concentration.  
  
   This dual-process theory helps explain various [[Cognitive Biases]] and decision-making phenomena…  
  
   [Your developed thoughts and connections]  
   ```  
  
4. Update or create an MOC:  
  
   ```yaml  
   ---  
   fileClass: moc  
   up: "[[Psychology MOC]]"  
   related: "[[Neuroscience MOC]]", "[[Philosophy of Mind MOC]]"  
   prev:  
   down: "[[Dual Process Theory]]", "[[Cognitive Biases]]", "[[Decision Making]]"  
   created: 2023-09-20  
   updated: 2023-09-24  
   tags:  
     - type/moc  
   ---  
  
   # Cognitive Psychology MOC  
  
   ## Core Concepts  
   - [[Dual Process Theory]]  
   - [[Cognitive Biases]]  
   - [[Decision Making]]  
  
   ## Key Thinkers  
   - [[Daniel Kahneman]]  
   - [[Amos Tversky]]  
  
   ## Important Studies  
   - [[Heuristics and Biases Program]]  
  
   [More structured links and brief descriptions]  
   ```  
  
5. Create or update Definition Notes:  
  
For a consolidated definition file:  
  
```yaml  
---  
fileClass: definition  
up: "[[Cognitive Psychology MOC]]"  
related: "[[System 1 and System 2]]"  
prev:  
down:  
created: 2023-09-24  
updated: 2023-09-24  
tags:  
  - type/definition  
def-type: consolidated  
---  
  
# Dual Process Theory  
  
*dual-process model, two-system theory*  
  
A psychological theory proposing two distinct systems of thinking: a fast, automatic, and intuitive system (System 1), and a slower, more deliberate, and analytical system (System 2). This theory is fundamental in understanding human cognition, decision making, and the formation of judgments.  
  
---  
  
# System 1  
  
*intuitive thinking, fast thinking*  
  
The cognitive process that operates automatically and quickly, with little or no effort and no sense of voluntary control. It's responsible for intuitive responses and gut reactions.  
  
---  
  
# System 2  
  
*analytical thinking, slow thinking*  
  
The cognitive process that allocates attention to effortful mental activities. It's associated with complex computations and the subjective experience of agency, choice, and concentration.  
  
```  
  
For an atomic definition file (e.g., "Dual Process Theory.md"):  
  
```yaml  
---  
fileClass: definition  
up: "[[Cognitive Psychology MOC]]"  
related: "[[System 1 and System 2]]"  
prev:  
down:  
created: 2023-09-24  
updated: 2023-09-24  
tags:  
  - type/definition  
def-type: atomic  
aliases:  
  - dual-process model  
  - two-system theory  
---  
A psychological theory proposing two distinct systems of thinking: a fast, automatic, and intuitive system (System 1), and a slower, more deliberate, and analytical system (System 2). This theory is fundamental in understanding human cognition, decision making, and the formation of judgments.  
```  
  
These structures now correctly incorporate the metadata required for the Note Definitions plugin:  
  
1. For consolidated files:  
  
   - The `def-type: consolidated` in the YAML frontmatter  
   - Each term is a level 1 header (#)  
   - Aliases are in italics on the line immediately following the header  
   - The definition follows, with multiple paragraphs if needed  
   - Definitions are separated by horizontal rules (---)  
  
2. For atomic files:  
   - The `def-type: atomic` in the YAML frontmatter  
   - Aliases are listed in the YAML frontmatter  
   - The entire content of the file (after the frontmatter) is the definition  
  
This approach allows you to use the Note Definitions plugin effectively within your Zettelkasten system, providing quick access to definitions while maintaining the connection to your broader knowledge structure through the `up`, `related`, `prev`, and `down` fields.  
In this flow, each note type plays a specific role:  
  
- Fleeting Notes capture initial ideas  
- Source Notes provide reference points  
- Literature Notes process source material  
- Insight Notes develop your own ideas  
- MOC Notes organize and structure your knowledge  
- Definition Notes clarify key concepts  
  
The connections between notes (using `up`, `related`, `prev`, `down`, and `[[backlinks]]`) create a rich network of ideas, allowing for easy navigation and discovery of relationships between concepts.  
  
This setup maintains the core principles of the Zettelkasten method while leveraging Obsidian's features for a digital implementation. It allows for flexible note-taking and organization while providing clear structures and connections between different types of information.  
  
## What Goes where  
  
folder structure  
  
type/litnote is same as type/incubating, they’re not exactly same but I don’t see a need for having another folder when anything WIP and anything which is a source/reference that needs to be processed stays in source it remains as a reference and not a litnote on your part. But it also depends what kind of content do you want to qualify as litnote and which remain source/reference. Most of my content is not directly a reference but they come from a source and most of these notes should remain in sources/misc for everything in state/process  
  
alright for now i will promote all of them to type/litnote but incubating i strictly want to use for my own bakings and not from whereelse but wouldnt that mean I am using fleeting notes? lets just fucking get rid off incubating. whats your problem with a name? the MOCs will later be ammended and all these files will have their rightful place in this wiki. But for time being all state/process should become type/incubating, you cannot have type/litnote, if you really cared about the source note then don’t use the source, you won’t ever be able to use a source if you cannot own it for yourself lol idk what i am writing bruh  
  
anyway.sd ds  
  
it literally means the same thing processing and incubating idk why I am making such a fuss about this thing. I will acknowledge its referenceness later.  
  
a task has to be time bounded otherwise the system is not going to filter it or I guess not for your daily note at least because the daily note only shows tasks with date, the “tasks” that don’t have a date, or are part of an initiative or an effort are not recurring in nature, they should be managed from a special place just for tasks without any dates  
  
Certainly! I'll walk you through a thorough example of how you might use the Obsidian Note Definitions plugin in your daily workflow, incorporating all of its features. Let's imagine you're a student studying biology and using Obsidian for note-taking.  
  
Day 1: Setting up the plugin  
  
1. Create a new folder called "Biology Definitions" in your Obsidian vault.  
2. Right-click on this folder and select "Set definition folder" to register it with the plugin.  
3. Create two files in this folder:  
   - "General Biology Terms.md" (for consolidated definitions)  
   - "Cell Structure.md" (for atomic definitions)  
  
4. Open "General Biology Terms.md" and use the command "Register consolidated definition file". This adds the frontmatter:  
   ```yaml  
   ---  
   def-type: consolidated  
   ---  
   ```  
  
5. Open "Cell Structure.md" and use the command "Register atomic definition file". This adds the frontmatter:  
   ```yaml  
   ---  
   def-type: atomic  
   ---  
   ```  
  
Day 2: Adding definitions during a lecture  
  
1. You're taking notes in a file called "Lecture: Introduction to Cell Biology.md".  
2. You encounter the term "mitochondria" and want to add a definition.  
3. Highlight the word "mitochondria" and use the "Add definition" command.  
4. In the pop-up, choose "General Biology Terms.md" as the target file.  
5. Enter the definition: "Organelles that generate most of the cell's supply of ATP (energy)."  
6. Add an alias: "powerhouse of the cell"  
  
The plugin adds this to "General Biology Terms.md":  
  
```markdown  
# Mitochondria  
*powerhouse of the cell*  
Organelles that generate most of the cell's supply of ATP (energy).  
---  
```  
  
1. Later in the lecture, you learn about the cell membrane. You decide to create an atomic definition for this.  
2. Create a new file "Cell Membrane.md" in your definitions folder.  
3. Use the "Register atomic definition file" command on this file.  
4. Add the content:  
    ```yaml  
    ---  
    def-type: atomic  
    aliases:  
      - plasma membrane  
      - cytoplasmic membrane  
    ---  
    The semipermeable membrane surrounding the cytoplasm of a cell, composed of a phospholipid bilayer with embedded proteins.  
    ```  
  
5. Use the "Refresh definitions" command to update the plugin's database.  
  
Day 3: Using definitions in your notes  
  
1. You're reviewing your notes and writing a summary in "Cell Biology Summary.md".  
2. As you type "mitochondria", you notice it's underlined, indicating a definition exists.  
3. Hover over the word to preview the definition.  
4. You want to add more detail, so you right-click and choose "Go to definition" to jump to the definition in "General Biology Terms.md".  
5. Edit the definition to add more information.  
6. Return to your summary and continue writing.  
7. You mention the cell membrane, and decide you want to use only cell-related definitions for this note.  
8. Use the "Add definition context" command and select "Cell Structure.md" and "Cell Membrane.md".  
9. This adds to your note's properties:  
   ```yaml  
   ---  
   def-context:  
     - Biology Definitions/Cell Structure.md  
     - Biology Definitions/Cell Membrane.md  
   ---  
   ```  
10. Now, only definitions from these files will be recognized in this note.  
  
Day 4: Expanding your definitions  
  
1. You're reading a paper and encounter the term "endoplasmic reticulum".  
2. You decide to add this as a new atomic definition.  
3. Create "Endoplasmic Reticulum.md" in your definitions folder and register it as an atomic definition file.  
4. Add the content:  
   ```yaml  
   ---  
   def-type: atomic  
   aliases:  
     - ER  
   ---  
   A network of membranous tubules within the cytoplasm of a eukaryotic cell, continuous with the nuclear membrane. It occurs in two forms: rough (with ribosomes) and smooth (without ribosomes).  
   ```  
5. Use the "Refresh definitions" command to update the plugin's database.  
  
Day 5: Reviewing and organizing  
  
1. Open your "General Biology Terms.md" file to review your consolidated definitions.  
2. Use markdown formatting to enhance your definitions, adding bold text, lists, or even links to other notes.  
3. Decide to move some definitions to atomic files for more detailed explanations.  
4. Create new atomic definition files as needed, and cut/paste content from the consolidated file.  
5. Update the "def-context" property in relevant notes to include or exclude specific definition files based on the topic of each note.  
  
By following this workflow, you're using all the main features of the plugin:  
- Creating and managing both consolidated and atomic definition files  
- Adding, editing, and viewing definitions  
- Using the editor menu and commands for easy access to definitions  
- Implementing definition contexts to customize which definitions are available in each note  
- Regularly refreshing the definitions to ensure all changes are recognized by the plugin  
  
This approach allows you to build a comprehensive, organized, and easily accessible personal dictionary within your Obsidian vault, enhancing your note-taking and study process.  
  
[^1]: [How to Use Tags](https://karl-voit.at/2022/01/29/How-to-Use-Tags/)  
[^2]: [Tags are an ineffective association structure](https://notes.andymatuschak.org/Tags_are_an_ineffective_association_structure)  
[^3]: “Allow your intuition to guide you to a conclusion, no matter how imperfect ― this is the ‘strong opinion’ part. Then –and this is the ‘weakly held’ part– prove yourself wrong. Engage in creative doubt. Look for information that doesn’t fit, or indicators that pointing in an entirely different direction. Eventually your intuition will kick in and a new hypothesis will emerge out of the rubble, ready to be ruthlessly torn apart once again. You will be surprised by how quickly the sequence of faulty forecasts will deliver you to a useful result.” [Strong Opinions, Weakly Held ― a framework for thinking | by Ameet Ranadive | Medium](https://medium.com/@ameet/strong-opinions-weakly-held-a-framework-for-thinking-6530d417e364)  
[^4]: [The PARA Method: The Simple System for Organizing Your Digital Life in Seconds](https://fortelabs.com/blog/para/)