---
title: Wiki Structure
socialImage:
socialDescription: One of the wikis in Rain World 3
---
If all you would like to do is edit the pages in the wiki, everything you need is in the `content` folder. Open `content` as a vault in obsidian and go to town.

If you are adding new pages to the wiki or changing header gifs for pages, it is very important that you add the new header gif to `static/embedHeaders` as this is where all of the references for embed images come from!

If you want to preview your changes, things get a bit more technical but you can skip the next couple paragraphs and go to [[#Building the wiki locally]].

## Important Quartz things
The next part is a lot more technical but it explains the inner workings of the wiki.

The wiki is built using [Quartz](https://quartz.jzhao.xyz/) which takes the vault of markdown files and converts them into web pages. At the root of the `wiki` repository there are a few things to focus on:
1. The `content` folder, this is where all of the pages that become the site end up
2. The `quartz` folder, this is where all of the inner workings for quartz are housed, most notably `quartz/static` (where all static site images are held; so embeds and the favicon) and `quartz/styles` (where all the css for styling the wiki can be found, you will only ever need to edit `custom.scss`)
3. `quartz.config.ts`, this is where the two themes (light and dark) for the site are declared as well as fonts and broader page information as well as plugins (the magic sauce of Quartz that gives us like, everything cool about the pages)
4. `quartz.layout.ts`, rarely needs touching but has the footer links

The keen eyed of you will notice the hints of Node around the place. Quartz comes packaged with several incredibly useful commands for syncing changes with the main repository as well as building and locally testing the wiki (THIS IS SUPER COOL!).

## Building the wiki locally
If you want to go beyond editing the pages in the wiki, or if you want to preview your page changes locally, you'll first need both [Node](https://nodejs.org/en) (version 22 at least) and npm (version 10.9.2 at least, this should come as part of Node).

Once you have those two pieces of software, you'll need to open the root `wiki` folder in a terminal, if you are on Windows, open the folder in file explorer, right click the background and press open in terminal. If you are on Linux, I trust you can find your way there.

Inside the terminal, type `npm i`. This will install all of the packages you need to truly build Quartz.
Once that is done, you can type `npx quartz build --serve` and this will build the website locally whereupon you can then open `http://localhost:8080/` in any browser to see the site.

## Using Quartz to sync
Quartz also has commands that interface with Git directly. `npx quartz sync` (once you have run `npm -i`) will push all of your changes to Github without much effort.
