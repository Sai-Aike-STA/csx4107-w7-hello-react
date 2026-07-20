Following the instructions

1.  Install React

    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr>
    <td><br />
    npm create vite@latest react-route-example --template react<br />
    </td>
    </tr>
    </tbody>
    </table>

2.  Answer:

    1.  React
    2.  Javascript
    3.  ESLint
    4.  No

3.  Change to "react-route-example" directory.

4.  Run npm install

    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr>
    <td><br />
    npm install<br />
    </td>
    </tr>
    </tbody>
    </table>

5.  Install react-router-dom with npm

    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr>
    <td><br />
    npm install react-router-dom<br />
    </td>
    </tr>
    </tbody>
    </table>

6.  Start VSCode in this directory

7.  Create a new file under "src" directory named "About.jsx" with the
    following content.

    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr>
    <td><br />
    &#10;<p>function About () {</p>
    <p>  return (</p>
    <p>   </p>
    <div>
    <p>     </p>
    <h1 id="about-page">About Page</h1>
    <p>   </p>
    </div>
    <p>  )</p>
    <p>}</p>
    <p>export default About</p></td>
    </tr>
    </tbody>
    </table>

8.  Create a new file under "src" directory named "Register.jsx" with
    the following content.

    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr>
    <td><br />
    &#10;<p>function Register () {</p>
    <p>  return (</p>
    <p>   </p>
    <div>
    <p>     </p>
    <h1 id="registration-page">Registration Page</h1>
    <p>   </p>
    </div>
    <p>  )</p>
    <p>}</p>
    <p>export default Register</p></td>
    </tr>
    </tbody>
    </table>

9.  Create a new file under "src" directory named "Home.jsx" with the
    following content.

    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr>
    <td><br />
    &#10;<p>function Home() {</p>
    <p>  return (</p>
    <p>   </p>
    <div>
    <p>     </p>
    <h1 id="home-page">Home Page</h1>
    <p>   </p>
    </div>
    <p>  )</p>
    <p>}</p>
    <p>export default Home</p></td>
    </tr>
    </tbody>
    </table>

10. Delete content in App.css

11. Replace the content in App.jsx with the following

    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr>
    <td><br />
    &#10;<p>import { HashRouter, Routes, Route } from "react-router-dom";</p>
    <p>import Home from './Home';</p>
    <p>import Register from './Register';</p>
    <p>import About from './About';</p>
    <p>function App () {</p>
    <p>  return(</p>
    <p>   </p>
    <p>     </p>
    <p>        }/&gt;</p>
    <p>        }/&gt;</p>
    <p>        }/&gt;</p>
    <p>     </p>
    <p>   </p>
    <p>  )</p>
    <p>}</p>
    <p>export default App</p>
    <br />
    </td>
    </tr>
    </tbody>
    </table>

12. Start React in dev mode, run the following command within the React
    directory.

    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <tbody>
    <tr>
    <td><br />
    npm run dev<br />
    </td>
    </tr>
    </tbody>
    </table>

13. Observe the result for path:

    1.  "/"
    2.  "/#/about"
    3.  "/#/register"

14. Build the static with npm build or pnpm build

15. Create a new repository on your Github

16. Push files and directories inside "dist" directory to the repository

17. Deploy the repository.

18. Observe the result.
