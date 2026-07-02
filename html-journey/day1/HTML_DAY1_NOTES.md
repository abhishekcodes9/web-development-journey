# 📝 HTML Notes — Video 1 (Introduction to HTML)
**By Abhishek Agarwal | abhishekcodes9**

---

## 🔑 What is HTML?

- HTML = **HyperText Markup Language**
- It is the **skeleton/structure** of every webpage
- It tells the browser **what to display** (heading, paragraph, image etc.)
- HTML is NOT a programming language — it is a **markup language**
- Every website you visit is built on HTML

---

## 📄 The Basic Structure of Every HTML File

```html
<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset="UTF-8">
        <title>My first web page</title>
    </head>

    <body>
        <h1>HELLO WORLD!</h1>
        <p>This is my first web page.</p>
    </body>

</html>
```

---

## 🧱 Every Tag Explained (Line by Line)

### `<!DOCTYPE html>`
- Always the **very first line** of every HTML file
- Tells the browser — "this is an HTML5 document"
- Without this, browser may not display page correctly
- Write it **only once**, at the very top

---

### `<html lang="en">`
- This is the **root tag** — everything goes inside it
- `lang="en"` tells browser the language is English
- Every HTML file has exactly **one** `<html>` tag
- Closed at the very bottom with `</html>`

---

### `<head>` tag
- Contains **information about the page** — not visible to users
- Things inside head are for the **browser**, not for display
- Always comes **before** `<body>`

#### What goes inside `<head>`:

| Tag | Purpose |
|---|---|
| `<meta charset="UTF-8">` | Supports all characters and symbols |
| `<title>` | Text shown on browser tab |
| `<style>` | CSS styling for the page |
| `<link>` | Connect external CSS file (later) |

---

### `<body>` tag
- Everything **visible on the webpage** goes here
- Text, headings, images, buttons — all inside body
- Comes **after** `</head>`
- Closed with `</body>` before `</html>`

---

### `<h1>` tag
- H = Heading, 1 = biggest size
- HTML has 6 heading sizes: `<h1>` to `<h6>`
- `<h1>` is largest, `<h6>` is smallest
- Use only **one `<h1>`** per page (important for SEO)

```html
<h1>Biggest Heading</h1>
<h2>Second Heading</h2>
<h3>Third Heading</h3>
```

---

### `<p>` tag
- P = Paragraph
- Used for normal body text
- Always close it with `</p>`

```html
<p>This is a paragraph of text.</p>
```

---

## 🎨 CSS Inside HTML (Basic Styling)

CSS can be written inside `<style>` tag in the `<head>`:

```html
<style>
    html {
        font-size: 22px;
    }

    body {
        background-color: #333;
        color: whitesmoke;
    }
</style>
```

### CSS Rules Explained:

| Property | Value Used | What it does |
|---|---|---|
| `font-size` | `22px` | Sets default text size for whole page |
| `background-color` | `#333` | Dark grey background (#333 is a hex color) |
| `color` | `whitesmoke` | Makes all text white/light colored |

### Important CSS Syntax Rule:
- Every CSS line ends with a **semicolon `;`**
- Without semicolon, styles may not apply correctly

---

## ⚡ Tags vs Elements

- A **tag** is just the label: `<h1>`
- An **element** is the full thing: `<h1>Hello</h1>`
- Most tags have **opening** `<h1>` and **closing** `</h1>`
- Notice closing tag has a **forward slash /**

---

## 📋 Quick Reference — Order of Structure

```
<!DOCTYPE html>        ← Always first
<html>                 ← Opens root
  <head>               ← Browser info (not visible)
    <meta>             ← Character support
    <title>            ← Browser tab text
    <style>            ← CSS styling
  </head>              ← Head closes
  <body>               ← Visible content starts
    <h1>               ← Main heading
    <p>                ← Paragraph
  </body>              ← Body closes
</html>                ← Root closes
```

---

## 💡 Key Habits to Build from Day 1

- Always press **Ctrl + S** to save → Live Server auto-refreshes
- Always close every tag you open
- Every CSS property ends with `;`
- Indent your code (use Tab) so it's readable
- One `<h1>` per page only

---

## 🏆 What You Built Today

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>My first web page</title>
        <style>
            html {
                font-size: 22px;
            }
            body {
                background-color: #333;
                color: whitesmoke;
            }
        </style>
    </head>
    <body>
        <h1>HELLO WORLD!</h1>
        <p>This is my first web page.</p>
    </body>
</html>
```

**This is your first webpage. Dark theme. Live in browser. Day 1 done. 🚀**

---

*Notes by Abhishek Agarwal | Full Stack + AI Journey | 2nd Year CS Student*
