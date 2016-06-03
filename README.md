# Big Data Analytics 2016
Big Data Analytics with Hadoop and Spark


### Setup Jupyter kernel

1. Create folder for kernels.
 ```bash
 mkdir -p ~/.ipython/kernels/pyspark
 ```

2. Create kernel file.
 ```bash
 touch ~/.ipython/kernels/pyspark/kernel.json
 ```

3. Example of a kernel file, modify it with your configuration:
 ```bash
 {
  "display_name": "pySpark (Spark 1.6.1)",
  "language": "python",
  "argv": [
   "/usr/bin/python27",
   "-m",
   "IPython.kernel",
   "-f",
   "{connection_file}"
  ],
  "env": {
   "SPARK_HOME": "<spark_dir>",
   "PYTHONPATH": "<spark_dir>/python/:<spark_dir>/python/lib/py4j-0.9-src.zip",
   "PYTHONSTARTUP": "<spark_dir>/python/pyspark/shell.py",
   "PYSPARK_SUBMIT_ARGS": "--master local[*] --packages graphframes:graphframes:0.1.0-spark1.6,com.databricks:spark-csv_2.10:1.4.0,org.apache.hadoop:hadoop-aws:2.6.0 pyspark-shell"
  }
 }
 ```
