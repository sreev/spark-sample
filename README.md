# Using Spark

## Using Spark Streaming - Stream & Process integers.

### Download & Install Spark

Download Spark [here](https://spark.apache.org/downloads.html)

```
% tar -zxf spark-2.4.7-bin-hadoop2.7.tgz
% cd spark-2.4.7-bin-hadoop2.7
```

### Build:
```
% git clone https://www.github.com/sreev/spark-sample.git
% cd spark-sample
% mvn clean package
```
_target folder has the built jar_


### Run:

`% bin/spark-submit --class org.sreev.spark.JavaQueueStream --master "local[2]" target/spark-sample-1.0-SNAPSHOT.jar`
