# Tuesday 1-5 Asyncrhonous Code > JS Promises 

_Journal Entry_

## What are the three states of a Promise?  
Pending: Initial state, this is before the promise has been assigned an outcome
Resolved: They kept their promise :D
Rejected: They failed to keep their promise 


 ## How do promises seek to resolve the issues of "callback Hell"?

Promises can be attached to Callbacks rather than passing them. By using promises we can clean up our code and makes it more legible for those who may need to understand it for reference in the future. 
 

 ## What is the difference between .then() and .catch() ?

.then() - Is called after a promise is resolved. From there we are able to decide waht to do with the resolve Promise!

.catch() - This is for when the promise fails. When/if the promise fails it will jump to the catch message and depending on how you coded it, you could see a different message in the console 


## Afternoon Challenge

https://github.com/Vincent-Girard/winter2020-api-gregslist