# Mission 005 - The Time Service

## Mission Statement

Provide a re-usable open source version of a Time Service, meant to be used in an internal Micro Services Architecture.

## Requirements

### Generic requirements

* Service should designed according to RESTful principles
* Easy to get up an running on developer machine and in the cloud
* Service should able to handle multiple requests at the same time

### Version 1.0 - The Basics

Provide basic service with the following features

* Get Time - Service should return the current time as a text string
* Get Date - Service should return the current date as a text string

### Version 1.1 - The Basics, Update 1

As part of the call to Get Time and/or Get Date, introduce the ability to select date and time format for the result

### Version 2.0 - Complexity

Introduce the ability to set the date and time. Setting the date and time shouldn't mess with the services internal clock. The changes doesn't have to survive a service restart.

### Version 2.1 - Complexity, Update 1

Updates set to date/time should be persisted and live through a service restart

### Version 3.0 - Scale out

Service should handle scale out scenarios, i.e. working correctly with above requirements even if server runs on many processes and/or many machines