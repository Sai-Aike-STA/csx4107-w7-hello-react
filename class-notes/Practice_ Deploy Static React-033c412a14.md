You cannot use your React project running as your web application
directly.

You have to build it into a static web application first and use the
output as your repository content instead.

This classwork will demonstrate you how to build and create a static
React + Vite application running on GitHub as a free service.

Instructions:

- Complete the React Component classwork.

- Consider your repository name, for example, "react-component".

- Appending "vite.config.js" so it looks like:

  export default defineConfig({

    plugins: \[react()\],

    base: '/react-counter/',

  })

- Build the project with

  pnpm build

- Ensure there is a "dist" directory created

- Create repository named as you set in the Vite, Public without Readme.

- Come back to your project on local machine.

- Ensure that you are inside your project, then:

  cd dist

  git init

  git add .

  git commit -m ""

  git branch -M main

  git remote add origin

  git push -u origin main

- Goto GitHub and deploy our page as we have done so far.
