

### 📦 1. `<div>`, `class`, and `id`

* `<div>`: A box/container to group elements. No default styling—just for structure.
* `class`: Used to group multiple elements under the same style. (Can be reused)
* `id`: Used to target one unique element. (Only once per page)

```html
<div class="box" id="intro">Welcome</div>
```

---

### 🧱 2. Semantic Tags

These give meaning to your HTML layout:

* `<header>` – Top of page (logo, nav)
* `<nav>` – Navigation menu
* `<main>` – Main content (only once per page)
* `<section>` – Logical content block
* `<article>` – Independent content like a blog post
* `<footer>` – Bottom of page

```html
<header><h1>My Site</h1></header>
<main><section>Content</section></main>
<footer>© 2025</footer>
```

---

### 📝 3. Forms and Inputs

Forms collect user input:

```html
<form action="/submit" method="post">
  <!-- inputs go here -->
</form>
```

#### Common Elements:

* `<input>` – Single-line input (text, email, number, etc.)
* `<textarea>` – Multi-line input
* `<label>` – Describes inputs, links using `for`
* `<select>` – Dropdown menu
* `<option>` – Choices in select
* `<button>` – Submits or triggers actions

---

### ⚙️ 4. Important Input Types

```html
<input type="text">         <!-- normal text -->
<input type="email">        <!-- must be valid email -->
<input type="password">     <!-- hidden characters -->
<input type="number">       <!-- only numbers -->
<input type="checkbox">     <!-- true/false -->
<input type="radio">        <!-- choose one -->
<input type="submit">       <!-- submit the form -->
```

---

### 🏷 5. Must-Know Attributes

| Attribute     | What It Does                            |
| ------------- | --------------------------------------- |
| `name`        | Key for form data when submitted        |
| `value`       | Sets default value / submitted value    |
| `placeholder` | Shows hint text inside input            |
| `required`    | Makes field mandatory before submission |
| `type`        | Defines the kind of input               |

```html
<input type="text" name="username" placeholder="Enter name" required>
```


### ✅ Tips

* Use `label` with `for` and `id` for accessibility.
* Use `class` for styling, `id` for unique targeting.
* Always set `name` in form elements if you want to collect that data.

