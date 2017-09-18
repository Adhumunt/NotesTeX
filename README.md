README for the NotesTEX Package

NotesTEX 1.0
Created by Aditya Dhumuntarao
Date: September 18, 2017

E-mail comments and suggestions to: adhumunt@gmail.com

This material is subject to the LaTeX Project Public License.
See http://www.ctan.org/tex-archive/help/Catalogue/licenses.lppl.html for 
the details of that license.

_Jhep for Students_ is a modification of the original Jhep journal format in order to suit the needs of the student. 

During my year as a Part III student at Cambridge, I realized that my theoretical physics professors, namely David Tong and David Skinner, would use the Jhep format to typeset the notes for their classes. As the year went on, I started typesetting my notes during class and realized that the Jhep format, while great for publications and lecture notes in general, was lacking a few small but useful features, for instance sidenotes. While the Memoir class and the Tufte style packages provide extensive functionality, much of which I was inspired by, it was difficult to setup, use, and -- especially -- modify them. These packages did more than I needed them to, and eventually these small gripes pushed me to start modifying the Jhep package to better suit the needs of a student.

The result of this year long work, from 2016-2017, is the package now known as _Jhep for Students_. The purpose of this package was to consolidate all these changes that I slowly incorporated into the original Jhep format, and to provide stable support for commonly used physics and mathematics environments. I sincerely hope that you enjoy the package!

## Installation

Installing just requires the following steps:

1. **Download** the [zip archive](https://github.com/Adhumunt/Jhep-for-Students/blob/master/JhepforStudents.zip)
2. **Build** the jhepforstudents.tex file. This compile should work without a problem, and it should look like jhepforstudents.pdf.
3. **Move** the jhepforstudents.sty file whereever you need, and notetake away!

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
