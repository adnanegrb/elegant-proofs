\documentclass[12pt]{article}
\usepackage[margin=3cm, paperwidth=16cm, paperheight=22cm]{geometry}
\usepackage{amsmath, amssymb}
\usepackage{xcolor}
\usepackage{pagecolor}
\usepackage{fontenc}
\usepackage{inputenc}
\usepackage{microtype}
\usepackage{setspace}
\usepackage{titlesec}

\pagecolor{black}
\color{white}

\titleformat{\section}
  {\normalfont\scshape\large\color{white}}
  {}{0em}{}[\vspace{-4pt}\noindent\rule{\linewidth}{0.2pt}]

\setlength{\parindent}{0pt}
\setlength{\parskip}{10pt}
\setstretch{1.35}

\begin{document}

\vspace*{1.2cm}

\begin{center}
{\fontsize{18}{22}\selectfont\scshape Elegant Proofs}\\[6pt]
{\small\itshape Classical Theorems, Unexpected Paths}\\[16pt]
\noindent\rule{6cm}{0.2pt}\\[14pt]
{\small\itshape
``Mathematics is not about numbers, equations, or algorithms.\\
It is about understanding.''\\[4pt]
\upshape --- William Paul Thurston}
\end{center}

\vspace{0.8cm}

I started this repository out of frustration.

Every textbook proves the same theorems the same way.
Cauchy's theorem via Green's theorem.
The Gaussian integral via polar coordinates.
The zeta function via Dirichlet series.
These proofs are correct, but they are not honest ---
they hide the real reason why the theorem is true.

What I collect here are the other proofs.
The ones that feel inevitable once you see them,
and completely mysterious before.
The ones where the method is more interesting than the result.
Each proof was chosen because it answers a question
I could not stop thinking about:
\textit{why is this true, really?}

Some of these proofs are well known to experts
and completely invisible to students.
Others are less standard.
All of them changed the way I think.

\vspace{0.3cm}
\section{What you will find here}

Each proof is a self-contained document,
typeset in \LaTeX\ with dark background
and hand-drawn contour diagrams in Ti\textit{k}Z.
The level varies ---
some proofs require only complex analysis,
others touch analytic number theory or functional analysis ---
but every argument is written to be followed line by line,
with no steps hidden.

At the end of each proof there is a short note.
Not a summary.
More like the thought I had when I finally understood
what was really going on.

\vspace{0.3cm}
\section{A note on style}

I write these proofs the way I wish I had read them.
Black background, white ink,
diagrams that look like they were drawn on a blackboard at 2am.

Mathematics should feel like something.

\vspace{0.3cm}
\section{About}

I am a second-year mathematics student at Sorbonne University,
working on random matrix theory and mathematical finance.
This repository is a side project ---
a place to think carefully about classical mathematics
before moving on to harder things.

If you find an error,
or if you know a more elegant proof of anything here,
I genuinely want to hear from you.

New proofs are added when I find something worth adding.

\vspace{1.2cm}
\begin{center}
\noindent\rule{4cm}{0.2pt}\\[10pt]
{\small\itshape Each one chosen for beauty, not difficulty.}
\end{center}

\end{document}
