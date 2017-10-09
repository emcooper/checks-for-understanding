## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?

How objects are constructed and used in Javascript.

2. What are some tools to help debug JavaScript code?

The Debugger, Chrome developer tools.

3. What are some tools you need in order to unit test your JavaScript?

Mocha, Chai

4. What is the syntax for invoking a function?

functionName();

5. What's `this` in JavaScript?

In a general sense 'this' is a way of refering it the parent element of a JS element, but differs depending on the context. Inside of an object, this refers to the object. Outside of an object, it will depend on the context but this can refer to the window.

6. What is Webpack and why is it useful?

Webpack is a tool that compiles JS and CSS assets. It is useful because it allows us to have separate files for JS and CSS that it will then import into one file. 

7. When/why do you want to use event delegation?

You might want to use event delegation when you want a parent or grandparent element to be clickable but still want to know which child element was actually clicked. 

8. What's `npm` and what do we use it for?

Node Package Manager. It is used to start the server, I'm not sure exactly what else. 

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.

The MVC design pattern is a way of structuring a web application that divides code into Models, Views and Controllers. The role of models is to make any necessary database calls and house any other logic. Controllers will utilize the model's methods to obtain objects to pass to the views. They will also implement CRUD functionality. Views will hold the html structure and utilize variables passed from the controller. 

10. What are a few ways to optimize a Rails application?

Caching, database query optimization, background workers.  

11. What's a background worker? When would we want to use a background worker?

A background worker executes a task separate from the normal flow of the application (ie in the background). We would want to use one for tasks that are not required for the user to continue their interaction with the application and which may be time-consuming, such as sending automated emails. 
