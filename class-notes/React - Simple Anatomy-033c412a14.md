If you list files and directories from the root project, they are as
shown below:

## 1. node_modules/

This folder contains all the installed packages (dependencies) your
project needs.

- Each library React uses (like React itself, Vite plugins, etc.) is
  stored here.
- Automatically generated — you should never edit this manually.
- Can be safely deleted and rebuilt using pnpm install.

Analogy: This is the "library storage" that pnpm fills when you install
dependencies.

## 2. public/

This folder stores static files that do not change.

Common files inside:

- images
- icons
- favicon
- static assets you want to serve directly

These files do not go through Vite’s build process.

## 3. src/

This is the main source code of your React app.

It typically includes:

- main.jsx → application entry point
- App.jsx → main React component
- custom components you create
- CSS files
- logic files (JS/TS)

## 4. .gitignore

Defines which files/folders should NOT be tracked by Git.

Common examples ignored:

- node_modules/
- .env
- build outputs

This prevents large or sensitive files from being pushed to GitHub.

## 5. eslint.config.js

ESLint configuration file.

- ESLint helps detect mistakes in your JavaScript code.
- Ensures consistency and better code style.

Students don't have to touch this unless they learn linting later.

## 6. index.html

The single HTML page used in your React application (SPA).

Important features:

- Contains a
  <div id="root">

  </div>

  where React is injected
- Scripts are handled by Vite
- You rarely modify this file, except for titles or metadata

React apps only have one HTML file; React changes the content
dynamically.

## 7. package.json

This is the project’s configuration and dependency list.

It contains:

- project name
- version
- scripts (pnpm dev, pnpm build, etc.)
- dependencies (React, Vite)
- devDependencies (tools for development)

You will reference this file often.

## 8. pnpm-lock.yaml

A lock file created by pnpm.

Its purpose:

- Locks exact versions of dependencies
- Ensures all team members use the same versions
- Auto-generated — do NOT edit manually

This file ensures consistent builds.

## 9. README.md

A markdown file containing basic information about the project.

Usually includes:

- how to run the project
- how to build the project
- notes for maintainers

Good practice: update it for your teammates or future you.

## 10. vite.config.js

Vite's configuration file.

It defines:

- plugins
- build settings
- development server options

The default is enough for beginners.

Students will modify this only when learning advanced topics (e.g.,
aliases, plugins).

## Summary

- src/ → Your React code
- public/ → Static files
- node_modules/ → Installed libraries
- index.html → Main page (SPA)
- package.json → Project settings + dependency list
- pnpm-lock.yaml → Exact versions lock
- vite.config.js → Vite settings
- eslint.config.js → Code linting rules
- .gitignore → Files Git should ignore
