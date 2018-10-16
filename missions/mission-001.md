# Mission 001 - The Calculator Service

## Mission Statement

Provide a re-usable open source version of a calculator service, meant to be used in an internal Micro Services Architecture.

## Requirements

### Generic requirements

* Service should designed according to RESTful principles
* Easy to get up an running on developer machine and in the cloud
* Service should able to handle multiple requests at the same time

### Version 1.0 - The Basics

Provide basic service with the following features

* Addition - Adds two numbers together
* Subtraction - Removes one number from the other

### Version 1.1 - The Basics, Update 1

Introduce additional features:

* Multiplication - Multiplies two numbers with each other
* Division - Divides one number with the other

### Version 2.0 - Complexity

Introduce the ability to calculate text string that describes a "complex math calculation". For example:

```
5+(4*3)
9/7+3
```

### Version 2.1 - Complexity, Update 1

Introduce the ability to retrieve a list of the last "complex math calculations" evaluated. No need to persist information in case of restart of service.

### Version 2.2 - Complexity, Update 2

Introduce the ability to clean the history of executed calculations.

### Version 3.0 - Scale out

Service should handle scale out scenarios, i.e. working correctly with above requirements even if server runs on many processes and/or many machines.