# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes provide the flexibility of combing data and methods/ provides re-usability called inheritance. 

Structs is typically used for grouping data. Structs make members default to public 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
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
The result
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It prevents the inheritance of a class or certain class that were previously marked virtual
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual is used to modify a method, property, indexer, or event declation and allow it to be overriden in a derived class. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public
private
protected
internal
proetected internal
private protected

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed by code in the same class or struct
```