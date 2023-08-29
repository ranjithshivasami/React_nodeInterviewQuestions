# FullStack Inteview questions


##  HTML

<details>
<summary><strong>Purpose of Doctype in HTML</strong></summary>
<p>

The <!DOCTYPE> declaration specifies the document type and version of HTML being used. It helps web browsers understand how to interpret and render the HTML code. It ensures that the browser uses the correct rendering mode and follows the appropriate standards.

</p>
</details>

<details>
<summary><strong>Difference between div and span elements</strong></summary>
<p>

The `<div>` element is a block-level container used to group and style elements together, often for layout purposes. The `<span>` element, on the other hand, is an inline container used to apply styles or manipulate small portions of text or content without affecting the overall layout.

</p>
</details>

<details>
<summary><strong>Purpose of the noscript tag in HTML</strong></summary>
<p>

The `<noscript>` tag is used to provide content that should be displayed when JavaScript is disabled or not supported in the browser. It's commonly used to show alternative content or instructions for users who have disabled JavaScript.

</p>
</details>

## CSS

<details>
<summary><strong>What are the possible ways to apply CSS styles to a web page?
</strong></summary>
<p>

Inline, intenal, extenal

</p>
</details>

<details>
<summary><strong>What are the css selectors?</strong></summary>
<p>
CSS selectors are patterns that define which elements on a web page should be targeted and styled. They include tag selectors, class selectors, ID selectors, attribute selectors, and more.
</p>
</details>

##   JavaScript

<details>
<summary><strong>What are Promises and how do they help manage asynchronous operations?</strong></summary>
<p>
 Promises are a way to handle asynchronous operations in JavaScript. They represent a value that might be available now, or in the future, or never. Promises help avoid callback hell and make async code more readable and manageable.
</p>
</details>

<details>
<summary><strong>What is the Event Loop in JavaScript?</strong></summary>
<p>
The Event Loop is a core concept in JavaScript's concurrency model. It's responsible for managing the execution of code by placing functions in a queue and executing them in a loop, ensuring non-blocking behavior.
</p>
</details>

<details>
<summary><strong>How does JavaScript handle asynchronous errors?</strong></summary>
<p>
Asynchronous errors in JavaScript can be caught using try-catch blocks around asynchronous code or by attaching error callbacks using .catch() on Promises.
</p>
</details>


<details>
<summary><strong>Explain the concept of debouncing and throttling in JavaScript.</strong></summary>
<p>
Debouncing and throttling are techniques used to control the rate at which a function is executed. Debouncing delays the execution until the input has ceased for a specified time, while throttling limits the rate of execution to a fixed interval.
</p>
</details>

<details>
<summary><strong>Explain the concept of the "event delegation" pattern?</strong></summary>
<p>
Event delegation is a technique where you attach a single event listener to a common ancestor element of multiple elements you're interested in. This allows you to handle events efficiently for dynamically created elements without attaching listeners to each element.
</p>
</details>


<details>
<summary><strong>Explain the difference between call, apply, and bind methods.
?</strong></summary>
<p>
All three methods are used to set the this value in a function. call and apply immediately invoke the function, while bind returns a new function with the specified this context.
</p>
</details>


<details>
<summary><strong>How can you create a private variable in JavaScript?</strong></summary>
<p>
In JavaScript, you can create private variables using closures or by leveraging ES6 features like WeakMaps. Closures encapsulate private variables within a function's scope.
</p>
</details>



<details>
<summary><strong>How does JavaScript handle asynchronous code in a single-threaded environment?</strong></summary>
<p>
JavaScript uses an event loop to manage asynchronous code execution. It keeps track of pending operations and processes them in a non-blocking manner, ensuring that the main thread is not blocked by long-running tasks.
</p>
</details>

<details>
<summary><strong>How can you improve the performance of a website's JavaScript code?</strong></summary>
<p>
Performance improvements can be achieved by minimizing DOM manipulation, using efficient algorithms and data structures, optimizing loops, reducing network requests, and employing tools like minification and bundling.
</p>
</details>

<details>
<summary><strong> How can you prevent or handle memory leaks in JavaScript?</strong></summary>
<p>
To prevent memory leaks, make sure to clean up event listeners, clear timeouts and intervals, avoid circular references, and use tools like the Chrome DevTools memory profiler to identify potential issues.
</p>
</details>

##   React Js
<details>
<summary><strong>Explain the differences between controlled components and uncontrolled components?</strong></summary>
<p>
Controlled components have their state managed by React, while uncontrolled components manage their state via the DOM. Controlled components provide more control and are typically recommended for most use cases.
</p>
</details>


<details>
<summary><strong>What are the css selectors?</strong></summary>
<p>
CSS selectors are patterns that define which elements on a web page should be targeted and styled. They include tag selectors, class selectors, ID selectors, attribute selectors, and more.
</p>
</details>

<details>
<summary><strong>Explain the concept of error boundaries in React.</strong></summary>
<p>
Error boundaries are React components that catch JavaScript errors in their child component tree and display fallback UI instead of crashing the entire application. They help to isolate and handle errors gracefully.
</p>
</details>

<details>
<summary><strong>Explain the differences between useState and useReducer.</strong></summary>
<p>
Both useState and useReducer are used to manage state in functional components, but useReducer is more suitable for complex state updates and business logic, while useState is simpler for basic state updates.
</p>
</details>

<details>
<summary><strong>How can you handle authentication and authorization in a React application?</strong></summary>
<p>
Authentication can be handled using JSON Web Tokens (JWT), OAuth, or other authentication mechanisms. Authorization can be controlled by using conditional rendering based on the user's role or permissions.
</p>
</details>
<details>
<summary><strong>Explain the concept of React portals?</strong></summary>
<p>
Portals allow you to render children outside of their parent DOM hierarchy. This is useful for scenarios like modals or tooltips where you want to render content in a different part of the DOM.
</p>
</details>

<details>
<summary><strong>How does React's reconciliation algorithm work?</strong></summary>
<p>
React's reconciliation algorithm compares the Virtual DOM representation of the current state with the previous state and computes the minimal set of changes needed to update the actual DOM.
</p>
</details>
<details>
<summary><strong>How can you handle side effects </strong></summary>
<p>
React's reconciliation algorithm compares the Virtual DOM representation of the current state with the previous state and computes the minimal set of changes needed to update the actual DOM.
</p>
</details>
<details>
<summary><strong>What are React hooks rules and why are they important?</strong></summary>
<p>
React hooks come with certain rules, such as using hooks at the top level of a functional component and not within loops, conditions, or nested functions. Adhering to these rules ensures that hooks work correctly and consistently.

These additional questions cover various advanced ReactJS topics, giving you a comprehensive set of concepts to prepare for in your interview. Make sure to understand not only the answers but also the underlying principles and best practices.
</p>
</details>

<details>
<summary><strong>List some of the cases when you should use Refs.
</strong></summary>
<p>
Following are the cases when refs should be used:

When you need to manage focus, select text or media playback
To trigger imperative animations
Integrate with third-party DOM libraries
</p>
</details>

<details>
<summary><strong>List down the components of Redux
</strong></summary>
<p>
Redux is composed of the following components:

Action – It’s an object that describes what happened.
Reducer –  It is a place to determine how the state will change.
Store – State/ Object tree of the entire application is saved in the Store.
View – Simply displays the data provided by the Store.
In case you are facing any challenges with these React interview questions, please comment on your problems in the section below.
</p>
</details>
<details>
<summary><strong>What are the different ways to pass data between components in React?
</strong></summary>
<p>
Data is passed as a property on the element when utilising props to communicate between components. For instance, you can do the following to send a user object from a parent component to a child component: The props object, props.user, can then be used in the child component to access the data. Data can be passed via the component tree using context rather than having to go through each level of the tree. You must establish a context object containing a Provider and a Consumer in order to use context.

The components that require the data are served by the Provider, and the components that need to access the data are served by the Consumer. Data that is local to a component can be stored in a state, which allows for the tracking of data across time. Through the useState Hook, state in a component can be obtained. The current state value and a function to update the state value are the two items of an array that the useState Hook returns after receiving an initial value.
</p>
</details>
<details>
<summary><strong>How do you handle performance optimization in a React application?

</strong></summary>
<p>
There are several ways to optimize the performance of a React application, including:

Using the shouldComponentUpdate lifecycle method to prevent unnecessary re-renders of components.
Using React’s built-in PureComponent or implementing a custom shouldComponentUpdate method to optimize performance for functional components.
Using the React developer tools to profile the application and identify performance bottlenecks.
Using the React.memo method for functional components
Using React’s Context API instead of props drilling.
Using the useEffect hook to handle side effects in functional components.
Using the useCallback and useMemo hooks to prevent unnecessary re-renders and improve performance.
Lazy loading of components and code splitting.
Minimizing the number of DOM updates by using the key prop when rendering a list of items.
Using the useReducer hook to manage state updates instead of useState
Using a virtualized list library like react-virtualized, react-window etc.
It’s always a good idea to test performance with real-world use cases and user interactions before and after making any optimization.

</p>
</details>

## Node Js


<details>
<summary><strong>What is the blocking code?
</strong></summary>
<p>
Blocking code is code that cannot be executed until the current code is completely executed.
</p>
</details>
<details>


## REST API

What is the concept of statelessness in REST?


<details>
<summary><strong>What is the concept of statelessness in REST?
</strong></summary>
<p>
The REST architecture is called stateless as it does not store any state related to the client session on the server. Essentially session states are entirely kept on the client side. This is effectively called Statelessness.

It ensures that the server cannot take undue advantage of any stored data. However, since no data is stored, each request from the client to the server must contain all the necessary information about the request.
</p>
</details>
<details>