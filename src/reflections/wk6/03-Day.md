# Wednesday - Frontend Frameworks with Vue3 > Understanding Vuejs Lifecycle hooks 

## What are lifecycle hooks?

Hooks are a way to look into your how your library is using works behind-the-scenes. They allow you to know exactly when you component is created, added to the DOM, updated, or destroyed. 

## What are lifecycle hooks used for? 

An example of a hook is the beforeCreate - What this does is it will log a message that tells you that at this point, events and lifecycle have been initialized. These are ways to track your information similarily to console logging in JS like we have done in the past. It will make it easier to isolate problems inside of your code, because yo uwill be able to follow what is going on as it happens. 



## What are mounting hooks? When might you use them? 

As the most often used hooks, they allow you access to component immediately before and after the first render. Something they do not do is run during server-side rendering. You could use these to fetch some data for your component during initialization. 

## Daily afternoon coding challenge 

(https://github.com/Vincent-Girard/winter2020-vue-gregslist)