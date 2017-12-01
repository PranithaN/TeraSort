# TeraSort
TeraSort application sorts a data of size implemented in 3 different ways: Java, Hadoop and Spark.
1. Shared-Memory TeraSort: TeraSort is multi-threaded (to process large files concurrently), and runs on 1 virtual node. The performance evaluation was done on Amazon EC2 on a “d2.xlarge” instance. Time to execute the application on datasets on 1 node by varying number of threads is evaluated.
2. Hadoop & Spark: Installed Hadoop(including the HDFS distributed file system) and Spark on a 16 node virtual Amazon ec2 d2.xlarge and c3.large instance cluster on which hadoop terasort and spark terasort (python) applications were implemented. The performance is evaluated by varying number of nodes from 1 to 16.
