### Variables
When working the programming, there will come a need to store information to be used later. This is done by the use of variables.  
A variable consists of a type, name and value.
```csharp
int myVariable = 42;
```
In the example above can we see the following:
* The type is int (Integer)
* The name is myVariable
* The value is 42

Multiple variables can be created and exists together.
```csharp
bool myBool = false;
int myInt = 42;
float myFloat = 3.14;
```
After a variable has been created, it can be updated like this:
```csharp
int a = 42; // Create the variable
a = 32;     // Update the variable
```
A list of supported types in C# can be found here: [Types and variables](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)

#### Scopes
The lifetime of a variable is within the scope it has been defined, where each scope starts and ends with curley brackets
```csharp
int a = 42;
{
    int b = 29; // New Variable created in scope
    a = 9;      // Variable a is still accessable here
}
 
a = 79; // Variable a is still accessable here
b = 23; // ERROR. Variable b is NOT accessable here.
        // It is "Out of Scope"
```
#### Var Keyword
When assigning variables, it is possible to get the compiler guess what type the values is with the var keyword.
```csharp
var myString = "Hello World!"; // Compiler  guess: string
var myVar = 42; // Compiler guess: int
```
