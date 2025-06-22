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

