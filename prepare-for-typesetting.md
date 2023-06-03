# Prepare for Typesetting

## Introduction
All external documents for Venturer Camp 2023 should be typeset using the LaTeX template. This gives us a unified style which meets all of Woodcraft's Branding Requirements while being *relatively* simple (if you know what you're doing).

If you don't know LaTeX, Thomas is happy to typeset documents - providing:
1. enough notice is given
2. the document is prepared in draft form as set out below.

## Why LaTeX?
A very good question....

LaTeX focuses on content over style, simply allowing users to define styles once and use that repeatedly throughout multiple documents. Thomas has built a style package, which can be found here: [`global-preamble.tex`](https://raw.githubusercontent.com/ThomasBoxall/venturer-camp-2023-docs/main/global-preamble.tex). 

Also, for floats (tables, figures, etc), LaTeX has much better control over placement of them. Unlike in popular WYSIWYG (What You See Is What You Get) editors where moving an image over my one pixel can cause multiple new pages to be inserted and all the formatting to go out of the window!

The final main reason for using LaTeX is the aesthetically pleasing output. LaTeX builds documents from [raw text files](https://raw.githubusercontent.com/ThomasBoxall/venturer-camp-2023-docs/main/info-pack-v1/info-pack-v1.tex), which means formatting is automatically applied. The most obvious formatting it does is to fully justify all content (unless you tell it not to) and add page breaks and spaces in where it feels it looks the best. This results in a pleasant-to-read document. 

## Typesetting Prerequisites
If you need a document to be typeset into LaTeX, please contact Thomas as soon as possible so its in his schedule! It helps to know the vague outline of content (e.g. will there be lots of complex tables, or will is just be paragraphs of text?) as this can drastically change the time it takes to typeset a document.

The content to go in the document should be produced as a Google Doc, with tables made available as Google Sheets files. Any images to be typeset should be saved separate to the document as `.png` or `.jpeg` files. 

Once you have a final draft ready to go, please send this to Thomas who will typeset it and make a *proof* copy available. You should check through this thoroughly to ensure it is correct. Once you are happy, the *proof* watermark will be removed and a final copy made available to the document owner. 

## Template Details
[Blank Example](https://thomasboxall.github.io/venturer-camp-2023-docs/00-TEMPLATE/template-long.pdf) // [Filled-out Example](https://thomasboxall.github.io/venturer-camp-2023-docs/info-pack-v1/info-pack-v1.pdf)

There are a few key things to note about the template:
1. The title page has space for a document title, subtitle (or humorous comment about the document) and publication date.
2. The top level heading will start a new page and get added to the table of contents, lower level headings do not get added to ToC.
3. The back page contains information which we have to publish in all external documents.