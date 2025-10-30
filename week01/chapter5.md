# Chapter 5: Building UI with Components

## 🧱 What Are Components?

Components are the **building blocks of React applications**. They allow developers to create **self-contained, reusable snippets of UI**—like LEGO bricks that can be assembled into larger structures.

### Benefits:
- Modular and maintainable code
- Easier updates and debugging
- Reusability across different parts of the app

---

## 🧠 Creating a Component

In React, a component is simply a **JavaScript function** that returns JSX.

```jsx
function Header() {
  return <h1>Develop. Preview. Ship.</h1>;
}
