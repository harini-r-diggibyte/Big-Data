# BIG DATA #

## INTRODUCTION ##
Big data is a collection of data which is huge in volume , grows exponentially with time.
It is a combination of structure, semi-structured or unstructured data.
Due to the huge volume and complexity, traditional databases fails to store or process it.

####  CHARATERISTICS OF BIG  DATA ####

Characteristics which need to be considered while dealing with Big data solution.
 - Volume – deals with amount of data
 - Value – quality of data (reliable and valuable data that we store, process, analyse)
 - Velocity – speed of generation of data.(i.e) speed in transaction and speed in processing
 - Variety – different formats of data (structured / semi-structured/unstructured) from various sources 

#### HDFS ####
Hadoop distributed file system HDFS.
Hadoop consists of HDFS and Map Reduce.
Hadoop framework consists of HDFS, MR, Hive.

###### METADATA ######
Metadata is data about data. It provides additional information about a specific set of data.

#### HADOOP ####
Hadoop is a distributed framework that makes it easier to process large data sets that reside in cluster of computers.
Hadoop provides a method to access the data that is distributed among multiple cluster, process the data and manage the resources.
Hadoop follows master slave architecture.
The modules in the hadoop are
  - HDFS Hadoop Distributed File Systems
  - Map Reduce
  - Yarn
  
#### HDFS ####
Similar to data residing in a local file system of a computer, in hadoop data resides in a distributed file system called Hadoop Distributed File System.
 - This takes care of the storage part of hadoop applications.
 - HDFS created multiple replica of data blocks, distribute them on compute nodes in a cluster.
 - This distribution enables reliable and rapid computations.

#### MAP REDUCE ####
Map reduce is a massive parallel processing technique used for processing data distributed on a cluster.
Hadoop deals with data in form of key_value pairs.
map reduce divides the task into two phases, 
 - map
 - reduce     
mapper formats the data into key-value pairs and inputs the key-value pairs to an intermediate key-value pairs.
Maps are the individual tasks that transform input records into intermediate records.
The process of transferring the intermediate records from map to where they are required by reducers is known as shuffling.
Reducers sort the itermediate records.
All of the values with same key are gathered in a single reducer together and the output is stored locally.

#### YARN ####
YARN - Yet Another Resource Negotiator.
It is the resource management layer of hadoop.
It provides the framework to schedule jobs and manage resources across the clusters that holds data.
 - Resouce manager - to manage the use of resources across the clusters
 - Node managers - for launching and monitoing computer containers on machines in the cluster.

#### HIVE ####
 - Hive is an open source data warehouse system built on hadoop for  querying and analysing large data sets stored in hadoop.
 - Hive uses a language called HQL (Hive Query Language) which is similar to SQL queries, which gets internally converted into Mapreduce jobs.
 - Hive organises data into tables.The Hive generally runs on your workstation and converts your SQL query into a series of jobs for execution on a Hadoop cluster. 

