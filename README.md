# 🎬 Netflix India - Landing Page Clone

## 📸 Screenshots

### Homepage

![Homepage](screenshots/header.png)

### Trending Section

![Trending](screenshots/trending.png)

### Footer Section

![Footer](screenshots/footer.png)

### extr-info Section

![Footer](screenshots/extra-info.png)

A pixel-perfect recreation of the Netflix India homepage. This project was built to master modern CSS layout techniques, complex positioning, and responsive design patterns without relying on CSS frameworks like Bootstrap or Tailwind.

🔗 **[https://github.com/skrm05/netflix-landing-page.git]**

---

## 🎯 The Motive

Why clone Netflix? Because it is the gold standard for landing pages.
The goal of this assignment wasn't just to "make it look similar." It was to deeply understand **how** big tech companies structure their UI. I wanted to challenge myself with:

- **Complex Gradients:** Mastering the dark overlays that make text pop against background images.
- **The "Red Curve":** Replicating that iconic curved bottom edge without using SVG images.
- **Positioning:** Getting elements like the "Top 10" rank numbers to sit partially behind/over images.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic structure for better SEO and accessibility.
- **CSS3:** Flexbox, CSS Grid, Custom Gradients, and Absolute Positioning.
- **FontAwesome:** For the scalable vector icons (search, chevron, plus signs).
- **Google Fonts:** Used 'Roboto' to match the clean, cinematic aesthetic.

---

## 🚀 Key Features & Approach

### 1. The Hero Section & Gradient Overlays

The header isn't just a simple background image. To ensure the white text is readable, I used a multi-layered CSS background approach:

```css
background:
  linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.3), ...), url(...);
```
