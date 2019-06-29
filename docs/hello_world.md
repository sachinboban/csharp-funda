# Hello World using Visual Studion

## `C#` Programming with Visual Studio
### Create a New Project
1. Goto _FIle_->_New_->_Project_
2. Select _Windows Desktop_ under _Visual C#_ on the left pane.
3. Select _Console Application_
4. Name out application accordingly (`HelloWorld`).
5. Click _OK_

### Solutions
In our basic application, the solution contains only one Project. But as our
application grows, solution will contain more than one project. You can explore
the solution using the `Solution Explorer`.

#### Project
* `Properties/`
  + `AssemblyInfo.cs`
     Assembly production as result of compiling the application. The assembly
     will have its identification (attributes): title, description, company etc.
* `References/`
  + Contains the assemblies that the current project is referring to
  + `App.config`
     * XML files
     * Configuration for this application. e.g. connection strings to database,
       settings etc.
* `Program.cs`
   Actual `C#` code.

## Hello World program
### Namespace
By default `vs` would have created a namespace `HelloWorld` in our HelloWorld
application. We may need to use classes defined from other namespaces in our
code. For this we use the `using` keyword to sort of _import_ any required
namespaces.

```c#
using System;
```

#### Basic namespaces
* `System`: Basic namespace in `.NET` framework containing basic utility classes
   and primitive types

### `class Program`
Any console application in VS will conists of `Program` class. This contains
the `Main()` method by defualt. `System::Program.Main` is the entry point of the
program.

## Execute the program
`Ctr + F5`

## References
1. [Source Code](../HelloWorld/)
