# akka-persistence-kafka

akka-persistence-kafka writes journal and snapshot entries to Kafka.

## Features

### Supported versions:

- Scala: `2.12.x` or `2.13.x` 
- Akka: `2.6.x+`
- Java: `1.8+`

### Alpakka Support

Supports [alpakka-kafka](https://github.com/akka/alpakka-kafka).

## Installation

Add the following to your sbt build (2.12.x, 2.13.x):

```scala
resolvers += "Sonatype OSS Release Repository" at "https://oss.sonatype.org/content/repositories/releases/"

val version = "..."

libraryDependencies += Seq(
  "com.github.j5ik2o" %% "akka-persistence-kafka" % version
)
```


