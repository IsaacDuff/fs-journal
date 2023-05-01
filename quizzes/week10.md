# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is used to declare a certain name in one place so it will not interact with anything outside that space that may be of the same name. 
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
a class is a reference type while a struct is a value type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void, void will allows the method to run but wont have a specific returning type on it. 
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
public is the access modifier.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
it is telling us what value type will be returned at the end of the method. 
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It is preventing the creation of objects within the class. 
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virual is a property used to modify the method to allow it to be overridden inside its class. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal and protected.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
when a method or class is set to private it can only be accessed by code inside of its same class. 
```