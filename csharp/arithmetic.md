### Arithmetic
When working with programs, it is often required to do some basic mathematical operations. These are native in programming languages, and C# supports the following:

* \+ (Addition)
* \- (Subtraction)
* \* (Multiplication)
* / (Division)
* % (Remainder / Modulus)

#### Syntax
The operation has to be performed and stored in a variable like this:
```csharp
int myInt = 40 + 2; // Result of myInt: 42.
```
When performing operations, variables can be used, and variables can even be used and stored in itself:
```csharp
int a = 40;
int b = 2;
int c = a + b; // a + b -> 40 + 2 = 42

// Variables can "use themselves"
c = c - 20; // c - 20 -> 42 - 20 = 24.
```
Calculations are executed first, in the order of calculation, and at last assigned to the variable.
When writing expressions, parenthesis ( & ) can be helpful.

#### Shorthand notations
When performing operations on the variables, a shorthand notation can be used.
```csharp
a += 5; // Same as: a = a + 5;
b -= 5; // Same as: b = b - 5;
c *= 5: // Same as: c = c * 5;
d /= 5; // Same as: d = d / 5;
e %= 5; // Same as: e = e % 5;
```
Often used operations are increasing or decreasing a variable by one. For this special shorthand notations are created:
```csharp
a++; // Same as: a = a + 1;
b--; // Same as: b = b - 1;
```