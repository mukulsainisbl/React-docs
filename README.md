# React-docs
React => React is a free and open-source front-end JavaScript library for building user interfaces based on components.


Who made React => React was created by Jordan Walke A  software engineer at Meta


What is Babel => Babel in react operates as a transpiler, converting the latest JavaScript syntax into a version that can run in all environments


How does Babel convert html code in React into valid code=> Babel is a key tool that can translate JSX syntax, which is used to create HTML-like code in React components, into valid JavaScript code that can be executed in preferred browsers


What is ReactDOM used for? Write an example => ReactDOM is a package in React that provides DOM-specific methods that can be used at the top level of a web app to enable an efficient way of managing DOM elements of the web page. ReactDOM provides the developers with an API containing the various methods to manipulate DOM.
 1- Render


How do you add react to a web application => 
const domContainer = document.querySelector('#like_button_container');
const root = ReactDOM.createRoot(domContainer);
root.render(e(LikeButton));


What is React.createElement => React.createElement is a fundamental method of React JS. The main use of React.createElement is the Creation of a React component. It is the JavaScript format for creating react components. Also, the JSX react component when transpired invokes this only method for creating the componen


What are the three properties that createElement accept => type , props , and children


What is the meaning of render and root =>  root. render() is used to render a React component into the DOM. It is typically used only once, in the entry point of your application