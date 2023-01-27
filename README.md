# Venturer Camp 2023 Documents
*A repository to store external documents produced for Venturer Camp 2023 which have been typeset using LaTeX and the Venturer Camp 2023 Template.*

## Folder Structure
Each document should have a folder made within the root of the repository for it to live in. This folder should be named the document ID. Document IDs should be short names for the document, which should not contain spaces. For example `village-handbook` or `info-pack-v0`.   
Within each of the folders, any additional resources for the document as well as the `.tex` can be stored. The final `.pdf` file should also be left in here.

## Template
There are two different types of template, one for longer form documents where chapters are used (using the `report` document class) and one for shorter form documents, where chapters are not required (using the `article` document class).
## Long Template
The template below should be used for all long format documents produced. The `\chapter{Introduction}` and line below should be replaced with the contents of the document. The `\backPage` command provides a back page to the document which includes links to the Woodcraft & Venturer Camp websites and some basic information about the project.
```tex
\documentclass[a4paper, 11pt]{report}

\input{../global-preamble.tex}

\begin{document}
    \bookTitle{Template Document}{Subtitle}{6th December 2022}{template}
    \tableofcontents
    \chapter{Introduction}
    ...

    \backPage
\end{document}
```
## Short Template
The template below should be used for all shorter format documents produced. The `\section{Introduction}` and line below should be replaced by the contents of the document. The `\backPage` command should be left in place.

This template uses the same title page as that of the long template for a consistent branding of Venturer Camp documents. 
```latex
\documentclass[a4paper, 11pt]{article}

\input{../global-preamble.tex}


\begin{document}
    \bookTitle{Template Document}{Subtitle}{6th December 2022}{template-short}
    \section{Introduction}
    ...

    \backPage
\end{document}
```