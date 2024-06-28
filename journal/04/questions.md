# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > Asynchronous code falls out of the normal flow of javascript and will wait for a promise to be resolved before moving onto the next line.

02. What is an event listener?

  > An event listener is a method (is that right? I think it is a method) that will do something if whatever trigger attached to it is set off. The guard example really helped me understand this, of someone always watching to see if something is changed and then sounding the alarm.

03. What does *REST* stand for, and in simple terms what does it mean??

  > REST stands for REpresentational State Transfer. It is sort of like a structure or set of requirements that an API should be made with. I'm a little unclear on some of the things that the readings were talking about, but I think I understand that it wants the way to access the information be the same regardless of client. I wants the client to only be sending requests and the server to only be sending responses, the API shouldn't be saving information about the client, there should be degrees of separation between the client and the server, and finally that it should be cacheable. The last one is the most murky to me, mostly because I don't know very much at all about caching or how it works or what it even does. Something about saving data I think.

04. What is a callback / higher order function?

  > A callback function is a function that is passed as an argument through another function, and a higher order function is a function that accepts functions as arguments. I'm a little unclear on this and on the distinction. Are getters callback functions? Is a listener a higher order function? I think it might be, but I'm not sure.

05. What is a `promise`? How do you capture an error from a `promise`?

  > I am strugggling with articulating this, but a promise occurs when a callback function or async function is called. A promise of information is made, and resolved later, either if the code was successful or if there was an error. Am I right? I understand that you can capture an error from a promise with a try/catch.

06. Name three processes used to make requests over `HTTP`?

  > I am worried I don't understand this question. Are we talking about CRUD? Create, Read, Update, Delete. And the actual methods are .post(), .get(), .put(), and .delete(). Post makes a new piece of data in an API, Get will retrieve a piece of data, Put will modify something, and Delete will remove something.

07. What does the `API` acronym stand for?

  > API stands for Application Programming Interface.

08. What must you do in order to `await` a promise inside of a function?

  > You can only await a promise inside of a function if you declare the function to be asynchronous by placing an async be the name of the function.

09. What is the purpose of encapsulation in programming?

  > The purpose of encapsulation is to hide the data in an application so that it is protected. It also helps with the organization of code.

10. What is `HTTP` response code for a successful request?

  > The response code is 200, it means that the request was received, processed and sent correctly. Am I right?

11. What is a 400 error?

  > A 400 error indicates that something is wrong with the code you are sending to the API.
