# Vite ReactTS Project Template
This is a React + TypeScript project built using **Vite**. It includes modern libraries for state management, routing, styling, and developer tools.

## 📖 Documentation
* [Vite Configuration Guide](.docs/VITE.md) - Details on our build setup.



## Project Setup
**Scripts:**
- `npm run dev` – Runs the development server using Vite.
- `npm run build` – Compiles TypeScript and builds the production bundle.
- `npm run lint` – Runs ESLint for code quality checks.
- `npm run preview` – Previews the production build.

## Recommended Usage
1. Update dependencies:
```bash
npx npm-check-updates -u
```
2. Install dependencies:
```bash
npm install
```


### Core Libraries
- **class-variance-authority** – Helps manage complex Tailwind CSS class variants.
- **clsx** – Utility for conditionally joining classNames.
- **react** & **react-dom** – The core React library and DOM renderer.
- **react-router-dom** – Routing library for React apps.
- **tailwind-merge** – Merges Tailwind CSS classes intelligently.
- **tanstack/react-query** – Data fetching and caching library.
- **tanstack/react-query-devtools** – Devtools for React Query.
- **zustand** – Lightweight state management library.


## DevDependencies
These packages are used for development, type checking, linting, and build tooling:

### Build & Tooling
- **types/node**, **types/react**, **types/react-dom** – Type definitions for Node and React.
- **typescript** – TypeScript language support.
- **vite** – Fast frontend build tool.
- **vitejs/plugin-react** – Enables React support in Vite.

### Styling
- **tailwindcss** – Utility-first CSS framework.
- **tailwindcss/vite** – Tailwind plugin for Vite.
- **tw-animate-css** – Prebuilt CSS animations for Tailwind.

### Linting & Code Quality
- **eslint** – Linting utility for JavaScript/TypeScript.
- **eslint/js** – ESLint core rules for JavaScript.
- **eslint-plugin-react-hooks** – Enforces best practices for React Hooks.
- **eslint-plugin-react-refresh** – Supports React Fast Refresh in ESLint.
- **globals** – Provides predefined global variables for linting.
- **typescript-eslint** – ESLint plugin for TypeScript.
