# Wednesday 1-6 Async and Chill
_Journal Entry_

## What is the purpose of Asyn / Await ? 

They were designed to reduce hte obilerplate around promises and the limitation of "don't break the chain" of chaining promises. It gives the appearance of synbchronous code, but it's actually asynchronous and non-blocking behind the scenes
 

 ## What must you do in order to await a promise inside of a function? 

 I believe that you would need to use the async keyboard before a fucntion definition. This would then allow you to use await within a function. If you do use async, then it means that the function is going to return a promise 

 ## What are some of the primary benefits of Asyn / Await ? 

It provides far easier debugging because the debugger will not step over asynchronous code. Doing this will also give the appaearance that it's syncrhonous code. 

