Component is one of React fundamental building blocks, representing a
self-contained, reusable piece of the UI. A component is an
encapsulation of logic and appearance. A Component must return JSX data.

Example:

// src/components/Greetings.jsx

import "../App.css"

function Greetings() {

  return (

<div>

# Hello, React!

This content is rendered on the browser.

</div>

  );

}

export default Greetings;

// src/App.jsx

import './App.css'

import Greetings from './components/Greetings'

import User from './components/User'

function App() {

  return (

<div data-classname="card">

</div>

  )

}

export default App

In this example, there is a component named "Greetings" defined in a
file named Greetings.jsx located in "src/components" folder.
Technically, you can locate the file anywhere but for best practice, it
is recommended to locate the components in the components folder.

After you create a component, then you can use it anywhere. In this
example, App.jsx call to Greetings component and the result is as shown
below:

A component my consists of none to any number of "prop". The prop is a
data parses down from parent to child. For example, this Greeting
component request one prop, message:

// src/components/Greetings.jsx

import "../App.css"

function Greetings({message}) {

  return (

<div>

# Hello, React!

{message}

</div>

  );

}

export default Greetings;

Then, when using Greetings component, a prop can be assigned to the
component, for example:

// src/App.jsx

import './App.css'

import Greetings from './components/Greetings'

function App() {

  return (

<div data-classname="card">

</div>

  )

}

export default App
