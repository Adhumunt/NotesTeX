<p align="center">

  <h1 align="center">NotesTeX</h1>

  <p align="center">
    An All-In-One LaTeX Notes Package For Students
    <br>
    <br>
    <a href="http://geodesick.com/">Website</a>
  </p>
</p>
<br>

| Table of contents | Purpose | 
| ------------- |------------- |
| - [Preview](#preview) <br> - [Installation](#installation) <br> - [Example](#example) <br> - [Documentation](#documentation) <br> - [License](#license) <br> - [Version and Contact](#version-and-contact) | _NotesTeX_ is a modification of the original Jhep journal <br> format in order to suit the needs of students in university. |

## Preview
| Page. 1 | Page. 2 |
|:---:|:---:|
| [![Preview](https://raw.githubusercontent.com/adhumunt/NotesTeX/master/Sample/Sample1.png)](https://raw.githubusercontent.com/adhumunt/NotesTeX/master/Sample/Sample1.pdf)  | [![Preview](https://raw.githubusercontent.com/adhumunt/NotesTeX/master/Sample/Sample2.png)](https://raw.githubusercontent.com/adhumunt/NotesTeX/master/Sample/Sample2.pdf) |

| Page. 3 | Page. 4 |
|:---:|:---:|
| [![Preview](https://raw.githubusercontent.com/adhumunt/NotesTeX/master/Sample/Sample3.png)](https://raw.githubusercontent.com/adhumunt/NotesTeX/master/Sample/Sample3.pdf)  | [![Preview](https://raw.githubusercontent.com/adhumunt/NotesTeX/master/Sample/Sample4.png)](https://raw.githubusercontent.com/adhumunt/NotesTeX/master/Sample/Sample4.pdf) |

## Installation
Installing just requires the following steps:

1. **Download** the [zip archive](NoTeX.zip).
2. **Build** the NotesTeX.tex file. This compile should work without a problem, and it should look like the pdf attached below.
3. **Move** the NotesTeX.sty file where ever you need it, and let your new notes file call to it as provided in the example below.

## Usage
Here is an example of a test page:

```latex
\documentclass{article}
\usepackage{/Path/to/package/NotesTeX} %/Path/to/package should be replaced with package location
\usepackage{lipsum}

\title{{\Huge Test Page Title}\\{\Large{Test Page Subtitle}}}
\author{Author Name\footnote{\href{https://google.com/}{\textit{Author Website}}}}

\affiliation{Affiliation of Author}
\emailAdd{Email of Author}
\begin{document}
  \maketitle
  \flushbottom
  \newpage
  \pagestyle{fancynotes}
  \part{Test Part 1}
  \lipsum[1]
  \section{Subtest Section 1}
  Some notes here.\sn{With some additional sidenotes}
\end{document}
```

## Documentation
All the documentation of this package is given in [NotesTeX.pdf](NoTeX/NotesTeX.pdf) and if you have any questions feel free to contact me.

## License
This material is subject ot the [LaTeX Project Public License](LICENSE).

## Version and Contact

> NotesTeX v2.0.  
> Created by Aditya Dhumuntarao.  
> Date: September 21, 2017.  
> E-mail comments and suggestions to adhumunt@gmail.com.  