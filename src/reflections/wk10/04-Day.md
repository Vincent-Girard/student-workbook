# Thursday 2-18-21 C# > C# Inheritance


## 1. What does Inheritance accomplish for us in C#? 

It allows us to define a child class that reuses, extends, or modifies the behavior of the parent class. The class that inherits is called the base class, whereas the class that inehrits the members of the base class is called the derivedclass. 

## 2. How does member inheritance work in C#? Does a class inherit all members of the base class?


not all members of a base class are inherited by the derived class. Such as 

Static Constructors 0 which initilize the static data of a class 

Instance constructors - Which you call to create a new instance of the class. Each class has to be defined by its own constructors (making sense why these would not be inherited)

Finalizers - These are called by the runtime's garbage colelctor to destroy instances of a class 


## 3. HOw does accessibility affect inheritance? 

It depends on how you define it. It's going to determine where you can access the information from 

Public: This is what you would use if you need to access it by the same assembly or any other assembly that references it. 

Private: Would be where it can only be in the same class or struct. 



## Daily Challenge 

https://github.com/Vincent-Girard/winter20-burgershack


# FRIDAY AFTERNOON CHALLENGE 

https://github.com/Vincent-Girard/allspice