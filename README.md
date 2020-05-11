<p align="center">
  <img src="https://lh3.googleusercontent.com/proxy/S9qpXl_CANk7jlGxdEppUadOBmSotiUaCrpvOyXB99F2OZ8uQOJ3j0WPzk_7GQSIX5ndALd_zarRawmmJrLjjL4f87F5gQ_IxrGrZ7nZtz6fsCJsr6o">
</p>

<h1 align="center">Code Examples</h1>

### Getting Started with Scala

- [Scala Documentation](https://docs.scala-lang.org/?_ga=2.94192925.1002217770.1589141912-1942157757.1588046986)

### Set up
- Scala Version: **2.11.8**
- JDK Version ([Java SE 8u251](https://www.oracle.com/java/technologies/javase-downloads.html)): **1.8.0**
- SBT Version: **1.3.10**

File [build.sbt](build.sbt):
```
name := "scala-code-examples"
version := "0.1"
scalaVersion := "2.11.8"
libraryDependencies ++= Seq(
  "org.apache.spark" %% "spark-core" % "2.1.0",
  "org.apache.spark" %% "spark-sql" % "2.1.0"
)
```
---

### Summary

#### Basics Codes
- [Variables](src/main/scala/basics/variables.sc)
- [Flow Control](src/main/scala/basics/flowControl.sc)
- [Functions](src/main/scala/basics/functions.sc)
- [Data Structures](src/main/scala/basics/dataStructures.sc)

#### Word Count
Create a RDD of lines from a text file, and keep count of how often each word appears.

- [Code](src/main/scala/wordCount/wordcount.scala)
- [Text file](src/main/scala/wordCount/book.txt)
