# Variables, Constants and Types

## Variable
* Name given to a storage location in memory

```
<dtype> <identifier>;

<dtype> <identifier> = <value>;
```
* `<dtype`: data type
* `<identifier>`: [Identifier](#identifiers)
* `<value>`: Value to be assigned to a variable.

e.g.:

```c#
int num;
int number = 1;
```

## Constant
* An immutable value.
* Value known at compile time.

```
const <dtype> <identifier> = <value>;
```
The `const` keyword identifies a constant.
> Value of a constant has to be assigned along with its definition.

## Identifiers
* Variable name
* Case-sensitive
* **CANNOT** start with a number
* **CANNOT** contain white space
* **CANNOT** be a reserved keyword
> Use meaningful names

## Naming Conventions
* Camel Case: **f**irst**N**ame
* Pascal Case: **F**irst**N**ame

## Types
* [Built-in C# types](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/built-in-types-table)
* Non-primitive Types
  + String
  + Array
  + Enum
  + Class
