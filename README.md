# The NotesTeX Package

> NotesTEX v1.0.  
> Created by Aditya Dhumuntarao.  
> Date: September 18, 2017.  
> E-mail comments and suggestions to adhumunt@gmail.com.  
---
## Purpose
_NotesTeX_ is a modification of the original Jhep journal format in order to suit the needs of students in university. 

## Installation
Installing just requires the following steps:

1. **Download** the [zip archive](NoTeX.zip)
2. **Build** the NotesTeX.tex file. This compile should work without a problem, and it should look like the pdf attached below.
3. **Move** the NotesTeX.sty file where ever you need it, and let your new notes file call to it as provided in the example below.

## Usage
Here is an example of a test page:

```latex
\documentclass{article}
\usepackage{/Path/to/package/jhepforstudents} %/Path/to/package should be replaced with package location
\usepackage{lipsum}

\title{{\Huge Test Page Title}\\{\Large{Test Page Subtitle}}}
\author{Author Name\footnote{\href{https://google.com/}{\textit{Author Website}}}}

\affiliation{Affiliation of Author}
\emailAdd{Email of Author}
\begin{document}
  \maketitle
  \flushbottom
  \newpage
  \pagestyle{fancyjhepmod}
  \part{Test Part 1}
  \section{Subtest Section 1}
\end{document}
```

## Details
All the documentation of this package is given in jhepforstudents.pdf and if you have any questions feel free to contact me.


## License
This material is subject ot the [LaTeX Project Public License](LICENSE).