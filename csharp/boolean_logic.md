### Boolean Logic
It is possible to compare expressions, to find out how they relate to each other. There are a number of operations possible, to compare different expressions, and each will return a bool (true/false) depending on the outcome.  

***Equal To***  
To assert if two properties are equal == is used.
```CSharp
int a = 20;
int b = 20;
int c = 42;
 
a == b // True
a == c // False
``` 
***Not equal To***  
To assert if two proerties are equal != is used.
```csharp
int a = 20;
int b = 20;
int c = 42;
 
a != b // False
a != c // True
```
***Less than***  
To assert if one value is small than the other, < is used.
```csharp
int a = 20;
int b = 15;
int c = 42;
 
a < b // False
a < c // True
```
***Less than or equal***  
To assert, if one value is small than or equal to the other, <= is used.
```csharp
int a = 20;
int b = 15;
int c = 42;
int d = 20;
 
a <= b // False
a <= c // True
a <= d // True
```
***Greater than***  
To assert if one value is small than the other, > is used.
```chsarp
int a = 20;
int b = 15;
int c = 42;
 
a > b // True
a > c // False
```
***Greater than or equal***  
To assert if one value is small than or equal to the other, >= is used.
```csharp
int a = 20;
int b = 15;
int c = 42;
int d = 20;
 
a >= b // True
a >= c // False
a >= d // True
```
***Logic And***  
Having multiple conditions where all needs to be true, the and && operator is needed.
```csharp
false && false // False
false && true // False
true && true // True
```
***Logic Or***  
Having multiple conditions where any can be true, the and || operator is needed.
```csharp
false || false // False
false || true // True
true || true // True
```