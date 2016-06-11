# Scala
Accordingly setup to the course "Functional Programming Principles in Scala"
by École Polytechnique Fédérale de Lausanne (Martin Odersky)

Quote: Functional programming is becoming increasingly widespread in industry. This trend is driven by the adoption of Scala as the main programming language for many applications. Scala fuses functional and object-oriented programming in a practical package. It interoperates seamlessly with both Java and Javascript. Scala is the implementation language of many important frameworks, including Apache Spark, Kafka, and Akka. It provides the core infrastructure for sites such as Twitter, Tumblr and also Coursera.

## The following targets are available:

The docker targets are named after the subdirectories of the repository.
+ :latest - Core installation with Java, SBT and Scala

       `docker run -ti tefworkshop/scala`
+ :eclipse - Eclipse with Scala plugin and HelloWorld project

       `docker run -ti --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix tefworkshop/scala:eclipse`
+ :ideaIC - Untested installation of IntelliJ IDEA with Scala plugin

       `docker run -ti --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix tefworkshop/scala:ideaIC`
+ :HelloWorld - End-to-end test of the automated build

       `docker run -ti tefworkshop/scala:HelloWorld`
 
