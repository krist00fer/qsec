# Mission 009 - The Sorting Service

## Mission Statement

Provide a re-usable open source version of a Sorting Service, meant to be used in an internal Micro Services Architecture.

## Requirements

### Generic requirements

* Service should designed according to RESTful principles
* Easy to get up an running on developer machine and in the cloud
* Service should able to handle multiple requests at the same time

### Version 1.0 - The Basics

Provide basic service with the following features

* Number Sort - Sort the numbers from smallest to largest
* Reverse Number Sort - Sort the numbers from largest to smallest

### Version 1.1 - The Basics, Update 1

Introduce additional features:

* String Sort - Sort string from A - Z
* Reverse String Sort - Sort string from Z - A

### Version 2.0 - Complexity

Introduce the ability to do a Merge Sort. Merge Sort is functionality to merge together two pre-sorted arrays such that the resulting array is also sorted.

### Version 2.1 - Complexity, Update 1

Introduce the ability to chose if duplicate entires in the inparameter should be included or excluded from the resulting, sorted array.


### Version 3.0 - Scale out

Service should handle scale out scenarios, i.e. working correctly with above requirements even if server runs on many processes and/or many machines.