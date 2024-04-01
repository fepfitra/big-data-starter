# big-data-starter
Setup for big data development environment
`fish`
```
  set JAVA_HOME /usr/lib/jvm/java-8-openjdk/
  set JRE_HOME /usr/lib/jvm/java-8-openjdk/jre

  set HADOOP_HOME /usr/local/hadoop
  set HADOOP_INSTALL $HADOOP_HOME
  set HADOOP_MAPRED_HOME $HADOOP_HOME
  set HADOOP_COMMON_HOME $HADOOP_HOME
  set HADOOP_HDFS_HOME $HADOOP_HOME
  set HADOOP_YARN_HOME $HADOOP_HOME
  set YARN_HOME $HADOOP_HOME
  set HADOOP_COMMON_LIB_NATIVE_DIR $HADOOP_HOME/lib/native
  set PATH $PATH $HADOOP_HOME/sbin $HADOOP_HOME/bin
  set PATH $PATH $JAVA_HOME/bin

  set FLUME_HOME /usr/local/flume
  set FLUME_CONF /usr/local/flume/conf/
  set PATH $PATH $FLUME_HOME/bin
```
