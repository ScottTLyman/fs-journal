# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it.
Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Struct are value types whereas Classes are reference types
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
data type of return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstract prevents instantiation of the class
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword is used to modify a method, property, indexer, or event declared in the base class and allow it to be overridden in the derived class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected,  internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed in the same class
```