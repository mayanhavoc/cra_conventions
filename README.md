# CRA conventions

## Good style

- Each react component goes in a **separate** file.
- The name of your file should **always** match the name of the component in that file. 

For example: 
`src/Car.js` for **Car** component.
`src/House.js` for **House** component.

Capitalized is the convention as well. 

- All components should **extend** `Component` (imported from React)
- Each component should be exported as the default object from its given file. 

```Javascript
import React, {Component} from 'react';
```

```Javascript
class App extends Component {...
```

```Javascript
export default App;
```

- Top level component should **always** be `App` in `App.js` (it's possible to tweak it), but the skeleton assumes it's called `App`.

# Topics to cover next week

Functional components
Class based components
Styling components
JSX





