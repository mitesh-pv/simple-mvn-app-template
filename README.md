# Simple Java Application using maven

Clone this project and change the name.

Create maven run configuration with following maven command:
```shell
compile exec:java -Dexec.mainClass=com.lld.app.App -Dexec.args=RegisterCallbackApplication
```

To generate new template use the following command:

```shell
mvn archetype:generate -DgroupId=com.lld.app -DartifactId=lld-template -DarchetypeArtifactId=maven-archetype-quickstart  -DinteractiveMode=false
```