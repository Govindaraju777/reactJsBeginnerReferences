## React Functional Components, Props, and JSX – React.js Tutorial for Beginners
  https://www.freecodecamp.org/news/react-components-jsx-props-for-beginners/
  
  React is one of the most popular JavaScript libraries for building user interfaces.
  
  What is JSX?
      The first thing you'll realize after installing your first React project is that a JavaScript function returns some HTML cod
<img width="915" alt="Screenshot 2022-05-31 at 10 49 14 PM" src="https://user-images.githubusercontent.com/17598334/171234843-ebb30b9a-63e3-4ac3-94f6-79cf1a93117e.png">

      This is a special and valid syntax extension for React which is called JSX (JavaScript XML). Normally in frontend-related projects, 
      we keep HTML, CSS, and JavaScript code in separate files. However in React, this works a bit differently.
  
  In React projects, we don't create separate HTML files, because JSX allows us to write HTML and JavaScript combined together in the same file,
  like in the example above. You can, however, separate your CSS in another file.
  



  JSX is very practical, because we can also execute any JavaScript code (logic, functions, variables, and so on) inside the HTML directly by using curly braces { }, like this:
  
  <img width="690" alt="Screenshot 2022-05-31 at 10 52 50 PM" src="https://user-images.githubusercontent.com/17598334/171235397-371c99d4-07f7-470f-a475-a47a468a9b88.png">
<img width="1070" alt="Screenshot 2022-05-31 at 10 53 17 PM" src="https://user-images.githubusercontent.com/17598334/171235476-3f0942f1-ac41-4425-b277-8f955987861b.png">


I won't go into further details of JSX, but make sure that you consider the following rules while writing JSX:

    HTML and component tags must always be closed < />
    Some attributes like “class” become “className” (because class refers to JavaScript classes), “tabindex” becomes “tabIndex” 
    and should be written camelCase
    We can’t return more than one HTML element at once, so make sure to wrap them inside a parent tag:


  <img width="975" alt="Screenshot 2022-05-31 at 10 54 51 PM" src="https://user-images.githubusercontent.com/17598334/171235723-d61e6cc5-43f1-40d7-ae64-e7c523c2094e.png">
  
  
  
# What are Class Components?
    The second type of component is the class component. 
    Class components are ES6 classes that return JSX. Below, you see our same Welcome function, this time as a class component:
    
    <img width="690" alt="Screenshot 2022-06-01 at 9 22 04 PM" src="https://user-images.githubusercontent.com/17598334/171446934-5cfff0a9-dbe2-499e-88d6-a3f261d15160.png">
    

## Different from functional components, class components must have an additional render( ) method for returning JSX.
      A Class Component:

      is an ES6 class, will be a component once it ‘extends’ a React component.
      takes Props (in the constructor) if needed
      must have a render( ) method for returning JSX

## Why Use Class Components?
    We used to use class components because of "state". In the older versions of React (version < 16.8), 
    it was not possible to use state inside functional components.



## What are Props in React?
  Another important concept of components is how they communicate.
  React has a special object called a prop (stands for property) which we use to <font color="green"> transport data from one component to another. </font> 

  But be careful – props only transport data in a one-way flow (only from parent to child components). 
  It is not possible with props to pass data from child to parent, or to components at the same level.
  
 
 
 https://www.freecodecamp.org/news/react-components-jsx-props-for-beginners/
 
 <img width="981" alt="Screenshot 2022-06-01 at 9 31 17 PM" src="https://user-images.githubusercontent.com/17598334/171448772-58349982-1f64-4b5c-a524-81e1e0ff5681.png">

<img width="966" alt="Screenshot 2022-06-01 at 9 45 25 PM" src="https://user-images.githubusercontent.com/17598334/171451404-58901081-f559-4eb3-9cc7-4a7cec19337a.png">

