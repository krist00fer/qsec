# Mission 004 - The Randomizer Framework

## Mission Statement

Provide a re-usable open source version of an Randomizer Framework, meant to be used as a "code library" referenced from other projects.

## Requirements

### Generic requirements

* Library should be easy to use, compile and contribute to
* Easy to reference and use from other projects
* Library should conform to Design Guidelines, Conventions, Idioms, and Patterns normally used in the eco system

### Version 1.0 - The Basics

Provide a basic re-usable "code library" that provides the following capabilities:

* Random word - Given a string, method should return a random word within.
* Shuffel - Given a list of T, method should return a shuffeled list of T

### Version 1.1 - The Basics, Update 1

Introduce additional features:

* Almost True - Create a method that returns true P % of the time, otherwise false
* Predictable Random - If not yet implemented make sure all methods have a way of returning a predictable random behaviour.

### Version 2.0 - Complexity

Introduce additional features:

* Noise - Create a method that creates and outputs "noise" to a stream
* Simulated Error - Create a method that given a string, sometimes, returns a slightly changed string. How often the string is messed up should be set by a parameter.

### Version 2.1 - Complexity, Update 1

Introduce a way to "subscribe" to Simulated Errors, so you can act if it happens (for example log, set break points, etc.)

### Version 2.2 - Complexity, Update 2

Provide a way to set the "Almost True" and "Simulated Error" rate in a configuration file.

### Version 3.0 - Additional Features

* Create a method that returns a random integer up to a specific number, but never the same number twice, even if process is reset.
* Introduce the ability to reset the ability to return the same value

