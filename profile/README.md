# Postgres Extension Templates

This repository provides template repositories to help you create extensions for PostgreSQL. These templates are designed to help you quickly develop an extension by providing basic examples of extensions that can be easily adapted into your own extension.

Pull Requests and additional templates are welcome!

## Current Templates

### [Function](https://github.com/pgextensions/function-template)

An example of a function using the [Soundex](https://en.wikipedia.org/wiki/Soundex) algorithm. This is an extension written in `C`, providing a function defined as `soundex(text)`, which returns the computed `Soundex` value.

### [Operator](https://github.com/pgextensions/operator-template)

An example of an operator using the [Soundex](https://en.wikipedia.org/wiki/Soundex) algorithm. This is an extension written in `C`, providing two operators, `>@@<` which provides word similarity, and `<@@>` which provides word dissimilarity.

### [Type](https://github.com/pgextensions/function-type)

An example of a type using the [Soundex](https://en.wikipedia.org/wiki/Soundex) algorithm. This is an extension written in `C`, providing a type that stores the computed `Soundex` value upon insert, and returns that computed value on read.
