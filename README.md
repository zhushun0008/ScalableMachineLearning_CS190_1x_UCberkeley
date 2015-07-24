# ScalableMachineLearning_CS190_1x_UCberkeley
* [itertools模块中product的例子](http://woodpecker.org.cn/diveintopython3/advanced-iterators.html)
* [Python中的map](http://my.oschina.net/zyzzy/blog/115096)



### Reference 
* [Spark's Python API](https://spark.apache.org/docs/latest/api/python/pyspark.html#pyspark.RDD)
* [NumPy Reference](http://docs.scipy.org/doc/numpy/reference/index.html)

#### Detail of APIs used
##### Lab 04
* SparseVector
    * [pyspark.mllib.html#pyspark.mllib.linalg.SparseVector](https://spark.apache.org/docs/latest/api/python/pyspark.mllib.html#pyspark.mllib.linalg.SparseVector) 
    * SparseVector(size, [indices of non-zeors], [non-zeors' value])

* zipWithIndex()
    * [Zips this RDD with its element indices](https://spark.apache.org/docs/latest/api/python/pyspark.html#pyspark.RDD.zipWithIndex) 

* collectAsMap()
    * [Return the key-value pairs in this RDD to the master as a dictionary](https://spark.apache.org/docs/latest/api/python/pyspark.html#pyspark.RDD.collectAsMap) 


##### Lab 05
* [numpy.linalg.eigh](http://docs.scipy.org/doc/numpy/reference/generated/numpy.linalg.eigh.html)
* [argsort in descending order](http://mail.scipy.org/pipermail/numpy-discussion/2008-September/037166.html)
