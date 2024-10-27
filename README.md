# JavaSandbox

## Running Questions

* What exactly is STATIC as a keyword in a class; how many fun ways are there to break it?
* Dynamic memory and the new keyword
* Maven as an ecosystem


## Crash Course Notes

### Videos

[Java in 100 seconds](https://www.youtube.com/watch?v=l9AzO1FMgM8) by Fireship

* Designed in 1990 at Sun Microsystems by James Gosling
* Mascot = Duke
* Integrations
  * Webapps powered by Spring
  * Big Data Pipelines by Hadoop
  * Mobile Apps on Android
* Comilation process:
  * C/C++: .cpp file -> machine code
  * Java: java file -> bytecode which runs on any OS without compiling
    * Possible due to the JVM (Java Virtual Machine)
    * Both a compiled and interpreted language (jvm does the interpreting)
    * Computer needs Java Runtime Envorinment (JRE) installed
* Big Pros
  * Platform agnostic
  * Write once, run anywhere
  * Includes Features:
    * Garbage Collection
    * Runtime Type Checking
    * Reflection
* Language Syntax Details
  * Strongly typed
* Getting Started
  * Source Code Notes
    * Install Java Development Kit (JDK)
    * Classname should match file name
    * Every class needs a main method
    * Declaring a variable is TYPE, NAME, VALUE
    * Functions are methods on the class
    * PUBLIC keyword = used outside of the class, and STATIC means member of the class itself, not an instance of the class
    * Public classes have attributes, Constructors, and methods
    * new will instantiate from the class
    * Supports anonymous lambdas too
  * Compiling it
    * javac HelloWorld.java
    * java HelloWorld.class

