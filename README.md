Tachyon
=======

The master branch is in version 0.7.0-SNAPSHOT:

- [Project Homepage](http://www.tachyonproject.org)
- [Previous Releases](https://github.com/amplab/tachyon/tags)
- [Master Branch Document](http://tachyon-project.org/master/)
- [Tachyon Issue Tracker](https://tachyon.atlassian.net/browse/TACHYON)
- [User Mailing List](https://groups.google.com/forum/?fromgroups#!forum/tachyon-users)
- [Meetup Group](http://www.meetup.com/Tachyon)
- [How to Contribute](http://tachyon-project.org/master/Contributing-to-Tachyon.html) and
[Beginner's Tasks](https://tachyon.atlassian.net/issues/?jql=project%20%3D%20TACHYON%20AND%20labels%20%3D%20Beginner)


## Building applications with Tachyon

### Dependency Information

#### Apache Maven
```xml
<dependency>
  <groupId>org.tachyonproject</groupId>
  <artifactId>tachyon-client</artifactId>
  <version>0.6.0</version>
</dependency>
```

#### Gradle

```groovy
compile 'org.tachyonproject:tachyon-client:0.6.0'
```

#### Apache Ant
```xml
<dependency org="org.tachyonproject" name="tachyon" rev="0.6.0">
  <artifact name="tachyon-client" type="jar" />
</dependency>
```

#### SBT
```
libraryDependencies += "org.tachyonproject" % "tachyon-client" % "0.6.0"
```
