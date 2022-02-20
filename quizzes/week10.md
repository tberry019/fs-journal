# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is a declarative region that provides a scope to the identifiers the names of types, functions, variables inside it.

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
the default accessibility of member variables and methods. In a struct they are public; in a class they are private.

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void and return.

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
the area.

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
It is looking back for an overiding method.

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
it is the blueprint on what the model wants.

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
making it virtual provides it from multiplying and creating other instances of it.
 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Private Access Modifier, Public Access Modifier, Protected Access Modifier, Internal Access Modifier. 

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
A class may be declared with the modifier public, in which case that class is visible to all classes everywhere. If a class has no modifier , it is visible only within its own package.

```