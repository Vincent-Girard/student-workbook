# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This is what allows the application to let NPM know how to identify the project and it's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The top, I believe it is so the application knows where to start and where to go from. Without it being at the top, it wouldn't find it before erroring out. 
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
connection strings I think... 
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
$ heroku logs --source app --tail
Logs on the web dashboard
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Log into heroku
open your project, initiate the git repository
add heorku as a remote origin
commit changes
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It breaks your code up into multiple parts, you wouldn't want people to be pushing over eachothers code and losing work. 
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
After automated checks have been fulfilled. This should happen before you merge branches
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```
