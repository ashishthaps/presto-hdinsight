# presto-hdinsight
Run Presto on Azure HDInsight

# TL;DR 
Run a cutsom [action script](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-linux) on existing or new HDInsight cluster with following as your bash script URI and run it on "HEAD" and "WORKER":
```
https://raw.githubusercontent.com/dharmeshkakadia/presto-hdinsight/master/installpresto.sh
```

Now you can SSH to your cluster and run the following to start using presto:
```
presto --schema default
```
