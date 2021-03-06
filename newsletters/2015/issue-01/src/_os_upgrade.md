## OS/Software Upgrades

\begin{tcolorbox}
As part of our commitment to constantly improve the services offered by the HPC
platform, we will proceed with an upgrade of the underlying software running the 
platform during Q1 and Q2 2015.
\end{tcolorbox}

\noindent
This includes the upgrade of the Operating System (OS) of all components to  [Debian 7 (Wheezy)](https://www.debian.org/releases/wheezy/), but also the upgrade of the software offered via [modules](http://modules.sourceforge.net/)/[Lmod](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod) with the new [RESIF](http://resif-pypi.readthedocs.org/en/latest/) framework. 

\noindent
To be as seamless as possible, these upgrades will be performed in a step-wise approach:

1. half of [gaia](https://hpc.uni.lu/systems/gaia/) (`gaia-83` to `gaia-154`) will be migrated to Debian 7 on **April 6th**, to benefit from the day off.
This phase is intended to last **three weeks**, giving enough time for everybody to adapt and test their workflow on the future configuration;
2. the rest of [gaia](https://hpc.uni.lu/systems/gaia/) will be  migrated to Debian 7 on **April, 27th**.
Also, the home directories of Gaia will be migrated from the current NFS storage server to a distributed GPFS setup;
3. the [chaos](https://hpc.uni.lu/systems/chaos/) cluster will be upgraded following gaia, _i.e._ on **April 28th**.

\noindent
The HPC team will strive to minimize the downtime of the clusters, with access
always being kept open to either Gaia or Chaos.

<!---
The operations outlined above will be performed on the following dates:

* Phase 1: March 16th 2015, Gaia under maintenance for 8h
* Phase 2: April 7th 2015, Gaia under maintenance for 8h
* Phase 3: April 14th 2015, Chaos under maintenance for 8h
-->
