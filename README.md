# ddb 压测 Java 程序

执行脚本：
<Br>
```shell
mvn compile exec:java -X -Dexec.mainClass="org.example.basicapp.GetMoviefromDax"   -Dexec.cleanupDaemonThreads=false -Dexec.args="daxtest.s9apfk.dax-clusters.us-west-2.amazonaws.com 8111 us-west-2"
```

如果虚机性能可以，可以增多线程数来增加并发数。
