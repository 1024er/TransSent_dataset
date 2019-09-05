This is the three datasets we constructed for Sentence Transfer tasks.

\begin{itemize}
\item\textbf{Yelp-dm} is extracted from a sentiment domain corpus Yelp, examples in Yelp dataset are from business review website $Yelp$.
\item\textbf{Wiki-dm} is extracted from an open domain corpus WikiText-103\cite{merity2016pointer}, which consists of Wikipedia articles. 
\item\textbf{Book-dm} is extracted from another open domain corpus BookCorpus~\cite{zhu2015aligning}, which consists of text from unpublished novels.
\end{itemize}

\begin{table}[htbp]
\small
\centering
\caption{Dataset statistics. Each discourse marker has the same amount in train/dev/test sets. }\label{tab2}
\begin{tabular}{ccccc}
\toprule
Dataset &Train &Dev &Test \\
\midrule
YELP-dm &10K &1K &1K \\
\midrule
Wiki-dm &80K&5K&3K \\
\midrule
Book-dm &400K&30K&30K \\
\bottomrule
\end{tabular}
\end{table}
