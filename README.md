# install github pages to your project:
npm install gh-pages --save-dev

# add homepage and your username and repo name in package.json file:
"homepage": "https://KashyapAnkur.github.io/reactpipeline",

# in sripts add command:
"predeploy": "npm run build",
"deploy": "gh-pages -d build"

