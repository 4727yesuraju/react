# 📚 Framework vs Library

## 📖 Simple Concept Explanation

Both **Framework** and **Library** help developers write code faster.

The main difference is **who controls the application**.

### 📦 Library

A **Library** is a collection of reusable code.

👉 **You are in control.**

You decide:
- When to use it.
- Which function to call.
- Which part of the library to use.

The library **does not control your application**.

> **Simple Definition:**
>
> A library is a collection of reusable code that **you call whenever you need it**.

---

### 🏗️ Framework

A **Framework** provides a complete structure for building an application.

👉 **The framework is in control.**

It decides:
- Project structure
- Folder organization
- Application flow
- When your code runs

You write your code by following the framework's rules.

> **Simple Definition:**
>
> A framework provides a structure for your application and **calls your code when needed**.

---

## 🤔 Why It's Needed

### Why do we need a Library?

Without a library:
- Write everything from scratch.
- More code.
- More time.

A library saves time by providing ready-made functions.

Examples:
- React (UI)
- Lodash (Utility functions)
- Axios (HTTP requests)

---

### Why do we need a Framework?

Without a framework:
- Every developer creates a different project structure.
- Hard to manage large applications.
- No standard way to build apps.

A framework provides:
- Standard folder structure
- Built-in features
- Better organization
- Easier teamwork

Examples:
- Angular
- Next.js
- NestJS
- Django

---

## 🌍 Real-World Example

### 📚 Library Example

Imagine you own a kitchen.

You buy a **Mixer Grinder**.

You use it only when needed.

You decide:
- When to switch it on.
- What to grind.
- How long to use it.

The mixer never tells you what to cook.

👉 That's a **Library**.

---

### 🏗️ Framework Example

Imagine working in a restaurant.

The restaurant already has:
- Kitchen
- Rules
- Recipes
- Staff
- Work process

You simply follow the system.

The restaurant decides:
- What to cook
- When to cook
- How work is organized

👉 That's a **Framework**.

---

## 🧠 Interview Explanation

> A library is a collection of reusable code that developers call whenever they need specific functionality, so the developer controls the application's flow. A framework, on the other hand, provides a complete structure for building an application and controls the application's flow by calling the developer's code. In simple terms, with a library you are in control, while with a framework the framework is in control.

---

## ✍️ Syntax

### Library (React)

```jsx
import { useState } from "react";

function App() {
  const [count, setCount] = useState(0);

  return <h1>{count}</h1>;
}
```

Here, **you call** `useState()`.

---

### Framework (Next.js)

```jsx
export default function Home() {
  return <h1>Home Page</h1>;
}
```

Next.js automatically finds this file and shows it as the home page.

You don't manually call this page.

---

## 💻 Example Queries

### Example 1 (Library)

```javascript
import axios from "axios";

axios.get("/users");
```

You decide when to call `axios.get()`.

---

### Example 2 (Library)

```javascript
import _ from "lodash";

_.capitalize("react");
```

You decide when to use Lodash.

---

### Example 3 (Framework)

```text
pages/
 ├── index.jsx
 ├── about.jsx
```

Next.js automatically creates routes:

```
/        → index.jsx
/about   → about.jsx
```

The framework handles the routing.

---

## ❓ Common Interview Questions

- What is a library?
- What is a framework?
- What is the difference between a library and a framework?
- Why is React called a library?
- Is Angular a library or a framework?
- Is Next.js a framework?
- What is Inversion of Control (IoC)?
- Give real-world examples of libraries and frameworks.

---

## 📝 Practice Exercises

- Identify whether these are libraries or frameworks:
  - React
  - Angular
  - Next.js
  - Express.js
  - Lodash
  - Axios

- Explain the difference between a library and a framework in your own words.

- Build a small React app and notice that **you decide** when to use React features.

- Build a Next.js app and notice that **Next.js decides** routing and project structure.

---

## ⚠️ Common Mistakes

- ❌ Thinking React is a framework.
- ❌ Thinking all frameworks are libraries.
- ❌ Believing there is no difference between them.
- ❌ Forgetting that the main difference is **who controls the application**.
- ❌ Assuming frameworks cannot use libraries (they often do).

---

## 🔁 Revision Summary

- ✅ A **Library** is reusable code that **you call**.
- ✅ A **Framework** provides a complete structure and **calls your code**.
- ✅ **Library = You are in control.**
- ✅ **Framework = Framework is in control.**
- ✅ React is a **Library**.
- ✅ Angular, Next.js, NestJS, and Django are **Frameworks**.
- ✅ The key difference is **Control (Inversion of Control)**.