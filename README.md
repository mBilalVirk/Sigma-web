"# Sigma-web" 


---

### ✅ Step 1: Create a Repository on GitHub

1. Go to [https://github.com](https://github.com)
2. Click the **+** icon (top right) → **New repository**
3. Name your repository (e.g., `my-project`)
4. (Optional) Add a description
5. **Don’t** initialize with a README (you already have code locally)
6. Click **Create repository**

---

### ✅ Step 2: Open Terminal or Git Bash on Your PC

Navigate to your project folder. For example:

```bash
cd path/to/your/project
```

---

### ✅ Step 3: Initialize Git (if not already)

```bash
git init
```

---

### ✅ Step 4: Add Your Remote GitHub Repo

Copy the repo link from GitHub (it will look like this: `https://github.com/username/my-project.git`)

Then in terminal:

```bash
git remote add origin https://github.com/your-username/your-repo-name.git
```

---

### ✅ Step 5: Add and Commit Files

```bash
git add .
git commit -m "Initial commit"
```

---

### ✅ Step 6: Push to GitHub

```bash
git branch -M main
git push -u origin main
```

> It may ask for your GitHub username and password or a **token** if you're using HTTPS.

---

### ❗If Git asks for a token instead of password

1. Go to [https://github.com/settings/tokens](https://github.com/settings/tokens)
2. Generate a **Personal Access Token** with `repo` permission
3. Use this token **as password** in Git when prompted

---

The **main structure of a website** typically includes both **frontend** (what users see) and **backend** (what powers it). Here's a clear breakdown:

---

### 🧱 **1. Basic Structure (Frontend Layout)**

```plaintext
📁 Website Root
├── index.html / home page
├── about.html / contact.html (other pages)
├── 📁 assets/
│   ├── 📁 css/
│   │   └── styles.css
│   ├── 📁 js/
│   │   └── script.js
│   └── 📁 images/
│       └── logo.png, background.jpg, etc.
```

---

### 🧑‍💻 **2. HTML Structure (Page Layout)**

Each webpage usually follows this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Website Title</title>
  <link rel="stylesheet" href="assets/css/styles.css">
</head>
<body>
  <header>Website Logo, Navigation</header>

  <main>
    <!-- Page content here -->
  </main>

  <footer>Copyright © 2025</footer>

  <script src="assets/js/script.js"></script>
</body>
</html>
```

---

### ⚙️ **3. Optional Backend Structure (for dynamic websites)**

If you're using something like **PHP, Laravel, Node.js**, etc., your structure might look like this:

**Example (Laravel or MVC-based)**

```plaintext
📁 app/
📁 public/
│   └── index.php (entry point)
📁 routes/
📁 resources/
│   └── views/ (Blade or HTML templates)
📁 database/
📁 .env
📁 composer.json / package.json
```

---

### 🧩 **4. Common Website Pages**

* **Home Page** (`index.html`)
* **About Page**
* **Contact Page**
* **Blog / Services / Products Pages**
* **Admin Panel** (if CMS or dashboard involved)

---

### 🧰 5. Optional Tech Stack Used

| Part     | Tech Example                    |
| -------- | ------------------------------- |
| Frontend | HTML, CSS, JS, Bootstrap, React |
| Backend  | PHP, Laravel, Node.js, Django   |
| Database | MySQL, MongoDB                  |
| Hosting  | GitHub Pages, cPanel, Vercel    |
| Tools    | Git, Vite, Webpack, NPM         |

---



## 🏷️ HTML Heading Tags

HTML provides **six heading tags** to define headings on a webpage, from `<h1>` (most important) to `<h6>` (least important).

### ✅ Syntax:

```html
<h1>This is a heading 1</h1>
<h2>This is a heading 2</h2>
<h3>This is a heading 3</h3>
<h4>This is a heading 4</h4>
<h5>This is a heading 5</h5>
<h6>This is a heading 6</h6>
```

---

## 📚 Explanation

| Tag    | Purpose                 | Default Size    |
| ------ | ----------------------- | --------------- |
| `<h1>` | Main title of the page  | Largest         |
| `<h2>` | Sub-heading of `<h1>`   | Smaller than h1 |
| `<h3>` | Sub-heading of `<h2>`   | Smaller than h2 |
| `<h4>` | Sub-heading of `<h3>`   | ...             |
| `<h5>` | Sub-heading of `<h4>`   | ...             |
| `<h6>` | Least important heading | Smallest        |

---

### 🎯 Key Points:

* Use **only one `<h1>` per page** for SEO (Search Engine Optimization) and accessibility.
* Headings help organize content and improve **readability**.
* Browsers apply **bold and spacing** by default.
* Headings are **block-level elements** (they start on a new line).

---

### 🧠 Example:

```html
<h1>Welcome to My Website</h1>
<h2>About Us</h2>
<h3>Our Mission</h3>
<h3>Our Team</h3>
<h2>Contact</h2>
```

---

### 💡 Tip:

If you're using CSS, you can **customize** how each heading looks:

```css
h1 {
  color: darkblue;
  font-size: 36px;
  font-weight: bold;
}
```

---



## 📄 What is Lorem Ipsum?

**"Lorem Ipsum"** is **dummy text** used in the publishing and web design industry. It's used as placeholder content when the actual text is not available yet.

---

## 💬 Example:

```html
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
```

This will display as:

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

---

## 🧠 Why Use Lorem Ipsum?

* To **focus on design/layout** without being distracted by real content.
* To **fill space** in templates or website mockups.
* It shows how **text will look** once added.

---

## 📚 Meaning of the Text?

"Lorem Ipsum" is actually derived from **Latin** literature from 45 BC. But the modern version is **nonsense text**, used purely for layout.

It **doesn't mean anything**, which makes it ideal for mockups because readers won't focus on the words.

---

## 🧰 How to Use in HTML?

```html
<h2>About Our Company</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam convallis eros ac massa vestibulum.</p>
```

---

## ✨ Shortcut in Code Editors

In **VS Code** or many editors, you can type:

```html
lorem50
```

and press **Tab**, and it will generate 50 words of lorem text.

---

## 🔗 `<a>` Tag in HTML

The `<a>` tag stands for **anchor** and is used to **create hyperlinks** — links that users can click to go to another page, website, or section of the same page.

---

## ✅ Syntax:

```html
<a href="URL">Link Text</a>
```

---

## 📘 Example:

```html
<a href="https://www.google.com">Visit Google</a>
```

🖱️ Output:
👉 [Visit Google](https://www.google.com)

---

## 🔍 Attributes of `<a>` Tag:

| Attribute  | Description                                                |
| ---------- | ---------------------------------------------------------- |
| `href`     | The URL of the page the link goes to                       |
| `target`   | Defines where to open the link (`_blank` opens in new tab) |
| `title`    | Tooltip text on hover                                      |
| `download` | Downloads the linked file instead of opening it            |

---

## 🌐 Example with Attributes:

```html
<a href="https://example.com" target="_blank" title="Go to Example">Click Here</a>
```

🔸 Opens in a new tab
🔸 Shows "Go to Example" when hovered

---

## ⛔ Empty Link (used in templates or JavaScript links)

```html
<a href="#">This does nothing</a>
```

---

## 📎 Anchor Link (same page scroll)

```html
<a href="#contact">Go to Contact Section</a>
...
<h2 id="contact">Contact Us</h2>
```

---

## 🎯 Styling Example with CSS:

```html
a {
  color: blue;
  text-decoration: none;
}
a:hover {
  color: red;
  text-decoration: underline;
}
```

---

# 🖼️ 1. `<img>` Tag – Image in HTML

## ✅ Basic Syntax:

```html
<img src="image.jpg" alt="Description">
```

## 📘 Attributes:

| Attribute | Description                   |
| --------- | ----------------------------- |
| `src`     | Image path or URL             |
| `alt`     | Alternate text if image fails |
| `width`   | Width in pixels or %          |
| `height`  | Height in pixels or %         |

### 🎯 Example:

```html
<img src="https://via.placeholder.com/150" alt="Sample Image" width="150" height="150">
```

## ✨ Styling:

```css
img {
  border-radius: 10px;
  border: 2px solid black;
}
```

### 📙 Urdu:

`<img>` ٹیگ ویب سائٹ پر تصویر لگانے کے لیے استعمال ہوتا ہے۔
`src` تصویر کا پتہ ہوتا ہے، `alt` تصویر کے نہ دکھنے کی صورت میں متبادل ٹیکسٹ۔

---

# 📋 2. `<table>` Tag – Table in HTML

## ✅ Basic Structure:

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bilal</td>
      <td>25</td>
    </tr>
    <tr>
      <td>Ali</td>
      <td>30</td>
    </tr>
  </tbody>
</table>
```

## 📘 Tags Explained:

| Tag                  | Meaning              |
| -------------------- | -------------------- |
| `<table>`            | Starts table         |
| `<tr>`               | Table row            |
| `<th>`               | Table heading (bold) |
| `<td>`               | Table data (cell)    |
| `<thead>`, `<tbody>` | Table sections       |

## ✨ CSS Styling:

```css
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 10px;
}
```

### 📙 Urdu:

`<table>` ٹیگ جدول (table) بنانے کے لیے ہوتا ہے۔
`<tr>` ہر لائن کے لیے، `<th>` سرخی کے لیے، `<td>` ڈیٹا کے لیے۔

---

# 📑 3. Lists in HTML – Ordered, Unordered, Description

### 📌 Types of Lists:

### ✅ a. **Unordered List** (bullets)

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

### ✅ b. **Ordered List** (numbers)

```html
<ol>
  <li>Wake up</li>
  <li>Brush</li>
  <li>Code</li>
</ol>
```

### ✅ c. **Description List** (terms & definitions)

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>
```

## 🎨 Styling Example:

```css
ul {
  list-style-type: square;
}
ol {
  list-style-type: upper-roman;
}
```

### 📙 Urdu:

* `<ul>` بغیر نمبر والی فہرست (• bullets)
* `<ol>` نمبر والی فہرست (1, 2, 3)
* `<li>` ہر آئٹم
* `<dl>` تعریفوں کی فہرست (مثال: glossary)

---

## ✅ Summary Table:

| Feature | Tag                    | Purpose               |
| ------- | ---------------------- | --------------------- |
| Image   | `<img>`                | Show image            |
| Table   | `<table>`              | Create rows & columns |
| List    | `<ul>`, `<ol>`, `<li>` | Show itemized data    |

---


## 🚀 What Are Core Web Vitals?

**Core Web Vitals** are a set of **three key performance metrics** introduced by Google to measure:

1. **Page loading speed**
2. **User interaction responsiveness**
3. **Visual stability**

These metrics directly impact your **website ranking** on Google and **user satisfaction**.

---

## 📊 The 3 Core Web Vitals

| Metric  | Full Form                | Measures                                                                   | Good Score    |
| ------- | ------------------------ | -------------------------------------------------------------------------- | ------------- |
| 1️⃣ LCP | Largest Contentful Paint | **Loading time** of the biggest visible content (e.g., image, heading)     | **≤ 2.5 sec** |
| 2️⃣ FID | First Input Delay        | **Interactivity** — how quickly your site responds when users click or tap | **≤ 100 ms**  |
| 3️⃣ CLS | Cumulative Layout Shift  | **Visual stability** — how much layout shifts when content loads           | **≤ 0.1**     |

---

## 🔍 Explanation of Each:

### 1. 🕒 **LCP (Largest Contentful Paint)**

* Measures: When the main content becomes visible.
* Example: If a banner image or large heading takes 3s to appear, LCP = 3s.
* Target: **Under 2.5 seconds**

### 2. ⚡ **FID (First Input Delay)**

* Measures: Delay between user interaction (click/tap) and response.
* Example: You click a button, and it takes 300ms to react → bad FID.
* Target: **Under 100 milliseconds**

### 3. 📐 **CLS (Cumulative Layout Shift)**

* Measures: Content shifting unexpectedly while loading.
* Example: A button jumps down as an ad loads.
* Target: **Less than 0.1**

---

## ✅ How to Check Core Web Vitals

You can use:

* [PageSpeed Insights](https://pagespeed.web.dev/)
* **Lighthouse** in Chrome DevTools
* **Google Search Console** → Core Web Vitals Report
* Web Vitals Chrome Extension

---

## 🧰 How to Improve Them?

| Metric | Fixes                                                    |
| ------ | -------------------------------------------------------- |
| LCP    | Optimize images, use lazy loading, fast hosting          |
| FID    | Minimize JavaScript, reduce third-party code             |
| CLS    | Set image/video dimensions, avoid dynamic content shifts |

---

## 📙 In Urdu (اردو میں):

**Core Web Vitals** تین اہم پیمائشیں ہیں جو یہ دیکھتی ہیں کہ آپ کی ویب سائٹ **کتنی تیزی سے لوڈ ہوتی ہے، کتنا responsive ہے، اور کتنی مستحکم دکھتی ہے**۔
گوگل ان کو استعمال کرتا ہے تاکہ اچھی user experience والی ویب سائٹس کو زیادہ رینک دے۔

---

## 📝 What is a Form in HTML?

An **HTML form** is used to **collect input from the user** and send it to a server for processing (like login, registration, search, etc.).

```html
<form> ... </form>
```

---

## 🧱 Basic Structure:

```html
<form action="submit.php" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="username">
  
  <input type="submit" value="Submit">
</form>
```

---

## ⚙️ Important Form Attributes

| Attribute      | Description                                   |
| -------------- | --------------------------------------------- |
| `action`       | URL or file where form data is sent           |
| `method`       | `GET` or `POST` method                        |
| `target`       | Where to display response (`_self`, `_blank`) |
| `autocomplete` | On/off for browser autocomplete               |
| `enctype`      | Encoding type (used for file uploads)         |

---

## 📬 Form Methods: GET vs POST

| Method | Purpose                        | Data Visible in URL? | Secure? |
| ------ | ------------------------------ | -------------------- | ------- |
| `GET`  | Retrieve data (search)         | Yes                  | No      |
| `POST` | Send data (login, file upload) | No                   | Yes     |

---

## 🔢 Common Form Input Types

### 📌 1. Text Input

```html
<input type="text" name="username">
```

### 📌 2. Password

```html
<input type="password" name="pass">
```

### 📌 3. Email

```html
<input type="email" name="email">
```

### 📌 4. Radio Buttons

```html
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female
```

### 📌 5. Checkboxes

```html
<input type="checkbox" name="hobby" value="reading"> Reading
<input type="checkbox" name="hobby" value="coding"> Coding
```

### 📌 6. Dropdown (Select)

```html
<select name="city">
  <option value="lahore">Lahore</option>
  <option value="karachi">Karachi</option>
</select>
```

### 📌 7. Textarea (Multi-line input)

```html
<textarea name="message" rows="4" cols="30"></textarea>
```

### 📌 8. File Upload

```html
<input type="file" name="resume">
```

### 📌 9. Submit Button

```html
<input type="submit" value="Submit">
```

---

## 🧠 Full Example:

```html
<form action="submit.php" method="post">
  <label>Name:</label>
  <input type="text" name="name" required><br><br>

  <label>Email:</label>
  <input type="email" name="email" required><br><br>

  <label>Gender:</label>
  <input type="radio" name="gender" value="male"> Male
  <input type="radio" name="gender" value="female"> Female<br><br>

  <label>Hobbies:</label>
  <input type="checkbox" name="hobby" value="coding"> Coding
  <input type="checkbox" name="hobby" value="reading"> Reading<br><br>

  <label>City:</label>
  <select name="city">
    <option value="lahore">Lahore</option>
    <option value="islamabad">Islamabad</option>
  </select><br><br>

  <label>Message:</label><br>
  <textarea name="message" rows="4" cols="40"></textarea><br><br>

  <input type="submit" value="Send">
</form>
```

---

## 🎨 Form Styling (CSS)

```css
form {
  width: 300px;
  padding: 20px;
  border: 1px solid #ccc;
  background-color: #f9f9f9;
}
input, textarea, select {
  width: 100%;
  margin-bottom: 10px;
  padding: 8px;
}
```

---


## 🔲 What Are Inline and Block Elements in HTML?

In HTML, every element is either a:

### 🔹 **Block-level element**

OR

### 🔹 **Inline element**

These determine **how elements behave in a document flow** — whether they take up the full line or just enough space.

---

## 🧱 1. Block-Level Elements

### ✅ Key Features:

* Always **start on a new line**
* Take **full width** of their parent container
* Can contain **inline elements or other block elements**
* Create **a "box"** on the page

### 📘 Common Block Elements:

```html
<div>, <p>, <h1>–<h6>, <form>, <header>, <footer>, <section>, <article>, <table>, <ul>, <ol>, <li>
```

### 🧠 Example:

```html
<p>This is a paragraph.</p>
<div>This is a div box.</div>
```

💡 Output:
Each will appear on a **new line**, one after another.

---

## 📏 2. Inline Elements

### ✅ Key Features:

* **Do NOT start on a new line**
* Only take up as much **width as needed**
* **Cannot** contain block-level elements (only text or other inline elements)

### 📘 Common Inline Elements:

```html
<span>, <a>, <img>, <strong>, <em>, <label>, <input>, <b>, <i>, <small>
```

### 🧠 Example:

```html
<p>This is <strong>bold</strong> and <em>italic</em> text.</p>
```

💡 Output:
All content appears **on the same line**, unless it wraps naturally.

---

## 🎨 Visual Example

```html
<div style="background: lightblue;">Block Element</div>
<span style="background: yellow;">Inline Element</span>
<span style="background: pink;">Another Inline</span>
```

---

## 🧰 Difference Summary:

| Feature            | Block Elements         | Inline Elements     |
| ------------------ | ---------------------- | ------------------- |
| Starts on new line | ✅ Yes                  | ❌ No                |
| Takes full width   | ✅ Yes                  | ❌ No                |
| Contains           | Blocks & Inline        | Only Inline or Text |
| Styling            | Margin, Padding, Width | Limited box styling |

---

In CSS, both `ID` and `class` are used to apply styles to HTML elements, but they serve **different purposes** and have **different rules**. Here are the main differences:

---

### 🔹 1. **Syntax**

| Feature  | ID        | Class        |
| -------- | --------- | ------------ |
| Selector | `#idName` | `.className` |
| Example  | `#header` | `.menu`      |

---

### 🔹 2. **Uniqueness**

| Property             | ID                     | Class                          |
| -------------------- | ---------------------- | ------------------------------ |
| How many times used? | Only **once per page** | Can be used **multiple times** |

✅ **ID** must be unique.
✅ **Class** can be shared across multiple elements.

---

### 🔹 3. **Specificity (Priority)**

| Priority Level | ID has **higher specificity** than class |
| -------------- | ---------------------------------------- |
| Example        | If both are applied, the ID style wins   |

```html
<style>
  #box { color: red; }
  .box { color: blue; }
</style>

<div id="box" class="box">Text</div>
```

📌 Result: Text will be **red** because ID has higher priority.

---

### 🔹 4. **Usage**

| ID                       | Class                              |
| ------------------------ | ---------------------------------- |
| Used for unique elements | Used for grouping similar elements |
| Example: Header, footer  | Example: Buttons, list items, etc. |

---

### 🔹 5. **In HTML**

```html
<!-- ID -->
<div id="mainHeader">Header Content</div>

<!-- Class -->
<div class="card">Card 1</div>
<div class="card">Card 2</div>
```

---

### ✅ Summary

| Feature     | ID             | Class         |
| ----------- | -------------- | ------------- |
| Prefix      | `#`            | `.`           |
| Unique?     | Yes            | No            |
| Reusable?   | No             | Yes           |
| Specificity | Higher         | Lower         |
| Usage       | Unique element | Group styling |

---



## 🎧 `<audio>` Tag — For Playing Sound

### ✅ Common Attributes:

| Attribute  | Description                                                                   |
| ---------- | ----------------------------------------------------------------------------- |
| `src`      | The path to the audio file (can also use `<source>` inside).                  |
| `controls` | Displays play/pause/volume UI.                                                |
| `autoplay` | Starts playing audio automatically (may be blocked by browsers).              |
| `loop`     | Repeats the audio once it ends.                                               |
| `muted`    | Starts muted.                                                                 |
| `preload`  | Controls how much audio is loaded before playing: `auto`, `metadata`, `none`. |

### 🔧 Example:

```html
<audio controls autoplay loop preload="auto">
  <source src="music.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

---

## 🎬 `<video>` Tag — For Playing Video

### ✅ Common Attributes:

| Attribute          | Description                                      |
| ------------------ | ------------------------------------------------ |
| `src`              | The video file (can also use `<source>` inside). |
| `controls`         | Adds playback controls.                          |
| `autoplay`         | Plays automatically (often requires `muted`).    |
| `loop`             | Restarts video when it ends.                     |
| `muted`            | Starts with no sound.                            |
| `poster`           | A thumbnail image shown before the video plays.  |
| `width` / `height` | Dimensions of the video player.                  |
| `preload`          | Like audio, controls preload behavior.           |

### 🔧 Example:

```html
<video width="500" controls poster="thumbnail.jpg" loop muted>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

---

## 🌐 `<iframe>` Tag — For Embedding External Media (e.g., YouTube)

### ✅ Common Attributes:

| Attribute          | Description                                      |
| ------------------ | ------------------------------------------------ |
| `src`              | URL of the embedded media (e.g., YouTube video). |
| `width` / `height` | Size of the frame.                               |
| `frameborder`      | Border thickness (often set to `"0"`).           |
| `allowfullscreen`  | Allows full-screen mode for videos.              |
| `loading="lazy"`   | Delays loading for performance.                  |

### 🔧 Example:

```html
<iframe width="560" height="315" 
  src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
  frameborder="0" allowfullscreen loading="lazy">
</iframe>
```

---

## 💡 Quick Styling with CSS:

```css
audio, video, iframe {
  display: block;
  margin: 20px auto;
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
  border-radius: 10px;
}
```

---

