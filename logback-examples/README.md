# Goal
* Examples supporting the main documentation

## How to run locally each example?
* `mvn clean compile`
* via
  * IDE
    * click to run
  * java commands
    * place the cursor | package declaration starts
    * `javac packageHierarchy/FileName.java`
      * _Example:_ `javac chapters/introduction/HelloWorld1.java`
      * Problems
        * Problem1: imported packages do NOT exist
          * Solution: TODO:
    * `java packageHierarchy.FileName`
      * Note1: -- depends on -- previous command succeed
      * Note2: IDE's command include `-classpath` argument
