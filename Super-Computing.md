__HPC, Distributed Computing, Cloud computing, Cluster computing, Grid computing, Parallel computing, etc..__

+ [Computer Performance](#computer-performance)
+ [CONCURRENCY](#concurrency)
   + [Cloud-Cluster](#cloud-cluster)
       + [AWS](#aws)
       + [APACHE](#apache)
   + [Distributed Computing](#distributed-computing)
   + [Grid Computing](#grid-computing)
   + [HPC](#hpc)
   + [Job Scheduler](#job-scheduler)
   + [Parallel Computing](#parallel-computing)

----

# Computer Performance
+ [Boxfish](https://github.com/scalability-llnl/boxfish) :: A platform for visualizing performance data across the domains the data was collected, (e.g. communication groups) to another (e.g. hardware processes).    
+ [PeachPy](https://github.com/Maratyszcza/PeachPy) :: A Python framework for writing high-performance assembly kernels - an efficient Assembly Code-generator in Higher-level Python.

----

# CONCURRENCY

## Cloud-Cluster
+ [arrayfire-python](https://github.com/arrayfire/arrayfire-python) :: A high performance library for parallel computing with an easy-to-use API.
+ [clusterlib](https://github.com/clusterlib/clusterlib) :: Tools to manage jobs on supercomputer. [Documentation](http://clusterlib.readthedocs.org/)
+ [Curio](https://github.com/dabeaz/curio) :: The coroutine concurrency library.
+ [lustre_kvm_quickstart](https://github.com/suykerbuyk/lustre_kvm_quickstart) :: Support scripts for the Lustre KVM. Quick Start Guide at :  http://wiki.lustre.org/KVM_Quick_Start_Guide
+ [Pathos](https://github.com/uqfoundation/pathos) :: A framework for parallel graph management and execution in heterogeneous computing. It primarily provides the communication mechanisms for configuring and launching parallel computations across heterogenous resources. Pathos provides configurable launchers for parallel and distributed computing, where each launcher contains the syntactic logic to configure and launch jobs in an execution environment.
+ [Pyina](https://github.com/uqfoundation/pyina) :: a MPI-based parallel mapper and launcher.
+ [Ufora](https://github.com/ufora/ufora) :: A compiled, automatically parallel subset of python for data science and numerical computing.

### AWS
+ [AmazonEC2scripts](https://github.com/swederik/AmazonEC2scripts) :: Useful scripts to setup Amazon EC2 Cloud Compute servers for Neuroimaging.
+ [Anaconda-ec2](https://github.com/ContinuumIO/anaconda-ec2) :: Anaconda plugin for StarCluster.
+ [Boto](https://pypi.python.org/pypi/boto) :: A Python package that provides interfaces to Amazon Web Services. The [source code](https://github.com/boto/boto/) on github.
+ [Cloudman](https://bitbucket.org/chapmanb/cloudman) :: Easily create a compute cluster on top of a cloud computing infrastructure.
+ [kappa](https://github.com/garnaat/kappa) :: Kappa is a command line tool that makes it easier to deploy, update, and test functions for AWS Lambda.
+ [StarCluster](http://star.mit.edu/cluster) is an open source cluster-computing toolkit for Amazon's Elastic Compute Cloud (EC2). [Source code on Github](https://github.com/jtriley/StarCluster)

### APACHE 
+ [SparklingPandas](https://github.com/holdenk/sparklingpandas) :: Make it easy to use the distributed computing power of [PySpark](http://spark.apache.org/) to scale your data anlysis with Pandas.
+ [Kazoo](https://github.com/python-zk/kazoo) :: A high-level Python library that makes it easier to use Apache Zookeeper. [Documentation](https://kazoo.readthedocs.org).

#### Hadoop
+ [Hue](https://github.com/cloudera/hue) :: A Web application for interacting with Apache Hadoop that supports a file and job browser, Hive, Pig, Impala, Spark, Oozie, HBase, Solr, Sqoop2, ZooKeeper and more.

###### Resources
+ [Native Hadoop file system (HDFS) connectivity in Python](http//wesmckinney.com/blog/python-hdfs-interfaces/) .
+ Blog post on [Querying 1.7 Billion Reddit Comments with Anaconda Platform Tools on Hadoop](https://www.continuum.io/blog/developer-blog/querying-17-billion-reddit-comments-anaconda-platform).

## HPC
+ [Dask](http://dask.pydata.org) :: Task scheduling and blocked algorithms for parallel processing. [Source code](https://github.com/ContinuumIO/dask) and [Documentation](https://dask.pydata.org/en/latest/).
+ [Luigi](https://github.com/spotify/luigi) :: A Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built in.
+ [Pyston](https://github.com/dropbox/pyston) : An open-source Python implementation using JIT techniques, built using LLVM for performance speed. Their blog [introducing Pyston](https://tech.dropbox.com/2014/04/introducing-pyston-an-upcoming-jit-based-python-implementation/)
+ [PySGE](https://github.com/jiahao/PySGE) : Low-level Python interface to Sun Grid Engine. 
+ [Pythran](https://pypi.python.org/pypi/pythran) : A Static Compilation of Parallel Scientific Kernels a.k.a. Python/Numpy compiler for the mass. [Source Code](https://github.com/serge-sans-paille/pythran) on Github.

###### Resources
+ PyData Paris [talk slides](https://serge-sans-paille.github.io/talks/pydata-2015-04-03.html#/0/1).
   

