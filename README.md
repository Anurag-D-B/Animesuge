# Animesuge clone using Tailwindcss
Steps:
1.npm init -y
2.npm install -D tailwindcss@3 postcss autoprefixer vite
3.npx tailwindcss init -p
4.Open package.json change script to
    "start": "vite"
5.In style.css add:
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
6.Open tailwind.config.js change:
    content: ["*"],
7.npm run dev