# react-app-gh-pages
Deployed a React App to GitHub-Pages. Used the npm module 'gh-pages'

Project URL -> <https://leanseverino1022.github.io/react-app-gh-pages/>

Steps Summary: 
1. use create-react-app to create your app
2. install gh-pages as a dev-dependency
3. In package.json file add properties
``` "homepage: http://leanseverino1022.github.io/react-app-gh-pages"``` . then locate “scripts” add these lines of code: 
```
{
   ...
   "predeploy": "yarn run build",
   "deploy": "gh-pages -d build",
   ...
}
```
4. In the terminal, run this command ```npm run deploy```  to deploy it to GitHub Pages.
