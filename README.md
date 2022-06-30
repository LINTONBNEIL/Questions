# Questions

+ What is a *"Data Model"*, and how does it relate to the DOM in a front-end application?

  + The *Data Model* holds onto the state of our application. It is the single source of truth for what should be displayed onto the page. 
  + The *DOM* is the visual represenation of our application. 
  + This array of object below is an example of our *Data Model*, every Object is a piece of the model that we use to render a visual represenation.
  + The key is everthing we see on the *DOM*, is backed up by a piece of our model. 
  
  ```
  var fruits = [
  {
    name: 'Lemon',
    img: 'https://bit.ly/2wQwmYG',
    rotten: false,
    id: 0
  },
  {
    name: 'Lime',
    img: 'https://bit.ly/344kBtA',
    rotten: false,
    id: 1
  },
  {
    name: 'Apple',
    img: 'https://bit.ly/2X1v3AJ',
    rotten: true,
    id: 2
  }]
  ```
  
+ What is a *"Framework"*? And how does it differ from a *"Libary"*?

  + A software framework provides a standard way to build and deploy applications. It is a universal, reusable software environment that provides particular functionality as part of a larger software platform to facilitate development of software applications, products and solutions
  
  + Libraries are usually a little bit smaller, and generally serve the purpose of providing us with abstractions over complex code that we would otherwise have to write ourselves. (Think jQuery.) Libraries are usually ‘syntactic sugar’ over something difficult.
  
  + Frameworks, on the other hand, offer us a bit more than just abstractions - they give us a lot more powerful ways to write our code, but at the same time, they prescribe a very strict and specific way for us to organize our code.
  
+ Why should we consider a *Framework* over *Vanilla JS*? 
  
  + KEEPING THE UI IN SYNC WITH THE STATE IS HARD!

+ What is *JSX*? 
  
  +  A mix of JavaScript and XML that facilitates rendering the appropriate HTML Components: standalone, independent parts of an application that are responsible for handling only a single UI element
  
+ What are *Props*? 

  + This is shorthand for *properties*. *Props* is an object that is given from it’s parent component down to the child functional/class component. Props should remain immutable

+ What is the React *State*? 

  + State holds data that represents the actual state of an application. State can be changed and mutated through user interactions
  
+ What does "Data Down, Actions up" mean in react?

  + This phrase helps developers understand the flow of information from parent to child component and vice versa.
The first and more simple concept, “data down,” refers to the passing of data and/or functions via props from parent to child components. These props are passed down when a child component gets created. We pass data down to child components so they can render them on to the DOM.
