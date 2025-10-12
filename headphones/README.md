# 🎧 Headphones Website

A responsive, modern headphones landing page built with HTML, CSS, and JavaScript.
The project features a hero banner, service descriptions, animated results, and a contact form — all designed to adapt seamlessly across desktop, tablet, and mobile views.
🖼️ Preview

## This website showcases:

- A hero section with a call-to-action button

- A "What We Do" section with four service icons

- An "Our Results" section displaying animated pentagon stats

- A Contact Us form with basic validation indicators

- A footer containing social media icons

- A hamburger navigation for mobile devices

## 🚀 Features

- ✅ Responsive Layout – Adapts to all screen sizes (desktop, tablet, mobile)
- ✅ Hamburger Menu – Toggles open/close navigation on smaller screens
- ✅ Animated Sections – Subtle hover and scale-up effects
- ✅ Dynamic Footer Year – Updates automatically via JavaScript
- ✅ Clean and Semantic HTML Structure
- ✅ CSS Grid and Flexbox for alignment and layout

## 🧩 HTML

- Defines the page structure with semantic tags: `<header>`, `<main>`, `<section>`, `<footer>`.

- The hamburger button (#menu) triggers the mobile navigation toggle.

- Sections include:

- Hero: Introduction and call to action.

- What We Do: Company services with icon illustrations.

- Our Results: Performance metrics with pentagon visuals.

- Contact Us: Simple contact form.

- Footer includes social media icons and an auto-updating copyright.

## 🎨 CSS

- Uses Flexbox and CSS Grid for layout and alignment.

- Implements media queries for responsive design at:

  - 768px (tablet)

  - 480px (mobile)

- Defines a mobile hamburger menu that toggles visibility of the navigation links.

- Animates hover effects and scales section titles with @keyframes.

## ⚙️ JavaScript

```javascript
const hamburger = document.querySelector("#menu");
const navigation = document.querySelector(".navigation");

hamburger.addEventListener("click", () => {
  navigation.classList.toggle("open");
  hamburger.classList.toggle("open");
});
```

- When the hamburger icon is clicked:

  - It toggles the "open" class on both the button and the nav list.

  - This makes the menu slide open or close on mobile view.

- Also, a small inline script in the footer dynamically sets the current year:

```javascript
const date = new Date();
document.getElementById(
  "currentyear"
).innerHTML = `&copy;headphones ${date.getFullYear()}`;
```

## 🌟 Future Enhancements

- Add smooth scroll behavior for internal links.

- Implement form validation with JavaScript.

- Add CSS transitions for the hamburger menu animation.

- Integrate an actual email API for contact form submission.

## 👤 Author

- David Adepegba
- 💻 Frontend Developer (in learning)

## Live Preview

- <a href="https://adepegba1.github.io/alx_html_css/headphones/8-index.html">Click Me!!</a>
