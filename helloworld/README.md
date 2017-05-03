Execute the following commands to run helloworld You should see the top 10 lines of the hdfs file in /user/cloudclump/big.txt From [http://cloudclump.com]

sbt package

spark-submit  --class "SimpleApp"  target/scala-2.10/helloworld_2.10-0.1.0.jar
To Understand whats going on, Take a look at SimpleApp.scala file
