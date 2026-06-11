# 🚀 Muhammad Abdullah Saif — Personal Portfolio Website

A modern, fully responsive personal portfolio website built with **HTML, CSS, and vanilla JavaScript**. Features a dark-themed UI with smooth animations, particle effects, and a working contact form.

---

## 📸 Preview

> Live demo link here(https://muhammadabdullahsaif49.github.io/my-portfolio/)

---

## ✨ Features

- **Animated Hero Section** — Typing effect, particle canvas background, and animated counter stats
- **Custom Cursor** — Stylish dual-layer cursor with follower effect
- **Scroll Animations** — Powered by AOS (Animate On Scroll) library
- **Skills Section** — Animated progress bars triggered on scroll
- **Portfolio Filter** — Filter projects by category with smooth transitions
- **Services Section** — Clean card layout showcasing offered services
- **Contact Form** — Functional email sending via **EmailJS** (no backend needed)
- **Sticky Navbar** — Active section highlighting + scroll-aware styling
- **Scroll To Top** — Button appears after scrolling 400px
- **Fully Responsive** — Mobile-first design using Bootstrap 5 grid

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3, Bootstrap 5.3 |
| Scripting | Vanilla JavaScript (ES6+) |
| Animations | AOS v2.3.4 |
| Icons | Font Awesome 6.4 |
| Fonts | Space Grotesk, Syne, JetBrains Mono (Google Fonts) |
| Email | EmailJS Browser SDK v4 |

---

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file (all sections included)
├── style.css           # Custom styles + CSS variables
└── README.md
```

---

## ⚙️ Setup & Usage

### 1. Clone the repository

```bash
git clone https://github.com/muhammadabdullahsaif49/your-repo-name.git
cd your-repo-name
```

### 2. Open locally

Just open `index.html` in your browser — no build step needed.

```bash
# Or with VS Code Live Server
code .
```

### 3. Configure EmailJS (Contact Form)

To enable the contact form to actually send emails:

1. Sign up for free at [emailjs.com](https://www.emailjs.com)
2. Create a **Gmail service** → copy your **Service ID**
3. Create an **Email Template** using these variables:
   - `{{from_name}}`, `{{from_email}}`, `{{subject}}`, `{{message}}`
4. Copy your **Public Key** from the Account tab
5. Update these values in `index.html`:

```javascript
const EMAILJS_PUBLIC_KEY  = 'YOUR_PUBLIC_KEY';
const EMAILJS_SERVICE_ID  = 'YOUR_SERVICE_ID';
const EMAILJS_TEMPLATE_ID = 'YOUR_TEMPLATE_ID';
```

### 4. Add Your Profile Photo

Replace the image path in the hero section with your own photo:

```html
<img src="your-photo.jpg" alt="Muhammad Abdullah Saif" class="profile-img">
```

---

## 🎨 Customization

All colors are defined as CSS variables in `style.css` for easy theming:

```css
:root {
    --primary:   #3B82F6;   /* Blue */
    --secondary: #8B5CF6;   /* Purple */
    --accent:    #06B6D4;   /* Cyan */
    --dark:      #0B1120;
    --darker:    #060C18;
}
```

---

## 📄 Sections

1. **Home** — Hero with typing effect and stats
2. **About** — Bio, personal info, and downloadable CV
3. **Skills** — Animated skill bars (Frontend, Backend, Tools)
4. **Services** — What I offer
5. **Portfolio** — Filterable project cards
6. **Contact** — EmailJS-powered contact form

---

## 📬 Contact

**Muhammad Abdullah Saif**
- 📧 abdullahch556677@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/your-profile) *(update link)*
- 🐙 [GitHub](https://github.com/muhammadabdullahsaif49)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
