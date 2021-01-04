# Wednesday 12-16 Advancing with JS > An Intro to JS Proxy objects
_Journal Entry_

## What are the two common operations that we will set in the handler?  

 Get: This is an operator that takes two parameters (the object and the property being access) 

 Set: This is an operator that takes three arguments. The object, the property being accessed, and the value being set for that property

 ## What do you have to make sure you are doing with every Get to insure the value does not become undefined? 

You need a return line. 

return obj[prop]; would return that value that was stored inside the key being accessed. 
 

 ## What are some of the benefits of the proxy object that we are using in our structure for applications? 


This would allow us to keep things a little closer to the chest and not allow people visibility into our code. It also decreases the amount of surface area that a hacker can use to exploit the website. 


