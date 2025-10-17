---
title: Adding New pages
socialImage:
socialDescription: One of the wikis in Rain World 3
---
If you would like to add new pages to the wiki, there are some important things to keep in mind. 
General formatting is something you can glean from seeing the other pages and opening them in Obsidian but the most important thing, Frontmatter, needs to be outlined specifically.

At the top of each note, just underneath the title is what is called the Frontmatter for the note. If you open a note in source mode in obsidian, you can see it declared with three hyphens and closed with three again.

Frontmatter for each note is incredibly important because not only does it keep information about the note for Obsidian, the format is specific for Quartz as well. 

## General Structure
We recommend editing Frontmatter in source mode.
```
---
title: Title
tags:
  - tag1
  - tag2
  - tag3
socialImage: embedHeaders/techname_header.gif
socialDescription: One of the moves in Rain World 3
---
```

The title will be what shows up at the top of the page and is shown in the explorer on the left of the page. Tags link notes with similar properties together. Social image is what the embed will be in something like Discord (super important! **Do not remove this tag ever, just leave it blank for no embed**) and the description is the text that will be beneath the image (just keep it the same "One of the moves in Rain World 3" for now).

When you add a new *header* gif, make sure to not only put it in `content/Files` but to put it in `quartz/static/embedHeaders` as that is where the `socialImage` field will be able to find it.


## Alternate Names
We try to make the note name and page title be the most "scientific" name for a tech, if you will. Oftentimes the community does not use this name however which can make searching for that tech annoying. Whenever you want to give a tech an alternate name, follow the formatting you see near the top of a note like [[turnflip]] .

```
<div class="hidden-alts">
name1
name2
</div>
```

Anything you put in here will not be visible on the site, but it will show this note if someone searches for it in the search bar. Make sure to leave a blank line after the div is closed in order to not mess with the header image below.