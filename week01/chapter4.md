# Chapter 4: Getting Started with React

## 🚀 Setting Up React in a Project

To use React in a basic HTML project, you need to load two scripts from [unpkg.com](https://unpkg.com):
- `react`: Core React library
- `react-dom`: DOM-specific methods for rendering React components

### 🧱 Initial Setup (Imperative JavaScript)
```html
<script type="text/javascript">
  const app = document.getElementById('app');
  const header = document.createElement('h1');
  const text = 'Develop. Preview. Ship.';
  const headerContent = document.createTextNode(text);
  header.appendChild(headerContent);
  app.appendChild(header);
</script>
