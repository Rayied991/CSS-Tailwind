<h1><b> CSS-Tailwind-Utility First Classes</b><h1>
<a href="https://tailwindcss.com/docs/installation/using-postcss">Source</a>
<h1>Why Use Tailwind CSS</h1>
<ul>
<li>No reinventing  of class names required</li>
<li>CSS doesn't  grow with your  html and designs</li>
<li>When you make a change ,  no risk of breaking  existing templates!</li>
<li>Will this makes sites slow? -> No!</li>
<li>Responsiveness!</li>
</ul>

<br>
<h1>Commands For CSS-Tailwind Setup for Development<h1>
<ol>
<li>
npm init</li>
<li>npm install -D tailwindcss postcss autoprefixer</li>
<li>npm install vite[ server start which automatically refreshes]</li>
<li>npx tailwindcss init
</li>

<br>
<h1>Commands For CSS-Tailwind Setup for Production<h1>
<p> To Setup  tailwind css Run-
<ol>
<li>npm init-y //This initializes the directory as  a nodejs  Project</li>
<li>npm install-D Tailwind  postcss autoprefixer vite //installs required packages</li>
<li>npx tailwindcss init -p</li>
<li>Create a css file "input.css", add it to your html  and edit this contents:<br>
      @tailwind base;<br>
      @tailwind components;<br>
      @tailwind utilities;<br>
      </li>
<li>In your tailwind .config.js file replace content:[], with content:["*"],</li>      
<li>Add "start:""vite" to your scripts in Package.json</li>      
<li>Run npm run start command to start a dev server</li>      
</ol>

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