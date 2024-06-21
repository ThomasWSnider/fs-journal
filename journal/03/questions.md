# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > First, Abstraction, make your code simpler and more reusable.
    Second, Encapsulation, keep things private and separate your code based on it direct responsibilities.
    Third, Inheritance, I don't understand this at all, I need help or review.
    Fourth, Polymorphism, this seems to be related to Inheritance??? I'm confused

02. How does `export` differ from `export default`?
  
  > We've only really worked with 'export' so far, but it seems that I should be using 'export' when I'm exporting multiple things at once, and I should use 'export default' when I only want to export one value. When would I need to do that? Have we been doing this and I haven't realized it?

03. What is Encapsulation?
  
  > Encapsulation is separating your code out based on responsibility. It has a lot to do with data security. I think of it like degrees of separation between the user and core data. The DOM is 1st, then the controller is 2nd, service is 3rd, and the Appstate is four degrees of separation from the user, safe and sound. Am I wrong? Please correct me if I am.

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > I have spent the last 40 minutes trying to understand what proxy objects are and what they do. All I can understand is that they can set 'traps' to prevent certain information from being obtained, but I don't understand how or what they are doing exactly. I feel like I'm watching a Christopher Nolan film.

05. What the difference between a `class` and an instance of a `class`?
  
  > A class is basically a sort of template that is used to create objects. But it does it more than that? When I make a controller class is that an object? It seems more like it's own set of javascript. I know that all of the functions within are technically methods. I think I just need to try to go at everything again.

06. What is a computed Property?
  
  > A computed property is when you interpolate a function rather than a straight value into HTML. Right? So the date opened property in case files was a computed Property because every time it was needed, it was calculated and then plugged in, as opposed to the date created property which was made once and then always used when called? Am I right?

07. What is the purpose of the `MVC` pattern?
  
  > The purpose of the MVC pattern is to protect the main data by limiting which parts of the application can interact with it.

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > The controller receives input from the user and changes elements on the DOM

09. What is the job of the `Service` in `MVC`?
  
  > The service does all of the 'business logic' which is anything that changes data from the app state

10. What is the job of the `Model` in `MVC`?
  
  > The Model provides a blueprint for everything that the Controller is drawing to the DOM and helps to keep track of what information is needed where.
