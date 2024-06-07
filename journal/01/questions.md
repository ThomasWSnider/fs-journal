# Foundations of Web Development
01. In your own words, why do we use Git?
    > We use Git to keep track of the changes we have made to our code. It also lets teams of developers work together so that each one can work on and see all of the code for a project, and it is a tool to help them merge all of their changes together. It is also probably very helpful is something goes very wrong and we need to go to the last instance of the project.
02. In the terminal, what is the command `mkdir` used for?
    > The terminal command "mkdir" stands for "make directory" and is used for making new directories (or files? Are they the same thing?) in which files can be kept and organized.

03. What is a ***pseudo-class*** and what are some of the most common ones you think you will use?
    > A pseudo-class is something we use in css to apply styles to elements only when certain conditions are met. The most common one so far has been the hover pseudo-class.

04. What is ***specificity*** and how might you use it to your benefit?
    > Specificity is a value that is used in CSS in order to determine which styles should be applied in case they conflict. An element selector has a value of 1, a class selector has a value of 10, an id selector has a value of 100. This can be used to make general changes to all sorts of a type of thing, but I will still be able to change individual styles by adding specificity.

05. What problems do you think you could run into if you over-utilized the `!important` feature?
    > If I overused the `!important` feature, I could see myself constantly finding styles that aren't applying or applying when I don't want them too. As Mick pointed out on Tuesday, two styless that have the feature will just revert back to normal specificity when compared to each other, so I'd have to utilize normal specificity anyways. 
06. What are the three components that makeup a `CSS` rule? <br> Example:

    ```css
        h1 {
            color: rgba(255, 210, 33, .75);
        }
    ```

    > H1 is the selector, what we use to identify the elements we want to style. Color is the property, or the thing we want to change. RGB here is the value, or what we want to set the property to.

07. How do you think good design influences people when visiting a website, and what sorts of things could you convey through design alone?
    > Good design could probably funnel people to scroll automatically, or show them the things they are most likely to look for without really having to search. You can show that your organization is professional, with a clean design.
08. What is the purpose of ***wireframing***?
    > Wireframing is for figuring out how you would like the site to look before even sitting down to code. It helps the developer to plan how they will achieve their design and also what sort of design that they'll decide to make.

09. Do you think wireframes are worth the time, energy, and effort that they require? Why or Why not?
    > The low fidelity wireframes make a lot of sense. It is very hard to start a project out of the blue. I suspect a website could turn out a little blocky if I didn't think about the design first. The higher fidelity wireframes make a little less sense to me. Why spend that much effort, when you could start on the project you already have a basic idea for. It is probably easier to make changes before I commit to anything though, so I'll probably change my mind with more practice wireframing.

10. Define the display `:flex property:`
    > 'Display: flex' is a property used to essentially have more versatility with how the page is layed out. It automatically will line up elements side-by-side, but, with flex directions, you can basically make it do whatever you want. It's like a magic wand for web developers.

11. What `CSS` properties affect the size of a box model?
    > A box model's size is affected by four different properties. 
        1. The margin, essentially an invisible wall that tells other elements to stay away
        2. The padding, space between the margin and the border. Useful for making buttons larger and smaller
        3. The border, the border is sort of the edge of the actual element itself
        4. The element at the center 
