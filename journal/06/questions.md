# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > I will be honest, I do not fully understand this question. I'm not sure why, but I think I am being asked what part of an application is the part that the user will interact with. In which case, that would be the App and Pages, which now also have the controller  built into them. Am I correct? Please tell me if I am wrong!!

02. What is the difference between a vue `component` and `page`?

  > First, pages are ALSO components!! I understand this finally! Second, pages are distinct from other components because the router uses them as VIEWS! Am I correct? I really hope so.

03. What is ***Component-Based Architecture***?

  > I am guessing a little bit here, but it sounds like a philosophy of development where you use components so that the whole app is more adaptable, responsive, and flexible? Like "This is the comment component." And that component is used all over the app instead of having to make a buttload of HTML that is the exact same? Abstraction of the OOP Pillars seems to be hard at work here.

04. What are the three tags that make up a Vue component?

  > The three tags are a script, a template, and a style tag. Script runs Javascript. Template runs HTML. Style runs CSS or SCSS. Although I'm pretty certain that is oversimplifying somehow, and it is all a lot less strict than that, but it is ***SUPER*** convenient!

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > A lifecycle hook is a function that will run a callback function at a specific point in a vue component's lifecycle. There are a few steps in the lifecycle of an instance, but the one we have used the most is the  ***onMounted*** hook.

06. Which component in Vue does the vue-router use to mount pages onto?

  > I think that Vue is using the App.vue to do this? That has the router view in it which is how every other page component is rendered. Am I correct?

07. What is the difference between the `AppState` and the state object within a component?

  > I do not know what the state object is. 

08. What is the responsibility of `Services` in our Vue projects?

  > Services in Vue projects work the same as in other MVC projects in that they are responsible for changing data in the `AppState` and do not talk directly to the View, or in Vue's case, pages or components.

09. What are ***props*** and how are they used? Provide an example

  > ***Props*** is short for ***Properties***, and they are used similarly to parameters and arguments with functions.

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > You can use the computed method! OR the watchEffect method! I thought both of these were functions that take in callback functions though. Am I misunderstanding something?
