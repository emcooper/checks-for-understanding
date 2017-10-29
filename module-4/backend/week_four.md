## Week Four - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's your favorite project management tool?

I like pivotal for group projects because it is easier to see who is working on what, because pivotal has columns showing work by person. I also like that pivotal has you click through the different states instead of having to remember to drag the cards.

I like waffle by myself because it is simpler, and the customizable color coded labels are helpful, but I don't have a strong preference when working alone.

2. Why do we create staging environments?

We create staging environments because the production environment can be different from the development environment and staging environments allow us to simulate production and make sure there are no environment issues that would cause problems. 

3. What are the characteristics of a good README (in your opinion)?

Fully explaining the purpose of the project, how to run the project locally, a link to the hosted site if applicable, and letting people know how they can contribute. 

4. What's one main improvement you're going to make to your code regarding accessibility issues?

Making sure someone can navigate the page by tabbing.

5. What are some basic security concerns to be aware of when building applications?

Authentication failures/attacks; sql injection; man in the middle attacks

6. Why is continuous integration helpful/important?

Continuous integration allows you to make sure, before you merge a PR, that the PR does not contain any code that would cause your tests to fail. This is especially important in group projects when someone may be working on an outdated version of the code, and even if the test suite passes on their branch, if it is not up to date with master they could still break some tests if they merge their branch. 

7. What are some continuous integration tools?

TravisCI, CircleCI

#### Review  

8. What are some characteristics of "good" git workflow?

Using branches for any new work, submitting pull requests and letting your teammates review and merge the PRs, having conversations on PRs.

9. What are the four fundamental concepts of object oriented programming?

abstraction - hide details of implementation in methods and classes
polymorphism - having methods with the same name do different things depending on the object
inheritance - classes can inherit from one another
encapsulation - wrap implementation in methods 

10. What's a module in Ruby and what's the difference between a class and a module?

A class is a blueprint for creating objects which defines their attributes, and methods specific to that class. A mixin module  is a way of encapsulating certain methods that you would want to utilize in classes. A mixin module can be imported into one or more classes and those classes will then have access to those methods. Namespacing modules do not have separate methods and are just a way of categorizing a class for organizational purposes, they don't provide any additional functionality. A class can be instantiated which creates an object but a module cannot. 
