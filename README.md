# ![alt text](https://avatars2.githubusercontent.com/u/1263946?v=3&s=84 "KBase") KBase SDK

The KBase SDK is a set of tools for developing KBase Apps that can be dynamically registered and run on the KBase platform.  Apps are grouped into modules that include all code, dependencies, specification files, and documentation needed to define and run Apps in the KBase Narrative interface.

> **[SDK user documentation can be found here](http://kbase.github.io/kb_sdk_docs)**

Documentation in this readme is for developing the SDK codebase itself. If you want to develop an app using the SDK, please visit the documentation website linked above.

## Dependencies and compilation

Run `make compile` to generate the binaries found in `/bin`

A [Vagrant]() image to run the tests for this codebase, which will take care of your dependencies. To build an image from scratch that can run all the tests, follow the [test dependencies](/docs/test_dependencies.md) guide.

## Running tests

Run `make vagrant-test` to run the tests.

## Project anatomy


#### Miscellania



## Notes and references

The codebase currently uses Java 8 and is incompatible with Java 9. Details about this incompatibility can be found here: https://blog.codefx.org/java/jsr-305-java-9/. Specifically, the "Generated" annotation is problematic.



