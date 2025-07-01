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

1. **Setting up the dev environment with Create Next App**

   - Introduction to Create Next App
   - Installing Node.js and npm
   - Creating a new Next.js project

2. **Next.js Project Structure**

   - Overview of the project files and folders
   - Understanding the purpose of each file
     - package.json
     - package-lock.json

3. **Node.js Runtime and Node Package Manager (npm)**

   - Overview of Node.js and its role in development
   - Introduction to npm and its functionalities

4. **Dependencies vs DevDependencies**

   - Explanation of dependencies and devDependencies
     - React.js `v19` and it's huge community
       - `Facebook Meta Company` & `Jordan Walke` - Software engineer and creator of `F-Bolt` later renamed to `FaxJS` component library for PHP
       - First deployment is `Facebook News Feed` in `2011` and the integrated to `Instagram` in `2012`
       - `Dan Abramov` - core contributor of React and the creator of `Redux` | `React Hot Loader` **(React Transform)**
     - Next.js `v15.2` and it's evolution
   - How to manage theme in a Next.js project

5. **NPM Commands**

   - Common npm commands (e.g., `npm install`, `npm run dev`, `npm run build`)
   - Practical examples and usage

6. **Running the project on Local Dev Server**

   - Starting the development server
   - Accessing the project in the browser
   - Troubleshooting common issues

7. [React Documentation](https://react.dev/learn)
8. [Next.js Documentation](https://nextjs.org/docs)
