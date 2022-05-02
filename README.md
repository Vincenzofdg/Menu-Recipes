## How I created and deployed this app

1. npx create-react-app mytunes
2. npm install gh-pages --save-dev
3. npm install react-router-dom --save
4. `package.json`:
	- "homepage": "https://Vincenzofdg.github.io/Menu-Recipes",
	- "predeploy": "npm run build",
	- "deploy": "gh-pages -d build",
5. On index.js importe `BrowserRouter` and use as `<BrowserRouter basename={process.env.PUBLIC_URL}><BrowserRouter/>`

## Knowledges:

 - All React Knowledges.

## Preview:

![image](preview.gif)