# CSS-Tailwind
<a href="https://tailwindcss.com/docs/installation/using-postcss">Source</a>

#Commands For CSS-Tailwind Setup
<ol>
<li>
npm init
npm install -D tailwindcss postcss autoprefixer
npm install vite[ server start which automatically refreshes]
npx tailwindcss init
</li>

config file add "*"
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
}

//change package.json
{
  "name": "css-tailwind",
  "version": "1.0.0",
  "description": "<a href=\"https://tailwindcss.com/docs/installation/using-postcss\">Source</a>",
  "main": "index.js",
  "scripts": {
    "start": "vite"
  },
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "autoprefixer": "^10.4.14",
    "postcss": "^8.4.23",
    "tailwindcss": "^3.3.2"
  },
  "dependencies": {
    "vite": "^4.3.8"
  }
}

<ol>