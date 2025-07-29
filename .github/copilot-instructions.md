# 🤖 GitHub Copilot Instructions for Portfolio Template

This file defines the design standards, coding best practices, and structural conventions for generating and editing the static one-page portfolio site using GitHub Copilot in Visual Studio Code.

All output must be in **English**.

---

## 🎨 Design & Styling Rules (Tailwind CSS)

- Use **dark theme** utilities:
  - `bg-gray-900`, `text-gray-100`, `text-gray-300`
- Apply `font-sans` to the body or root wrapper
- Keep layout centered using:
  - `max-w-5xl`, `mx-auto`, `px-4`, `py-8`
- Section titles:
  - `text-2xl font-bold uppercase`
- Paragraphs:
  - `text-sm text-gray-300 leading-relaxed`
- Use responsive Tailwind prefixes:
  - `sm:`, `md:`, `lg:`, `xl:`
- Add `scroll-smooth` class to the `<html>` tag for smooth navigation
- Ensure accessibility (semantic HTML + contrast + alt attributes)
- All icons must be from **Font Awesome**

### Font Awesome Setup

Always include the following in `<head>`:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
```

Use:
```html
<i class="fa-brands fa-python text-white text-xl"></i>
```

---

## 🧱 HTML Structure Guidelines

- Use semantic HTML5: `<nav>`, `<section>`, `<main>`, `<header>`, `<footer>`, `<aside>`
- One `<main>` container with multiple `<section>`s
- Sidebar must use `<nav>` and be fixed on desktop (`hidden md:block`)
- Sections should have unique `id`s for anchor navigation
- Footer at the bottom with links or copyright

---

## ⚙️ Coding Best Practices

- **Write all code and comments in English**
- Follow **DRY (Don't Repeat Yourself)** principle
- Avoid inline styles – always use Tailwind utility classes
- Use reusable utility classes or components where appropriate
- Keep indentation consistent (2 spaces)
- Comment non-obvious sections of code
- Use relative units (`rem`, `%`, `vh`, `vw`) for scalability
- Optimize images and media assets before using
- Ensure cross-browser compatibility and responsiveness
- Group related elements with `<div>` and use Tailwind spacing to separate blocks

---

## ✅ Accessibility

- Add `aria-label` and `alt` attributes where applicable
- Use semantic tags to assist screen readers
- Ensure contrast ratios meet WCAG 2.1 standards

---

## 📂 Folder Structure Convention

```
portfolio/
├── index.html
├── styles/
│   └── tailwind.css
├── scripts/
│   └── main.js (optional)
├── assets/
│   └── images, pdfs, icons, etc.
├── .github/
│   └── copilot-instructions.md
├── README.md
```

---

## 🚫 Do Not

- Do not use frameworks like Bootstrap, React, Vue, etc.
- Do not include unused Tailwind classes or dead code
- Do not hardcode colors, use Tailwind's color palette
- Do not use `!important` unless absolutely necessary

---

## 🧪 Validation and Testing

- Use [W3C HTML Validator](https://validator.w3.org/) to validate markup
- Test layout in Chrome, Firefox, Safari, and mobile devices
- Use Lighthouse to check accessibility and performance

---

## 💡 Tips

- Start building from `index.html` using a mobile-first approach
- Build the sidebar first, then add sections one by one
- Use Tailwind’s `flex`, `grid`, and `gap-*` utilities to control layout
- Reuse icons and components where possible
