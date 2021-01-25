# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
One way data binding - Binds the data from the component to the dom
Two way data binding - This is a way to bind information from a form element to a object/variable that you are using/passing. 
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
The main advantage of this is speed. They are loaded initially with the page and it doesn't need to continually load in order to get the features to work .
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
This is what has access to reactive components nad will actually mount something to the page. 
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
When you want to two way data bind. It's usually used to enable two-way data binding on a form and works with almost all types of input types. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
This is usually used to listen for DOM events and triggers some of your javascript functions. 
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
Directives are tiny commands that you can attach to dom elements. They are prefixed with v- to let the library know you're using a special bit of make up. 
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
This tells it what to use in order to differeniate the things that it is iterating over. It is saying okay, I have all of these posts (for example), but what makes them unique? The post id

```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
This is a placeholder inside a web component that you can fill with your own mark up, which will create separate DOM trees and present them together.
```