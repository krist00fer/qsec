# Mission 003 - The Encryption Service

## Mission Statement

Provide a re-usable open source version of an Encryption service, meant to be used in an internal Micro Services Architecture.

## Requirements

### Generic requirements

* Service should designed according to RESTful principles
* Easy to get up an running on developer machine and in the cloud
* Service should able to handle multiple requests at the same time

### Version 1.0 - The Basics

Provide basic service with the following features

* Encrypt - Encrypts the provided string
* Decrypt - Decrypts the provided string

### Version 1.1 - The Basics, Update 1

Introduce the ability to chose what encryption to use.

Select two encryption algoritms that the end user can select to use.

### Version 2.0 - Complexity

Introduce the ability to upload a new encryption key. The key doesn't need to survive service restarts.

### Version 2.1 - Complexity, Update 1

Make sure key is persisted between service restarts.

### Version 2.2 - Complexity, Update 2

Introduce encryption and decryption using "The Robber Language"
