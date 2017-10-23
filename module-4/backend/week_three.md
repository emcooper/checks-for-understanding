## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?

Node is a server-side environment for Javascript.

2. What is Express? What is Express similar to in the Ruby world?

Express is a framework for Node that comes with various functionality that make writing web applications in Node easier. Express feels more similar to Sinatra than Rails. 

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
```
app.get(url, callbackFunction)
```

4. What do we use Knex for?

Knex is used for accessing the database in Node. It comes with various methods, including 'raw' which can be used to make raw SQL queries to the database.

5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?

You can follow the MVC pattern by breaking out code into models and controllers, depending on their purpose. In terms of the view, I think you could use Vanilla JS or JQuery to append data directly to html view within a Node app, without needing endpoints. 

6. How do you execute raw SQL in node?

Using Knex's '.raw' function, which is called on the database configured by knex. 

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?

Advantages: organization and readability,  performance benefits (?), can limit loading vendor assets to where you actually use them (ie no need for bootstrap on backend) (?)
Disadvantages: possibly more time-consuming to create and connect endpoints, more possibilities for problems with deployment 

#### Review  

8. Describe DNS.

Domain Name System, directory of domain names

9. What does writing clean code mean to you?

Keeping code DRY, writing reusable and flexible methods, short methods, code divided into files based on responsbility

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?

A hotel model class, a hotel controller class. The model class would handle database queries and other logic. The controller class would pass the data from the models to the views.
