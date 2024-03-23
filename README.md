step 1: npm create vite@latest ./ -- --template react
step 2: install tailwind css:
->npm install -D tailwindcss postcss autoprefixer
->npx tailwindcss init -p
-> import this code in tailwind.config.js:
--> export default {
content: [
"./index.html",
"./src/**/*.{js,ts,jsx,tsx}",
],
theme: {
extend: {},
},
plugins: [],
}
step 3: install GSAP:
-> npm install gsap @gsap/react
step 4: install Three.js:
-> npm install three @react-three/drei @react-three/fiber

Notes:
-Github repository that turns GLTFs into JSX : https://github.com/pmndrs/gltfjsx
So just drag and drop the 3D model

-After implementing the Lights.jsx and IPphone.jsx, go to .eslintrc.cjs and add "@react-three" to plugins

-Open Sentry on your browser and follow the steps of installations after developing your application and before running npm build.
Make sure to edit the properties in main.jsx and edit App.jsx
This is to check the performance of your application
