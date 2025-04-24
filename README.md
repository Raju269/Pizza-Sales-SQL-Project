# Pizza Sales SQL Project

## Introduction
This project analyzes pizza sales data using SQL to derive key insights into customer preferences, revenue generation, and order patterns.

## Objectives
The project answers key questions ranging from basic to advanced SQL queries, such as total revenue generation, identifying popular pizza types, and understanding sales trends over time.

## Features
- Retrieve the total number of orders placed
- Calculate total revenue from pizza sales
- Identify top-ordered pizzas and their contribution to revenue
- Analyze order patterns by time of day and date

## Usage
To run the SQL scripts, you can use any SQL client like MySQL Workbench or an online SQL editor. Simply import the provided dataset and execute the queries.

## Files
- `queries/`: SQL scripts containing all the queries used in the analysis.
- `docs/`: Contains the PDF file summarizing the project for GitHub and LinkedIn.
- `data/`: Sample dataset for testing the queries.

## Credits
Special thanks to WSCUBE @AYUSHI JAIN nducting the analysis and creating the documentation.

## Code 
\documentclass[a4paper,10pt]{article}
\usepackage[top=0.8in, bottom=0.8in, left=0.8in, right=0.8in]{geometry}
\usepackage{fontspec}
\setmainfont{Arial}
\usepackage{hyperref}
\hypersetup{
  colorlinks=false,
  linkcolor=black,
  urlcolor=black,
  pdfborder={0 0 0}
}

\usepackage{titlesec}
\titleformat{\section}{\large\bfseries}{}{0em}{}[\titlerule]

\newcommand{\resumeItem}[1]{\item\small{#1}}
\newcommand{\resumeSubheading}[4]{
  \vspace{2pt}\item
    \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{#3} & \textit{#4} \\
    \end{tabular*}\vspace{-7pt}
}

\begin{document}

% Header
\begin{center}
    {\LARGE \textbf{Sujal Burman}}\\
    \vspace{3pt}
    Phone: +91-7838741689 \quad 
    Email: \href{mailto:priyambarman28@gmail.com}{priyambarman28@gmail.com} \quad 
    LinkedIn: \href{https://www.linkedin.com/in/sujalburman}{Sujal Burman}
\end{center}

% Profile
\section*{Profile}
\begin{itemize}
  \resumeItem{BCA student with a strong foundation in data analytics and a growing passion for data science. Google-certified in Data Analytics with hands-on experience in SQL, Python, and statistical analysis. Actively building skills and projects to transition into a full-fledged data science role.}
\end{itemize}

% Education
\section*{Education}
\begin{itemize}
  \resumeSubheading{Bachelor of Computer Applications (General)}{2022 -- 2025}{YMCA University, Faridabad, India}{}
\end{itemize}

% Skills & Tools
\section*{Skills \& Tools}
\begin{itemize}
  \resumeItem{\textbf{Technical:} SQL, Python, Statistics, Machine Learning, Data Cleaning}
  \resumeItem{\textbf{Tools:} Excel, MySQL, Jupyter Notebook, VS Code, Git}
\end{itemize}

% Certifications
\section*{Certifications}
\begin{itemize}
  \resumeItem{Google Data Analytics – Coursera, Mar 2023}
  \resumeItem{Advance Diploma in Computer Application – Prayagdas Tomar Computer Education, Jun 2022}
  \resumeItem{Fundamentals of Digital Marketing – Google, Aug 2022}
  \resumeItem{Introduction to IoT – NPTEL, Oct 2023}
\end{itemize}

% Projects
\section*{Projects}
\begin{itemize}
  \resumeSubheading{\href{https://github.com/Sujal8860/Pizza-Sales-SQL-Project}{Pizza Sales SQL Project}}{}{Tech Stack: MySQL}{}
  \begin{itemize}
    \resumeItem{Executed 12 complex SQL queries—including JOINs, CTEs, and window functions—to analyze pizza sales and uncover ordering patterns.}
    \resumeItem{Identified top-selling pizzas and revenue contributors; analyzed time-based order trends for business insights.}
    \resumeItem{Applied SQL date functions and aggregations to support recommendations for menu and marketing strategies.}
  \end{itemize}

  \resumeSubheading{\href{https://github.com/Sujal8860/Maximizing-revenue-for-taxi-drivers/blob/main/README.md}{Maximizing Revenue for Taxi Cab Drivers}}{}{Tech Stack: Python, Pandas, Matplotlib, Statsmodels}{}
  \begin{itemize}
    \resumeItem{Processed 10,000+ NYC taxi records to analyze fare differences by payment type using OLS regression.}
    \resumeItem{Found cash rides were on average \$0.25 cheaper than card rides, controlling for trip duration.}
    \resumeItem{Used Mann–Whitney U test and R² = 0.783 to validate insights and recommend promoting cashless payments.}
  \end{itemize}
\end{itemize}

% Achievements
\section*{Achievements}
\begin{itemize}
  \resumeItem{Solved Top 50 SQL problems on LeetCode to sharpen query optimization and real-world problem-solving.}
  \resumeItem{Participated in the “MCTS Variant” Kaggle competition—focused on tuning Monte Carlo Tree Search algorithms for game-playing AI.}
  \resumeItem{Demonstrated commitment to self-growth through projects, courses, and participation in multiple tech communities.}
\end{itemize}

\end{document}
