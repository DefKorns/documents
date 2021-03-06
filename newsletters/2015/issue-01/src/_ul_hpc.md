\vspace{-2em}
\resizebox{1.0\textwidth}{0.65\textwidth}{
 \centering 
 \begin{tikzpicture}[mindmap, level 1 concept/.append style={level distance=6cm}]
    \begin{scope}[mindmap, concept color=blue!60, text=white]
    \node[concept,text width=14em] (compute) {\textbf{404 computing nodes: 4316 cores, 49.9 TFlops}}
      [clockwise from=75]
      child { node[concept,scale=1.1] (rooms) {\textbf{3 server rooms: 2 in Kirchberg, 1 in Belval}}}
      child { node[concept,scale=1.1] (clusters) {\textbf{4 clusters: 2 production, 2 research}}}
      child { node[concept,scale=1.1] (servers)  {\textbf{147 servers: 37 physical and 110 Virtual Machines}}};
    \end{scope}
    \begin{scope}[mindmap, concept color=green!50!yellow!70!black, text=white]
      \node[concept,text width=8em] (storage) at (8.5,5) {\textbf{3368 TB total storage}}
      [clockwise from=0]
      child { node[concept,scale=1.1] (backup) {\textbf{1712 TB for backup}}};
    \end{scope}
    \begin{scope}[mindmap, concept color=red!60, text=white]
      \node[concept] (sysadmins) at (12,0) {\textbf{4 system \\ administrators}}
      [clockwise from=225]
      child { node[concept,scale=1.1,text width=6em] (sysadmindiv) {\textbf{3 at FSTC \& 1 at LCSB}}};
    \end{scope}
%    \begin{scope}[mindmap, concept color=gray!60, text=white]
%      \node[concept,text width=12em] (services) at (7,-9) {\textbf{Complementary \\ services}}
%      child { node[concept,scale=1.1,text width=8em] (virt) at (-4,8) {\textbf{Virtualization: on demand VMs for R\&D}}}
%      child { node[concept,scale=1.1,text width=8em] (collab) at (-4,3) {\textbf{Collaboration: \\ GForge {\tiny (Git, SVN)} \\ Gitlab \\ Etherpad \\ Jabber}}}
%      child { node[concept,scale=1.1,text width=8em] (bioinf) at (6,9) {\textbf{Bioinformatics: \\ Galaxy}}}
%      child { node[concept,scale=1.1,text width=8em] (cloud) at (4,3) {\textbf{Cloud: \\ OpenStack}}}
%      child { node[concept,scale=1.1,text width=8em] (cloud) at (-2,0) {\textbf{BigData storage \\ OwnCloud}}};
%    \end{scope}
  \end{tikzpicture}
}

## UL HPC Statistics

The [UL HPC](http://hpc.uni.lu) platform has continuously evolved since the initial computing servers ordered in 2006.
The HPC equipment is based on both classical Commercial off-the shelf (COTS) and specialized products.
\begin{tcolorbox}
  The \ulhpc features as of march 2015, \underline{\textbf{49.9 TFlops}} for computations
  (over 4316 computing cores) and \underline{\textbf{3 PetaBytes}} for storage (incl.
  1.7 PB for backups).
\end{tcolorbox}

\noindent
The evolution of both computing and storage capacity, is depicted in the below figures.
\begin{figure}[htbp]
  \centering
  \includegraphics[width=0.7\textwidth]{ul_hpc_evolution_computing}
  \includegraphics[width=0.7\textwidth]{ul_hpc_evolution_storage}
  %\caption{UL HPC computing and storage capacity evolution}
\end{figure}

As of March 2015, **281 users** are registered and active on the platform.
The used computing effort in 2014 by the registered users is measured as **1407 CPUYears** , thus performed in a single year period.
