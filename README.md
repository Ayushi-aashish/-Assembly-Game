
Capstone Project
This is a React 19 application bootstrapped with Vite for ultra-fast development, and includes ESLint integration and hot module replacement. It serves as a capstone or final project built with a modern frontend toolchain.

🚀 Features
⚛️ React 19 (with JSX and HMR support)

⚡️ Vite for fast build and dev server

🎉 UI Effects using react-confetti

✅ ESLint configured with React hooks and refresh plugins

🧱 Modular and maintainable project structure

📦 Project Structure
php
Copy
Edit
capstone/
├── public/             # Static assets
├── src/                # Source code
│   ├── components/     # Reusable components
│   ├── App.jsx         # Main app component
│   └── main.jsx        # React DOM entry
├── index.html          # HTML template
├── package.json        # Project metadata and scripts
└── vite.config.js      # Vite configuration
🛠️ Installation
Make sure you have Node.js ≥ 18 installed.

bash
Copy
Edit
# Clone the repository
git clone <repo-url>
cd capstone

# Install dependencies
npm install
🧪 Available Scripts
Script	Description
npm run dev	Start the development server
npm run build	Build the app for production
npm run preview	Preview the production build
npm run lint	Lint the code using ESLint

✨ Dependencies
react

react-dom

clsx — utility for conditionally joining classNames

react-confetti — for celebration effects

🧪 Dev Dependencies
vite

eslint, eslint-plugin-react-hooks, eslint-plugin-react-refresh

@vitejs/plugin-react

@types/react, @types/react-dom (for future TypeScript compatibility)

📄 License
MIT
