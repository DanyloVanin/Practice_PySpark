

## Resources
- [PySpark Container](https://github.com/bitnami/containers/blob/main/bitnami/spark/docker-compose.yml)
- [Difference Between Hadoop and Spark](https://www.geeksforgeeks.org/difference-between-hadoop-and-spark/)
- [Hadoop vs. Spark: Not Mutually Exclusive but Better Together](https://www.projectpro.io/article/hadoop-vs-spark-not-mutually-exclusive-but-better-together/235)
- [Getting Started with PySpark](https://medium.com/analytics-vidhya/getting-started-with-pyspark-251a0af0f2c4)
- [How to use PySpark on your computer](https://towardsdatascience.com/how-to-use-pyspark-on-your-computer-9c7180075617)

## To run

1. Start Spark
```sh
docker-compose up --detach
```


## Jupyter

Running notebook with Spark
```sh
docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
```
