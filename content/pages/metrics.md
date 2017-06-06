Title: Performance Metrics
date: 2017-03-21 07:51
slug: metrics.html
Authors: Oliver Gutsche
Summary: Documentation of Performance Metrics for the CMS Big Data Project
Template: page

## Application metrics

* How quickly can I reduce how many events? Depends on
 * reduction factor
 * size per event
 * how much of the event is accessed during reduction (to make decision (skimming) and also to pass on to output (slimming))

## System metrics

* memory usage and caching strategy
    * I/O metrics
    * spark inbuilt metrics
    * CPU time of all executors
    * time spent on garbage in garbage collection, time in serialization
    * from HDFS you get rows and data read from HDFS
* measure network traffic, important for reading from EOS
