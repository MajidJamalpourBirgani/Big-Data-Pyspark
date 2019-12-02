# Big-Data-Pyspark

Apache Spark : The Unified Analytics Engine

The largest open source project in data processing framework that can do ETL, analytics, 
machine learning and graph processing on large volumes of data at rest (batch processing)
or in motion (streaming processing) with rich high-level APIs for the programming languages
like Scala, Python, Java and R.

Spark has seen immense growth over the past several years. Hundreds of contributors working collectively
have made Spark an amazing piece of technology powering the de facto standard for big data processing and
data sciences across all industries.

Internet powerhouses such as Netflix, Yahoo, and eBay have deployed Spark at massive scale, collectively processing
multiple petabytes of data on clusters of over 8,000 nodes.

Why Spark ?
Typically when you think of a computer you think about one machine sitting on your desk at home or at work. This machine
works perfectly well for applying machine learning on small dataset . However, when you have huge dataset(in tera bytes or
giga bytes), there are some things that your computer is not powerful enough to perform. One particularly challenging area is
data processing. Single machines do not have enough power and resources to perform computations on huge amounts of information
(or you may have to wait for the computation to finish).

A cluster, or group of machines, pools the resources of many machines together allowing us to use all the cumulative resources as
if they were one. Now a group of machines alone is not powerful, you need a framework to coordinate work across them. Spark is a tool
for just that, managing and coordinating the execution of tasks on data across a cluster of computers.

Spark Architecture
Apache Spark allows you to treat many machines as one machine and this is done via a master-worker type architecture where there is
a driver or master node in the cluster, accompanied by worker nodes. The master sends work to the workers and either instructs them 
to pull to data from memory or from disk (or from another data source).

Read more about Architecture

https://spark.apache.org/docs/latest/cluster-overview.html
