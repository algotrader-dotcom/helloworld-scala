# helloworld-scala
## On MAC
```
$ brew update
$ brew install scala
$ brew install sbt

$ sbt new sbt/scala-seed.g8
....
Minimum Scala build.

name [My Something Project]: helloworld

Template applied in ./helloworld

$ cd helloworld
$ sbt
...
> run
...
[info] Compiling 1 Scala source to /xxx/helloworld/target/scala-2.12/classes...
[info] Running example.Helloworld
helloworld

OR
sbt clean && sbt compile && sbt package
scala target/scala-2.12/hello_2.12-0.1.0-SNAPSHOT.jar
```
