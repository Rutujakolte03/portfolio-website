# Rutuja Kolte — Portfolio Website

This is my personal portfolio website built with **Next.js**. It showcases my projects, experience, technical skills, education, and certifications. The site is fully customizable via a JSON-based content management structure.

## 🔧 Features

- JSON-based content updates (`data/portfolio-data.json`)
- Modular project data management (`lib/projects.ts`)
- Clean, responsive, and accessible UI
- Built with modern technologies: Next.js, TypeScript, Tailwind CSS
- SEO-optimized and easily deployable on platforms like Vercel

## 📁 Folder Structure

- `data/portfolio-data.json` – Main content file for personal info, about, experience, etc.
- `lib/projects.ts` – Project descriptions, tech stack, gallery, and links.
- `public/` – Assets like profile pictures, icons, project images.
- `components/` – Modular React components used across pages.
- `pages/` – Main pages powered by Next.js routing.

## 🧩 How to Update Content

All portfolio content can be updated easily without modifying the code:
- Edit personal info, bio, skills, experience, etc. in `data/portfolio-data.json`
- Add or update projects in `lib/projects.ts`
- Add images to the `public/` folder and reference them in your data files

## 🚀 Getting Started

To run this project locally:

```bash
git clone https://github.com/yourusername/your-portfolio.git
cd your-portfolio
npm install
npm run dev
