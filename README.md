
# Chalise Sudoku — HTML & CSS Only (Mock)

This repo contains a **non-interactive mock** of a Sudoku website built **without JavaScript**.

Github link:https://akchalise.github.io/sudoku-project1/
---



##  Pages

* Home (`/`)
* Selection (`/selection/`)
* Hard Game (`/game-hard/`)
* Easy Game (`/game-easy/`)
* Rules & Credits (`/rules/`)
* High Scores (`/highscores/`)
* Login (`/login/`)
* Register (`/register/`)

---

##  Tech & Constraints

* Pure **HTML + CSS**.
* No JavaScript, frameworks, or styling libraries.
* Shared CSS in `/assets/css/common.css`.
* Clean URLs: each page has its own `index.html`.
* Navbar is fixed on desktop and moves to the bottom on mobile.

---

##  Requirements Covered

* **HTML Elements:** `div, span, a, img, p, head, button, input, body, h1–h6, ul/ol/table`.
* **CSS Features:** `font-family, background, margin, padding, position, flex/grid, @media`, pseudo-selectors (`:hover`, `:first-child`), transitions.
* **Mobile friendly:** tested on iPhone 12 Pro width (390px).
* **Design:** consistent color theme, imported Google Font (Inter), SVG logo.

---

##  Writeup

### 1. What was the most challenging piece of this assignment?

The most challenging part of this assignment was building the **Sudoku grids (9×9 and 6×6)** while ensuring that the subgrid separators (3×3 and 3×2) were styled correctly with only CSS. Getting the `nth-child` selectors right for borders required careful testing.
I also found that working only with HTML and CSS made me think differently — instead of adding JavaScript to validate or control inputs, I had to rely on **HTML attributes** (`pattern`, `maxlength`, `inputmode`).
Overall, the project took me several sessions spread across a few days, and I estimate it took me about **8–10 hours in total**.

---

### 2. What decisions did you make when you made your site mobile friendly?

I decided to **move the navbar to the bottom** of the screen for mobile devices, so that it doesn’t block the content area on smaller screens.
I also used **flexbox and CSS grid** so the layout adjusts naturally to different screen widths. Text, buttons, and the Sudoku grids shrink and grow using relative units and `clamp()` so they stay usable and legible.
These choices ensure that whether the site is viewed on a desktop or on an iPhone 12 Pro (as specified), the experience is consistent.

---

### 3. What did you take into account when you developed the design of your website?

I wanted the design to look professional while still being simple. I used a **dark theme with accent colors (green and teal)** for contrast and readability.
I imported the **Inter font** from Google Fonts because it is clean and highly readable on screens.
I am particularly proud of the way the **Sudoku boards look uniform** with perfect square cells, responsive scaling, and clear subgrid separators. It feels polished even though it’s only a mock.

---

### 4. Given more time or resources, what additional features would you add to your site in the future?

With more time, I would add:

* **Interactivity** (filling in numbers, checking correctness, highlighting conflicts).
* **User accounts** connected to real high scores.
* A **theme switcher** (light/dark mode).
* Accessibility enhancements like **keyboard-only navigation** and **screen reader support** for gameplay.

---

### 5. How many hours did you spend on this assignment?

I spent around **8–10 hours** in total.

---

### 6. (Optional) Assumptions

I assumed that the assignment required **input restrictions (1–9)** but did not require **live input validation** beyond what HTML alone could provide. I also assumed that placeholder data (usernames, scores, puzzle names) was acceptable since no real backend was needed.

---

### 7. Sources / Attributions

* Imported **Inter font** from Google Fonts.
* Used a self-made **SVG logo** for branding.
* No external JavaScript or CSS libraries were used.
* Some general CSS patterns (e.g., `:hover`, flexbox usage) were based on common examples but written by hand for this project.

---

##  Deliverables

* Working GitHub repo & GitHub Pages link.
* Demo video walkthrough (<5 min).
* This README as the writeup.

