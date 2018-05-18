# xyz-generator

An updated version of maven-archetype-quickstart.

For interactive mode, just run:

```java
    mvn archetype:generate -DarchetypeGroupId=xyz.luan.generator -DarchetypeArtifactId=xyz-generator -DarchetypeVersion=0.2.0
```

And fill the information.

If you want batch mode, use this instead, but fill in the gaps:

```java
    mvn archetype:generate -DarchetypeGroupId=xyz.luan.generator -DarchetypeArtifactId=xyz-generator -DarchetypeVersion=0.2.0 -DgroupId=<your.group.id> -DartifactId=<your-atifact-id> -Dversion=<your.version> -DinteractiveMode=false
```

Are you looking for [xyz-gae-generator](https://github.com/luanpotter/xyz-gae-generator)? If you'd like to create a base GAE project, ready to run, test and deploy, check it out.

## Why is it better than quickstart?

 * It adds UTF-8 encoding and Java 8 support to your pom (zero warnings first build)
 * It adds better test libraries (updated JUnit plus AssertJ)
 * It adds a gitignore (hurray!)
