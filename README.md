# 🧠 Frontend Quick Tour – A Senior Developer’s Guide

> 📚 A comprehensive, no-fluff guide to advanced frontend development practices — from semantic HTML to modern patterns.

---

## 🧭 Table of Contents

1. [Why This Guide?](#why-this-guide)
2. [Semantic HTML for Senior Developers](#semantic-html-for-senior-developers)
3. [Next Steps & Features to Add](#next-steps--features-to-add)
4. [Project Structure](#project-structure)
5. [Contributing](#contributing)

---

## 💡 Why This Guide?

Frontend development is more than just frameworks and libraries. This guide dives into the **less obvious but powerful aspects** of building for the web — things that **senior developers** need to know to write scalable, maintainable, and accessible code.

We cover:

- 🧠 Semantic HTML best practices
- 🔍 Accessibility patterns
- 🧱 Component structure
- 🧩 Advanced patterns (ARIA, progressive enhancement, etc.)
- 📦 Tooling and performance

---

## 📚 Semantic HTML for Senior Developers

> A guide to advanced semantic HTML usage — not just for accessibility, but for **maintainability, SEO, and future-proofing** your markup.

### 1. `<header>`
✅ A container for introductory content or navigation.

💡 Use it at the top of the page or section.

⚖️ Use `<header>` inside `<article>` or `<section>` for local headers.

---

### 2. `<nav>`
✅ Contains navigation links (menus, links to other parts of the site).

💡 Use it for primary/secondary site nav or in-page nav (like table of contents).

⚠️ Don’t use for every group of links (e.g. in footer), only for navigational purposes.

---

### 3. `<main>`
✅ Represents the main content of the document (unique per page).

💡 Use it once per page to wrap the primary content, excluding headers, sidebars, and footers.

⚖️ Don't nest inside `<article>` or `<section>`.

---

### 4. `<section>`
✅ A thematic grouping of content, often with a heading.

💡 Use when content has a specific theme or purpose (e.g. Features section, Contact section).

⚖️ If it doesn't need a heading, use `<div>` instead.

---

### 5. `<article>`
✅ Represents independent, self-contained content.

💡 Use for blog posts, news articles, forum posts, cards.

⚖️ Use `<section>` when content is related but not standalone.

---

### 6. `<aside>`
✅ Content indirectly related to the main content (sidebars, pull quotes, ads).

💡 Use for tips, notes, or extra links.

⚠️ Not for primary content; it’s supplemental.

---

### 7. `<footer>`
✅ Contains footer content (credits, links, contact info).

💡 Can be used globally (at page level) or locally (inside `<article>`).

⚖️ Can have multiple `<footer>` tags.

---

### 8. `<h1>` to `<h6>`
✅ Headings that define content hierarchy.

💡 Use only one `<h1>` per page (usually in `<main>`), then descend to `<h2>`, `<h3>`, etc.

⚠️ Don’t skip levels (`<h1>` → `<h3>`); it breaks accessibility.

---

### 9. `<address>`
✅ Provides contact information.

💡 Use for email, physical address, author details — usually inside `<footer>` or near `<article>`.

⚠️ Don’t use for random locations (e.g. store addresses on map).

---

### 10. `<figure>` and `<figcaption>`
✅ `<figure>` wraps self-contained media (images, diagrams), and `<figcaption>` provides a label.

💡 Use when image/diagram needs explanation.

⚠️ Don’t use for decorative images.

---

### 11. `<mark>`
✅ Highlights text relevant to user’s interest/search.

💡 Use in search result matches or callout highlights.

⚠️ Not for generic emphasis (use `<strong>` or `<em>` instead).

---

### 12. `<time>`
✅ Represents a specific time or date.

💡 Use with `datetime` attribute for machine-readability (good for SEO).

⚠️ Don’t just format time visually; use:

```html
<time datetime="2023-07-18">July 18</time>
