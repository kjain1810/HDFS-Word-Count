# Word Count on a HDFS Cluster

Running the basic job of a word count on a HDFS cluster with Maven.

## Running Instructions

HDFS should be set up properly on the system

```bash
mvn package
mvn compile
hadoop jar target/wordcountjava-1.0-SNAPSHOT.jar  org.apache.hadoop.examples.WordCount <input file> <output file>
```

