# video-tutorials > What is JSON?

[![What is JSON?](https://img.youtube.com/vi/ut2Pw2tS7Ek/0.jpg)](https://www.youtube.com/watch?v=ut2Pw2tS7Ek)

JSON (JavaScript Object Notation) is a lightweight format for storing and transporting data. It's heavily used on modern web.

## Syntax

* File extension is ".json"
* Root element must be an object or an array
* All keys must be double-quoted
* String values must be double-quoted (escape double quotes in the value)
* Number and boolean values must NOT be double-quoted
* Comments are not supported by design
* No trailing commas

A browser's environment, as well as Node.js, has the global object `JSON` working with this format. Basically, you need to know just two its methods:

* `JSON.parse(argument)`: string -> object/array
* `JSON.stringify(argument)`: object/array -> string
