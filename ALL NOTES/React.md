# Learning Resources
- [5 free React courses thread](https://twitter.com/akoskm/status/1470341456921518085)

# Study Notes from Udemy React Guide
## Section 2: React Basics & Working With Components
- Index.js is the first file to execute
- React and React Dom are part of the same library, despite being separate dependencies 
- ReactDOM.createRoot defines the main entry point
- `<div id="root">` corresponds to this in index.html (this can be different but this is the common way to do it)
- Omit ".js" from JavaScript imports in React. include extension for other file types like .css
- `App.js` is the "router" , or the root of the component tree
- A component in react is just a javascript function
- Only one root element allowed per component. 
- {props.children} in a function definition, between the tags of a component, will let you access the content of child components
- `Import React from "react"` is no longer necessary, but once was
