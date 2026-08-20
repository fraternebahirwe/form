# 📋 Responsive Survey Form

> An accessible, fully responsive user feedback and survey form built with semantic HTML5 form controls, input validations, custom select dropdowns, radio groups, and multi-select checkboxes.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![freeCodeCamp](https://img.shields.io/badge/freeCodeCamp-0A0A23?style=for-the-badge&logo=freecodecamp&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## ✨ Form Sections & Inputs

- **Personal Information Controls:**
  - **Name:** Text input with `autocomplete="name"` and strict `required` state.
  - **Email:** Native email validation field (`type="email"`).
  - **Age:** Numeric field with `min="13"` and `max="100"` bounds checking.
- **Role Selector:** Accessible dropdown (`<select>`) with disabled placeholder defaults (`Student`, `Worker`, `Unemployed`).
- **Recommendation Group:** Semantically grouped radio inputs (`<fieldset>`) with pre-checked option handling (`Yes`, `No`, `Maybe`).
- **Languages & Frameworks Checklist:** Multi-selection checkboxes covering C, C++, C#, Java, Python, JavaScript, React, Angular, Django, and Spring.
- **Feedback & Comments Area:** Multi-line `<textarea>` input for additional suggestions.
- **Accessibility Integration:** Engineered using `<label for="...">` associations, semantic `<fieldset>`/`<legend>` groupings, and clean structural containers.

---

## 🛠️ Built With

- **HTML5:** Native validation attributes (`required`, `min`, `max`, `type="email"`), semantic tags, and layout elements.
- **CSS3:** Custom form styling, responsive layouts, and container constraints (`style.css`).
- **JavaScript (ES6+):** Form interaction behavior, submission handling, or client-side feedback logic (`script.js`).

---

## 📂 Repository Structure

```text
.
├── index.html       # Primary HTML form structure
├── style.css        # Stylesheet for card layout, fieldsets, and controls
└── script.js        # JavaScript logic for form validation and user interactions
