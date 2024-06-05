# ResumeTemp
Created by LATEX Code.
\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

% Just in case someone needs a heading that does not need to be in a list
\newcommand{\resumeHeading}[4]{
    \begin{tabular*}{0.99\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
  \textbf{\href{http://sourabhbajaj.com/}{\Large Alok Kumar}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{Hialok0208@gmail.com}\\
  \href{http://sourabhbajaj.com/}{https://www.linkedin.com/in/alok-kumar-a23a9815b/} & Mobile : \href{tel:+11234567890}{8809746212} \\
\end{tabular*}

%-----------EXPERIENCE-----------------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {TechSera Software Pvt Ltd.}{Bengaluru}
      {Software Engineer}{Mar 2021 - Mar 2024}
      \resumeItemListStart
        \resumeItem{Performance Tuning}
          {Conducted regular performance tuning and query optimization to ensure efficient database operations.}
            \resumeItem{Stored Procedures} 
            {Wrote complex stored procedures and function to enhance database functionality and performance.}
            \resumeItem{Database}
            {Designed, developed, and maintained SQL databases to support business applications and improve data retrieval processes.}
        \resumeItem{}
          {Created the database for the reporting team.}
           \resumeItem{}
          {Excellent at performing 'CRUD' Operations on any RDBMS.}
           \resumeItem{}
          {Good understanding of SQL language, including complex queries, Joins, Subqueries, and aggregate functions.}
           \resumeItem{}
          {Writing efficient SQL queries to retrieve, update, and manipulate data.}
        \resumeItem{}
          {Generating Reports using SQL queries based on client
                   requirements.}
         
      \resumeItemListEnd
      
% --------Multiple Positions Heading------------
  %  \resumeSubSubheading
  %   {Software Engineer I}{Oct 2014 - Sep 2016}
  %   \resumeItemListStart
  %      \resumeItem{Apache Beam}
  %        {Apache Beam is a unified model for defining both batch and streaming data-parallel processing pipelines}
  %   \resumeItemListEnd

%-----------PROJECTS-----------------
\section{Projects}
 
    \resumeSubheading
      {NORTHERN TOOL}{Burnsville, Minnesota, United States}
      {Managing Databases}{May 2021 - Mar 2024}
      \resumeItemListStart
        \resumeItem{Query Optimization}
          {Designed and implemented a database solution to integrate sales, inventory, and customer data from multiple sources, improving reporting and data analysis capabilities.}
        \resumeItem{Normalization}
          {Learned about ER Diagrams and Normalization.}
        \resumeItem{Workflows}
          {Optimized the existing inventory management database, resulting in a 30 percent improvement in query performance and faster data retrieval times.}
        \resumeItem{Data Collection}
          {Collaborated with development teams to design and implement effective database solutions.}
        \resumeItem{Prod Environment}
          {Resolved production issues by modifying backend code when required.}
        \resumeItem{Client Relation}
          {Schedule a call with the client and understand requirements.}
        
      \resumeItemListEnd

    \resumeSubheading
      {Columbia Sportswear}{Portland, United States}
      {Data Analysis}{May 2021 and Mar. 2024}
      \resumeItemListStart
        \resumeItem{Data Analysis}
          {Monitor database performance and troubleshoot issues.}
        \resumeItem{Report}
          {Develop and maintain reporting and analytics solutions.}
        \resumeItem{Retrive Recods}
          {Retrieving and analyzing records from the database.}
       \resumeItem{Production}
          {Resolved production issues by modifying backend code as and
            when required.}
      \resumeItemListEnd
%
%--------PROGRAMMING SKILLS------------
\section{Programming Skills}
 \resumeSubHeadingListStart
   \item{
     \textbf{}{} Microsoft SQL Server, MySQL, Oracle, Performance Tuning, Stored Procedures, Query optimization, DB2, AS400}
  }
  \resumeSubHeadingListEnd
%-------------------------------------------
%-----------EDUCATION-----------------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Sanskriti University}{Mathura, India}
      {Bachlor of Technology in Computer Science }{Aug. 2017 -- June 2021}
  \resumeSubHeadingListEnd
%-------------------------------------------
\end{document}
