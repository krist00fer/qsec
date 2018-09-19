# Mission 002 - The Image Framework

## Mission Statement

Provide a re-usable open source version of an Image Framework, meant to be used as a "code library" referenced from other projects.

## Requirements

### Generic requirements

* Library should be easy to use, compile and contribute to
* Easy to reference and use from other projects
* Library should conform to Design Guidelines, Conventions, Idioms, and Patterns normally used in the eco system

### Version 1.0 - The Basics

Provide a basic re-usable "code library" that provides the following capabilities:

* Pixel Count - Given an image object, method should return the number of pixels that make up the image
* Pixel Count from File - Given a file name, method should return the number of pixels that make up the image


### Version 1.1 - The Basics, Update 1

Introduce additional features:

* Re-Size - Given an image and a size, method should return a re-sized image object
* Re-Size from/to File - Given two file names and a size, resizes the image referred to by first file name and saves it to the second

### Version 2.0 - Complexity

Introduce additional features:

* Batch Re-Size - Same as above but works on several images
* Batch Re-Size from/to File - Same as above but works on a folder

Execute operations sequentially

### Version 2.1 - Complexity, Update 1

Same as above but introduce the ability to execute batch operations in parallel

### Version 2.2 - Complexity, Update 2

Introduce the asynchronous version of above batch operation

### Version 3.0 - Additional Features

Introduce the ability to add a "Water Mark" on a batch of images, where the Water Mark is defined as a .PNG file
