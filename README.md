# rscalaexample
Example for using Scala from R

You will find here an example for integrating Scala into your R scripts.

Basically it uses rJava to load the Scala classes and call the methods.

The example provides two functions:

* calcScala(x,y) to let the Scala class calculate the sum of x+y
* calcR(x,y) to let the Scala class call R (using JRI) to calculate within R the sum of x+y

# build
You can run the build process of the JAR package that contains the Scala class by entering the subdirectory "scala" and run there "build.sh". This shell script uses [sbt](http://www.scala-sbt.org/) to assemble a JAR and [ScalaTest] (http://www.scalatest.org/) to unit test the Scala methods.
By using these tools, you can ensure a proper build and quality process for your Scala classes/methods used from R.
