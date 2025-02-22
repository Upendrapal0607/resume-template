# Resume Template

## Overview
This repository provides a **LaTeX-based resume template** that you can use to create a professional resume. The template is designed for use with **Overleaf** and can be easily customized to fit your needs.

## How to Use
### 1. Open Overleaf
Go to [Overleaf](https://www.overleaf.com/) and log in or create an account if you haven't already.

### 2. Copy and Paste the Template
- Create a **new project** in Overleaf.
- Copy and paste the following LaTeX template into your new project.

```latex
%-----------------------------------------------------------------------------------------------------------------------------------------------%
% The MIT License (MIT)
%-----------------------------------------------------------------------------------------------------------------------------------------------%

\documentclass[a4paper,12pt]{article}

%----------------------------------------------------------------------------------------
% PACKAGES
%----------------------------------------------------------------------------------------

\usepackage{url}
\usepackage{parskip} 	
\usepackage{color}
\usepackage{graphicx}
\usepackage[usenames,dvipsnames]{xcolor}
\usepackage[scale=0.9]{geometry}
\usepackage{tabularx}
\usepackage{enumitem}
\usepackage{supertabular}
\usepackage{titlesec}
\usepackage{multicol}
\usepackage{multirow}
\usepackage[style=authoryear,sorting=ynt, maxbibnames=2]{biblatex}
\usepackage[unicode, draft=false]{hyperref}
\definecolor{linkcolour}{rgb}{0,0.2,0.6}
\hypersetup{colorlinks,breaklinks,urlcolor=linkcolour,linkcolor=linkcolour}
\addbibresource{citations.bib}
\setlength\bibitemsep{1em}
\usepackage{fontawesome5}

%----------------------------------------------------------------------------------------
% BEGIN DOCUMENT
%----------------------------------------------------------------------------------------
\begin{document}

\pagestyle{empty}

%----------------------------------------------------------------------------------------
% TITLE
%----------------------------------------------------------------------------------------

\begin{tabularx}{\linewidth}{@{} C @{}}
\Huge{Your Name} \\
\href{https://github.com/yourgithub}{\raisebox{-0.05\height}\faGithub\ yourgithub} \ $|$ \
\href{https://www.linkedin.com/in/yourprofile/}{\raisebox{-0.05\height}\faLinkedin\ Your Name} \ $|$ \
\href{mailto:youremail@gmail.com} {\raisebox{-0.05\height}\faEnvelope \ youremail@gmail.com} \ $|$ \
\href{tel:+1234567890}{\raisebox{-0.05\height}\faMobile \ +1234567890} \\
\end{tabularx}

%----------------------------------------------------------------------------------------
% SUMMARY
%----------------------------------------------------------------------------------------

\section{Summary}
A brief professional summary highlighting your key skills and expertise.

%----------------------------------------------------------------------------------------
% SKILLS
%----------------------------------------------------------------------------------------

\section{Skills}
\begin{tabularx}{\linewidth}{@{}l X@{}}
\textbf{Technical Skills:} JavaScript, React, Node.js, Express, MongoDB, TypeScript, Git, REST APIs \
\textbf{Soft Skills:} Problem Solving, Team Collaboration, Adaptability
\end{tabularx}

%----------------------------------------------------------------------------------------
% WORK EXPERIENCE
%----------------------------------------------------------------------------------------

\section{Work Experience}
\textbf{Your Job Title (Company Name)} \hfill Month Year - Present  \\
\textit{Responsibilities and key achievements.}

%----------------------------------------------------------------------------------------
% PROJECTS
%----------------------------------------------------------------------------------------

\section{Projects}
\textbf{Project Name} \hfill \href{https://github.com/yourproject}{GitHub Link} \hspace{} \href{https://yourproject.live}{Live Link}
\begin{itemize}
    \item Description of the project and technologies used.
    \item Features and functionalities implemented.
\end{itemize}

%----------------------------------------------------------------------------------------
% EDUCATION
%----------------------------------------------------------------------------------------

\section{Education}
\textbf{Degree} \hfill University Name, Year

\vfill

\end{document}
```

## Customization
- Replace `Your Name`, `Your Job Title`, and other placeholders with your actual details.
- Add or remove sections as needed.
- Modify the **skills, work experience, and projects** to reflect your expertise.

## Exporting as PDF
Once you have finalized your resume in Overleaf:
- Click **Recompile** to generate the document.
- Download the final PDF using **Download > PDF**.

## License
This template is released under the **MIT License**. Feel free to use and modify it as needed.

---
### Author
Developed by **Upendra Pal**. Connect with me on [GitHub](https://github.com/Upendrapal0607) and [LinkedIn](https://www.linkedin.com/in/upendra-pal-505b4a26a/).

