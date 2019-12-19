---
title: Workflow and Software
author: Bryn Hughes
date: '2018-06-04'
slug: workflow-and-software
categories:
  - tech
tags:
  - software
  - open-source
  - privacy
  - R
  - zotero
  - Google Drive
  - R Studio
header:
  caption: ''
  image: ''
---

Anyone who knows me knows that I enjoy all things geeky and nerdy. Part of that is my never-ending quest to find the most efficient, most ethical, and most future-proof software for my work. These three things are often at odds. I thought I would take a moment to document my current workflow. It will be interesting (to me, at least) to come back to this in the future to see how my opinions have inevitably changed. 

## Cloud Storage and Backup: Google Drive

I've been using Google Drive for many years, save for a brief spell when I was using Dropbox because it integrated better with iPad apps. I pay $10 USD/month to back up and sync everything I need across three computers. I stick with Google Drive out of convenience, more than anything, because, in addition to being serviceable cloud storage, it is also the space in which I do most of my collaborative writing, and it is the place where I back up all of my photos. Ideally, I would use some kind of roll-your-own cloud storage, like [ownCloud](https://owncloud.org/), but I haven't gotten around to it yet. Google has become [increasingly evil](https://gizmodo.com/5878987/its-official-google-is-evil-now) over the years, and have been known to [terminate beloved software](https://lifehacker.com/google-reader-is-shutting-down-here-are-the-best-alter-5990456)--strikes against both my second and third ideals in my software quest. Nevertheless, I work between three computers (a desktop at home and at work, plus a laptop), so I depend on a reliable sync across machines. 

## Collaborative Writing: Google Docs

Ugh. Google again?! The fact is, the kind of research I do is collaborative by nature. Most of my work involves collaborative writing, and I'm not going to be able to convince my collaborators to use Git anytime soon. So, collaborative drafts, at least, remain in Google Docs. For now. 

## Reference Management: Zotero

I still reflect upon my panicked state while putting the finishing touches on my dissertation, realizing that there were references in the text that weren't in the bibliography, and vice versa. I've used Zotero ever since. It's free and open-source, and with a few plugins, allows for seamless integration with Google Drive. Its browser plugin is invaluable during the early stages of any research project. The [Better BibTex](https://retorque.re/zotero-better-bibtex/installation/) plugin and integration with [citr](https://github.com/crsh/citr) and [RStudio](https://www.rstudio.com/) (more below) was a game-changer for my writing process, too. I should do a separate post about my Zotero setup. It is a bit of a pain to get started, but really worth it in the end. 

## Data Analysis: R

When I was working on my dissertation, I used a pirated copy of SPSS to do my data analysis. Now that I'm in a research position, I have come back to many of the analyses I did during that time. I haven't been able to open my old files, because SPSS is obscenely-priced proprietary software. I've started to use [R](https://www.r-project.org/), and I'm hooked. R is much more unforgiving than SPSS, and I've found that I have gained a much more thorough understanding of statistics as a result. It is definitely a steep learning curve. Thankfully, it has an active community, and I have a few wonderfully generous colleagues who can help me out when I'm banging my head against a wall, looking for answers.

## Research and Writing: RStudio, RMarkdown, Citr, Papaja, Knitr, Pandoc...

I flirted briefly with Scrivener, but I think I've found my favourite new writing environment in RStudio and its various plugins. It allows you to write in R-flavoured markdown: Basically just Markdown with the option to include code chunks from R (or even Python, but I haven't tried this yet). This is tremendously useful when you're doing work that involves data analysis, as I can simply have my paper render tables and plots in the same place, instead of having to copy and paste things by hand. This makes it much easier to avoid errors, in the long run, when preparing a document. As I mentioned before, the Citr plugin works with my Zotero library (and a Bibtex back end). I can simply press "Insert Citation" (or map it to a keyboard shortcut--even better!), and it will allow me to search for the citation by typing any word that might be entered into the Zotero metadata, and then plop a citation key directly into the text. When I render the document, the citations are formatted precisely to my specifications, and a reference list is created at the end of the document that includes everything cited in the text. It's the kind of computer magic that makes me scream with delight. It allows parent/child documents, which offers similar functionality to Scrivener's cork board (my favourite feature in Scrivener). And [Papaja](https://github.com/crsh/papaja) is a *fantastic* plugin for creating APA journal articles that are ready to submit. If I can convince my collaborators to climb aboard, this will be the way I put together work for publication going forward. 

## Blogging: RStudio, Blogdown, Hugo

Lately, all I seem to ask myself is "how can I do this task in RStudio?" So, naturally, RStudio is where I'm doing my blogging now! The [blogdown](https://bookdown.org/yihui/blogdown/) package generates a static site that is easily hosted on Github. I'm able to write in markdown, so it's quite similar to what I used to do with my old Jekyll site. 

That's all for now! I didn't get to presentation software or music notation. That will have to wait for a future post.

