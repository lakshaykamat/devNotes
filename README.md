# 📝 Software Developer Notes

Welcome to my curated collection of Software Development notes, resources, and projects. Whether you're just starting out or looking to deepen your expertise, this repository serves as your comprehensive guide. Explore various sections crafted to enhance your skills and knowledge across different domains of software development.

---

## 📚 Table of Contents

1. **[Development](https://github.com/lakshaykamat/sde-notes/tree/main/Development)**
   - ### Backend Development
     - [API and Auth](https://github.com/lakshaykamat/sde-notes/tree/main/Development/Backend/API%20and%20Auth): Learn about RESTful APIs, OAuth, JWT, and more.
     - [Node. Js](https://github.com/lakshaykamat/sde-notes/tree/main/Development/Backend/Nodejs): Dive into Node.js for building scalable server-side applications.
     - [Spring Boot](https://github.com/lakshaykamat/sde-notes/tree/main/Development/Backend/Spring%20Boot): Explore Spring Boot for robust and easy-to-maintain Java applications.
   - ### Frontend Development
     - [React. Js](https://github.com/lakshaykamat/sde-notes/tree/main/Development/Frontend/React): Master React.js for building dynamic and interactive UIs.
   - ### Mobile Development
     - [Android Dev](https://github.com/lakshaykamat/sde-notes/tree/main/Development/Mobile/Android%20Dev): Learn Android development from basics to advanced topics.

2. **[Learning Resources](https://github.com/lakshaykamat/sde-notes/tree/main/Learning%20Resources)**
   - [Databases](https://github.com/lakshaykamat/sde-notes/tree/main/Learning%20Resources/Databases): Comprehensive resources on SQL, NoSQL, and database design principles.
   - [Programming Languages](https://github.com/lakshaykamat/sde-notes/tree/main/Learning%20Resources/Programming%20Languages): Deepen your understanding of languages like Python, JavaScript, Java, and more.
   - [System Design](https://github.com/lakshaykamat/sde-notes/tree/main/Learning%20Resources/System%20Design): Essential concepts and best practices for designing scalable systems.

3. **[Career Preparation](https://github.com/lakshaykamat/sde-notes/tree/main/Career%20Preparation)**
   - [HR Questions](https://github.com/lakshaykamat/sde-notes/blob/main/Career%20Preparation/HR%20Questions.md): Prepare for behavioral interviews with common HR questions and tips.

4. **[Roadmaps](https://github.com/lakshaykamat/sde-notes/tree/main/Roadmap)**
   - [Databases](https://github.com/lakshaykamat/sde-notes/blob/main/Roadmap/Databases.md): A step-by-step guide to mastering databases, from basics to advanced concepts.
   - [MongoDB](https://github.com/lakshaykamat/sde-notes/blob/main/Roadmap/MongoDB.md): A step-by-step guide to mastering MongoDB
   - [Node. Js](https://github.com/lakshaykamat/sde-notes/blob/main/Roadmap/Node.md): A comprehensive roadmap for becoming a proficient Node. Js developer.
   - [Reactjs](https://github.com/lakshaykamat/sde-notes/blob/main/Roadmap/Reactjs.md): Learn about react fundamentals and thoery will help you in cracking interviews

---
# Interview Questions
| Title                                                            | Full Link                                                                                                                                    |
|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| [ReactJS](#react-interview-questions)                            | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Development/Frontend/React/React%20Interview%20Questions.md)                      |
| [JavaScript](#javascript-interview-questions)                    | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Learning%20Resources/Programming%20Languages/Javascript/Interview%20Questions.md) |
| [NodeJS](#nodejs-interview-questions)                            | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Development/Backend/Nodejs/Interview%20Questions.md)                              |
| [Application Programm Interface (API)](#api-interview-questions) | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Development/Backend/API%20and%20Auth/API/Interview%20Questions.md)                |
| [Authentication and Authorization](#auth-interview-questions)    | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Development/Backend/API%20and%20Auth/Auth/Interview%20Questions.md)               |
| [Database](#database-interview-questions)                        | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Learning%20Resources/Databases/Interview%20Questions.md)                          |
| SQL                                                              | Link                                                                                                                                         |
| [MongoDB](#mongodb-interview-questions)                          | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Learning%20Resources/Databases/MongoDB/Interview%20Questions.md)                  |
---

# Practical Problems
| Title                                     | Full Link                                                                                                                                |
|-------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| [Javascript](#javascript-coding-problems) | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Learning%20Resources/Programming%20Languages/Javascript/Coding%20Problems.md) |
| [MongoDB](#mongodb-coding-problems)       | [Link](https://github.com/lakshaykamat/sde-notes/blob/main/Learning%20Resources/Databases/MongoDB/Coding%20Problem.md)                   |


# React Interview Questions
### 1. **What is React, and why is it used?**

**Answer:** React is a JavaScript library for building user interfaces, particularly single-page applications where you need a fast, interactive, and dynamic UI. React allows developers to build web applications that can update and render efficiently in response to data changes. It’s used because of its component-based architecture, virtual DOM, and declarative nature, which makes managing the UI state easier and improves performance.

### 2. **What are the main features of React?**

**Answer:**

- **JSX (JavaScript XML):** A syntax extension for JavaScript that allows you to write HTML directly within JavaScript, making the code easier to understand.
- **Components:** React apps are built using components, which are reusable, independent pieces of UI.
- **Virtual DOM:** React creates a virtual copy of the DOM and updates it in response to changes, which makes updates faster.
- **One-Way Data Binding:** Data flows in a single direction, making it easier to debug and track changes.
- **State Management:** React provides state management through components, allowing you to manage data and UI updates efficiently.

### 3. **What is the difference between a class component and a functional component?**

**Answer:**

- **Class Component:**
  - Uses ES 6 class syntax.
  - Can hold and manage its own state using `this.state`.
  - Uses lifecycle methods like `componentDidMount`, `shouldComponentUpdate`, etc.
- **Functional Component:**
  - A simpler way to write components using plain JavaScript functions.
  - Initially stateless, but with React Hooks, functional components can now manage state (`useState`) and side effects (`useEffect`).
  - Easier to read, write, and test compared to class components.

### 4. **What are React Hooks, and why are they important?**

**Answer:** React Hooks are functions that let you "hook into" React state and lifecycle features in functional components. They are important because they allow developers to use state and other React features without writing a class. Some of the most commonly used hooks include:

- **useState:** Manages state in a functional component.
- **useEffect:** Manages side effects like data fetching, subscriptions, or manual DOM changes.
- **useContext:** Accesses the context API to manage global state.
- **useReducer:** An alternative to `useState` for managing more complex state logic.
- Hooks promote cleaner, more reusable, and more maintainable code.

### 5. **What is the Virtual DOM, and how does it work in React?**

**Answer:** The Virtual DOM is a lightweight, in-memory representation of the real DOM elements generated by React components. When a component's state or props change, React creates a new Virtual DOM tree, compares it with the previous one (a process known as "reconciliation"), and then efficiently updates the real DOM with only the parts that have changed. This makes UI updates faster and more efficient.

### 6. **How does React handle forms and form validation?**

**Answer:** React handles forms using controlled components, where the form data is managed by the component's state. Input elements like `<input>`, `<textarea>`, and `<select>` can have their values controlled by the state, and any changes trigger events (like `onChange`) to update the state. For form validation, developers typically manage validation rules within the component's state and update the UI accordingly when the user input does not meet the criteria. Libraries like Formik and Yup are often used for more complex form handling and validation in React.

### 7. **What is the difference between state and props in React?**

**Answer:**

- **State:**
  - Managed within the component (internal).
  - Mutable, meaning it can be changed within the component.
  - Represents the dynamic data of the component.
- **Props:**
  - Passed down from parent components (external).
  - Immutable, meaning they cannot be changed by the component that receives them.
  - Used to pass data and event handlers to child components.

### 8. **What are keys in React, and why are they important?**

**Answer:** Keys are unique identifiers used by React to track which items have changed, been added, or removed in a list. They help React optimize the rendering process by minimizing re-renders. Without keys, React would re-render all list items unnecessarily. Keys should be stable and unique within the list, often derived from the data being displayed (e.g., an ID).

```jsx
{items.map(item => (
  <li key={item.id}>{item.name}</li>
))}
```

### 9. **What is the context API in React, and when should you use it?**

**Answer:** The Context API in React is a way to manage global state across a React application without having to pass props down manually through every level of the component tree. It’s used when you have data or functions that need to be accessible by many components at different nesting levels, such as themes, user authentication, or localization.

**Usage Example:**

```jsx
const ThemeContext = React.createContext('light');

function App() {
  return (
    <ThemeContext.Provider value="dark">
      <Toolbar />
    </ThemeContext.Provider>
  );
}

function Toolbar() {
  return (
    <div>
      <ThemedButton />
    </div>
  );
}

function ThemedButton() {
  const theme = React.useContext(ThemeContext);
  return <button className={theme}>Button</button>;
}
```

### 10. **What are higher-order components (HOCs) in React?**

**Answer:** A Higher-Order Component (HOC) is a function that takes a component and returns a new component with additional props or behavior. HOCs are used for reusing component logic, like handling data fetching, authentication, or state management.

Example:

```js
function withLogging(WrappedComponent) {
  return function(props) {
    console.log('Rendering component');
    return <WrappedComponent {...props} />;
  };
}

const EnhancedComponent = withLogging(MyComponent);
```

Here, `withLogging` is an HOC that logs a message every time `MyComponent` renders.

### 11. **What is the difference between controlled and uncontrolled components in React?**

**Answer:**

- **Controlled Components:**
  - Form data is handled by the React component's state.
  - Every change in the form input is handled by a state update, giving React full control over the input value.
  - Easier to validate and control form data.
- **Uncontrolled Components:**
  - Form data is handled by the DOM itself, not by the component state.
  - Uses refs to access form values directly from the DOM.
  - Useful for simple forms where you don’t need to track state continuously.

```javascript
   // Controlled component
   function ControlledInput() {
     const [value, setValue] = useState("");

     return (
       <input
         type="text"
         value={value}
         onChange={(e) => setValue(e.target.value)}
       />
     );
   }

   // Uncontrolled component
   function UncontrolledInput() {
     const inputRef = useRef();

     const handleSubmit = () => {
       console.log(inputRef.current.value);
     };

     return <input type="text" ref={inputRef} />;
   }
```

### 12. **What is prop drilling, and how can it be avoided?**

**Answer:**

- **Prop Drilling**: The process of passing props down multiple levels of a component tree to reach a deeply nested component.
- **Problems**: It can make the code harder to maintain and refactor as the number of components grows.
- **Avoiding Prop Drilling**:
  - **Context API**: Use React's Context API to create a context and provide the data at a higher level, making it accessible to deeply nested components.
  - **State Management Libraries**: Use libraries like Redux, Zustand, or Recoil to manage global state.

### 13. **What are Higher-Order Components (HOCs)?**

**Answer:**

- A **Higher-Order Component (HOC)** is a function that takes a component and returns a new component with additional props or functionality.
- HOCs are useful for reusing component logic, like authentication checks, logging, or data fetching.
- Example:

```javascript
function withLogging(WrappedComponent) {
  return function(props) {
    console.log('Component rendered');
    return <WrappedComponent {...props} />;
  };
}

const EnhancedComponent = withLogging(MyComponent);
```

### 14. **What is the difference between `useEffect` and `useLayoutEffect`?**

**Answer:**

- **useEffect**: Runs asynchronously after the DOM has been updated. It’s typically used for side effects like data fetching, subscriptions, or modifying the DOM.
- **useLayoutEffect**: Runs synchronously after all DOM mutations but before the browser paints. It’s used for measuring the DOM or applying immediate changes that should happen before the user sees the update.

```javascript
useEffect(() => {
  console.log('Runs after render');
});

useLayoutEffect(() => {
  console.log('Runs before the paint');
});
```

### 15. **What are React fragments, and why would you use them?**

**Answer:**

- **React Fragments**: A way to group multiple elements without adding extra nodes to the DOM.
- Useful when you need to return multiple elements from a component but don’t want to wrap them in an extra `div` or other HTML element.
- Syntax:

```javascript
return (
  <>
    <h1>Hello</h1>
    <p>World</p>
  </>
);
```

### 16. **What are keys in React, and why are they important?**

**Answer:**

- **Keys**: Unique identifiers used by React to track which items in a list have changed, been added, or removed.
- Keys help React optimize rendering by only updating the elements that have changed, rather than re-rendering the entire list.
- Keys should be stable, unique, and consistent across renders.

```javascript
const items = ['Apple', 'Banana', 'Cherry'];
return items.map((item, index) => <li key={index}>{item}</li>);
```

### 17. **What is the difference between `React.createElement` and JSX?**

**Answer:**

- **React. CreateElement**: A method that creates a React element, which is an object representing a DOM node or component.
- **JSX**: A syntax extension that allows you to write HTML-like code within JavaScript. JSX is syntactic sugar for `React.createElement`.
- Under the hood, JSX code is transpiled to `React.createElement` calls by tools like Babel.

```javascript
// React.createElement
const element = React.createElement('h1', null, 'Hello, world');

// JSX (which gets compiled to React.createElement)
const element = <h1>Hello, world</h1>;
```

### 18. **What is React’s reconciliation process?**

**Answer:**

- **Reconciliation**: The process React uses to compare the current Virtual DOM with the new Virtual DOM to determine the minimal number of changes needed to update the real DOM.
- **Key Concepts**:
  - **Diffing**: React compares elements by their type and key.
  - **Updates**: If an element’s type or key changes, React will unmount the old element and mount a new one.
  - **Reordering**: Elements can be moved if their position in the list changes but their key remains the same.

### 19. **How does React handle forms?**

**Answer:**

- React handles forms using controlled components, where form data is managed by the component's state.
- Every input field is controlled by a state variable, and changes are reflected by updating the state.
- Validation and submission can be easily managed within the component.

```javascript
function MyForm() {
  const [value, setValue] = useState("");

  const handleSubmit = (e) => {
    e.preventDefault();
    alert('A name was submitted: ' + value);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Name:
        <input type="text" value={value} onChange={(e) => setValue(e.target.value)} />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}
```

### 20. **How can you optimize a React application?**

**Answer:**

- **Memoization**:
  - Use `React.memo` to prevent unnecessary re-renders.
  - Use `useCallback` and `useMemo` to optimize functions and computed values.
- **Code Splitting**:
  - Split code using `React.lazy` and `Suspense` to load components only when needed.
- **Virtualization**:
  - Use libraries like `react-window` or `react-virtualized` to efficiently render large lists.
- **Optimizing Re-renders**:
  - Avoid inline functions and objects as props.
  - Use immutable data structures to prevent unnecessary updates.
- **Efficient State Management**:
  - Use `useReducer` for complex state logic.
  - Consider using context or global state management libraries for shared state.

These questions and answers cover a wide range of topics in React, from basic to advanced concepts. Preparing with these will give you a strong foundation for React interviews.

# Javascript Interview Questions
### 1. What is JavaScript?

**Answer:**  
JavaScript is a high-level, interpreted scripting language that is used to create and control dynamic website content, like interactive forms, animations, and other user interactions on web pages. It is a core technology of the web, alongside HTML and CSS.

### 2. What are variables in JavaScript? How do you declare them?

**Answer:**  
Variables are containers for storing data values. In JavaScript, you can declare variables using `var`, `let`, and `const`.

```javascript
var name = 'John';  // function-scoped
let age = 30;       // block-scoped
const city = 'New York'; // block-scoped and read-only
```

### 3. What are JavaScript operators?

**Answer:**  
Operators are used to perform operations on variables and values. JavaScript supports various types of operators including:

- Arithmetic (`+`, `-`, `*`, `/`)
- Comparison (`==`, `===`, `!=`, `!==`, `>`, `<`)
- Logical (`&&`, `||`, `!`)
- Assignment (`=`, `+=`, `-=`, etc.)

### 4. What are functions in JavaScript?

**Answer:**  
Functions are blocks of code designed to perform a particular task. They are executed when they are called (invoked).

```javascript
function greet(name) {
  return 'Hello, ' + name;
}
console.log(greet('Alice')); // Hello, Alice
```

### 5. What are arrays in JavaScript?

**Answer:**  
Arrays are used to store multiple values in a single variable. They are a special type of object in JavaScript.

```javascript
let fruits = ['Apple', 'Banana', 'Cherry'];
console.log(fruits[0]); // Apple
```

### 6. What is an object in JavaScript?

**Answer:**  
Objects are collections of properties, where each property is defined as a key-value pair. They are used to store various keyed collections and more complex entities.

```javascript
let person = {
  name: 'John',
  age: 30,
  city: 'New York'
};
console.log(person.name); // John
```

### 7. What is the purpose of `typeof` operator in JavaScript?

**Answer:**  
The `typeof` operator is used to determine the type of a variable.

```javascript
Console.Log (typeof 42); // number
Console.Log (typeof 'Hello'); // string
Console.Log (typeof true); // boolean
Console.Log (typeof undefined); // undefined
Console.Log (typeof null); // object
Console.Log (typeof {}); // object
Console.Log (typeof []); // object (arrays are objects)
Console.Log (typeof function (){}); // function
```

### 8. What is NaN in JavaScript?

**Answer:**  
`NaN` stands for Not-a-Number. It is a value representing a computational error.

```javascript
Console.Log (0 / 0); // NaN
Console.Log (Number ('abc')); // NaN
```

### 9. What is the use of `isNaN` function?

**Answer:**  
The `isNaN` function determines whether a value is NaN (Not-a-Number).

```javascript
Console.Log (isNaN (NaN)); // true
Console.Log (isNaN ('abc')); // true
Console.Log (isNaN (123)); // false
```

### 10. What are template literals in JavaScript?

**Answer:**  
Template literals are string literals that allow embedded expressions. They are enclosed by backticks (`` ` ``) instead of quotes.

```javascript
Let name = 'John';
Let message = `Hello, ${name}!`;
Console.Log (message); // Hello, John!
```

### 11. What are conditionals in JavaScript?

**Answer:**  
Conditionals are used to perform different actions based on different conditions. JavaScript supports `if`, `else if`, `else`, and `switch` statements.

```javascript
Let age = 20;
If (age >= 18) {
  Console.Log ('Adult');
} else {
  Console.Log ('Minor');
}
```

### 12. What are loops in JavaScript?

**Answer:**  
Loops are used to execute a block of code multiple times. JavaScript supports `for`, `while`, and `do... While` loops.

```javascript
For (let i = 0; i < 5; i++) {
  Console.Log (i);
}
```

### 13. What is the difference between `for` and `for... In` loops?

**Answer:**

- `for` loop is used to iterate over the values in an array or other iterable objects.
- `for... In` loop is used to iterate over the properties of an object.

```javascript
Let array = [10, 20, 30];
For (let i = 0; i < array. Length; i++) {
  Console.Log (array[i]); // 10, 20, 30
}

Let object = { a: 1, b: 2, c: 3 };
For (let key in object) {
  Console.Log (key, object[key]); // a 1, b 2, c 3
}
```

### 14. What is a switch statement in JavaScript?

**Answer:**  
The `switch` statement is used to perform different actions based on different conditions.

```javascript
Let fruit = 'apple';
Switch (fruit) {
  Case 'banana':
    Console.Log ('Banana is yellow');
    Break;
  Case 'apple':
    Console.Log ('Apple is red');
    Break;
  Default:
    Console.Log ('Unknown fruit');
}
```

### 15. What is an immediately invoked function expression (IIFE)?

**Answer:**  
An IIFE is a function that runs as soon as it is defined. It is often used to create a private scope to avoid variable hoisting and conflicts.

```javascript
(function () {
  Console.Log ('IIFE executed');
})();
```

### 16. What is the DOM?

**Answer:**  
The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

### 17. What is an event in JavaScript?

**Answer:**  
An event is an action or occurrence detected by the browser, such as a mouse click, a key press, or the loading of a web page. Events are used to trigger JavaScript functions to run.

```javascript
document.getElementById('myButton').addEventListener('click', function() {
  alert('Button clicked!');
});
```

### 18. What is the difference between `window.onload` and `document.ready`?

**Answer:**

- `window.onload` is an event that fires when the entire page, including all dependent resources such as stylesheets and images, has loaded.
- `document.ready` (often used with libraries like jQuery) fires when the DOM is fully loaded, without waiting for stylesheets, images, and other resources to finish loading.

```javascript
window.onload = function() {
  console.log('Window loaded');
};

document.addEventListener('DOMContentLoaded', function() {
  console.log('DOM fully loaded and parsed');
});
```

### 19. What are the different types of pop-up boxes available in JavaScript?

**Answer:**  
JavaScript provides three types of pop-up boxes:

- `alert()`: Displays a message with an OK button.
- `confirm()`: Displays a message with OK and Cancel buttons, returning true if OK is pressed and false otherwise.
- `prompt()`: Displays a message with a text input field and OK and Cancel buttons, returning the input value or null if Cancel is pressed.

```javascript
alert('This is an alert box.');
let result = confirm('Do you want to continue?');
let name = prompt('What is your name?');
```

### 20. What are JavaScript data structures?

**Answer:**  
JavaScript provides several built-in data structures:

- **Arrays:** Ordered collections of elements.
- **Objects:** Collections of key-value pairs.
- **Sets:** Collections of unique values.
- **Maps:** Collections of key-value pairs where keys can be any data type.

```javascript
let array = [1, 2, 3];
let object = { name: 'Alice', age: 25 };
let set = new Set([1, 2, 3]);
let map = new Map([['key1', 'value1'], ['key2', 'value2']]);
```

### 21. How do you create an object in JavaScript?

**Answer:**  
Objects can be created using object literals, the `Object` constructor, or the `class` syntax introduced in ES 6.

```javascript
// Object literal
let obj1 = {
  name: 'Alice',
  age: 25
};

// Object constructor
let obj2 = new Object();
obj2.name = 'Bob';
obj2.age = 30;

// ES6 class syntax
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
}
let obj3 = new Person('Charlie', 35);
```

### 22. What is JSON and how is it used?

**Answer:**  
JSON (JavaScript Object Notation) is a lightweight data interchange format that is easy for humans to read and write and easy for machines to parse and generate. It is used to exchange data between a server and a web application.

```javascript
// JSON string
let jsonString = '{"name": "Alice", "age": 25}';

// Parse JSON string to object
let obj = JSON.parse(jsonString);
console.log(obj.name); // Alice

// Convert object to JSON string
let newJsonString = JSON.stringify(obj);
console.log(newJsonString); // {"name":"Alice","age":25}
```

### 23. What are JavaScript events and how are they handled?

**Answer:**  
JavaScript events are actions that occur in the browser, such as clicks, key presses, or form submissions. Events are handled by assigning event listeners to HTML elements.

```javascript
// Add event listener
document.getElementById('myButton').addEventListener('click', function() {
  alert('Button clicked!');
});

// Inline event handler
<button onclick="alert('Button clicked!')">Click me</button>
```

### 24. What is the difference between `innerHTML` and `innerText`?

**Answer:**

- `innerHTML` retrieves or sets the HTML content inside an element.
- `innerText` retrieves or sets the text content inside an element, ignoring any HTML tags.

```javascript
let div = document.createElement('div');
div.innerHTML = '<p>Hello, <b>world</b>!</p>';
console.log(div.innerHTML); // <p>Hello, <b>world</b>!</p>
console.log(div.innerText); // Hello, world!
```

### 25. What are callback functions in JavaScript?

**Answer:**  
A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of action or routine.

```javascript
function greet(name, callback) {
  console.log('Hello, ' + name);
  callback();
}

function sayGoodbye() {
  console.log('Goodbye!');
}

greet('Alice', sayGoodbye);
// Output:
// Hello, Alice
// Goodbye!
```

### 26. What is the use of `addEventListener` in JavaScript?

**Answer:**  
`addEventListener` is used to attach an event handler to a specified element. It allows multiple event handlers for the same event and can be removed later with `removeEventListener`.

```javascript
function handleClick() {
  alert('Button clicked!');
}

document.getElementById('myButton').addEventListener('click', handleClick);
```

### 27. What is the `this` keyword in JavaScript?

**Answer:**  
The `this` keyword refers to the object that is executing the current function. Its value can change depending on the context in which the function is called.

```javascript
let person = {
  name: 'Alice',
  greet: function() {
    console.log('Hello, ' + this.name);
  }
};

person.greet(); // Hello, Alice
```

### 28. What are prototypes in JavaScript?

**Answer:**  
Prototypes are objects from which other objects inherit properties. Every JavaScript object has a prototype, which is used for inheritance.

```javascript
function Person(name) {
  this.name = name;
}

Person.prototype.greet = function() {
  console.log('Hello, ' + this.name);
};

let alice = new Person('Alice');
alice.greet(); // Hello, Alice
```

### 29. What is the difference between `call`, `apply`, and `bind`?

**Answer:**

- `call` invokes a function with a given `this` value and arguments provided individually.
- `apply` invokes a function with a given `this` value and arguments provided as an array.
- `bind` returns a new function, where `this` is bound to the provided value, allowing for partial application of function arguments.

```javascript
function greet(greeting, punctuation) {
  console.log(greeting + ', ' + this.name + punctuation);
}

let person = { name: 'Alice' };

greet.call(person, 'Hello', '!'); // Hello, Alice!
greet.apply(person, ['Hi', '!']); // Hi, Alice!
let boundGreet = greet.bind(person, 'Hey');
boundGreet('!'); // Hey, Alice!
```

### 30. What are JavaScript Promises?

**Answer:**  
Promises are used to handle asynchronous operations in JavaScript. They represent a value that may be available now, in the future, or never. Promises have three states: `pending`, `fulfilled`, and `rejected`.

```javascript
let promise = new Promise((resolve, reject) => {
  setTimeout(() => {
    resolve('Success!');
  }, 1000);
});

promise.then((message) => {
  console.log(message); // 'Success!' after 1 second
});
```

# Nodejs Interview Questions
### 1. **What is Node. Js?**
   **Answer**: 
   Node. Js is a runtime environment that allows developers to execute JavaScript code on the server-side. It is built on the V 8 JavaScript engine, which is also used by Google Chrome, and uses an event-driven, non-blocking I/O model, making it efficient and scalable for building web applications.

### 2. **What is the difference between `require()` and `import` in Node. Js?**
   **Answer**: 
   - `require()` is the syntax used in CommonJS modules, the default module system in Node. Js. It loads modules synchronously and returns the exports object of the module.
   - `import` is part of ES Modules (ESM), introduced in ECMAScript 2015 (ES 6). It allows for static imports and is asynchronous by default. Node. Js supports both, but CommonJS is more widely used in older codebases.

### 3. **Explain the Event Loop in Node. Js.**
   **Answer**: 
   The event loop is the core of Node. Js's asynchronous behavior. It is a single-threaded loop that handles callbacks, performs non-blocking I/O operations, and processes asynchronous code. The event loop continuously checks the call stack to see if there’s any function that needs to be executed and also checks if there are any pending asynchronous operations in the callback queue.

### 4. **How does Node. Js handle asynchronous operations?**
   **Answer**: 
   Node. Js handles asynchronous operations using the event loop along with callback functions, Promises, or async/await. When an asynchronous operation is initiated, Node. Js offloads it to the system kernel or a thread pool, which then processes it and sends the result back via a callback or resolves/rejects a Promise, allowing the event loop to handle the next task without being blocked.

### 5. **What is middleware in Express. Js?**
   **Answer**: 
   Middleware functions in Express. Js are functions that have access to the request object (`req`), the response object (`res`), and the next middleware function in the application’s request-response cycle. They can execute code, modify the request/response objects, end the request-response cycle, or call the next middleware in the stack.

### 6. **What is the difference between `process.nextTick()` and `setImmediate()`?**
   **Answer**: 
   - `process.nextTick()` schedules a callback function to be invoked in the next iteration of the event loop, before any I/O tasks.
   - `setImmediate()` schedules a callback to be executed on the next iteration of the event loop, after the I/O events have been processed.

   Essentially, `process.nextTick()` executes sooner than `setImmediate()`.

### 7. **What are streams in Node. Js?**
   **Answer**: 
   Streams are abstract interfaces in Node. Js that allow working with streaming data. There are four types of streams:
   - **Readable**: Streams from which data can be read (e.g., `fs.createReadStream`).
   - **Writable**: Streams to which data can be written (e.g., `fs.createWriteStream`).
   - **Duplex**: Streams that are both readable and writable (e.g., TCP sockets).
   - **Transform**: Streams that can modify or transform the data as it is written and read (e.g., `zlib.createGzip`).

   Streams are particularly useful for handling large files or real-time data as they allow processing of data piece by piece rather than all at once.

### 8. **How can you avoid callback hell in Node. Js?**
   **Answer**: 
   Callback hell, also known as "Pyramid of Doom," occurs when callbacks are nested within callbacks, making code difficult to read and maintain. To avoid it:
   - Use **Promises**: Promises allow chaining of asynchronous operations and provide better readability.
   - Use **async/await**: This syntactic sugar over Promises allows writing asynchronous code in a synchronous manner, making it even more readable.
   - Break down code into **smaller functions**: This makes it easier to manage and avoid deep nesting.

### 9. **What is the purpose of the `package.json` file in a Node. Js project?**
   **Answer**: 
   The `package.json` file is the manifest file of a Node. Js project. It contains metadata about the project, including the project name, version, author, dependencies, scripts, license, and other configurations. It is essential for managing project dependencies and scripts, and it allows others to easily install the project and its dependencies using npm or yarn.

### 10. **Explain the concept of clustering in Node. Js.**
   **Answer**: 
   Clustering in Node. Js is a way to scale an application by creating multiple instances (workers) of the Node. Js process that can run on multiple CPU cores. The `cluster` module allows you to spawn child processes that share the same server port, effectively allowing the application to handle more concurrent requests. Each worker is a separate Node. Js process and operates independently, but they all share the same server port.

### 11. **What is the purpose of the `Buffer` class in Node. Js?**
   **Answer**: 
   The `Buffer` class in Node. Js is used to handle binary data directly. Buffers are used when dealing with raw binary data, such as reading from a file or receiving data over a network, which cannot be handled efficiently with standard JavaScript data types like strings or arrays.

### 12. **How do you handle uncaught exceptions in Node. Js?**
   **Answer**: 
   Uncaught exceptions can be handled using the `process.on('uncaughtException', callback)` event. However, it’s generally not recommended to rely on this event for error handling because it could leave your application in an inconsistent state. Instead, you should use proper error handling in your code using `try-catch` blocks, and by using middleware for error handling in frameworks like Express.

### 13. **What is the role of the `module.exports` and `exports` in Node. Js?**
   **Answer**: 
   In Node. Js, `module.exports` and `exports` are used to expose functions, objects, or variables from a module so that they can be imported and used in other modules. `module.exports` is the object that is actually returned as the result of a `require()` call. `exports` is simply a reference to `module.exports`. You can use either to expose functionality, but if you assign a new object or function to `exports`, you should use `module.exports` instead to avoid breaking the reference.

### 14. **Explain the use of the `async` and `await` keywords in Node. Js.**
   **Answer**: 
   The `async` keyword is used to declare an asynchronous function that returns a Promise. The `await` keyword is used to pause the execution of the function until the Promise is resolved or rejected. It allows writing asynchronous code in a more readable, synchronous-looking manner. `await` can only be used inside an `async` function.

### 15. **How do you secure a Node. Js application?**
   **Answer**:
   - **Use HTTPS**: Ensure data in transit is encrypted.
   - **Data Validation and Sanitization**: Prevent SQL Injection and XSS attacks.
   - **Helmet. Js**: Secure your Express. Js apps by setting various HTTP headers.
   - **Rate Limiting**: Prevent DDoS attacks by limiting the number of requests.
   - **Authentication**: Implement secure authentication using JWT, OAuth, etc.
   - **Environment Variables**: Use environment variables to store sensitive information.

# API Interview Questions 
### 1. **What is REST, and what are its key principles?**

**REST** (Representational State Transfer) is an architectural style used for designing networked applications. It relies on a stateless, client-server communication model where requests are made using standard HTTP methods (GET, POST, PUT, DELETE, etc.).

**Key Principles of REST:**
- **Statelessness**: Each request from a client to a server must contain all the information needed to understand and process the request. The server does not store any state between requests.
- **Client-Server Architecture**: The client and server are separate entities. The client handles the user interface and user state, while the server manages the data and logic.
- **Uniform Interface**: REST uses standard HTTP methods and URIs to provide a consistent interface for accessing resources.
- **Cacheability**: Responses from the server can be marked as cacheable, allowing clients to reuse data and reduce load on the server.
- **Layered System**: The client does not know if it is connected directly to the server or through intermediaries, such as load balancers or proxies.
- **Code on Demand (optional)**: Servers can extend client functionality by transferring executable code (e.g., JavaScript) to the client.

### 2. **What are the differences between REST and SOAP?**

**REST**:
- **Simplicity**: REST is simpler and easier to implement, using standard HTTP methods and typically JSON or XML for data exchange.
- **Flexibility**: REST allows a variety of data formats (JSON, XML, HTML, etc.) and is stateless, making it more scalable.
- **Performance**: REST is more performant due to its stateless nature and ability to cache responses.
- **Use Cases**: Commonly used in web services, mobile applications, and public APIs.

**SOAP** (Simple Object Access Protocol):
- **Complexity**: SOAP is more complex, requiring strict XML formatting and adherence to the WS-* standards.
- **Protocol**: SOAP is a protocol with built-in error handling, security (WS-Security), and transaction management, making it suitable for enterprise applications.
- **Statefulness**: SOAP can be stateful, supporting operations like transactions and sessions.
- **Use Cases**: Often used in enterprise environments for operations that require ACID compliance, high security, and formal contracts (WSDL).

### 3. **How do you design a RESTful API?**

**Best Practices for Designing RESTful APIs**:
- **Use Nouns for Resource Names**: URIs should represent resources using nouns (e.g., `/users`, `/orders`), not actions or verbs.
- **Use HTTP Methods Appropriately**:
  - **GET** for retrieving resources.
  - **POST** for creating new resources.
  - **PUT** for updating existing resources or creating resources if they don’t exist (idempotent).
  - **PATCH** for partially updating resources.
  - **DELETE** for removing resources.
- **Use HTTP Status Codes**: Use appropriate status codes to communicate the result of an API request (`200 OK`, `201 Created`, `404 Not Found`, etc.).
- **Versioning**: Version your API (e.g., `/v1/users`) to handle changes without breaking existing clients.
- **Handle Pagination, Filtering, and Sorting**: Implement pagination, filtering, and sorting to manage large datasets efficiently (`/users?page=2&limit=10`).
- **Security**: Use authentication and authorization (e.g., API keys, OAuth, JWT) to secure the API.
- **Documentation**: Provide clear API documentation to help developers understand how to use your API.

### 4. **What is idempotency, and which HTTP methods are idempotent?**

**Idempotency** refers to the property of certain operations where performing the same operation multiple times yields the same result. In the context of HTTP, an idempotent method means that making multiple identical requests will not change the state of the resource beyond the initial application.

**Idempotent HTTP Methods**:
- **GET**: Retrieving the same resource multiple times does not alter the resource.
- **PUT**: Updating a resource with the same data repeatedly results in the same resource state.
- **DELETE**: Deleting a resource multiple times results in the resource being removed (if it exists) or remains removed.
- **PATCH**: Partially updating a resource multiple times with the same data results in the same state.

**Non-Idempotent HTTP Method**:
- **POST**: Sending the same data multiple times can result in multiple resources being created, making it non-idempotent.

### 5. **What are some common HTTP status codes used in RESTful APIs?**

- **200 OK**: The request was successful, and the server returned the requested resource.
- **201 Created**: A new resource was successfully created as a result of the request.
- **204 No Content**: The request was successful, but there is no content to return (often used with DELETE).
- **400 Bad Request**: The server could not understand the request due to invalid syntax or bad data.
- **401 Unauthorized**: The client must authenticate itself to get the requested resource.
- **403 Forbidden**: The client does not have access rights to the resource.
- **404 Not Found**: The server cannot find the requested resource.
- **500 Internal Server Error**: The server encountered an unexpected condition that prevented it from fulfilling the request.

### 6. **How do you handle pagination in a RESTful API?**

**Techniques for Implementing Pagination**:
- **Query Parameters**: Use query parameters to specify the page number and the number of items per page.
  - Example: `/users?page=2&limit=10` retrieves the second page of users with 10 users per page.
- **Link Headers**: Include links in the response headers to indicate the next, previous, first, and last pages.
  - Example: 
    ```
    Link: <https://api.example.com/users?page=1&limit=10>; rel="first",
          <https://api.example.com/users?page=3&limit=10>; rel="next",
          <https://api.example.com/users?page=10&limit=10>; rel="last"
    ```
- **Offset and Limit**: Use `offset` to indicate where the results start, and `limit` to specify the number of results to return.
  - Example: `/users?offset=20&limit=10` retrieves 10 users starting from the 21 st user.
- **Cursor-Based Pagination**: Use a cursor (a pointer to a specific record in the result set) for efficient pagination, especially with large datasets.
  - Example: `/users?cursor=xyz123&limit=10`.

### 7. **What is HATEOAS, and how is it used in RESTful APIs?**

**HATEOAS** (Hypermedia as the Engine of Application State) is a constraint of REST that requires the server to provide hyperlinks in its responses. These hyperlinks guide clients on what actions they can take next.

**Usage in RESTful APIs**:
- When a client requests a resource, the server responds with the resource's representation, along with links to related actions or resources.
- **Example**:
  ```json
  {
    "userId": 123,
    "name": "John Doe",
    "links": [
      {
        "rel": "self",
        "href": "/users/123",
        "method": "GET"
      },
      {
        "rel": "update",
        "href": "/users/123",
        "method": "PUT"
      },
      {
        "rel": "delete",
        "href": "/users/123",
        "method": "DELETE"
      }
    ]
  }
  ```
  - Here, the response includes links to view, update, or delete the user, guiding the client on what actions can be performed.

### 8. **How do you implement security in RESTful APIs?**

**Methods for Securing RESTful APIs**:
- **API Keys**: Simple method where each request must include an API key in the request header for authentication.
- **OAuth**: A widely used authorization framework that allows third-party services to exchange access tokens without exposing user credentials.
  - **OAuth 2.0** is the most common version, allowing the use of tokens to access resources on behalf of a user.
- **JWT (JSON Web Token)**: A compact, URL-safe token that represents claims between two parties. Used for stateless authentication, where the server does not need to maintain session data.
  - **Token Structure**: Consists of a header, payload, and signature.
- **HTTPS**: Always use HTTPS to encrypt data in transit, protecting it from being intercepted by attackers.
- **Rate Limiting**: Prevent abuse by limiting the number of requests a client can make in a given period.
- **CORS (Cross-Origin Resource Sharing)**: Configure CORS policies to control which domains can access your API.

### 9. **What are the advantages and disadvantages of using REST?**

**Advantages of REST**:
- **Simplicity**: REST is easy to implement and understand, using standard HTTP methods and formats like JSON.
- **Scalability**: REST’s stateless nature makes it easier to scale horizontally across multiple servers.
- **Flexibility**: REST allows for a wide variety of data formats and is not tied to any specific protocol or architecture.
- **Performance**: REST can leverage caching, reducing server load and improving response times.

**Disadvantages of REST**:
- **Lack of State**: Since REST is stateless, each request must contain all necessary information, which can

 Lead to overhead in complex interactions.
- **Over-fetching/Under-fetching**: Clients may receive more or less data than needed, as REST APIs typically return fixed data structures.
- **Limited Security**: REST relies on HTTPS and additional layers for security, which can be less robust than SOAP’s built-in security features.

### 10. **What is the difference between PUT and PATCH?**

**PUT**:
- **Purpose**: Update an entire resource with new data. If the resource does not exist, it may be created.
- **Idempotency**: PUT is idempotent, meaning multiple identical requests will produce the same result.
- **Use Case**: Replacing a user’s profile (`PUT /users/123`) with new data.

**PATCH**:
- **Purpose**: Partially update a resource with new data. It is used when only certain fields need to be updated.
- **Idempotency**: PATCH is also idempotent, but the result depends on the provided data.
- **Use Case**: Updating just the email field of a user’s profile (`PATCH /users/123`) without affecting other fields.

# Auth Interview Questions
### **1. What is the difference between authentication and authorization?**
- **Answer**: 
  - **Authentication** is the process of verifying the identity of a user or entity. It determines "who you are." 
  - **Authorization** is the process of determining if the authenticated user has permission to access a resource or perform an action. It determines "what you are allowed to do."
  - **Example**: When you log into a system (authentication), the system then checks if you have the rights to access specific resources or perform actions like editing data (authorization).

### **2. What is JWT, and how does it work?**
- **Answer**: 
  - **JWT (JSON Web Token)** is a compact, URL-safe token used for transmitting claims between two parties. It consists of three parts: Header, Payload, and Signature.
  - **How it works**:
    - **Header**: Contains the token type (JWT) and signing algorithm (e.g., HMAC SHA 256).
    - **Payload**: Contains the claims, which are statements about an entity (usually the user) and additional metadata.
    - **Signature**: Created by encoding the header and payload and then signing it with a secret key or RSA private key.
    - **Usage**: The token is sent by the client in the `Authorization` header (`Bearer <token>`) with each request. The server verifies the signature to ensure the token’s integrity and authenticity.

### **3. What are the common methods of implementing authentication in web applications?**
- **Answer**: 
  - **Basic Authentication**: Credentials are sent in the `Authorization` header encoded in Base 64 with each request.
  - **Token-Based Authentication**: After successful login, the server issues a token (e.g., JWT) that the client uses for subsequent requests.
  - **OAuth 2.0**: A framework that allows third-party services to exchange tokens without exposing user credentials, often used in social logins.
  - **SAML (Security Assertion Markup Language)**: Used for Single Sign-On (SSO) in enterprise environments.
  - **Multi-Factor Authentication (MFA)**: Requires two or more verification factors, such as something you know (password) and something you have (mobile phone).

### **4. What is OAuth 2.0, and how does it differ from OAuth 1.0?**
- **Answer**:
  - **OAuth 2.0** is an authorization framework that allows third-party applications to access a user’s resources without exposing their credentials. It uses tokens to grant access.
  - **Differences from OAuth 1.0**:
    - **Simpler**: OAuth 2.0 is more straightforward and uses tokens instead of signatures for requests, making it easier to implement.
    - **More Secure**: OAuth 2.0 requires SSL/TLS, whereas OAuth 1.0 allowed plaintext communication, leading to potential vulnerabilities.
    - **Token Types**: OAuth 2.0 introduces access tokens, refresh tokens, and the concept of scopes, providing more granular control over permissions.

### **5. What is the principle of "least privilege," and why is it important in authorization?**
- **Answer**:
  - **Principle of Least Privilege**: This principle states that users and services should be granted the minimum level of access necessary to perform their tasks.
  - **Importance**:
    - **Security**: Reduces the attack surface by limiting what an attacker can do if they gain access.
    - **Minimizes Risk**: Prevents users from accidentally or maliciously performing unauthorized actions.
    - **Compliance**: Many regulations require enforcing least privilege to protect sensitive data.

### **6. How does Multi-Factor Authentication (MFA) improve security?**
- **Answer**:
  - **MFA** adds an additional layer of security by requiring two or more independent credentials before granting access. These factors typically include:
    - **Something you know**: A password or PIN.
    - **Something you have**: A physical token, mobile phone (for SMS codes or app-based authentication).
    - **Something you are**: Biometric verification, such as fingerprints or facial recognition.
  - **Improvement**:
    - **Reduces Reliance on Passwords**: Even if a password is compromised, the additional factor (s) provide a strong defense against unauthorized access.
    - **Mitigates Common Attacks**: Protects against phishing, password spraying, and other common attacks.

### **7. What is the purpose of using access tokens and refresh tokens in OAuth 2.0?**
- **Answer**:
  - **Access Token**: A short-lived token used to access protected resources. It is included in API requests to prove the identity of the client.
  - **Refresh Token**: A long-lived token that can be used to obtain a new access token without re-authenticating. This allows for continuous access without requiring the user to log in repeatedly.
  - **Purpose**:
    - **Security**: Limits the exposure of the user's credentials by not requiring them to be sent with each request.
    - **Convenience**: Allows clients to remain logged in for longer periods without asking users to re-authenticate frequently.

### **8. What are some common security vulnerabilities in authentication systems, and how can they be mitigated?**
- **Answer**:
  - **Brute Force Attacks**: Attackers attempt to guess passwords by trying many combinations.
    - **Mitigation**: Implement rate limiting, account lockout mechanisms, and use CAPTCHA after several failed attempts.
  - **Phishing Attacks**: Attackers trick users into revealing their credentials via fake login pages or deceptive emails.
    - **Mitigation**: Educate users, implement MFA, and use email filters.
  - **Session Hijacking**: Attackers steal session cookies or tokens to impersonate a user.
    - **Mitigation**: Use secure (HttpOnly, Secure) cookies, implement token expiration, and enforce HTTPS.
  - **Cross-Site Request Forgery (CSRF)**: Attackers trick users into submitting requests on their behalf.
    - **Mitigation**: Use anti-CSRF tokens and require re-authentication for sensitive actions.

### **9. What is Role-Based Access Control (RBAC), and how does it differ from Attribute-Based Access Control (ABAC)?**
- **Answer**:
  - **Role-Based Access Control (RBAC)**: Users are assigned roles, and roles are granted permissions to access resources.
    - **Example**: An "admin" role might have access to all resources, while a "user" role has limited access.
  - **Attribute-Based Access Control (ABAC)**: Access is granted based on attributes (user attributes, resource attributes, environment conditions).
    - **Example**: A user can access a document only if they are in a specific department, the document is classified as public, and it is during business hours.
  - **Differences**:
    - **RBAC** is simpler and easier to manage, suitable for environments with clear role hierarchies.
    - **ABAC** is more granular and flexible, allowing for complex access control decisions based on various attributes.

### **10. What are API keys, and how do they differ from OAuth tokens?**
- **Answer**:
  - **API Keys**: Simple tokens used to authenticate a client making API requests. They are typically sent as a query parameter or in the header of an HTTP request.
  - **OAuth Tokens**: More complex tokens that represent the identity of a user and their permissions. OAuth tokens are often JWTs and include claims that specify what actions can be performed.
  - **Differences**:
    - **API Keys**: Generally static, providing simple authentication. They do not inherently include permissions or scopes.
    - **OAuth Tokens**: Include detailed information about the user and what they are authorized to do. They are more secure and support granular access control.

### **11. How do you securely store passwords?**
- **Answer**:
  - **Hashing**: Passwords should never be stored in plain text. Instead, they should be hashed using a strong, one-way hashing algorithm like bcrypt, scrypt, or Argon 2.
  - **Salting**: A unique salt (random data) should be added to each password before hashing to protect against rainbow table attacks.
  - **Pepper**: An additional secret value known only to the server can be added to the hash, further strengthening password security.
  - **Iteration**: The hashing algorithm should be computationally intensive to slow down brute-force attacks.

### **12. What is Cross-Site Request Forgery (CSRF), and how can it be prevented?**
- **Answer**:
  - **CSRF**: An attack where an attacker tricks a user into performing actions on a web application where they are authenticated, without their consent.
  - **Prevention**:
    - **Anti-CSRF Tokens**: Include a unique token in each form submission or AJAX request that the server validates. The token ensures that the request is coming from the legitimate user.
    - **SameSite Cookies**: Set cookies with the `SameSite` attribute to ensure they are only sent with requests from the same origin.
    - **Double Submit Cookie**: Include the CSRF token in both the cookie and the request, and verify that they match.

### **13. What are the common HTTP status codes related to authentication and authorization?**
- **Answer**:
  - **401 Unauthorized**: The request requires authentication, but the client has not provided valid credentials.
  - **403 Forbidden**: The client’s credentials are valid, but they do not have

# MongoDB Interview Questions

### 1. What is MongoDB?

MongoDB is a document-oriented NoSQL database that stores data in flexible, JSON-like documents. It is designed for high performance, high availability, and easy scalability, making it suitable for handling large volumes of data.

### 2. What are the advantages of using MongoDB?

- **Flexible Schema**: MongoDB allows for a dynamic schema, enabling easy modifications to the data model.
- **Scalability**: It supports horizontal scaling through sharding, distributing data across multiple servers.
- **High Performance**: Optimized for read and write operations, making it suitable for high-traffic applications.
- **Rich Query Language**: Supports complex queries, including filtering, sorting, and aggregation.
- **Built-in Replication**: Ensures data availability and redundancy through replica sets.

### 3. What is BSON?

BSON (Binary JSON) is a binary-encoded serialization format used by MongoDB to store documents. It extends JSON by adding support for additional data types, such as dates and binary data, and is designed for efficient storage and retrieval.

### 4. Explain the structure of a MongoDB document.

A MongoDB document is a set of key-value pairs, similar to a JSON object. Each document can contain various data types, including arrays and nested documents, allowing for a rich and flexible data representation.

### 5. What is a collection in MongoDB?

A collection is a grouping of MongoDB documents, analogous to a table in relational databases. Collections do not enforce a schema, allowing documents within the same collection to have different structures.

### 6. How do you perform queries in MongoDB?

Queries in MongoDB are performed using the `find` method. This method retrieves documents from a collection based on specified criteria. For example:

```javascript
db.collection.find({ "field": "value" })
```

### 7. What is an upsert operation in MongoDB?

An "upsert" is a combination of "update" and "insert." It updates an existing document if it matches the specified criteria or inserts a new document if no match is found. This operation is facilitated by the `update` method with the `upsert` option set to true.

### 8. How does MongoDB handle relationships between documents?

MongoDB does not support traditional foreign key constraints. Instead, relationships can be managed using embedded documents (storing related data within a single document) or by referencing documents (storing references to other documents' IDs).

### 9. What is sharding in MongoDB?

Sharding is the process of distributing data across multiple servers or shards to handle large datasets and high throughput operations. Each shard is a separate database instance that holds a subset of the data, allowing for horizontal scaling.

### 10. What are indexes in MongoDB, and why are they important?

Indexes in MongoDB are special data structures that improve the speed of data retrieval operations. They allow for efficient querying by providing quick access paths to documents based on indexed fields. Proper indexing is crucial for optimizing query performance and reducing response times.

### 11. What are some of the advantages of using MongoDB?

- **Flexible Schema**: MongoDB allows for a dynamic schema, enabling easy modifications to the data model.
- **Scalability**: It supports horizontal scaling through sharding, distributing data across multiple servers.
- **High Performance**: Optimized for read and write operations, making it suitable for high-traffic applications.
- **Rich Query Language**: Supports complex queries, including filtering, sorting, and aggregation.
- **Built-in Replication**: Ensures data availability and redundancy through replica sets.

### 12. When should you use MongoDB?

MongoDB is suitable for applications that require rapid development and scalability, such as:

- Applications with evolving data requirements.
- Systems that need to handle large volumes of read and write operations.
- Projects that require flexible data models, such as content management systems or real-time analytics.

### 13. What is the significance of BSON in MongoDB?

BSON (Binary JSON) is a binary-encoded serialization format used by MongoDB to store documents. It extends JSON by adding support for additional data types, such as dates and binary data, and is designed for efficient storage and retrieval. This binary format allows MongoDB to optimize data handling compared to text-based JSON.

### 14. Describe the structure of a MongoDB document.

A MongoDB document is composed of key-value pairs, similar to a JSON object. Each document can contain various data types, including arrays and nested documents, allowing for a rich and flexible data representation.

### 15. Explain the SET modifier in MongoDB.

The `$set` operator is used to update the value of a field in a document. If the field does not exist, `$set` will create it. This is useful for modifying existing documents without overwriting the entire document. For example:

```javascript
db.collection.updateOne(
   { "_id": ObjectId("document_id") },
   { "$set": { "newField": "newValue" } }
)
```

### 16. What is a replica set in MongoDB?

A replica set is a group of MongoDB servers that maintain the same data set, providing redundancy and high availability. It consists of a primary node (which receives all write operations) and one or more secondary nodes (which replicate the data from the primary). If the primary node fails, one of the secondary nodes can be elected as the new primary.

### 17. How does MongoDB handle data consistency?

MongoDB provides eventual consistency by default in sharded clusters, meaning that data might not be immediately consistent across all nodes. However, it offers strong consistency for single-document operations, ensuring that once a write operation is acknowledged, subsequent reads will return the updated data.

### 18. What is the purpose of the `aggregate` function in MongoDB?

The `aggregate` function is used to process data and return computed results. It allows for the execution of complex data processing operations, such as filtering, grouping, and sorting, on the data stored in a collection. The aggregation framework provides a powerful way to perform operations like calculating averages, sums, and counts.

### 19. How can you import and export data in MongoDB?

Data can be imported and exported in MongoDB using the following tools:

- **mongoimport**: Used to import data from JSON, CSV, or TSV files into a MongoDB collection.
- **mongoexport**: Used to export data from a MongoDB collection to a JSON or CSV file.

Example of importing data:

```bash
mongoimport --db database_name --collection collection_name --file data.json
```

### 20. What is sharding, and how does it work in MongoDB?

Sharding is the process of distributing data across multiple servers or shards to handle large datasets and high throughput operations. Each shard is a separate database instance that holds a subset of the data. MongoDB automatically manages the distribution of data and queries across the shards, allowing for horizontal scaling and improved performance.


# Database Interview Questions

### 1. What is DBMS and what is its utility?

DBMS stands for Database Management System. It is a software system that enables users to create, maintain, control and access a database efficiently. DBMS provides an interface for performing various operations such as inserting, deleting, updating data in a database. It helps overcome issues like data redundancy, inconsistency and makes data management more organized and secure compared to traditional file-based systems.

### 2. What are the advantages of DBMS over file-based systems?

Some key advantages of DBMS over file-based systems include:

- Reduced data redundancy and inconsistency
- Easier data access and management 
- Enforced data integrity
- Atomicity of updates
- Ability to handle concurrent access by multiple users
- Improved data security and privacy

### 3. What is a database?

A database is an organized, consistent and logical collection of interrelated data that can be easily accessed, managed and updated. It typically consists of one or more tables, where each table contains a set of related data organized into rows and columns. The columns represent attributes or fields, while each row represents a record or tuple.

### 4. What are the different types of database models?

The main types of database models are:

1. **Hierarchical model** - Data is organized into a tree-like structure with parent-child relationships.

2. **Network model** - Allows for multiple parent-child relationships, forming a graph-like structure.

3. **Relational model** - Data is stored in tables with rows and columns. Tables can be related to each other using keys.

4. **Object-oriented model** - Data and methods are encapsulated into objects which are instances of classes.

5. **Entity-relationship model** - Conceptual model that views the real world as entities and relationships[1][4].

### 5. What is a primary key and a foreign key?

A **primary key** is a column or a set of columns that uniquely identifies each row in a table. It cannot contain NULL values and there can be only one primary key per table.

A **foreign key** is a column or a set of columns that refers to the primary key of another table. It establishes a link between two tables, allowing data from one table to reference data in the associated table.

### 6. What is database normalization?

Database normalization is a process of organizing data in a database to reduce redundancy and dependency. It involves decomposing a table into smaller tables and defining relationships between them. The main goals are to:

1. Minimize data redundancy 
2. Eliminate insertion, update and deletion anomalies
3. Simplify queries

Some common normal forms are 1NF, 2NF, 3NF, BCNF, 4NF and 5NF.

### 7. What is a stored procedure and a trigger?

A **stored procedure** is a set of SQL statements with an assigned name that are stored in the database. They can take parameters, perform complex operations and return values. Stored procedures help encapsulate business logic and improve performance.

A **trigger** is a special type of stored procedure that automatically executes when a specific event occurs on a table, such as an insert, update or delete operation. Triggers are commonly used to maintain data integrity and enforce business rules.

### 8. How can database performance be monitored and improved?

Database performance can be monitored and improved using techniques like:

- Regular monitoring of key metrics like CPU usage, memory, disk I/O, query times
- Optimizing slow queries using execution plans, indexing, rewriting
- Creating and maintaining indexes on frequently used columns
- Configuring database parameters for specific workloads
- Upgrading hardware components like CPU, memory, storage
- Partitioning large tables to distribute data across disks
- Performing routine maintenance tasks like vacuuming, reindexing

### 9. What are the best practices for database backup and recovery?

Best practices for database backup and recovery include:

- Taking regular full and incremental backups 
- Testing backup and restore procedures
- Deploying redundant database servers and storage
- Establishing a disaster recovery site in a separate location
- Implementing automated monitoring and alerting
- Documenting disaster recovery procedures
- Conducting regular disaster recovery testing
- Ensuring compliance with regulatory requirements

### 10. How do you restore a database from a backup?

To restore a database from a backup:

1. Identify the most recent backup to restore
2. Prepare the environment with sufficient storage space
3. Stop any services or applications accessing the database 
4. Restore the database backup using the appropriate tools
5. Verify the integrity and completeness of the restored database
6. Restart services and applications once restore is complete

### 11. What is the difference between a clustered and a non-clustered index?

A **clustered index** determines the physical order of data in a table. There can be only one clustered index per table, as the data rows themselves are stored in this order. 

A **non-clustered index**, on the other hand, maintains a separate structure from the data rows. It contains pointers to the actual data, allowing for more than one non-clustered index per table. This type of index is useful for speeding up queries that do not require the data to be in a specific order.

### 12. What is ACID compliance in databases?

ACID stands for Atomicity, Consistency, Isolation, and Durability. These properties ensure reliable processing of database transactions:

- **Atomicity** ensures that all operations within a transaction are completed successfully; if not, the transaction is aborted.
  
- **Consistency** guarantees that a transaction will bring the database from one valid state to another, maintaining all predefined rules.
  
- **Isolation** ensures that transactions occur independently without interference, even if they are executed concurrently.
  
- **Durability** means that once a transaction is committed, it will remain so, even in the event of a system failure.

### 13. What is denormalization, and why is it used?

Denormalization is the process of intentionally introducing redundancy into a database by merging tables or adding redundant data. This is done to improve read performance and reduce the complexity of queries, particularly in scenarios where read operations are more frequent than write operations. While it can enhance performance, it may also lead to data anomalies and increased storage requirements.

### 14. Explain the concept of a view in a database.

A **view** is a virtual table that is based on the result of a SELECT query. It does not store data physically but provides a way to simplify complex queries, encapsulate logic, and present data in a specific format. Views can be used to restrict access to certain data or to aggregate data from multiple tables.

### 15. What is the purpose of a transaction log?

A **transaction log** is a file that records all transactions and modifications made to a database. It plays a crucial role in ensuring data integrity and recovery. In the event of a failure, the transaction log can be used to restore the database to its last consistent state by replaying or rolling back transactions.

### 16. What are the different types of relationships in databases?

In databases, there are three primary types of relationships:

1. **One-to-One**: Each record in one table corresponds to a single record in another table.
  
2. **One-to-Many**: A single record in one table can be associated with multiple records in another table.
  
3. **Many-to-Many**: Records in one table can be related to multiple records in another table, typically managed through a junction table.

### 17. What is a data warehouse?

A **data warehouse** is a centralized repository that stores large volumes of historical data from various sources. It is designed for query and analysis rather than transaction processing. Data warehouses support business intelligence activities, including reporting, data mining, and decision-making.

### 18. What is a schema in a database?

A **schema** is a logical structure that defines how data is organized in a database. It includes the definitions of tables, fields, relationships, views, indexes, and other elements. Schemas help to enforce data integrity and provide a blueprint for the database's structure.

### 19. What is the purpose of indexing in databases?

Indexing is a technique used to improve the speed of data retrieval operations on a database table. An index creates a data structure that allows for faster searches by providing a quick lookup mechanism. While indexes can significantly enhance performance, they also require additional storage space and can slow down write operations due to the need to maintain the index.

### 20. How do you ensure data integrity in a database?

Data integrity can be ensured through various methods, including:

- **Constraints**: Enforcing rules at the database level, such as primary keys, foreign keys, unique constraints, and check constraints.
  
- **Transactions**: Using ACID properties to ensure that operations are completed successfully and consistently.
  
- **Validation**: Implementing application-level validation to check data before it is entered into the database.

- **Regular Audits**: Conducting periodic checks to identify and rectify any data inconsistencies or errors.
## 11. What is the purpose of a transaction log in a database?

The transaction log records all transactions and modifications made to a database. It is crucial for ensuring data integrity and enabling recovery in case of failures. By replaying or rolling back transactions from the log, the database can be restored to its last consistent state.

Data integrity can be maintained through various methods:

- **Constraints**: Enforcing rules like primary keys, foreign keys, unique constraints, and check constraints at the database level.
- **Transactions**: Using ACID properties to ensure operations are completed successfully and consistently. 
- **Validation**: Implementing application-level validation to check data before inserting into the database.
- **Regular Audits**: Conducting periodic checks to identify and fix any data inconsistencies or errors.

## 21. What is the purpose of normalization in databases?

Normalization is the process of organizing data in a database to reduce redundancy and dependency. The main goals are:

1. Minimize data redundancy 
2. Eliminate insertion, update and deletion anomalies
3. Simplify queries

Some common normal forms are 1NF, 2NF, 3NF, BCNF, 4NF and 5NF.

A **clustered index** determines the physical order of data in a table. There can be only one clustered index per table, as the data rows themselves are stored in this order.

A **non-clustered index** maintains a separate structure from the data rows. It contains pointers to the actual data, allowing for more than one non-clustered index per table. This is useful for speeding up queries that do not require the data to be in a specific order.

## 22. What is the purpose of a view in a database?

A **view** is a virtual table based on the result of a SELECT query. It does not store data physically but provides a way to simplify complex queries, encapsulate logic, and present data in a specific format. Views can be used to restrict access to certain data or aggregate data from multiple tables.

## 23. What is the difference between a primary key and a foreign key?

A **primary key** is a column or set of columns that uniquely identifies each row in a table. It cannot contain NULL values and there can be only one primary key per table.

A **foreign key** is a column or set of columns that refers to the primary key of another table. It establishes a link between two tables, allowing data from one table to reference data in the associated table.

## 24. What is the purpose of ACID compliance in databases?

ACID stands for Atomicity, Consistency, Isolation, and Durability. These properties ensure reliable processing of database transactions:

- **Atomicity** ensures all operations in a transaction are completed successfully; if not, the transaction is aborted.
- **Consistency** guarantees a transaction will bring the database from one valid state to another, maintaining all predefined rules.
- **Isolation** ensures transactions occur independently without interference, even if executed concurrently.
- **Durability** means once a transaction is committed, it will remain so, even in the event of a system failure.

## 25. What is the purpose of a data warehouse?

A **data warehouse** is a centralized repository that stores large volumes of historical data from various sources. It is designed for query and analysis rather than transaction processing. Data warehouses support business intelligence activities like reporting, data mining, and decision-making.

The three primary types of relationships in databases are:

1. **One-to-One**: Each record in one table corresponds to a single record in another table.
2. **One-to-Many**: A single record in one table can be associated with multiple records in another table. 
3. **Many-to-Many**: Records in one table can be related to multiple records in another table, typically managed through a junction table.

## 26. How do you monitor and improve database performance?

Database performance can be monitored and improved using techniques like:

- Regular monitoring of metrics like CPU usage, memory, disk I/O, query times
- Optimizing slow queries using execution plans, indexing, rewriting
- Creating and maintaining indexes on frequently used columns
- Configuring database parameters for specific workloads
- Upgrading hardware components like CPU, memory, storage
- Partitioning large tables to distribute data across disks
- Performing routine maintenance tasks like vacuuming, reindexing


---


# MongoDB Coding Problems

### 1. Insert Multiple Documents into a Collection
**Problem:** Insert multiple documents into a collection named `students` with fields `name`, `age`, and `grade`.

**Solution:**
```javascript
db.students.insertMany([
  { name: "John", age: 18, grade: "A" },
  { name: "Jane", age: 19, grade: "B" },
  { name: "Alice", age: 17, grade: "A" }
]);
```

### 2. Find Documents with a Specific Field Value
**Problem:** Find all documents in the `products` collection where the `category` field is `"electronics"`.

**Solution:**
```javascript
db.products.find({ category: "electronics" });
```

### 3. Update a Document by Adding a New Field
**Problem:** Update a document in the `users` collection to add a new field `lastLogin` with the current date.

**Solution:**
```javascript
db.users.updateOne(
  { _id: 102 },
  { $set: { lastLogin: new Date() } }
);
```

### 4. Delete Documents Based on a Condition
**Problem:** Delete all documents from the `events` collection where the `eventDate` is in the past.

**Solution:**
```javascript
db.events.deleteMany({
  eventDate: { $lt: new Date() }
});
```

### 5. Increment a Numeric Field in a Document
**Problem:** Increment the `views` field by 10 for all documents in the `articles` collection where the `status` is `"published"`.

**Solution:**
```javascript
db.articles.updateMany(
  { status: "published" },
  { $inc: { views: 10 } }
);
```

### 6. Aggregate Data Using `$group` and `$sum`
**Problem:** Create an aggregation pipeline to calculate the total sales for each `productId` in the `sales` collection.

**Solution:**
```javascript
db.sales.aggregate([
  { $group: { _id: "$productId", totalSales: { $sum: "$quantity" } } }
]);
```

### 7. Find Documents with an Array Field Matching Criteria
**Problem:** Find all documents in the `books` collection where the `authors` array contains `"John Doe"`.

**Solution:**
```javascript
db.books.find({ authors: "John Doe" });
```

### 8. Project Specific Fields from Documents
**Problem:** Find all documents in the `employees` collection and return only the `name` and `salary` fields.

**Solution:**
```javascript
db.employees.find(
  {},
  { _id: 0, name: 1, salary: 1 }
);
```

### 9. Sort Documents by a Field
**Problem:** Retrieve all documents from the `orders` collection and sort them by the `orderDate` in ascending order.

**Solution:**
```javascript
db.orders.find().sort({ orderDate: 1 });
```

### 10. Use `$lookup` to Perform a Join
**Problem:** Join the `orders` collection with the `customers` collection using the `customerId` field and return the combined details.

**Solution:**
```javascript
db.orders.aggregate([
  {
    $lookup: {
      from: "customers",
      localField: "customerId",
      foreignField: "_id",
      as: "customerDetails"
    }
  }
]);
```

### 11. Create an Index on a Field
**Problem:** Create an index on the `username` field in the `accounts` collection to optimize query performance.

**Solution:**
```javascript
db.accounts.createIndex({ username: 1 });
```

### 12. Remove a Specific Field from All Documents
**Problem:** Remove the `temporary` field from all documents in the `sessions` collection.

**Solution:**
```javascript
db.sessions.updateMany(
  {},
  { $unset: { temporary: "" } }
);
```

### 13. Find Documents with a Range Condition
**Problem:** Find all documents in the `transactions` collection where the `amount` is between 200 and 1000.

**Solution:**
```javascript
db.transactions.find({
  amount: { $gte: 200, $lte: 1000 }
});
```

### 14. Count the Number of Documents Matching a Condition
**Problem:** Count the number of documents in the `users` collection where `isActive` is `true`.

**Solution:**
```javascript
db.users.countDocuments({ isActive: true });
```

### 15. Use `$unwind` to Flatten an Array Field
**Problem:** Write an aggregation query to unwind the `tags` array in the `posts` collection and list each tag with its associated post.

**Solution:**
```javascript
db.posts.aggregate([
  { $unwind: "$tags" },
  { $group: { _id: "$tags", posts: { $push: "$$ROOT" } } }
]);
```

# Javascript Coding Problems
| # | Question                                                                                                                                                                                                                                | Difficulty |
|---|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| 1 | [Write a function in JavaScript to remove duplicate elements from an array.](https://github.com/lakshaykamat/sde-notes/blob/main/Career%20Preparation/javascript-questions/easy/removeDuplicates.js)                                    | Easy       |
| 2 | [Write a JavaScript function that takes an array of numbers and returns a new array with only the even numbers.](https://github.com/lakshaykamat/sde-notes/blob/main/Career%20Preparation/javascript-questions/easy/sortEvenNumbers.js) | Easy       |
| 3 | [Write a JavaScript function to check if a given string is a palindrome (reads the same forwards and backwards).](https://github.com/lakshaykamat/sde-notes/blob/main/Career%20Preparation/javascript-questions/easy/palindrome.js)     | Easy       |
| 4 | [Write a JavaScript program to find the maximum number in an array.](https://github.com/lakshaykamat/sde-notes/blob/main/Career%20Preparation/javascript-questions/easy/maxNumber.js)                                                   | Easy       |
| 5 | [Write a JavaScript function to check if a given number is prime.](https://github.com/lakshaykamat/sde-notes/blob/main/Career%20Preparation/javascript-questions/easy/isPrimeNumber.js)                                                 | Easy       |
| 6 | [Write a JavaScript function to print the Fibonacci series up to the nth number.](https://github.com/lakshaykamat/sde-notes/blob/main/Career%20Preparation/javascript-questions/easy/fibonacci.js)                                      | Easy       |
| 7 | [Write a JavaScript program to calculate the factorial of a given number.](https://github.com/lakshaykamat/sde-notes/blob/main/Career%20Preparation/javascript-questions/easy/factorial.js)                                             | Easy       |

## 🌟 Highlights

- **Up-to-Date Content**: Regular updates with the latest best practices, tools, and technologies.
- **Structured Learning**: Organized notes and resources to guide you through different levels of complexity.
- **Project-Based Learning**: Apply your knowledge with hands-on projects and challenges.

---

## 🚀 Getting Started

To get the most out of these notes:

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/lakshaykamat/sde-notes.git
   ```
2. **Explore a Section**:  
   ```bash
   cd sde-notes/Development
   ```
3. **Start Learning**:  
   Dive into the markdown files and expand your expertise!

---

## 🎯 Contributing

Your contributions are valuable! If you find any errors, have suggestions, or want to add new content, feel free to open an issue or submit a pull request. Check out the [contribution guidelines](https://github.com/lakshaykamat/sde-notes/blob/main/CONTRIBUTING.md) for more details.

---

## 📬 Contact

Have questions or feedback? Reach out via [email](mailto:lakshaykamat.dev@gmail.com) or open an issue.

---

Happy Learning! 🚀