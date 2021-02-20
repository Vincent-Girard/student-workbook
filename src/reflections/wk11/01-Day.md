# Monday Feb-22-2021 C# > C# Inheritance

## 1.  What does Inheritance accomplish for us in C#? 

It's what allows us to define how two things relate to eachother. The two sets of information may need to be passed to correctly pull information from a database or make sure that we can pull thigns that are related. 

## 2. How does Member inheritance work in C#? Does a class inherit all members of the base class?

Not all members of the class are inherited. They typically inherit methods and properties from their parents, which the child can manipulate as necessary. 

## 3. How does accessibility affect inheritance? 

Things that are private for example would not be inherited by the child because it's private to the parent in this case. So if you want to inherit, you need to use public or internal. 