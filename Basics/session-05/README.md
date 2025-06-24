## 7. What is React and why use it?

### What is React?

React is a popular JavaScript library for building user interfaces, especially single-page applications. It allows you to create reusable UI components and efficiently update the UI when data changes.

### Why Use React?

- **Component-Based**: Build encapsulated components that manage their own state.
- **Declarative**: Describe what you want to see, and React updates the UI efficiently.
- **Virtual DOM**: React uses a virtual DOM to optimize rendering and improve performance.
- **Strong Community**: Large ecosystem and community support.

### Example

```javascript
import React from "react";

function Welcome(props) {
  return <h1>Hello, {props.name}!</h1>;
}

// Usage in a React app
// <Welcome name="Alice" />
```

React makes it easy to build interactive and dynamic web applications by breaking the UI into small, manageable pieces.

1. [React Documentation](https://react.dev/learn)
2. [Next.js Documentation](https://nextjs.org/docs)
