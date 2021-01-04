# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```

```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
staff[name]
```

```
**3.** What is Encapsulation?
Encapsulation is the bundling of data and restricts it to inside the bundle. You are unable to pull that information out of the bundle. 
```

```
**4.** What does the S stand for in the `SOLID` principles?
Single Responsibility
```

```
**5.** What the difference between a `class` and an instance of a `class`?

```
class - These are more static, if you make a change to it, it will appear in other classes!
instance - If changes are made to the var are not reflected in other instances in that class
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy is created with two parameters: 

target: the original object you want to proxy 

handler: This is an object that decides what will be intercepted and how to redefine those interceptions 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To bring modularity to application devs and allows:

Resusable and extendable code
separation of view logic from business logic
allows simultaenous work between devs who are responsible for different components
easier to maintain

src="developer.chrome.com"
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
It holds a reference to both the model and a datastore and is responsible for keepign the model persisted. It responds to events like Load,Save, Delete and tells the datastore to fetch or update the model 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
???
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
domain-specific representation of the information on which the application operates. Model is just another name for domain layer 
```

