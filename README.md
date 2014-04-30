## How to Run PtaPCG
### 0. Clone the project
### 1. Download the benchmarks 
([Karim Ali](http://plg.uwaterloo.ca/~karim/ "Karim Ali") provides the benchmarks on his website, who is the author of "Averroes: Whole-Program Analysis without the Whole Program")
#### 1.1. Original benchmarks
[http://plg.uwaterloo.ca/~karim/projects/averroes/tutorial.php](http://plg.uwaterloo.ca/~karim/projects/averroes/tutorial.php "http://plg.uwaterloo.ca/~karim/projects/averroes/tutorial.php")
#### 1.2 Benchmarks processed by Averroes
[http://plg.uwaterloo.ca/~karim/projects/averroes/tutorial.php](http://plg.uwaterloo.ca/~karim/projects/averroes/tutorial.php "http://plg.uwaterloo.ca/~karim/projects/averroes/tutorial.php")
### 2. Setup the environment

#### 2.1 JDK environment for Soot
Set JDK path as below:

> C:/Program Files/Java/jdk1.7.0/jre/lib/rt.jar;C:/Program Files/Java/jdk1.7.0/jre/lib/jce.jar;C:/Program Files/Java/jdk1.7.0/jre/lib/jsse.jar;

#### 2.2 Modify the properties in the files under the directory "properties" and "properties/averroes" according to your environment
appJarPath

benchmarkDir

libDir

tamiflexLog

### 3. Run
#### 3.1 Install ANT
#### 3.2 Run 
> ant -buildfile run-PtaPCG.xml