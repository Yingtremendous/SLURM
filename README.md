# SLURM

SuperMUC-NG (MUC Flughafencode des Münchener Flughafens), 6480 REchenknoten, jeweils 48 kernen, Suse Linux, Batch SCheduling system ist das SLURM, Filesystem is IBM Spectrum Scale. 

different cluster: eine Anzahl von vernetzten Computern. Die in einem CLuster befindlichen Computer (Knoten) werden oft als Sserverfarm bezeichnet. 

Storage Systems: Filesystem: IBM Spectrum Scale (General Parallel File System)
  Support hybrid cloud (big data and artificial intelligence workloads along with traditional applications while ensuring security, reliability, data efficiency and high performance. 
  
Environment module system 
Slurm Workload manager

* Supercomputer
  * many CPUs and compute nodes
  * nodes are connected by a high-speed internal network
  * diskles
  * access to paralell file system (Lustre, GPFS)
  * not directly access, login nodes, SSH, a batch scheduler application 
  * Communication (MPI: message passing interface) between nodes and OpenMP(open multi-processing)
