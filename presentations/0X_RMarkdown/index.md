---
title: "Markdown and RMarkdown"
subtitle: "Data analysis best practice"
author: "Natalie Thurlby"
highlighter: highlight.js
hitheme: tomorrow
job: Data scientist, Jean Golding Institute
# logo: jgi-logo.jpg
mode: selfcontained
framework: io2012
url:
  assets: ../assets
  lib: ../libraries
widgets: mathjax
---



## Good communication

In order for your work to be reproducible, you have to share it with others and communicate what it does. As I've already said, that means writing READMEs, using version control (e.g. Git) and making your work available online (e.g. GitHub/OSF)

Markdown is a nice and simple way to display READMEs, GitHub comments and pull requests (you will understand what they are by the end of the day if you don't yet!) and OSF pages.

---

## Markdown

Markdown is a intuitive language which can easily be converted to html. It's a really simple way to style text for websites. It's a good language to write your README files in, commits/pull requests on GitHub, or other files to store on GitHub/the OSF, and it's also the basis for RMarkdown. 

```markdown
It's very easy to make some words **bold** and other words *italic* with Markdown. 

It's also very easy to  [link to Google!](http://google.com).

It's also how this presentation was formatted! 

```

Try it out!
* Go to [goo.gl/Kx1ys2] (a document I created at hackMD.io - like google docs for Markdown - you can link your login to your GitHub account)
* Sign up/log in
* Spend 5-10 minutes playing with Markdown.

---

## RMarkdown

With RMarkdown, you can interlace the markdown language that you just practiced in HackMD.io (minus the smileys) with snippets of R code. This way you can create a document that contains all the code, figures, and explanation for your work.

With Rmarkdown files you can:

(A) __knit__: to run the code chunks and display the output of those code chunks. This stops author from doing the manual labour of making the graph, saving it as a file, and then copying and pasting it into the final report every time they want to update the graph.

(B) __convert__: from Rmarkdown to html (websites), PDF, word files, presentations, or even books.

---

## Exercise

1. Open RStudio
2. Create a new RMarkdown file (File>New File>R) (an example file will be generated)
3. Run and individual code snippet from the generated file.
4. Knit and convert the document into a PDF.
