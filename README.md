# tailwind-boilerplate-using-postcss-with-vite

Tailwind CSS Installation
Lets generate a package.json file
npm init -y
Lets install tailwind with dev Dependencies(-D), All modern Technology use
postcss
npm install -D tailwindcss postcss autoprefixer vite
Lets generate a config file ⇒ tailwind.config.js file
npx tailwindcss init -p
Configure your template paths
Add the paths to all of your template files in your  tailwind.config.js file.
/** @type {import('tailwindcss').Config} */
module.exports = {
content: ['*'],
theme: {
extend: {},
},
plugins: [],
}
Tailwind CSS Installation 2
Add the Tailwind directives to your CSS
Add the  @tailwind directives for each of Tailwind’s layers to your main CSS file.
/**
* This injects Tailwind's base styles and any base styles registered by
* plugins.
*/
@tailwind base;
/**
* This injects Tailwind's component classes and any component classes
* registered by plugins.
*/
@tailwind components;
/**
* This injects Tailwind's utility classes and any utility classes registered
* by plugins.
*/
@tailwind utilities;


NB: "npm run start" this commend use for start vite local server. Just simple 😊. TNX 
