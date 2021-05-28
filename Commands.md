## App

Java/multi-module-demo/app
✦ ❯ gradle init

Select type of project to generate:
1: basic
2: application
3: library
4: Gradle plugin
Enter selection (default: basic) [1..4] 1

Select build script DSL:
1: Groovy
2: Kotlin
Enter selection (default: Groovy) [1..2] 1

Project name (default: app):

> Task :init
Get more help with your project: Learn more about Gradle by exploring our samples at https://docs.gradle.org/7.0.2/samples

BUILD SUCCESSFUL in 7s
2 actionable tasks: 2 executed

## Core

Java/multi-module-demo/core
✦ ❯ gradle init

Select type of project to generate:
1: basic
2: application
3: library
4: Gradle plugin
Enter selection (default: basic) [1..4] 2

Select implementation language:
1: C++
2: Groovy
3: Java
4: Kotlin
5: Scala
6: Swift
Enter selection (default: Java) [1..6] 3

Split functionality across multiple subprojects?:
1: no - only one application project
2: yes - application and library projects
Enter selection (default: no - only one application project) [1..2] 2

Select build script DSL:
1: Groovy
2: Kotlin
Enter selection (default: Groovy) [1..2] 1

Project name (default: core):
Source package (default: core):

> Task :init
Get more help with your project: https://docs.gradle.org/7.0.2/samples/sample_building_java_applications_multi_project.html

BUILD SUCCESSFUL in 22s
2 actionable tasks: 2 executed

## Domain

Java/multi-module-demo/domain
✦ ❯ gradle init

Select type of project to generate:
1: basic
2: application
3: library
4: Gradle plugin
Enter selection (default: basic) [1..4] 2

Select implementation language:
1: C++
2: Groovy
3: Java
4: Kotlin
5: Scala
6: Swift
Enter selection (default: Java) [1..6] 3

Split functionality across multiple subprojects?:
1: no - only one application project
2: yes - application and library projects
Enter selection (default: no - only one application project) [1..2] 1

Select build script DSL:
1: Groovy
2: Kotlin
Enter selection (default: Groovy) [1..2] 1

Select test framework:
1: JUnit 4
2: TestNG
3: Spock
4: JUnit Jupiter
Enter selection (default: JUnit 4) [1..4] 4

Project name (default: domain):
Source package (default: domain):

> Task :init
Get more help with your project: https://docs.gradle.org/7.0.2/samples/sample_building_java_applications.html

BUILD SUCCESSFUL in 21s
2 actionable tasks: 2 executed

## Lib

Java/multi-module-demo/lib
✦ ❯ gradle init

Select type of project to generate:
1: basic
2: application
3: library
4: Gradle plugin
Enter selection (default: basic) [1..4] 3

Select implementation language:
1: C++
2: Groovy
3: Java
4: Kotlin
5: Scala
6: Swift
Enter selection (default: Java) [1..6] 3

Select build script DSL:
1: Groovy
2: Kotlin
Enter selection (default: Groovy) [1..2] 1

Select test framework:
1: JUnit 4
2: TestNG
3: Spock
4: JUnit Jupiter
Enter selection (default: JUnit 4) [1..4] 4

Project name (default: lib):
Source package (default: lib):

> Task :init
Get more help with your project: https://docs.gradle.org/7.0.2/samples/sample_building_java_libraries.html

BUILD SUCCESSFUL in 16s
2 actionable tasks: 2 executed

## Final output

![img](./img/Screenshot%202021-05-28%20at%202.05.43%20PM.png)
