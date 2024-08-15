# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > I think the namespace is essentially just the scope of the project, right? And I can split that that namespace into further spaces which is why I write allspice.Model. Am I correct?

02. What is the difference between a `class` and an `interface`?

  > As of the answering of this question, I don't think that  I have heard of a c sharp interface before. I also don't really understand what it is supposed to be once I have researched it. I will probably need to follow up on this one.

03. What is the method that returns an instance of a class, yet it has no return type?

  > After a beneficial conversation, I understand that this question is asking about the constructor and It is because the constructor returns an instance but does not have a return type on it.

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > The access modifier for the Start method is public.

06. In the Car example what is `string` an indication of?

  > The string is an indication that this method will return something of the type 'string'

07. In the Car example what is `abstract` preventing?

  > Abstract is preventing the car class from being made directly, it instead must be inherited by another class, such as a Honda Civic or a Mazda Miata.

08. In a SQL table, what is the difference between information in a row and information in a column?

  > Information in a row all pertains to one specific item in the database. Information in a column is all of the data that corresponds to that key in the entire table.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > 
    CREATE TABLE characters(
      id INT NOT NULL PRIMARY KEY,
      name VARCHAR(255) NOT NULL,
      age VARCHAR(255) NOT NULL,
      description VARCHAR(2000) NOT NULL
    ) default charset utf8mb4 COMMENT '';


10. In SQL how can you query more than a single table? Provide an example.

  > I can query multiple tables by including them after the query--

  "SELECT characters.*, plotPoints.*"

  In this snippet, the select query will get information from both the characters and the plotPoints tables. This might only be how you populate things though.
