
# 1 Optimization
Spark optimization techniques are used to modify the settings and properties of Spark to ensure that the resources are utilized properly and the jobs are executed quickly

    
# 2 Pyspark
PySpark is an interface for Apache Spark in Python. It not only allows you to write Spark applications using Python APIs, but also provides the PySpark shell for interactively analyzing your data in a distributed environment.

# 3 Need Of Optimization

- To reduce the execution time of spark jobs

# 4 Shuffling
- Shuffle is a mechanism for redistributing or re-partitioning data so that the data is grouped differently across partitions
- 
# 5 Performance Tunning
- Spark Performance tuning is a process to improve the performance of the Spark and PySpark applications by adjusting and optimizing system resources (CPU cores and memory)

# 6 File Format Selection

- Spark jobs can be optimized by choosing the parquet file with snappy compression which gives high performance and best analysis

# 7 Cache and Persist

- Spark provides its own caching mechanisms like persist() and cache()

# 8 Catalyst Optimizer

- Catalyst contains a general library for representing trees and applying rules to manipulate them

# 9  Business Overview Of Airlines Industry

- https://openflights.org/
- https://developer.ibm.com/exchanges/data/all/airline/
- https://www.bts.dot.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics

# 10 S3 link for dataset

- s3://airlines555/airline/data


# 11 Code Description
    File Name : optimization.ipynb , and optimization.py  
    DataSets : data.zip  
    File Description : Implement optimization techniques  
    
## Steps to Run
There are two ways to execute the end to end flow.
- Command Prompt => python script
- spark_path spark-submit file_path
- spark_path => <path_to_spark>>
- file_path => <path_to_file>
- Data file path is same as script file path

eg. <C:\Users\admin\Desktop\spark\bin>spark-submit C:\Users\admin\Desktop\optimization\optimization.py>


- IPython

### Modular code
- Create virtualenv
- Install requirements `pip install -r requirements.txt`
- Run Code `python optimization.py`
- Check output for all the visualization
### IPython
Follow the instructions in the notebook `optimization.ipynb`
