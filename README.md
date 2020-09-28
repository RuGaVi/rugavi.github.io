# rugavi.github.io
Steps:
1. npx create-react-app rugavi.github.io
2. cd rugavi.github.io
3. npm start
4. npm install --save gh-pages
5. add following line to package.json
"scripts": {
+   "predeploy": "npm run build",
+   "deploy": "gh-pages -d build",
    "start": "react-scripts start",
    "build": "react-scripts build",
6. npm run deploy
7. change the setting for source to gh-pages branch
