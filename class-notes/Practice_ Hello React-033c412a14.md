Instruction:

- Create a new React + Vite project

  pnpm create vite@latest hello-react --template react

- Quite pnpm or open new teminal

- Modify index.css, remove everything and apply this CSS:

  body {

    margin: 0;

    background-color: lightgrey;

    display: flex;

    justify-content: center;

    align-items: center;

    min-height: 100vh;

  }

- Modify App.css, remove everything and apply this CSS:

  .card {

    margin-top: 10px;

    background-color: white;

    width: 200px;

    min-height: 200px;

    border-radius: 8px;

    display: flex;

    justify-content: center;

    align-items: center;

  }

Modify App.jsx, modify the file to look like this:

import { useState } from 'react'

import reactLogo from './assets/react.svg'

import viteLogo from '/vite.svg'

import './App.css'

function App() {

  return (

    \<\>

<div data-classname="card">

        Hello React

</div>

    \</\>

  )

}

export default App

Run the pnpm as (of if you not stop it, do nothing)

pnpm start dev

Open the URL on browser

Expected Result:
