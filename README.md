# Ionic Vue Boilerplate

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Ionic](https://img.shields.io/badge/Ionic-8.0.0-3880FF.svg)](https://ionicframework.com/)
[![Vue](https://img.shields.io/badge/Vue-3.3-4FC08D.svg)](https://vuejs.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.1-38B2AC.svg)](https://tailwindcss.com/)
[![Pinia](https://img.shields.io/badge/Pinia-3.0-yellow.svg)](https://pinia.vuejs.org/)

A clean, ready-to-use boilerplate combining the power of Ionic Framework with Vue 3, Tailwind CSS, and Pinia state management.

![Ionic Vue Boilerplate](https://via.placeholder.com/800x400?text=Ionic+Vue+Boilerplate)

## 🚀 Features

- ⚡️ [Ionic 8](https://ionicframework.com/) - Mobile UI toolkit
- 🖖 [Vue 3](https://v3.vuejs.org/) with Composition API
- 🏗️ [TypeScript](https://www.typescriptlang.org/) - Type safety
- 📦 [Pinia](https://pinia.vuejs.org/) - Modern Vue store with persistence support
- 🎨 [Tailwind CSS 4](https://tailwindcss.com/) - Utility-first CSS framework
- 📱 [Capacitor 7](https://capacitorjs.com/) - Native app development
- 🧪 Testing setup with [Vitest](https://vitest.dev/) and [Cypress](https://www.cypress.io/)
- 📝 [ESLint](https://eslint.org/) - Code quality
- 🔥 [Vite](https://vitejs.dev/) - Fast build tooling

## 📋 Prerequisites

- Node.js (>= 18.x)
- npm (>= 9.x) or yarn

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/ArnarValur/ionic-vue-boilerplate.git
cd ionic-vue-boilerplate

# Install dependencies
npm install
# or
yarn

# Start development server
npm run dev
# or
yarn dev
```

Your app will be available at: http://localhost:5173

## 📝 Available Scripts

```bash
# Development
npm run dev          # Start dev server

# Production
npm run build        # Build for production
npm run preview      # Preview production build

# Testing
npm run test:unit    # Run unit tests
npm run test:e2e     # Run end-to-end tests

# Linting
npm run lint         # Run ESLint
```

## 📁 Project Structure

```
ionic-vue-boilerplate/
├── public/              # Static assets
├── src/
│   ├── css/             # Global CSS including Tailwind
│   ├── router/          # Vue Router configuration
│   ├── theme/           # Ionic theming variables
│   ├── views/           # Page components
│   ├── App.vue          # Main app component
│   └── main.ts          # App entry point
├── tests/               # Test files
├── capacitor.config.ts  # Capacitor configuration
├── ionic.config.json    # Ionic configuration
├── tailwind.config.ts   # Tailwind CSS configuration
├── vite.config.ts       # Vite configuration
└── package.json         # Project dependencies
```

## 🔒 Environment Variables

Create a `.env` file in the root directory of your project to store environment variables:

```
VITE_API_URL=your_api_url_here
```

## 📱 Mobile Development

```bash
# Add mobile platforms
npx cap add ios
npx cap add android

# Build and synchronize with Capacitor
npm run build
npx cap sync

# Open native IDEs
npx cap open ios
npx cap open android
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is [MIT licensed](LICENSE).

## 👨‍💻 Author

- Arnar Valur
- GitHub: [@arnarvalur](https://github.com/ArnarValur)

---

Made with ❤️ using Ionic, Vue, Tailwind CSS, and Pinia.
