# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > CCRUD stands for Create, Read, Update, and Delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > Create = Post
    Read = Get
    Update = Put
    Delete = Delete

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > ORM stands for Object Relational Mapping. We use Mongoose when we interact with MongoDB.

04. Which two `HTTP` request types include a body?

  > Both Put and Post requests include a body so that the information can be added or saved. Get finds information that already exists, and delete doesn't need to know what information it is deleting, just where it is.

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > Asynchronous and Synchronous? I feel that this is not the correct answer, but it is the only one that sounds right with the context.

06. What are the three types of data relationships? Provide an example of each.

  > First, One to One, where a piece of data has only one relationship to another. An example Jeremy gave me was that of a student Id, but it isn't a very common relationship.
  
  Second, One to Many, where a data has many relationships with other pieces of data. An example I really liked was that of a State and Cities. One State has multiple Cities, but a city doesn't belong to multiple states.

  Third, Many to Many, where pieces of data can have many relationships. An example I liked for this was that of Students and Classes. A student will have many classes, and Classes will have many students.

07. What is middleware?

  > Middleware is software that sits between two other programs and helps them to talk to each other. In class, we have mostly used to verify users, but it seems to be much more wide ranging and broad than just that purpose.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > I think the Request pipeline delivers from the client and the Response pipeline returns it. If not, I have no idea.

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > Is it this: '?tag=winter'?

10. What is a ***virtual property***?

  > A virtual property is a property that a Schema will only calculate when it is accessed.
