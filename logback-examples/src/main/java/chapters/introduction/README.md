# Goal
* Most of your class need to import
  * specific loggers -- _Example:_ SLF4J --
  * NOT logback reference
* if NO configuration file -> logback, by default configuration policy, add a `ConsoleAppender` | root logger
* `StatusPrinter.print(Context)` prints `Context`'s status data
  * you can see that
    * default configuration (`ConsoleAppender`) was set up -- "Setting up default configuration" --
      * Reason: 🧠 other configuration files (logback.xml, logback-test.xml, ..) were NOT found  🧠