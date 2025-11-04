# Frontend Developer Portfolio

Welcome to my **Frontend Developer Portfolio**! This is a personal portfolio website built to showcase my projects, skills, experience, and contact information.

---

## 🚀 Features

- **Smooth Loading Screen** – A visually appealing initial loader for a better user experience.
- **Responsive Navigation** – Includes both desktop navbar and mobile menu with toggle functionality.
- **Sections Included**:
  - **Home** – Hero section with an introduction.
  - **About** – Brief about me and my skills.
  - **Projects** – Showcase of personal and professional projects.
  - **Contact** – Contact form integrated for direct messages.
- **Dynamic & Interactive UI** – Smooth transitions, animations, and responsive design using Tailwind CSS.
- **Modern Design** – Dark theme with gradients and intuitive layout.

---

## 🛠️ Tech Stack

- **Frontend Framework:** React 18
- **Styling:** Tailwind CSS
- **Build Tool:** Vite
- **Email Integration:** EmailJS for contact form
- **Deployment:** GitHub Pages

---

## 📂 Project Structure

```

src/
├── components/
│   ├── LoadingScreen.jsx
│   ├── Navbar.jsx
│   ├── MobileMenu.jsx
│   └── sections/
│       ├── Home.jsx
│       ├── About.jsx
│       ├── Projects.jsx
│       └── Contact.jsx
├── App.jsx
└── index.css

```

- `App.jsx` – Main component that handles loading state and renders all sections.
- `components/` – Reusable components including Navbar, MobileMenu, and LoadingScreen.
- `sections/` – Individual sections for portfolio content.
- `index.css` – Global styles using Tailwind CSS.

---

## ⚡ Getting Started

1. **Clone the repository**

```bash
git clone ""
cd portfolio
```

2. **Install dependencies**

```bash
npm install
```

3. **Run in development mode**

```bash
npm run dev
```

4. **Build for production**

```bash
npm run build
```

5. **Preview production build**

```bash
npm run preview
```

6. **Deploy to GitHub Pages**

```bash
npm run deploy
```

---

## 🎨 Customization

- Modify **Home**, **About**, **Projects**, and **Contact** sections in `src/components/sections/` to add your personal information and projects.
- Update **Navbar** and **MobileMenu** to include your preferred links.
- Customize colors, fonts, and layouts using Tailwind CSS in `index.css`.
