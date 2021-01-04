# Monday 1-4 Asynchornous Code > Callbackk Hell
_Journal Entry_

## What are some of the signs and causes of Callback Hell?
The execution of the codes happens visually from top to bottom. It usually looks as though someone has vomitted code into a pyramid shape. 
 

 ## What does asynchronous mean and how are callbacks involved?

It's a programming language where one thing can happen at a time. It allows the code to to be executed without waiting for something else to happen. Callbacks are involved because we are only passing the reference as an argument. Callbacks don't have to finish doing whatever their purpose is, they can be 'called back' when other contingencies have finished. 
 

 ## Summarize the 3 ways to avoid / fix Callback Hell

1. Keep your code shallow - Naming the functions will help you figure out reference actual functions instead of it telling you "anonymous" 
2. Modularize - The act of separating code into small modules that do a bigger thing. 
3. Handle every single error - Don't ignore any error that you get and plan for those errors to occur through your code. You can use $ standard in your code to identify any unhandled errors. This method is what is used to make the code STABLE. 




