# Basic Hello World Example : 
## React.createClass: 
----
Using React's createClass method we create React components which have embedded state. A component implements a render method which returns one single child. That child may have an arbitrarily deep child structure. 

In this Example we created a single React component which is HelloElem. 
### render : 
In render method of HelloElem we are returning a native React DOM element.
```
<div id="hello-elem"> Hello from geeky {this.state.name} </div>
```
This child element returned by render function can be either a virtual representation of a native DOM component (such as <div /> or React.DOM.div()) or another composite component that you've defined yourself.
### getInitialState : 
Invoked once before the component is rendered. The return value will be used as the initial value of this.state.
```
return {name : 'Sumit'};
```

### state : 
this.state is an object that is used to store private data of a component,
use
```
this.state.{name of a property} 
```
to get state values.