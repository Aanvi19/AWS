AWS EC2 Types ---

1. General Purpose Instacnce ---
balanced for compute, networking, memory.
ideal for web servers, small database, application server,test enviorment.

t series: t4g,T3,T2 (cost effective,CPU Permission ) m series : M7g,M4,M5

2. Compute Optimized: optimized for compute-intensive task
ideal for high-performance web servers, batch-processing,machine learning interface,and gaming servers.

example : Gaming Server
C series : C7g.C6i

3.Memory Optimized : optimized for memory intensive applications

ideal for in-memory database like redis or Memcached.

R series: R7g.R6i
X series : x2idn,x2iedn.
z1d series : high memory with cpu performance.

4.Storage Optimized : Optimized for storage-intensive task with low-latency,high iops.
ideal for large-scale database, data warehousing and disturbed file systems.

series :
I :I4i, I3en
D :D3,D2
H : H1

5.Accelarated Optimized :
Equopped with GPU or FPG
Ideal for deep learning, Machine Learning,

series : 
P 
G
Inf
F

6.HPC Optimized

High performance Computing for HPC Workloads
example : Hpc7g

7.MAC Instances
Optimized for MACos workload
macos application development.

example : mac1.metal

##EC2 pricing details##
```
a> ondemand
2> spot
3>Reserve
4>dedicated
5> compute savings plan
```


