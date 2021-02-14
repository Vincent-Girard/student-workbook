# Monday 2-15-21 Foundations of C# > C# Data Types 

## 1. What are the three categories of data types? How are they different? 

Value type - This is where if it holds a data value within its own memory space. If this value gets changed in a method, it will NOT affect the variable in a different method. 

Reference type - This is where it doesn't store its value directly, it stores the address where the value is actually being stored. It's a pointer to another location where the data is contained. This means that if we change the value, it is going to be changeda t hte address its being stored and therefor will change calling it into other methods. 

Pointer type - Variable that holds memory address of another type. Pointer types are not tracked by the default garbage collection mechanism 



## 2. What are the Value-type data types? What differences do you notice from Javascript? 

The biggest difference that I see in it is that it does NOT change the value outside of the method it is being used it. It will allow us to do a little bit more without being bogged down by trying to constantly get the original method. It may cause problems because we'd have to write more code if we need the same answer from a separate method in the one we are currently writing. 


## 3. How do Reference types work? 

Reference types have a pointer that show what the value for the reference type is. It stores a location, to which it knows to go and grab the value for the reference type. 


## Afternoon Challenge link

