# big-data-starter
Setup for big data development environment
`fish`
```
  set JAVA_HOME <your java dir>
  set JRE_HOME <your jre dir>

  set BIG_DATA_HOME <this repo>
  set HADOOP_HOME $BIG_DATA_HOME/hadoop
  set HADOOP_INSTALL $HADOOP_HOME
  set HADOOP_MAPRED_HOME $HADOOP_HOME
  set HADOOP_COMMON_HOME $HADOOP_HOME
  set HADOOP_HDFS_HOME $HADOOP_HOME
  set HADOOP_YARN_HOME $HADOOP_HOME
  set YARN_HOME $HADOOP_HOME
  set HADOOP_COMMON_LIB_NATIVE_DIR $HADOOP_HOME/lib/native
  set PATH $PATH $HADOOP_HOME/sbin $HADOOP_HOME/bin
  set PATH $PATH $JAVA_HOME/bin

  set FLUME_HOME $BIG_DATA_HOME/flume
  set FLUME_CONF $BIG_DATA_HOME/flume/conf/
  set PATH $PATH $FLUME_HOME/bin
```
