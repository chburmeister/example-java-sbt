prepare
-------

download sbt (scala build tool), version: 0.13.15 and add the bin directory to your path.

```
$ sbt about
[...]
This is sbt 0.13.15
[...]
```


compilation
-----------
```
$ sbt clean compile
[...]
[info] Loading project definition from /home/christoph/workspace/example-java-sbt/project
[info] Set current project to example-java-sbt (in build file:/home/christoph/workspace/example-java-sbt/)
[success] Total time: 0 s, completed 24.06.2017 23:39:21
[info] Updating {file:/home/christoph/workspace/example-java-sbt/}example-java-sbt...
[info] Resolving org.fusesource.jansi#jansi;1.4 ...
[info] Done updating.
[info] Compiling 1 Java source to /home/christoph/workspace/example-java-sbt/target/scala-2.10/classes...
[success] Total time: 1 s, completed 24.06.2017 23:39:22
```

packaging
---------
```
[...]
$ sbt clean package
[info] Loading project definition from /home/christoph/workspace/example-java-sbt/project
[info] Set current project to example-java-sbt (in build file:/home/christoph/workspace/example-java-sbt/)
[success] Total time: 0 s, completed 24.06.2017 23:39:30
[info] Updating {file:/home/christoph/workspace/example-java-sbt/}example-java-sbt...
[info] Resolving org.fusesource.jansi#jansi;1.4 ...
[info] Done updating.
[info] Compiling 1 Java source to /home/christoph/workspace/example-java-sbt/target/scala-2.10/classes...
[info] Packaging /home/christoph/workspace/example-java-sbt/target/scala-2.10/example-java-sbt_2.10-0.1-SNAPSHOT.jar ...
[info] Done packaging.
[success] Total time: 1 s, completed 24.06.2017 23:39:31
```

publishing to local m2 repository
---------------------------------
```
```	



Notes:
* https://janzhou.org/2015/10/29/use-sbt-and-git-to-create-your-own-maven-repository.html
* http://www.scala-sbt.org/0.12.4/docs/Detailed-Topics/Publishing.html
* http://alvinalexander.com/scala/sbt-how-to-compile-run-package-scala-project
* http://www.scala-sbt.org/0.12.4/docs/Getting-Started/Basic-Def.html
* http://xerial.org/blog/2014/03/24/sbt/
