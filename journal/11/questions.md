# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > Inheritance allows us to give a class features that another class has. In practice it seems to mostly be used to avoid rewriting the same code over and over, but it also helps with limiting what information appears on what class objects, profiles and accounts for example. Over all, I'm a big fan.

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > Inheritance seems to work mostly like it does in javascript. The biggest difference is the accessibility modifiers, which do affect whether or not a member is a inherited.

3. How does ***accessibility*** affect inheritance?

  > I believe a class will inherit all Public and Internal items from an inherited class. Protected items will also be inherited, but will only be accessed from within that class, similar to how private items function. private items will not be inherited.

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > A foreign key is a value (typically an Id) on a row in a table that checks the primary key of every row on another table. Basically, a primary key is how a row identifies itself, while a foreign key compares itself to another table's primary keys.

5. What is an ***alias***?

  > A SQL alias is a temporary name for a table. For example you could set an alias for the restaurant table as the letter r, and you won't need to spell out the word restaurant for the rest of the statement.

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  );

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  );

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  );

  ```

  > 
  ```SQL
  SELECT patient_doctors.*, patients.*
  FROM patient_doctors
  JOIN patients ON patients.id = patient_doctors.patientId
  WHERE patient_doctors.doctorId = @DoctorId;
  ```
