A React component is just a JavaScript function that returns JSX — and
JSX is what React shows on the browser.

Whatever you put inside the return() is what gets rendered.

The return must contain one root element (like

<div>

or a fragment \<\>...\</\>).

Finally, you must export the component so React can use it.

Example:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr>
<td><p>function App() {</p>
<p>return (</p>
<p>&lt;&gt;</p>
<h1 id="hello-react">Hello, React!</h1>
<p>This content is rendered on the browser.</p>
<p>&lt;/&gt;</p>
<p>);</p>
<p>}</p></td>
</tr>
</tbody>
</table>

export default App;

What this component does

- function App() { ... } → defines a React component
- return ( ... ) → React renders everything inside this block
- \<\>...\</\> → one root element (React Fragment)
- export default App; → allows React to import and display this
  component

Do not return like this:

return (

# Hello, React!

This content is rendered on the browser.

);

</div>
