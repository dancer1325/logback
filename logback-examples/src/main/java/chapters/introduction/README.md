# Goal
* Most of your class need to import
  * specific loggers -- _Example:_ SLF4J --
  * NOT logback reference
* if NO configuration file -> logback, by default configuration policy, add a `ConsoleAppender` | root logger
  * 