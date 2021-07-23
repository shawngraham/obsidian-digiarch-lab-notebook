---
title: Getting Started with Obsidian
date: 2021-07-23
tags: introduction, help
---

# What is this?

This is a folder of individual text files using the markdown extension & conventions. When used in combination with the [obsidian.md](https://obsidian.md) interface which permits and encourages interlinkages of files, like a personal wiki, this folder becomes a knowledge base for your research and learning. It can become not just a _repository_ of what you've learned, but a _generator_ for new insights.

A short video that shows the basics of Obsidian (not by SG):
[https://www.youtube.com/watch?v=QgbLb6QCK88](https://www.youtube.com/watch?v=QgbLb6QCK88)

A video showing just how powerful Obsidian can be for your notetaking can be found at [' How to turn your notes into published articles and books using the Obsidian app with Eleanor Konik'](https://www.youtube.com/watch?v=nO5N_x2so0g).

# Basic use
- make a daily note (there's a button in the toolbar) every day you're working on the course. Dump into that note thoughts, problems, issues, inspirations. You can always copy and move the contents elsewhere later if you want.
- when you make a new note, you can begin typing right away, or you can hit the 'templates:insert template' command from the tool bar or the command pallette.
	- when you're working on a tutorial, create a new note, and insert the `log` template to help keep track of your thoughts (on the course website, this is sometimes also called the 'notes' file)
	- when you're working on a reflective journal entry, use the `journal` template to help keep track of your thoughts. 
	- when you're working on a consolidation entry, use the `consolidation` template
- otherwise, make notes as you read or think about the content of the course. One strategy is to make a new note for a unique thought/idea. You can make your own templates by making a note with the headings you want, and then move it into the `_simple-templates` folder.

Periodically, explore and re-read your notes with an eye to creating links between them.  Type `[[` and `]]` to find connections between your notes, and to interlink them (you can also highlight a word, and then type the square brackets). As you type, Obsidian searches through your notes to find notes by title or content. (NB: one square bracket `[like this]` is the first part of making an _external_ link in your note, `[like this](https://example.com)`).

If you click on the 'open vault' button, you can load/open the default vault that comes with Obsidian, and which will show you other aspects of Obsidian's functionality. You can have more than one vault open at a time.

# Slightly More Complex Use
- Open the command palette to find the complete list of commands you can run. These include:
	- inserting templates into new notes, for consistency (make a new note, click the cursor in there, then insert template) "templates: insert template"
	- grabbing hypothesis annotations (via the Templater) command (make a new note, click the cursor in there, then insert template)  "templater: insert templates". Note, **templater**. Also available from command bar under the relevant icon 
	- selecting a block of text to turn into a new note, connected to the original note "note composer: extract text"
- Use the backlinks and outgoing links panel, and the graph panel, to see how your notes interconnect, and to find _potential_ connections
- When you search for notes, you can copy the search results into a _new_ note; the results will all be links.
- You can create notes (new files) in Obsidian that _embed_ notes, paragraphs, or headings from _other_ notes. In this way, you can build up drafts, outlines, and more complex pieces of writing that you can then export to Word and so on. This features is called _transclusion_ and you do this by putting an exclamation point in front of the `[[` to link to your note.
	- if you install the pandoc plugin for obsidian (after first installing [pandoc](https://pandoc.org/installing.html) on your computer) you can export notes into a .docx file formatted for Word etc by selecting pandoc from the command pallette. 
	- If you don't, that's ok too: just hit the preview button and then copy and paste into word.
- images that are dropped into this folder aka vault can be displayed by using the normal markdown convention for an image, eg, `![title](filename.png)` but will only be displayed in the preview, not the editor.

# Create notes from your hypothesis annotations
- Create a new note, then insert the hypothesis template.
- When you run the `templater:insert template` command, and then select hypothesis templater command in a new note, Obsidian will first prompt you for your Hypothesis user token. You find that at your Hypothesis user page. Once you give that to Obsidian (which it will keep in a file here in your vault for you, so you only ever have to do it the first time), you will be prompted  for the url or date for the resource you annotated; it will then grab those annotations as separate notes. 
- remember that hypothesis is pretty handy for annotating pdfs too, if you open the pdf in your browser
- Interlink those notes to your daily notes, or your tutorial notes, as appropriate

# The Point

Obsidian works as a personal knowledge base; seeing your notes develop and beging to interlink - and being able to search those patterns - supercharges your note taking abilities and the value of your reading. With time, you'll start to see connections and patterns in your thoughts. You're building up a **personal knowledge base** that becomes more valuable the more you use it. 

I have a vault with over 400 notes in it. When I get an idea, I search my vault for relevant notes, and then embed them into a new document. I write around the existing notes, and then export to word for final polishing, citations. This accelerates my writing considerably, and helps me pull my research together into coherent form.

## Going Further

There are any number of plugins that can enhance Obsidian, from citations and notes pulled from Zotero & pdf readers, to calendars, to using natural language processing to find notes with similar ideas that are otherwise unconnected. One I quite like is called 'Journey' which finds paths between notes. Feel free to explore!