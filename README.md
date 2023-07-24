# tailwind-css

## Taiwlind CSS Install and Projects Building

```
npm init -y
```
```
npm install -D tailwindcss postcss autoprefixer vite
```
```
npx tailwindcss init -p
```

## Change tailwind.config.js
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ['*'],
  darkMode: 'media',
  darkMode: 'class',
  theme: {
    extend: {},
  },
  plugins: [],
}
```
##add script packege.json file
```
  "scripts": {
    "start": "vite",
    "build": "tailwindcss -i style.css -o ./css/style.min.css --minify",
    "dev": "vite build"
  },
```
npm init -y
```
