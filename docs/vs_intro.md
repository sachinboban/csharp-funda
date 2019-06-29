# `C#` Programming with Visual Studio

## Create a New Project
1. Goto _FIle_->_New_->_Project_
2. Select _Windows Desktop_ under _Visual C#_ on the left pane.
3. Select _Console Application_
4. Name out application accordingly (`HelloWorld`).
5. Click _OK_

## Solutions
In our basic application, the solution contains only one Project. But as our
application grows, solution will contain more than one project. You can explore
the solution using the `Solution Explorer`.
### Project
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
