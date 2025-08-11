
\documentclass[a4paper,8pt]{article}

\usepackage{parskip} 
\usepackage{hologo}
\usepackage{fontspec}

%other packages for formatting
\RequirePackage{color}
\RequirePackage{graphicx}
\usepackage[usenames,dvipsnames]{xcolor}
\usepackage[scale=0.9, top=.4in, bottom=.4in]{geometry}

%tabularx environment
\usepackage{tabularx}

%for lists within experience section
\usepackage{enumitem}

% centered version of 'X' col. type
\newcolumntype{C}{>{\centering\arraybackslash}X} 

%to prevent spillover of tabular into next pages
\usepackage{supertabular}
\usepackage{tabularx}
\newlength{\fullcollw}
\setlength{\fullcollw}{0.42\textwidth}

%custom \section
\usepackage{titlesec}				
\usepackage{multicol}
\usepackage{multirow}

%CV Sections inspired by: 
%http://stefano.italians.nl/archives/26
\titleformat{\section}{\Large\scshape\raggedright}{}{0em}{}[\titlerule]
\titlespacing{\section}{1pt}{2pt}{2pt}

%for publications
\usepackage[style=authoryear,sorting=ynt, maxbibnames=2]{biblatex}

%Setup hyperref package, and colours for links
\usepackage[unicode, draft=false]{hyperref}
\color[HTML]{110223}%{1C033C}
\addbibresource{citations.bib}
\setlength\bibitemsep{1em}

%for social icons
\usepackage{fontawesome5}
% \usepackage{times}

% For underline
\usepackage[normalem]{ulem}

\setmainfont{Arial}  % Set it to whatever you like

\begin{document}

% non-numbered pages
\pagestyle{empty} 


\begin{tabularx}{\linewidth}{@{} C @{}}
\color[HTML]{1C033C} \Huge{Utkarsh Dixit} \\[6pt]
\\
\textcolor[HTML]{371e77}{\underline{\href{mailto:utkarshdixit.2k21@gmail.com}{\raisebox{-0.05\height}{\faEnvelope} utkarshdixit.2k21@gmail.com}} $|$}
\textcolor[HTML]{371e77}{\href{tel:+916394924092}{\raisebox{-0.05\height}{\faMobile} +91-6394924092}}

\textcolor[HTML]{371e77}{\underline{\href{https://github.com/Utkarshh-Dixit}{\raisebox{-0.05\height}{\faGithub} github.com/Utkarshh-Dixit}} }
\textcolor[HTML]{371e77}{\underline{\href{https://linkedin.com/in/Utkarshh-Dixit}{\raisebox{-0.05\height}{\faLinkedin} linkedin.com/in/Utkarshh-Dixit}}}
\textcolor[HTML]{371e77}{\underline{\href{https://utkarshdixit.in}{\raisebox{-0.05\height}{\faEnvelope} utkarshdixit.in}}}
\end{tabularx}

% Education
\section{Education}
\begin{tabularx}{\linewidth}{ @{}l r@{} }
\color[HTML]{1C033C} \textbf{Dr. APJ Abdul Kalam Technical University, Lucknow} & \hfill \color[HTML]{371e77}  August. 2020 - July. 2024 \\
\color[HTML]{371e77} B.Tech in Computer Science $|$  & \hfill \color[HTML]{4B28A4} \textit{\textbf{CGPA: 7.52/10}} \\
\multicolumn{1}{@{}X@{}}{}
\end{tabularx}

% Experience
\section{Experience}
\begin{tabularx}{\linewidth}{ @{}l r@{} }
\color[HTML]{1C033C} \textbf{\uline{\href{https://frautect.com/}{Full Stack Developer Intern}}} \hfill \color[HTML]{371e77} March. 2025 - Present \\[4pt]
\color[HTML]{371e77}\textbf{\textit{Frautect}}  \hfill \color[HTML]{4B28A4} \textit{NextJs, MongoDB, ExpressJs, API development, Software Testing} \\[5pt]
\begin{minipage}[t]{\linewidth}
   \begin{itemize}[nosep,after=\strut, leftmargin=2em, itemsep=2pt]
        % \item Integrated role-based access control (RBAC) and secure authentication, safeguarding 50+ critical features within the application.
        \item Developed a dynamic client dashboard using Next.js and MongoDB, including a multi-step company profile form, a real-time threat monitoring page, and a data-rich overview dashboard with interactive charts and insights.
        \item Built robust REST APIs with advanced error handling and concurrency control to prevent data collisions during simultaneous updates by multiple users of the same company.
        % \item Executed extensive load and stress testing across multiple web applications, independently orchestrating API benchmarking to fine-tune backend performance under high traffic volumes.
        % \item Enhanced backend infrastructure by designing advanced Firebase schema modifications and optimizing database operations, ensuring seamless integration and robust data management across projects.
    \end{itemize}
\end{minipage}
\end{tabularx}
\begin{tabularx}{\linewidth}{ @{}l r@{} }
\color[HTML]{1C033C} \textbf{\uline{\href{https://iqnaut.com/}{Full Stack Developer Intern}}} \hfill \color[HTML]{371e77} Sept. 2024 - Jan. 2025 \\[4pt]
\color[HTML]{371e77}\textbf{\textit{Madrocket Technologies}}  \hfill \color[HTML]{4B28A4} \textit{ReactJS, Firebase, Product development, Software Testing} \\[5pt]
\begin{minipage}[t]{\linewidth}
   \begin{itemize}[nosep,after=\strut, leftmargin=2em, itemsep=2pt]
        \item Engineered a role-based school ERP system using Node.js, Firebase, and Firestore, enhancing security and user access for 1,000+ students and staff. Optimized database queries, reducing API response times by 40\%.
        % \item Integrated role-based access control (RBAC) and secure authentication, safeguarding 50+ critical features within the application.
        \item Conducted comprehensive testing with diverse datasets, achieving 99\% system reliability and resolving 100+ critical issues, ensuring a robust application launch.
        % \item Executed extensive load and stress testing across multiple web applications, independently orchestrating API benchmarking to fine-tune backend performance under high traffic volumes.
        \item Enhanced backend infrastructure by designing advanced Firebase schema modifications and optimizing database operations, ensuring seamless integration and robust data management across projects.
    \end{itemize}
\end{minipage}
\end{tabularx}

% Projects
\section{Projects}
\begin{tabularx}{\linewidth}{ @{}l r@{} }
\textbf{\uline{\href{https://kaarigarsathi-project.onrender.com/}{Kaarigar-Sathi | (Where skills meet needs)}}} \hfill Feb. 2024 - May. 2024 \\[4pt]
\color[HTML]{371e77}\textbf{\textit{Effortless Connections for Local Services. }} \hfill \color[HTML]{4B28A4} \textit{NodeJS, ExpressJS, MongoDB, ReactJS, JavaScript, HTML/CSS, Bootstrap} \\[5pt]
\begin{minipage}[t]{\linewidth}
    \begin{itemize}[nosep,after=\strut, leftmargin=2em, itemsep=2pt]
        \item  Implemented a real-time tracking feature that enabled users to monitor service progress, enhancing transparency and fostering a more reliable service experience; this feature is now used by 1,200 active users monthly.
        \item Revamped the user experience by implementing a location-based algorithm, resulting in a 40\% increase in successful connections between users and local tradespeople.
        \item  Architected an efficient API framework with Node.js and Express.js that supported high traffic volumes, enabling real-time data retrieval from a MongoDB database, thereby improving system response times by 40%.
    \end{itemize}
\end{minipage}
\end{tabularx}

\begin{tabularx}{\linewidth}{ @{}l r@{} }
\color[HTML]{1C033C} \textbf{\uline{\href{https://price-wise-theta.vercel.app/}{PriceWise}}} \hfill \color[HTML]{371e77} Oct. 2023 \\[4pt]
\color[HTML]{371e77}\textbf{\textit{Automated Price Tracker}} \hfill \color[HTML]{4B28A4} \textit{NextJs, MongoDB, Tailwind CSS} \\[5pt]
\begin{minipage}[t]{\linewidth}
    \begin{itemize}[nosep,after=\strut, leftmargin=2em, itemsep=2pt]
        \item Designed a full-stack app enabling 500+ users to track product prices in real-time, with URL-based monitoring.
\item Integrated Nodemailer for email notifications, sending welcome emails and real-time alerts .
\item Leveraged MongoDB for efficient data storage and price tracking, supporting seamless management of 10,000+ product records and ensuring high performance and scalability.

    \end{itemize}
    \end{minipage}
\end{tabularx}

% \begin{tabularx}{\linewidth}{ @{}l r@{} }
% \color[HTML]{1C033C} \textbf{\uline{\href{https://price-wise-theta.vercel.app/}{SnapWorld}}} \hfill \color[HTML]{371e77} July. 2024 - July. 2024 \\[4pt]
% \color[HTML]{371e77}\textbf{\textit{Capture.Share.Explore}} \hfill \color[HTML]{4B28A4} \textit{NextJs, MongoDB, Tailwind CSS} \\[5pt]
% \begin{minipage}[t]{\linewidth}
%     \begin{itemize}[nosep,after=\strut, leftmargin=2em, itemsep=2pt]
%         \item Developed secure user authentication and authorization, enabling effortless sign-in, sign-out, and profile updates to enhance the personalized user experience.
% \item Facilitated interactive content management capabilities, empowering users to upload, delete, and engage with posts from others, enhancing platform interactivity and user engagement.
% \item Integrated a robust search feature allowing users to find others by username, enhancing the social connectivity
% aspect of the platform and facilitating user discovery within the community.
%     \end{itemize}
%     \end{minipage}
% \end{tabularx}
% \begin{tabularx}{\linewidth}{ @{}l r@{} }
% \color[HTML]{1C033C} \textbf{\uline{\href{https://clone-f1ed7.web.app/}{MarketHub}}} \hfill \color[HTML]{371e77} Sep. 2023 \\[4pt]
% \color[HTML]{371e77}\textbf{\textit{Your Ultimate Shopping Destination}} \hfill \color[HTML]{4B28A4} \textit{ReactJS, Firebase, JavaScript, HTML/CSS, Bootstrap} \\[5pt]
% \begin{minipage}[t]{\linewidth}
%     \begin{itemize}[nosep,after=\strut, leftmargin=2em, itemsep=2pt]
%        \item Developed an e-commerce web application with Amazon-like functionality, managing 1,000+ user accounts securely.
% \item Designed a responsive and user-friendly front-end using React, featuring product listings and interactive shopping cart.
% \item Utilized Firebase to enhance account security, supporting secure user access management for 1,000+ accounts.
%     \end{itemize}
%     \end{minipage}
% \end{tabularx}


% % Leadership and Volunteering
% \section{Leadership and Volunteering}
% \begin{tabularx}{\linewidth}{ @{}l r@{} }
% \color[HTML]{1C033C} \textbf{Club de Algoritmia GDA} \hfill \color[HTML]{371e77} Jun. 2023 - Ongoing \\[5pt]
% \color[HTML]{371e77}\textbf{\textit{Board of Directors}} \\[5pt]
% \begin{minipage}[t]{\linewidth}
%     \begin{itemize}[nosep,after=\strut, leftmargin=2em, itemsep=2pt]
%         \item Guiding a community of 550+ CS students in their professional development, technical skills and interest in tech.
%         \item Orchestrating workshops, coding sessions, and events to enhance skills and encourage continuous learning.
%     \end{itemize}
% \end{minipage}
% \end{tabularx}

\section{Skills}
\color[HTML]{1C033C}\textbf{Languages:} \\[2pt]
\color[HTML]{371e77} \hspace*{4ex} Java, Javascript, TypeScript\\[3pt]
\color[HTML]{1C033C}\textbf{Technologies \& Tools:} \\[2pt]
\color[HTML]{371e77} \hspace*{4ex} {\color{1C033C}Backend:} Node.js, Express.js, MongoDB, Firebase, RESTful APIs, SQL\\[3pt]
\color[HTML]{371e77} \hspace*{4ex} {\color{1C033C}Frontend: }React.js, Next.js, Tailwind CSS\\[3pt]
\color[HTML]{371e77} \hspace*{4ex} {\color{1C033C}Tools:} Git, Postman, Github, Firestore\\[3pt]
\color[HTML]{371e77} \hspace*{4ex} {\color{1C033C}Other:} System Design, Performance Optimization, Role-Based Access Control\\[3pt]
\color[HTML]{1C033C}\textbf{Achievements} \\[2pt]
\color[HTML]{371e77} \hspace*{4ex}  Solved 800+ problems and earned 20+ badges on \textbf {Leetcode}.{\href{https://www.leetcode.com/uutkarshdixitt}{(Leetcode Profile)}}\\[3pt]
\color[HTML]{371e77} \hspace*{4ex}  Secured a Top 20 rank among 150+ teams at the HACK THIS FALL 2024 Hackathon held at Karnavati University.\\[3pt]
\color[HTML]{371e77} \hspace*{4ex}  Achieved a Top 10 rank among 100+ teams at the Code for Good Hackathon at Delhi Technical University.\\[3pt]
\color[HTML]{1C033C}\textbf{Certifications:} \\[2pt]
\color[HTML]{371e77} \hspace*{4ex} Earned Java Certification from {\href{https://www.hackerrank.com/certificates/fc443c9e8bad}{ HACKERRANK}}.

\end{document}
