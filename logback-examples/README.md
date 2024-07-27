# Goal
* Examples supporting the main documentation

## How to run locally each example?
* At root parent level
  * `mvn clean compile`
  * via
    * IDE
      * click to run
    * java commands
      * place the cursor | root of "logback-exaples"
      * `java -classpath lib/slf4j-api-2.1.0-alpha1.jar:lib/logback-core-1.5.6.jar:lib/logback-classic-1.5.6.jar:logback-examples-1.5.6.jar:target/classes chapters.subfolder.MainFileName`
        * _Example:_ `java -classpath lib/slf4j-api-2.1.0-alpha1.jar:lib/logback-core-1.5.6.jar:lib/logback-classic-1.5.6.jar:logback-examples-1.5.6.jar:target/classes chapters.introduction.HelloWorld1`
        * previous failures 
          * `javac packageHierarchy/FileName.java`
            * _Example:_ `javac chapters/introduction/HelloWorld1.java`
            * Problems
              * Problem1: imported packages do NOT exist
                * Solution: TODO:
          * `java packageHierarchy.FileName`
            * Note1: -- depends on -- previous command succeed
            * Note2: IDE's command include `-classpath` argument
      * You can set environment variables & run the scripts
        * "setClasspath.sh"
        * "setClasspath.cmd"
