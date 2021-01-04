# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous code is executed in sequence, it goes from 1 to 2 to 3
Asynchronous code doesn't have to wait for your nonsense, the program can continue to run without error and eventually  it circles back when it completes. 
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
A procedure in js that waits for something to happen (event). It will wait until it hears it's trigger and then start to work .
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-closed principle - it means we should be able to add new features or components without destroying our code 
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
Callback - a function that is passed as an argument to another function 
Higher order funciton - functions that operate on other functions, either by returning them or taking them as arguments 

```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is something that is either going to come back as resolved or rejected. It is something that WILL execute, but it may take time. 
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
HEAD - this method asks for an identical to a GET request, but without hte response body 

GET - Requests a representation of the specified source, This should only retrieve data 

DELETE - Deletes the specified source

```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming INterface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
Controller
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
It allows values or state of an object inside a class, preventing access to people who should not have it 
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200-299
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A server error!
```