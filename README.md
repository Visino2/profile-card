# 🚀 Frontend Wizards — Stage 0 & 1: Testable Multi-Page Profile Card  

Welcome to my **Stage 0 and Stage 1 submission** for **Frontend Wizards**! 🎉  
This project is a responsive, accessible **Profile Card application** built with **HTML**, **TailwindCSS**, and **vanilla JavaScript**.  
It evolves from a single testable card into a multi-page app with an **About Me** and **Contact Us** page.  

---

## 🧠 Overview  

**Goal:**  
Create a semantic, accessible, and responsive profile card with testable attributes — then extend it to include new pages that demonstrate reflection and form validation.  

**Live Demo:** [👉 View on Netlify](https://glittering-paletas-47d1c6.netlify.app/)  
**Repository:** [📦 View on GitHub](https://github.com/Visino2/profile-card)

---

## 🧩 Features Overview  

### 🏠 Home Page (Stage 0)  
| Feature | Requirement Met | Description |
|----------|----------------|--------------|
| `data-testid="test-profile-card"` | ✅ | Root container |
| `test-user-name` | ✅ | Displays user’s name |
| `test-user-bio` | ✅ | Short biography text |
| `test-user-time` | ✅ | Live time using `Date.now()` |
| `test-user-avatar` | ✅ | Avatar with descriptive alt text |
| `test-user-social-links` | ✅ | Social media links with `target="_blank"` |
| `test-user-hobbies` | ✅ | List of hobbies |
| `test-user-dislikes` | ✅ | List of dislikes |

---

### 👤 About Me Page (Stage 1)  
A reflective page that includes personal thoughts and program goals.  
**Data-testids used:**  
- `test-about-bio`  
- `test-about-goals`  
- `test-about-confidence`  
- `test-about-future-note`  
- `test-about-extra`  

---

### 📧 Contact Us Page (Stage 1)  
A fully accessible contact form with live validation and success message.  
**Data-testids used:**  
- `test-contact-name`  
- `test-contact-email`  
- `test-contact-subject`  
- `test-contact-message`  
- `test-contact-submit`  
- `test-contact-error-*`  
- `test-contact-success`  

**Validation Rules:**  
- All fields are required  
- Email must be valid (`name@example.com`)  
- Message must be at least 10 characters  
- Success message appears only after valid submission  

---

## 🧰 Tech Stack  

- **HTML5** → Semantic & accessible structure  
- **TailwindCSS** → Modern responsive UI  
- **Vanilla JavaScript** → Live time + Form validation  
- **Flexbox & Grid** → Clean layout design  
- **Netlify / GitHub Pages** → Hosting  

---

## 💡 Bio Preview  

> I’m a frontend developer passionate about creating accessible and performant web and mobile experiences.  
> I love solving problems and taking on new challenges.  
> When I’m not coding, I’m watching soccer games or learning new web technologies.  

---

## 🎨 Theme & Design  

The design uses a **bright orange accent** over a **dark and white background**, ensuring good contrast and readability.  
Animations are minimal and non-distracting, powered by Tailwind’s utility classes.  

---

## 📱 Responsiveness  

| Screen Size | Layout Behavior |
|--------------|----------------|
| **Mobile** | Components stack vertically; centered layout |
| **Tablet** | Two-column layout (avatar ↔ content) |
| **Desktop** | Spacious layout with balanced typography |

---

## 💬 Reflection  

> Completing this project helped me strengthen my understanding of **semantic HTML**, **accessibility**, and **form validation**.  
> I also learned how to maintain **consistent design and navigation** across multiple pages while keeping the code modular and readable.  

---

## ⚙️ Installation & Setup (Local)  

1. Clone the repository  
   ```bash
   git clone https://github.com/Visino2/profile-card.git
   cd profile-card
