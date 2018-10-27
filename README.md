## TODO
 **Add Supense and Lazy**

# What are hooks?

Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don’t work inside classes — they let you use React without classes.  

```js
import { useState } from 'react';

function Button() {
  // Declare a new state variable, which we'll call "count"
  const [clickCount, setCount] = useState(0);

  return (
    <div>
      <p>You clicked {clickCount} times</p>
      <button onClick={() => setCount(clickCount + 1)}>
        Click me
      </button>
    </div>
  );
}
```  

Read more about React Hooks on the official documentation [here](https://reactjs.org/docs/hooks-overview.html)

This repo will host my future projects written using React Hooks..  
