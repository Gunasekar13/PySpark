# PySpark
https://colab.research.google.com/drive/1G894WS7ltIUTusWWmsCnF_zQhQqZCDOc
search the above link and create a new file 
after that follow above the create Pyspark in colab.

What is RDD?
    Rdd is resilient distributed dataset , The data will be distributed across the multiple nodes.RDD is collection of immutable objects.Once the rdd is created we cann't able to delete but we can able to transform the data.

Types of RDD creation?
     1)Parallelize 
           ex: rdd1=spark.sparkContext.parallelize(data)
     2)Read the file
           ex: To read csv,avro,parquet,ect
     3)create a new rdd from external rdd

What is sparkContext?
     In spark 1.x architecture we need to create context  for each .It main entery point of spark.
     
what is SparkSession?
      In Spark 2.x architecture all context are under the single unit that is called SparkSession.
	
What is UDF?
      UDF mean's user defined function. User can explore the Own function. In pyspark UDF is solw, because the query first convert to the JVM after that will be runing.
      

