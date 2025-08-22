## Shadow bug

This demo project was created using https://micronaut.io/launch 

`./gradlew clean build` works fine with `id("com.gradleup.shadow") version "8.3.7"`, but fails when using `id("com.gradleup.shadow") version "9.0.2"` with:

```
> Configure project :
The legacy Shadow plugin (id 'com.github.johnrengelman.shadow') is deprecated. Please use the Gradle Shadow plugin instead (id = 'com.gradleup.shadow')

FAILURE: Build failed with an exception.

* What went wrong:
'com.github.jengelman.gradle.plugins.shadow.tasks.ShadowJar com.github.jengelman.gradle.plugins.shadow.tasks.ShadowJar.mergeServiceFiles()'
```
