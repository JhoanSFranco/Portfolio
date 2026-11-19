# Personal Portfolio - Jhoan Sebastián Franco Ruiz

Personal portfolio website built with React + TypeScript + Vite.

🔗 **Live site:** [portafolio-livid-psi-25.vercel.app](https://portafolio-livid-psi-25.vercel.app/)

## 🚀 Tech Stack

**Frontend:** React 18, TypeScript, Vite, Bootstrap 5, React Bootstrap, CSS3  
**Contact form:** EmailJS, SweetAlert2  
**Other:** i18n (Spanish / English / French), React Context API

## 📋 Features

- Modern, responsive design
- Multi-language support (ES / EN / FR)
- Contact form with automatic sending and confirmation
- Smooth scrolling between sections
- Downloadable CV in each language
- Social media integration

## ⚙️ Getting Started

```bash
npm install        # Install dependencies
npm run dev        # Start the development server
npm run build      # Production build
```

## 📁 Project Structure

```
src/
├── components/        # React components
│   ├── common/        # Reusable components (Button, CardProjects, etc.)
│   ├── layout/        # Layout (Header, Footer, Navigation)
│   └── sections/      # Page sections (MainBanner, About, Services, Projects, Contact)
├── hooks/             # Custom hooks
├── context/           # React Context (LanguageContext)
├── data/              # Content and translations
├── styles/            # Global CSS and variables
├── types/             # TypeScript types
└── utils/             # Helpers and validators
```

## 🎨 Customization

**Personal data:** `src/data/personalData.ts`  
**Translations:** `src/data/translations.ts`  
**Styles / colors:** `src/styles/variables.css`  
**CVs:** Add PDFs to `public/assets/resumes/`, named by language

---

**Developed by Jhoan Sebastián Franco Ruiz**
