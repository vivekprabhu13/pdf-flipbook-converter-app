# 📖 PDF Flipbook Converter

A modern, fast, and privacy-first web application that converts static PDF documents into an interactive 3D double-page flipbook directly in your browser.

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-19-61dafb.svg?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178c6.svg?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38bdf8.svg?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-6-646cff.svg?logo=vite&logoColor=white)

---

## ✨ Features

- **Realistic 3D Page Turning**: Experience realistic double-page spreads powered by `react-pageflip`. Turn pages by clicking or dragging corner edges with realistic shadows.
- **100% Client-Side & Private**: All PDF parsing and rendering happens locally inside your browser using `pdf.js`. No files are uploaded to any server or stored remotely.
- **Centered Header Controls**:
  - **Zoom & Magnification**: Smooth zoom controls (from 50% up to 200%) with centered scaling and auto-scroll capability when magnified.
  - **Quick Page Jump**: Directly jump to any specific page by typing the page number.
  - **Previous & Next Buttons**: Clean navigation buttons placed right in the header bar.
  - **Full Screen Mode**: Seamless full-screen toggle with persistent controls and automatic viewport fit.
  - **New File**: Quick reset button to load a new PDF at any time.
- **Odd-Page Auto Balancing**: Automatically inserts an elegant blank closing page for odd-paged documents, ensuring double-page books close naturally.
- **Drag & Drop Upload**: Fluid drag-and-drop zone with visual feedback for quick document loading.
- **Responsive & Modern Design**: Clean editorial aesthetic built with Tailwind CSS and smooth animations powered by `motion`.

---

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/) + [Vite 6](https://vitejs.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **PDF Engine**: [PDF.js](https://mozilla.github.io/pdf.js/) (`pdfjs-dist`)
- **Flipbook Engine**: [react-pageflip](https://github.com/nodlik/react-pageflip)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Animations**: [Motion](https://motion.dev/)

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18+ recommended)
- `npm`, `pnpm`, or `yarn`

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/pdf-flipbook-converter.git
   cd pdf-flipbook-converter
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

4. **Build for production:**
   ```bash
   npm run build
   ```
   The production-ready assets will be created in the `dist` directory.

---

## 🌐 Deployment Options

### 1. Static Hosting (Vercel, Netlify, Cloudflare Pages, GitHub Pages)
Because this app is completely client-side, the output of `npm run build` (`dist/`) can be deployed to any static host:
- **Vercel / Netlify**: Connect your GitHub repository and set build command to `npm run build` and output directory to `dist`.
- **GitHub Pages**: Deploy the `dist` folder using `gh-pages` or GitHub Actions.

### 2. Google Apps Script Web App
You can also run this as a standalone Google Apps Script web app (using `Code.gs` and `index.html`) with no servers or cloud hosting needed.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/<your-username>/pdf-flipbook-converter/issues).

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
