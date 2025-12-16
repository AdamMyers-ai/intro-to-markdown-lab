# How to Write an HTML Boilerplate

HTML boilerplate gives your webpage it's fundamental structure. In this tutorial, you'll learn **what an HTML boilerplate is, why it matters**, and **how to write one from scratch**.

---

## What is an HTML Boilerplate?

An HTML boilerplate is the **basic structure** of an HTML document. It tells the browser:

- What type of document this is
- What language the page uses
- How to interpret characters
- How the page should scale on different devices

Every HTML page you build will start with this foundation.

## Step 1: Create a New HTML File

Create a file called:

`index.html`

HTML files always use the **.html** extension.

## Step 2: Add the DOCTYPE

At the very top of your file, add:

`<!DOCTYPE html>`

### Why this matters

- It tells the browser you're using **HTML5**

## Step 3: Add the `<html>` Element

Next, add the root element of your document:

```js
<html lang="en"></html>
```

### What this does:

- Wraps **all** your HTML content
- `lang="en"` helps with accessibility and SEO

## Step 4: Create the `<head>` Section

Inside the `<html>` tags, add a `<head>` section as shown below:

```js
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Web Page</title>
</head>
```

### Key elements explained

- **charset="UTF-8"**: Supports most characters and symbols
- **viewport**: Makes your site responsive on mobile devices
- **title**: Text shown in the browser tab

## Step 5: Add the `<body>` Section

Below the `<head>`, add the `<body>`:

```js
<body>
  <h1>Hello, World!</h1>
  <p>This is my first HTML page.</p>
</body>
```

### What goes in the body?

- Headings
- Paragraphs
- Images
- Buttons
- Forms
- Anything visible on the page

## Step 6: Putting it all together

Here's the **complete HTML boilerplate**:

```js
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>My Web Page</title>
</head>
<body>
<h1>Hello, World!</h1>
<p>This is my first HTML page.</p>
</body>
</html>
```

## Common Mistakes to Avoid

- Forgetting the `<!DOCTYPE html>
- Putting visible content inside the `<head>`
- Missing closing tags
- Using multiple `<html>` or `<body>` tags

## Summary

You learned how to:

- Create a basic HTML file
- Understand each part of an HTML boilerplate
- Build a clean, valid HTML structure

This boilerplate will be the starting point for **every HTML project you build**.
