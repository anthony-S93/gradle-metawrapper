# Gradle Metawrapper
A wrapper for Gradle's [wrapper](https://docs.gradle.org/current/userguide/gradle_wrapper.html)

## Purpose
The recommended way to execute any gradle build is via the gradle wrapper, which is often located in the root directory of a single or multi-project build. This means that to use the wrapper, one has to either `cd` into the project root first and then run `./gradlew`, or input the wrapper's relative (or absolute) path into the command line, which can be tedious. This metawrapper eliminates that step, allowing you to execute the gradle wrapper from anywhere inside the project directory. 

## Install
No installation necessary. Download a copy of this script and run it.
