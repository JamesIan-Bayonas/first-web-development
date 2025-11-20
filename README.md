# 🏛️ Archive: Freshman Year Web Project (202x)

> **⚠️ NOTE TO RECRUITERS & DEVS:**
> *This repository has been intentionally preserved in its original state to demonstrate my progression as a an Individual pursuing tech. It represents my technical knowledge during my first year of college.*

---

## 📖 About This Project
This was my very first attempt at building a multi-page website from scratch using **Vanilla HTML, CSS, and JavaScript**.

At the time, my goal was simply to "make it work." I was learning the basics of the DOM, the box model, and linking assets. While the site functions, the architecture reflects a beginner's understanding of file organization and maintainability.

I have chosen **not to modifyr** this code. Instead, I am using it as a baseline to measure how far my coding skills throughout all the years have evolved.

---

## 🔍 Self-Audit: The "Code Review"
Looking back at this codebase today, I can identify several critical bad practicies that I have since corrected in my modern workflow.

### 1. Naming Conventions & Case Sensitivity
* **The Freshman Mistake:** I used a chaotic mix of `Snake_Case`, `ALL CAPS` directories, and redundant filenames (e.g., `Computer_Studies_Css.css`, `yoo.html`, `solve_Css.css`).
* **The Problem:** This causes massive issues on case-sensitive servers (Linux) and makes programmatic file access difficult.
* **My Standard Today:** I strictly adhere to **kebab-case** for all filenames (`computer-studies.css`) and **camelCase** for JavaScript variables.

### 2. Folder Structure & Architecture
* **The Freshman Mistake:** I grouped files by "University Department" (e.g., `/NURSING`, `/SHRIM`), creating isolated silos where HTML and CSS were mixed together.
* **The Problem:** This violates the **Separation of Concerns**. It made the project impossible to scale without duplicating code.
* **My Standard Today:** I utilize a clean, tiered architecture:
    * `/assets` (Images, Fonts)
    * `/css` (Global Styles & Modules)
    * `/js` (Scripts)
    * `/pages` (Views)

### 3. The "DRY" Principle (Don't Repeat Yourself)
* **The Freshman Mistake:** I created separate CSS files for every single page (`Nursing_Css.css`, `Medtech_Css.css`), often copy-pasting the same navbar styles and color codes 20 times.
* **The Problem:** Changing the website's main color would require editing 20+ files manually. Technical debt was high.
* **My Standard Today:** I implement **Global CSS Variables (`:root`)** for theming and use utility classes or SASS to maintain design tokens in one central location.

### 4. Semantic HTML
* **The Freshman Mistake:** The layout relies heavily on generic `<div>` tags and lacks semantic markers like `<header>`, `<main>`, or `<article>`.
* **The Problem:** This hurts Accessibility (Screen Readers) and SEO rankings.
* **My Standard Today:** I prioritize semantic document structure to ensure my applications are accessible and discoverable.

---

## 🛠️ Tech Stack (At the time)
* **HTML5** (Non-semantic)
* **CSS3** (No pre-processors)
* **JavaScript** (Vanilla DOM manipulation/No frameworks involved)

---

## 🚀 View My Current Work
To see how I apply **Industry-Standard** practices, clean architecture, and optimized algorithms today, please visit my main portfolio or check out my latest repositories:

* **https://github.com/JamesIan-Bayonas/dormfix.git** - *Modern Architecture & Clean Code*

