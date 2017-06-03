# xq-java-gradle-custom-repository

How to use custom repository in gradle project.

Just config the mvn repository address like this:

```groovy
repositories {
    maven {
        url 'http://localhost:5000/repository/maven-central/'
    }
}
```
