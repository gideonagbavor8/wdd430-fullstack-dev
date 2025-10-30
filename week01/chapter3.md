# Chapter 3: Updating UI with JavaScript

## 🧱 Building UI with Plain JavaScript

In this chapter, we learned how to use **JavaScript and DOM methods** to dynamically update the user interface. The example involved creating an `<h1>` element and inserting it into a `<div>` using JavaScript.

### Key Steps:
1. Create an `index.html` file with a `<div id="app"></div>`.
2. Use a `<script>` tag to write JavaScript directly in the HTML.
3. Use `document.getElementById()` to select the div.
4. Create an `<h1>` element using `document.createElement("h1")`.
5. Create a text node and append it to the `<h1>`.
6. Append the `<h1>` to the `div`.

```html
<script type="text/javascript">
  const app = document.getElementById('app');
  const header = document.createElement('h1');
  const text = 'Develop. Preview. Ship.';
  const headerContent = document.createTextNode(text);
  header.appendChild(headerContent);
  app.appendChild(header);
</script>
