$
\documentclass[11pt,a4paper,sans]{moderncv}
% moderncv themes
\moderncvstyle{classic}
\moderncvcolor{blue}

\usepackage{amssymb}
\usepackage{xcolor}
\usepackage{verbatim}
% character encoding
\usepackage[utf8]{inputenc}                   % replace by the encoding you are using
% For comments and modification
\usepackage{soul}
% adjust the page margins
\usepackage[scale=0.82]{geometry}
% \usepackage[left=1cm,right=1cm,top=1cm,bottom=1cm]{geometry}
%\setlength{\hintscolumnwidth}{3cm}						% if you want to change the width of the column with the dates
%\AtBeginDocument{\setlength{\maketitlenamewidth}{6cm}}  % only for the classic theme, if you want to change the width of your name placeholder (to leave more space for your address details
%\AtBeginDocument{\recomputelengths}                     % required when changes are made to page layout lengths


% personal data
\firstname{Fan}
\familyname{Zhang}
\mobile{+86 188-1139-3669}                    % optional, remove the line if not wanted
\email{zfdaidai@gmail.com}                      % optional, remove the line if not wanted
\homepage{zhang-f.github.io/cv}                % optional, remove the line if not wanted
\social[github]{zhang-f}

% to show numerical labels in the bibliography; only useful if you make citations in your resume
%\makeatletter
%\renewcommand*{\bibliographyitemlabel}{\@biblabel{\arabic{enumiv}}}
%\makeatother

%\nopagenumbers{}                             % uncomment to suppress automatic page numbering for CVs longer than one page
%----------------------------------------------------------------------------------
%            content
%----------------------------------------------------------------------------------
\begin{document}
\maketitle

\section{Education}
\cventry{\footnotesize August 2017 \\ -- July 2021}{\href{https://www.tsinghua.edu.cn}{Tsinghua University,}}{}{Beijing, China}{}{B.Eng. (Expected) in \href{http://www.ee.tsinghua.edu.cn/}{\color{blue} Electronic  Engineering}}
\cvline{}{\textbf{GPA:} 3.43/4.0 }
%\cvline{}{\textbf{Course Highlights:} Fundamentals of Computer Graphics ($A^+$), Database Special Topic Training ($A^+$), Data Structures ($A$), Artificial Neural Networks ($A$), Foundation of Object-Oriented Programming ($A$)}

%\section{Publications and/or Submitted Manuscripts}
%
%\cvline{\footnotesize August 2019}{\textbf{\href{https://trinkle23897.github.io/cv/viz2018.html}{Playing FPS Game with Environment-aware Hierarchical Reinforcement Learning}}}
%\cvline{}{
%\href{http://bellasong.site/}{Shihong Song*}, 
%\href{https://trinkle23897.github.io/cv}{\textbf{Jiayi Weng*}}, 
%\href{http://www.suhangss.me/}{Hang Su}, Dong Yan, Haosheng Zou, and \href{http://ml.cs.tsinghua.edu.cn/~jun/index.shtml}{Jun Zhu}
%\newline The 28th International Joint Conferences on Artificial Intelligence (IJCAI 2019). Oral Presentation. Acceptance rate: 17.9\% (850/4752). {\scriptsize *co-first author}}
%
%\cvline{\footnotesize November 2018}{\textbf{\href{https://trinkle23897.github.io/cv/urber.html}{URBER: Ultrafast Rule-Based Escape Routing Method for Large-Scale Sample Delivery Biochips}}}
%\cvline{}{
%\href{https://trinkle23897.github.io/cv}{\textbf{Jiayi Weng}}, 
%\href{http://www.cs.nthu.edu.tw/~tyho/}{Tsung-Yi Ho}, Weiqing Ji, 
%\href{http://1.202.132.116:8080/cms/wwwroot/baswqhsys/zxcy/zxsz/13763.shtml}{Peng Liu}, Mengdi Bao, and 
%\href{http://biocad.cs.tsinghua.edu.cn/static/hailongyao.html}{Hailong Yao}
%\newline IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)}
%
%\cvline{\footnotesize March 2019}{\textbf{\href{https://trinkle23897.github.io/cv/rmdp.html}{Model-based Credit Assignment for Model-free Deep Reinforcement Learning}}}
%\cvline{}{Dong Yan, \href{https://trinkle23897.github.io/cv}{\textbf{Jiayi Weng}},  \href{http://ml.cs.tsinghua.edu.cn/~shiyu/}{Shiyu Huang}, \href{http://ml.cs.tsinghua.edu.cn/~chongxuan/}{Chongxuan Li}, Yichi Zhou, \href{http://www.suhangss.me/}{Hang Su}, and \href{http://ml.cs.tsinghua.edu.cn/~jun/index.shtml}{Jun Zhu}
%\newline IEEE Transactions on Neural Networks and Learning Systems (TNNLS), Submitted}

\section{Professional Experiences}

%\cventry{\footnotesize March 2019 -- October 2019}{\href{http://mila.quebec/en}{Montreal Institute for Learning Algorithms (MILA)}}{}{\href{https://www.umontreal.ca/}{\hfill Université de Montréal (UdeM)} \newline Advisor: Professor \href{https://mila.quebec/en/yoshua-bengio/}{\color{blue} Yoshua Bengio}}{}{Worked on Rule-Transformer based on \href{https://arxiv.org/abs/1709.08568}{the Consciousness Prior}
%\begin{itemize}
%\item Proposed the Rule-Transformer model by integrating the Consciousness Prior and programming language into \href{https://arxiv.org/abs/1706.03762}{Transformer architecture} for better disentanglement
%\item Implemented the Rule-Transformer by incorporating a novel self-attention mechanism \textit{Rule-Attention} into both the encoder and decoder of Transformer model
%\item Validated the proposed model in various scenarios, including language modeling, machine translation, natural language inference, and multi-task imitation learning
%\end{itemize}
% }
\cventry{\footnotesize July 2019\\ -- present}{\href{http://network.ee.tsinghua.edu.cn/niulab/}{Edge learning and Edge coding}}{}{\hfill Tsinghua University \newline Advisor: Professor 
	\href{http://network.ee.tsinghua.edu.cn/shengzhou/}{\color{blue} Sheng Zhou
		% \& \href{http://www.suhangss.me/}{\color{blue} Hang Su}
}}{}{ 
	\begin{itemize}
		\item Considered a tree network structure on the basis of distributed network.Proved that the tree network structure can effectively reduce the communication cost and reduce the influence of stragglers.Considered the minimum delay and minimum energy loss in a heterogeneous network with multiple base stations and multiple edge servers
		\item Build a distributed computing architecture on amazon EC2 and conduct relevant experiments
		\item Plan to finish the paper in March
%		\item Proposed an environment-aware hierarchical reinforcement learning algorithm. \textbf{We achieved the first place in \href{http://vizdoom.cs.put.edu.pl/competitions/vdaic-2018-cig}{\color{blue} VizDoom AI Competition 2018}}, and \href{https://www.ijcai.org/proceedings/2019/0482.pdf}{\textbf{our work is accepted by IJCAI 2019}}
%		\item Proposed an efficient model-based deep reinforcement learning algorithm which incorporates first-order logic and reward shaping leveraging on Relational Markov Decision Process. \textbf{Our work is under review by TNNLS} \href{https://github.com/sproblvem/tianshou}{Tianshou} by changing the structure of frame buffer and adding parallel training, which was 10x faster than previous version within DQN, A2C, DDPG, and PPO algorithms
	\end{itemize}
}

\cventry{\footnotesize March 2019 \\-- June 2019}{Run machine learning experiments on lab servers}{}{\hfill Tsinghua University \newline Advisor: PhD Candidate \href{http://network.ee.tsinghua.edu.cn/niulab/?p=3649}{\color{blue} Xiufeng Huang}}{}{
	\begin{itemize}
		\item Considered distributed systems with multi-user machine learning tasks.My main job was to implement machine learning code on the GPU in the lab
	\end{itemize}
}

%\section{Selected Awards and Honors}
%
%\cventry{\footnotesize November 2018}{Comprehensive Excellence Award}{}{\hfill Tsinghua University}{}{Top 5\% of 171 students}
%
%\cventry{\footnotesize August 2018}{Rank 1st,}{}{}{\href{http://vizdoom.cs.put.edu.pl/competitions/vdaic-2018-cig}{VizDoom AI Competition 2018 Single Player Track(1)} \newline \textcolor{white}{,} \hfill{\href{https://project.dke.maastrichtuniversity.nl/cig2018/}{IEEE Computational Intelligence and Games (CIG) 2018}}}{
%\href{http://vizdoom.cs.put.edu.pl/}{VizDoom AI Competition} is famous in the reinforcement learning community, and our team achieved the best score among 51 teams
%}
%
%\cventry{\footnotesize September 2017}{Highest Score,}{}{11th CCF Certified Software Professional (CSP)\newline \textcolor{white}{,} \hfill{China Computer Federation (CCF)}}{}{Top 0.02\% of 6414 participants}
%
%% \cventry{\footnotesize July 2015}{Bronze Prize}{}{National Olympiad in Infomatics (NOI), issued by China Computer Federation (CCF)}{}{}
%
%\section{Selected Course Projects}
%
%%\cvline{}{Proficient in Python and C++. Capable of Java, LaTeX, Matlab, JavaScript, HTML/CSS.}
%\cvline{}{For more infomation, please refer to this \href{https://github.com/Trinkle23897/Undergraduate}{\color{blue} GitHub link} ($\bigstar$404 by 11/11/2019)}
%\cventry{\footnotesize June 2018}{Realistic Image Rendering}{}{\hfill  Fundamentals of Computer Graphics}{}{Implemented Path Tracing (PT), Progressive Photon Mapping (PPM), and Stochastic Progressive Photon Mapping (SPPM) algorithms. Rendered 3D models with Bezier surface. Proposed a novel algorithm for solving the intersection of line and rotating Bezier curve. $\bigstar$58 on \href{https://github.com/Trinkle23897/Computational-Graphics-THU-2018}{\color{blue} GitHub} by 11/11/2019}
%
%% \cventry{\footnotesize January 2019}{MIPS32 CPU}{}{\hfill Computer Organization}{}{Designed and implemented a complete CPU that supports the 32-bit MIPS instruction set with TLB module, precise exception handling, and VGA extension. $\bigstar$ 53 on \href{https://github.com/Trinkle23897/mips32-cpu}{\color{blue} GitHub} by 10/22/2019}
%
%\cventry{\footnotesize January 2018}{Login Security}{}{\hfill Network Security Engineering and Practice}{}{Measured the login security of all campus websites and found a serious security vulnerability for all sites. The campus network was therefore fully upgraded}
%
%\cventry{\footnotesize June 2017}{Escape Routing}{}{\hfill Foundation of Object-Oriented Programming}{}{Designed and implemented a heuristic escape routing method which was fundamentally faster than previous network-flow-based proposals. Follow-up work has been published in IEEE Trans. on CAD}

\section{Extracurricular Activities and Competitions}

\cventry{\footnotesize Augest 2017 \\-- July 2018}{Member of Student Association for Science and Technology}{}{\hfill Tsinghua University}{}{Organized and participated in a number of technological innovation events, including the 18th technological innovation competition and the first hackathon}

\cventry{\footnotesize Augest 2018 \\-- December 2018}{Team leader of The 20th Electronic Design Competition}{}{\newline \textcolor{white}{,}\hfill Tsinghua University}{}{
	\begin{itemize}
		\item Code on STM32 microcontroller to control the trolley.Use infrared sensor and ultrasonic device to aviod structure and use wifi system to abtain the location information from the host computer
		\item Won The Winning Award in 67 teams
	\end{itemize}
}

\cventry{\footnotesize March 2019 \\-- May 2019}{Member of The Second Artificial Intelligence Challenge Competition}{}{\hfill Tsinghua University}{}{
	\begin{itemize}
		\item Submit four AI codes for each team to control four characters, cooperate with each other to kill all non-teammates in the map.
		\item Entered The Finals in 127 teams
	\end{itemize}
}

\cventry{\footnotesize September 2019 \\-- December 2019}{Member of The Practice of Intelligent Robot Design}{}{\hfill Tsinghua University}{}{
	\begin{itemize}
		\item Write code to control the robot to avoid obstacles, cross the gully, identify traps and identify traffic lights.Simultaneously control the robot's steering gear to adjust the motion
		\item Won the 3'rd Place Award and the Best Performance Award
	\end{itemize}
}

\section{Skills}
\cvline{}{\textbf{Programming Languages:} \small Python, C/C++, MATLAB, Verilog, Go, HTML,}
\cvline{}{\textbf{Tools and Frameworks:} \small Git, \LaTeX, PyTorch, TensorFlow, OpenCV, django}
%\cvline{}{\textbf{Amateur Hobbies:} \small Photography}

\end{document}
$
