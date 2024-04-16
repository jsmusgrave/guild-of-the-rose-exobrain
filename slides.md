---
# try also 'default' to start simple
# theme: seriph
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
## This is only used by default & seriph
background: ./img/chuttersnap-gKmpcDQWPmY-unsplash.jpg
# some information about your slides, markdown enabled
title: Welcome to Slidev
info: |
  ## Building an Exobrain
   Guild of the Rose

   More about [Guild of the Rose](https://guildoftherose.org/)
# apply any unocss classes to the current slide
# class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
# transition: slide-left
transition: fade-out
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
author: Jason Musgrave
# favicon: https://guildoftherose.org/images/logo/rose/seal/gold/circle/rose-192.png
favicon: ./img/gotr/gotr-icon.svg
#############
layout: intro-image
image: './img/wave.webp'
---

<!-- # Creating an ExoBrain -->
<!-- # (aka Second Brain) -->
<!-- * * * -->
<!-- What / Why / Hows -->


<div class="absolute top-10">
  <span class="font-700">
      {{ $slidev.configs.author }} / 2024-04-20
  </span>
</div>

<div class="absolute bottom-10">
  <h1>Creating an ExoBrain</h1>
  <p>What / Why / Hows</p>
</div>



---
transition: fade-out
---
# Meetup Format

- Business / Miscellaneous. (10 minutes)
- Workshop. (90 minutes)
- Collaborative debugging / socializing. (30 minutes)
- Post-meeting organizer evaluation. (10 minutes)

<br>
<br>
<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<!--
<style>
.slidev-layout li {
  font-size: 1.6rem
}
</style>
-->

<!--
Here is another comment.
-->

---
transition: fade-out
---
# Guild of the Rose Overview
<!-- <img src="/img/gotr-icon.svg" style="position: fixed; top: 10px; right: 10px; height: 10%" /> -->

- Founded in 2020 as the answer to community-oriented success engineering.
- Runs weekly workshops online and facilitates small “cohorts,” online meetup groups.
- Ongoing development of the skill tree.
<br>

<div class="flex justify-around  mt-4">
  <img src="/img/gotr/workshops.webp" class="w-1/4" />
  <img src="/img/gotr/skilltree.webp" class="w-1/4" />
</div>

<!--
<style>
.slidev-layout li {
  font-size: 1.4rem
}
</style>
-->

---
layout: two-cols-headers-jsm
---
# Guild of the Rose Overview

::left::

- Pragmatist
  - Development of practical skills.
  - Focus on results.
  - Rooted in instrumental rationality.
- Meditative
  - Self-understanding, self-expression.
  - The missing ingredient for holistic rationality.
- Empiricist
  - Performs experiments.
  - Scholarship and learning.
  - Rooted in epistemic rationality.

::right::

  <img src="/img/gotr/archetypes.webp" />


---
layout: two-cols-headers-jsm
---
# Guild of the Rose Overview

::left::
- Lead Empiricist
  - Take notes and give feedback on the meeting.
  - Craft procedural experiments, record the results.
  - Experimentation, evaluation, iteration.
- Chief Pragmatist
  - Keep things organized and on track.
  - Practical skills training.
  - Group debugging.

::right::
- Principal Meditative
  - See to the aesthetics, group dynamics, and comfort of the meeting.
  - Make Rose meetings a place you would want to bring a friend.

---
---
# Guild of the Rose Overview
- About the Guild
  - Contribution and service is linked to advancement. TBD.
  - Commitments are finite, time-bound, action specific.
  - Members are allowed (encouraged!) to lead their own projects or events under the aegis of the Guild of the Rose.
  - Culture of feedback with “commend-recommend-commend” format.

---
layout: intro-image-right
image: ./img/brain-making.webp
class: text-center
---

# What

---
layout: two-cols-headers-jsm
---
# What - Concepts

<!--
<style>
.slidev-layout li {
  font-size: 1.8rem
}
</style>
-->

::left::
- Inputs
- Inboxes
- Reviews (Retros)
- Weekly / Monthly / Yearly
- [Open Loops](https://gettingthingsdone.com/2011/10/gtd-best-practices-collect-part-1-of-5/)
- Mental Sweep
::right::
- Systems / Methodologies
- Tools
  - Calendar
  - Todo List
  - Notes

---
layout: intro-image-right
image: ./img/sweep-the-brain.webp
class: text-center
---
# Sweep The <s>Leg</s> Brain

---
layout: intro-image-right
image: ./img/why-doc.webp
class: text-center
---
# Why

--- 
---
 <!-- This one? -->
<!--
<style>
li:not(li li) {
  font-size: 2em !important;
}
</style>
-->
# Why
* Get Shit done
  * Define, Track, Organize and Do Tasks
* Organize and inputs
* Retain and expand on thoughts

---
layout: section
---

# What Again


---
layout: two-cols-headers-jsm
---
# System - PARA & CODE - (Tiago Forte BSB)
<style>
li {
  font-size: 2em !important;
}
</style>

::left::
* Project
* Area
* Resource
* Archive

::right::
* Capture
* Organize
* Distill
* Express


---
layout: image-right
image: ./img/horizons.webp
---

# GTD Horizons

* Ground: Current actions 
* Horizon 1: Current projects 
* Horizon 2: Areas of focus and accountability 
* Horizon 3: 1–2 year goals 
* Horizon 4: Long-term visions 
* Horizon 5: Life

---
---

# GTD 

* [Jump to Zen Flowchart](https://www.zenflowchart.com/guides/gtd-flowchart)

---
---
# What
* Calendar
* Task Manager
* Note Taking App



---
layout: intro-image-right
image: ./img/athletes.webp
class: text-center
---

# Best Athlete?

---
layout: two-cols-headers-jsm
---
# What - Systems
::left::
Tasky
* [GTD](https://gettingthingsdone.com)
* [Time Block Planner](https://www.amazon.com/Time-Block-Planner-Daily-Method-Distracted/dp/0593192052/)
* [Bullet Journal](https://bulletjournal.com/)
* [The Pomodoro Technique](https://www.pomodorotechnique.com/what-is-the-pomodoro-technique.php)
* [PARA](https://fortelabs.com/blog/para/) & [CODE](https://fortelabs.com/blog/how-to-organize-your-life-ali-abdaal/)
* [Kanban](https://en.wikipedia.org/wiki/Kanban_(development))

::right::

Notey
* [GTD](https://gettingthingsdone.com)
* [Zettelkasten & Linked PKM](http://amazon.com/How-Take-Smart-Notes-Nonfiction/dp/B09HSSFCPR/)
* [Robert Greene Note Cards](https://ryanholiday.net/the-notecard-system-the-key-for-remembering-organizing-and-using-everything-you-read/)

---
layout: two-cols-headers-jsm
---
# What - Task Management Tools (a short list)
::left::
* 🍎 Only
  * [Omnifocus](https://www.omnigroup.com/omnifocus/)
  * [Things](https://culturedcode.com/things/)
* Multi-Platform (🍎🪟🐧+🤖📱)
  * [TickTick](https://ticktick.com/)
  * [Todoist](https://todoist.com/)
  * [Remember the Milk](https://www.rememberthemilk.com/)
* Multi-Platform (🍎🪟+🤖📱)
  * [Microsoft Todo](https://to-do.office.com/tasks/)
  * [Notion](https://www.notion.so/) + Web
  * [Trello](https://trello.com/)
  * [Any.do](http://Any.do)

::right::

* Misc
  * [Todo.txt](Todo.txt)
  * Google Sheets / Excel
  * [Bullet Journal](https://bulletjournal.com/)
  * A literal notepad
  * Apple Reminders
  * Google Cal Reminders / Tasks

---
layout: intro-image-right
image: ./img/dog-flames.webp
class: text-center
---

# Demos
## Task Managment


---
layout: two-cols-headers-jsm
---
# PKM / Note Taking Tools (a short list)

::left::
* 🍎 Only
  * Bear
* Multi-Platform (🍎🪟🐧+🤖📱)
  * [Obsidian](https://obsidian.md/)
  * [Roam Research](https://roamresearch.com/)
  * [Zettlr](https://www.zettlr.com/)
  * [Logseq](https://logseq.com/)
  * [Joplin](https://joplinapp.org/)
  * [TiddlyWiki](https://tiddlywiki.com/)

::right::
* Multi-Platform (🍎🪟+🤖📱)
  * [Microsoft Onenote](https://www.onenote.com/)
  * [Evernote](https://evernote.com/)
  * [Notion](https://www.notion.so/)
* Misc
  * Google Docs or MS Office
  * [Bullet Journal](https://bulletjournal.com/)
  * A literal notepad
  * Apple Notes or Google Keep
  * Notecards

---
layout: intro-image-right
image: ./img/dog2.webp
class: text-center
---

# Demos
## Notes

---
layout: intro-image-right
image: ./img/crash.webp
class: text-center
---

# How
## Failuremodes

---
---
# Failure Modes
* Shiny Toy Syndrome (https://nesslabs.com/shiny-toy-syndrome)
  * Jumping from tool to tool and not doing the thing
* Perfect Notebook/Laptop Syndrome
  * You can’t start unless you have the perfect tool
* Building Bookshelves (or  your own software system)
  * Working  on adjacent things and not doing the thing
* Improving your notebook
  * Working on the system and not the thing
* Omnifocus Syndrome
  * Having an overwhelming number of lists that you feel guilty about and don’t do the thing

---
layout: intro-image-right
image: ./img/who.webp
class: text-center
---

# Who

---
layout: two-cols-headers-jsm
---
# People

::left::
* [David Allen](https://gettingthingsdone.com/)
  * [Getting Things Done](https://www.amazon.com/Getting-Things-Done-Stress-Free-Productivity-ebook/dp/B00KWG9M2E/)
* [ Merlin Mann](http://www.merlinmann.com/)
  * [43 Folders](https://www.43folders.com/) & Popularizing GTD
* [Cal Newport](https://calnewport.com/)
  * [Deep Work](https://www.amazon.com/Deep-Work-Focused-Success-Distracted/dp/1455586692)
* [Tiago Forte](https://fortelabs.com/)
  * [Building a Second Brain](https://www.amazon.com/Building-Second-Brain-Organize-Potential-ebook/dp/B09LVVN9L3/)
* [Ryder Carroll](https://www.rydercarroll.com/)
  * [Bullet Journal](https://bulletjournal.com/)

::right::
* [Shida Li & Erica Xu](https://obsidian.md/about)
  * [Obsidian](https://obsidian.md) 
* [Ryan Holiday](https://ryanholiday.net) 
  * [Popularizing Note Cards](https://ryanholiday.net/the-notecard-system-the-key-for-remembering-organizing-and-using-everything-you-read/)
* [Niklas Luhmann](https://en.wikipedia.org/wiki/Niklas_Luhmann)
  * [Zettelkasten](https://en.wikipedia.org/wiki/Zettelkasten)
* [Alex Hedtke](https://guildoftherose.org/about)
  * [Original GotR Workshop](https://guildoftherose.org/workshops/creating-an-exobrain)

---
layout: section
---

# Appendices

---
---
# Activities
* Mental Sweep
* What are your inboxes
* Roles / GTD Horizons
* Choose Calendar
* Choose Task Manager
* Choose Notes Tool

---
layout: two-cols-headers-jsm
---
# Note Taker Types (Tiago Forte)
::left::
* Architect
  * Systems
* Gardener
  * Exploratory
* Librarian
  * Collecting & Categorizing
* Student
::right::
<youtube id=f3dDVtJ2sec />

---
---
# Additional links

* [Ness Labs on choosing a Note Taking Tool](https://nesslabs.com/how-to-choose-the-right-note-taking-app)
* [Tiago Forte’s podcast on BASB](https://fortelabs.co/blog/basbpodcast/)
* [Ryder Carroll on BuJo (Bullet Journal)](https://www.youtube.com/watch?v=GfRf43JTqY4)
* [Forte Labs Weekly Reviews](https://fortelabs.com/blog/the-one-touch-guide-to-doing-a-weekly-review/)