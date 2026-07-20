To create a React project with Vite, we use npm to run the command as
follow:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr>
<td><br />
npm create vite@latest --template react<br />
</td>
</tr>
</tbody>
</table>

This command will create a new directory named as with latest version of
Vite.

Install dependencies

When you create a Node.js project with npm, it automatically generates a
file called package.json.

This file contains:

- the project information
- a list of dependencies (libraries your project needs)
- a list of scripts you can run

However, only the list of libraries is created, not the actual libraries
themselves. So at this stage, your project knows what libraries it
needs, but the libraries are not downloaded yet.

To install the dependencies, perform the following:

1.  Change directory to the project directory

2.  Run:

    npm install

    The npm will check your Node version and attempt to install most
    compatible dependencies.

    However, it is possible that some dependencies may not compatible
    with other dependencies or the current Node JS and the installation
    will fail.

Walkthrough:

Here an example (screen capture) when you create a new React + Vite with
pnpm

Then the pnpm will start up the Vite immediately:

At this point, you can browse to "<http://localhost:5173/>" to see the
output of your initial project.

You may try to click the count button to update the count!!

This is the initial code it provided as a simple example.

To stop the server, type "q" and then enter

Alternatively, you can create project without installation and running
the React by selecting "no" when it ask to "install with pnpm and start
now?", as shown below:
