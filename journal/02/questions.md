# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > The keywords are Let, Var, and Const.

02. What is the definition of a function?

    > A function is a line of code that only runs when it is invoked

03. What are the `SOLID` principles?

    > S = Single Responsibility
      O = Open- Closed Principle
      L = Liskov Substitution Principle
      I = Interface Segragation Principle
      D = Dependency Inversion Principle

      I only really understand S.

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > You could remove pineapple like so:
    ```js
    fruit.find((fruit) => fruit == 'pineapple')
    ```

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > I think you could push each object into the other's arrays into.
    ```js
    you.friends.push(them);
    them.friends.push(you);
    ```
      This may be incorrect

06. Give an example of a JavaScript `Conditional`:

    > I think this is a good example
    ```js
    if (puppet.isHungry == true) {
        eatTheCake()
    } else {
        haveTheCake{}
    }
    ```

07. What is the main difference between `parameters` and `arguments`?

    > A parameter is what is plugged into a function inside the parentheses. Arguments are the data that is actually being passed through the function.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > I suppose I could use code breaks and check the code line by line?

09. What is the difference between a `primitive` value and a `reference` value?

    > A primitive value is a basic piece of data such as a number, a string, a boolean, or null. A reference is an object or an array.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > Is there a method that would do this more easily? I think methods only work for arrays and objects, so there wouldn't be one to help here, is that right?
    ```js
    for (let i =-100; i <=100; i++) {
        console.log(i)
    }
