# NS Solutions

**Beautiful Websites & MERN Development**

NS Solutions is a professional web development agency template built with [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/), and [Tailwind CSS](https://tailwindcss.com/). It features a modern, responsive landing page for agencies or freelancers specializing in custom websites and MERN stack applications.

## Features

- ⚡ Lightning-fast Vite + React + TypeScript setup
- 🎨 Beautiful, responsive design with Tailwind CSS
- 🖼️ Portfolio, Services, Process, Team, and Testimonials sections
- 📱 Mobile-friendly navigation and layout
- 📦 Ready-to-use contact form UI
- 🌙 Modern icons via [lucide-react](https://lucide.dev/)
- 🧑‍💻 Clean, maintainable code structure

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or newer recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd project
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

4. **Open in your browser:**
   Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

### Building for Production

```sh
npm run build
# or
yarn build
```

The output will be in the `dist/` directory.

### Linting

```sh
npm run lint
# or
yarn lint
```

## Project Structure

- [`src/App.tsx`](src/App.tsx): Main application component with all sections.
- [`src/main.tsx`](src/main.tsx): Entry point.
- [`src/index.css`](src/index.css): Tailwind CSS imports.
- [`index.html`](index.html): HTML template.
- [`vite.config.ts`](vite.config.ts): Vite configuration.
- [`tailwind.config.js`](tailwind.config.js): Tailwind CSS configuration.
- [`postcss.config.js`](postcss.config.js): PostCSS configuration.
- [`tsconfig.*.json`](tsconfig.app.json): TypeScript configuration.

## Customization

- **Content:** Edit [`src/App.tsx`](src/App.tsx) to update sections, images, and text.
- **Branding:** Change colors in [`tailwind.config.js`](tailwind.config.js) or Tailwind classes.
- **Icons:** Uses [lucide-react](https://lucide.dev/) for scalable vector icons.

## License

This project is for educational and demonstration purposes. For commercial use, please customize and review all dependencies and assets.

---

Made with ❤️ using React, TypeScript, and Tailwind
