# Introduction to C# and .NET

## .NET v/s C#
**C#**
* Programming language

**.NET**

* Framework for building application on Windows

* Supported on by other languages such as F#, VB.NET etc

* Consists of 2 components
  1. Common Language Runtime (CLR)
  2. Class Library (for building applications

## C#

C/C++ code ==> Compiler ==> Native (Machine) code

Java code ==> ByteCode

C# ==> IL (Intermediate Language) code ==> Native Code

IL code to native code translation is done by the **CLR**. This translation is
called **Just-In-Time (JIT)** compilation.

## Architecture of a .NET Application
### Application
* Collection of **classes**
* Classes collaborate at run-time

### Class
* Consists of:
  1. Data/attributes
  2. Methods/functions
* e.g. Cars:
  + Data: Make, Model, Color etc.
  + Methods: Start(), Move() etc.

### Namespace
* Container for related **classes**
* e.g.: Namespace working with images

### Assembly (DLL/EXE)
> DLL: Dynamically Linked Library
* Collection of related **namespaces**
* Physically - a file

> After compilation:
> **Application** is nothing but a collection of assemblies.
