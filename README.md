# HelloWorldKotlin

A repository with a HelloWorld Kotlin application with no Spring, with Gradle's Kotlin DSL.

## Medium article

[Hello World Kotlin application with the Gradle Kotlin DSL](https://medium.com/p/b4a2ae398afe/edit)

## Getting Started

This application contains a HelloWorld application created with Gradle's Kotlin DSL.

### Prerequisites

To use this, you need java 8, gradle 5+ and Intellij IDEA installed in your local environment.

### Builing

For building the project you need to execute this command:

```sh
$> gradle build
```

For building the project, cleaning it firstly:

```sh
$> gradle clean && gradle build
```

### Running the application

For running the project you need to execute this command:

```sh
$> gradle run
```

For running the project, cleaning and building it firstly:

```sh
$> gradle clean && gradle build && gradle run
```

## Running the tests

For running all the tests

```sh
$> gradle test
```

For running all the tests, cleaning and building the project firstly:

```sh
$> gradle clean && gradle build && gradle test
```

## Git

### Tagging

For creating a tag pointing to a commit

```sh
$> git tag -a <version> <commit-sha> -m "<message>"
```

## Built With

* [Kotlin](https://kotlinlang.org/) - The Kotlin programming language
* [Gradle](https://gradle.org/) - Dependency Management
* [Git](https://git-scm.com/) - Distributed version-control system
