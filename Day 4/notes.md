
## 📊 Tables (Used to Display Data)

| Tag       | What it does                   |
| --------- | ------------------------------ |
| `<table>` | Starts a table                 |
| `<tr>`    | Table row                      |
| `<td>`    | Table data cell (normal cell)  |
| `<th>`    | Table header (bold + centered) |
| `<thead>` | Groups header rows             |
| `<tbody>` | Groups content/body rows       |

### ✅ Example:

```html
<table>
  <thead>
    <tr><th>Name</th><th>Age</th></tr>
  </thead>
  <tbody>
    <tr><td>Alice</td><td>24</td></tr>
    <tr><td>Bob</td><td>28</td></tr>
  </tbody>
</table>
```

---

## 🎬 Multimedia – Audio & Video

### 🔊 Audio:

```html
<audio controls>
  <source src="sound.mp3" type="audio/mpeg">
</audio>
```

### 📽️ Video:

```html
<video width="400" controls>
  <source src="movie.mp4" type="video/mp4">
</video>
```

> Always use `<source>` for better browser support.

---

## 🔖 Meta Tags – Page Info (go inside `<head>`)

```html
<meta charset="UTF-8">
<!-- Character set -->

<meta name="description" content="My cool HTML page">
<!-- For search engines -->

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- Makes the site responsive on mobile -->
```

---

## 🌐 Embeds – Show External Stuff

### 🌍 iFrame – Embed other websites

```html
<iframe src="https://example.com" width="500" height="300"></iframe>
```

### 📄 Embed – Embed PDFs or other content

```html
<embed src="file.pdf" width="400" height="300">
```

> Use these when you want to show something from outside your page.

---

## ♿ Accessibility Basics (Make sites usable for everyone)

| What          | How to use                            |
| ------------- | ------------------------------------- |
| `alt`         | Describes an image for screen readers |
| `<label>`     | Describes what a form input is for    |
| Semantic tags | Help screen readers understand layout |

### ✅ Examples:

```html
<img src="cat.jpg" alt="Black cat sitting on a windowsill">

<label for="email">Email:</label>
<input type="email" id="email" name="email">
```

---

## 🔁 Quick Recap

✔ Tables = Structured data
✔ Multimedia = Audio/video support
✔ Meta = Info for browsers and SEO
✔ Embeds = Show external content (site, PDF, etc.)
✔ Accessibility = Use `alt`, `label`, and clean semantic HTML


