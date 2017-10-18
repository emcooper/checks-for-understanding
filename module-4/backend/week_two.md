## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's one difference between ES5 and ES6?

In ES6 classes can be defined using the 'class' syntax, while in ES5 classes must be defined using the constructor function syntax.

2. What's the difference between asynchronous and synchronous JavaScript? 

Asynchronous JS can run a JS script separately and simultaneously from the main program. Synchronous JS runs the program from top to bottom, moving onto the next code only when the current code has completed it's runtime.

3. What are the four pillars of Object Oriented programming?

Encapsulation
Abstraction
Polymorphism
Inheritance

4. What are some tools available in JavaScript to help you write object oriented code?

In ES6, the class syntax is available to define object classes. In ES5 the constructor function notation is available to define classes. In ES5 methods can be added to existing classes using the prototype synatx. 

5. What are some key concepts to be aware of when refactoring your JavaScript?

Object Oriented programming is one approach that can be used to refactor Javascript. This refactor would involve breaking the code into classes, for example a requests class, event handlers class, etc. TDD is another key concept in refactoring because breaking code into smaller methods that do only one thing will better allow the code to be tested. DRY is also an useful concept in refactoring - creating small reusable methods will help create more readable code. 

6. What's a callback function and what are some reasons when we use/need callback functions?

A callback function is an anonymous function used as an argument to another function that is being envoked. We need to use them because it is essentially a wrapper for a block of code that the first function needs to run. 

7. What's the scope of variables in Javascript?

The scope of variables in JS is the context in which the variables are recognized. An example would be that variables defined inside a function are out of scope outside that function.

8. What's the difference between `==` and `===` in JavaScript?

'===' is strict equality operator, meaning it does not coerce the data being evaluated into a different data type (aka 2 === '2' is false).  '==' is not strict equality operator, meaning it will coerce the data into a different type when performing the comparison (aka 2 == '2' is true).

9. Why do front end frameworks exist?

Frontend frameworks exist to make manipulating the dom easier and allow for more dynamic user experiences. For example the concept of re-rendering only the part of the dom that was changed is a main premise of frontend frameworks like React and is easier to implement in these frameworks than in jQuery.


#### Review  

10. Why do people say "HTTP is stateless"?

They say this because the browser does not hold state, ie it does not remember anything from previous requests. Only the database, and things like sessions and cookies, hold state.

11. Describe a RESTful API.

A RESTful API is an a way that an application can communicate data to another machine by rendering data in a machine readable language such as JSON. It is RESTful because it uses RESTful http verbs in its request, such as GET, POST, PUTS, DELETE.

12. What are some main characteristics of a team following an agile workflow?

2 week sprints that add new features for the client to review and give feedback on. Constant adaptation to client requirements and feedback. Daily standups.

13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?

Advantages include:
- fewer security concerns because you are not storing passwords in your database, and because a 3rd party is authenticating the user 
- being able to access other data from teh user that the api provides without an additional authentication process
Disadvantages:
- reliance on 3rd party API (what if the API changes or the service goes under)
- not every user is a member of the 3rd party site

