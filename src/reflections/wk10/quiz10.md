# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It defines the scope of your code, creating the boundary under which your data is confined to.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Generally: a class has limitless user definition while a struct is mostly a collection of variables tied to a unit.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
"new"(?)
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
"public"
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The return type of "Start()"
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The class cannot be instantiated on its own, and needs to be implemented by a non-abstract class.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
This property can be overridden by any class that inherits the "Car" class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Can be accessed only by code in the same class or struct.
```