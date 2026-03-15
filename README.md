# Oasis_Internship_Task2

# 🧑‍💻 Ritul Ingole — Personal Portfolio

A bold, neobrutalist personal portfolio website built with pure HTML and CSS — developed as **Task 2** of the Oasis Infobyte Web Development Internship.

---


## 📸 Project Overview

This is a fully hand-crafted **personal portfolio website** showcasing my skills, projects, and contact information. It features a neobrutalist design aesthetic — chunky borders, offset box shadows, bold display typography, and structured layout sections — all built without any CSS framework or JavaScript library.

The portfolio is designed to reflect personality and technical identity, not just list information.

---

## 🎨 Design Aesthetic

This portfolio follows a **Neobrutalist** design language:

- 🖤 Warm white background (`#F8F5EF`) with inky black borders and text
- 💛 Yellow (`#FCEE09`) and Red (`#FF3B30`) as primary accent colors
- 📦 Chunky 3px borders with hard offset box shadows (no blur)
- 🔤 **Black Ops One** for display headings + **Space Mono** for UI labels + **DM Sans** for body text
- 🎭 Subtle SVG doodle elements (circle, triangle, X) as fixed background decorations
- 🏷️ Rotated sticker badge, highlight underline effect on name, hover lift on skill tags

---

## 📄 Sections

| Section | Description |
|---|---|
| **Hero** | Full-viewport intro with name, role, availability badge, and CTA buttons |
| **Skills & Tools** | Three-column grid — Frontend, Backend, Learning & Other |
| **About Me** | Personal bio with emoji list and stat cards (Projects, Hackathons, Learning) |
| **Let's Connect** | Contact info (Email, GitHub, LinkedIn) + Contact form |
| **Footer** | Name, nav links, and dynamic copyright year via JS |

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Neobrutalist styling, grid, transitions |
| Google Fonts | Black Ops One, DM Sans, Space Mono |
| Vanilla JS | Dynamic year in footer (`new Date().getFullYear()`) |

---

## 📁 Project Structure

```
personal-portfolio/
│
├── index.html       # Full page structure and content
├── style.css        # All styling, layout, and design system
└── README.md        # Project documentation
```

---

## 🧠 Key Concepts Practiced

- CSS Custom Properties (`--color-*`, `--font-*`) for a consistent design system
- CSS Grid with `auto-fit` and `minmax()` for responsive layouts
- `clamp()` for fluid responsive typography
- Fixed `z-index` stacking for background doodle SVGs
- CSS `::after` pseudo-element for the hand-drawn highlight underline effect
- `scroll-behavior: smooth` + `scrollIntoView()` for in-page navigation
- Offset box shadows without `blur` for the neobrutalist hard-shadow style
- Hover micro-interactions using `transform: translate()` + `box-shadow` change

---

## 🏁 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ritul-Ingole/personal-portfolio.git
   ```

2. **Navigate into the folder**
   ```bash
   cd personal-portfolio
   ```

3. **Open in browser**
   ```bash
   open index.html
   ```

No dependencies, no build tools — just open and run.

---

## 📬 Contact

**Ritul Ingole**
- 📧 ritulmi007@gmail.com
- 💻 [github.com/Ritul-Ingole](https://github.com/Ritul-Ingole)
- 💼 [linkedin.com/in/ritul-ingole-529a58298](https://linkedin.com/in/ritul-ingole-529a58298)

---

## 📌 Internship Context

This project was built as part of the **Oasis Infobyte Web Development Internship — Task 2**.

The task required creating a personal portfolio using HTML and CSS, demonstrating:
- Multi-section page layout and navigation
- Consistent personal branding and design identity
- Skills, projects, and contact information presentation
- Creative use of typography, color, and spacing

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
