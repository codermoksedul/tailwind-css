# tailwind-css

## Taiwlind CSS Install and Projects Building

```
npm init -y
yarn init -y
```
```
npm install -D tailwindcss postcss autoprefixer vite
yarn add -D tailwindcss postcss autoprefixer vite
```
```
npx tailwindcss init -p
```
### Add this code CSS file
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Change tailwind.config.js
#### Add * from content
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ['*'],
  darkMode: 'class',
  theme: {
    extend: {},
  },
  plugins: [],
}
```
### Add script packege.json file
```
  "scripts": {
    "start": "vite",
    "develop": "tailwindcss -i style.css -o ./css/style.min.css --minify",
    "build": "vite build"
  },
```
### Run Projects from vit
```
npm run start
```

### Build Projcts Form Vite
```
npm run build
```
### Build Custom CSS Folder
```
npm run develop
```
