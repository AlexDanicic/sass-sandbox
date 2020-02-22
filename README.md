SASS Practice
*** Syntactically Awesome StyleSheets ***
<br>
Go to nodejs.org and install it...lts or current
<br>
in terminal check: npm --version
<br>
"npm init -y" to create package.json
<br>
npm install node-sass
<br>
inside package json repair the scripts: to--> "sass": "node-sass -w scss/ -o dist/css/ --recursive"
<br>
create a folder "scss" and inside that create a file "main.scss"
<br>
create a folder "dist" and here will go the compiled css
<br>
in terminal run: "npm run sass"
<br>
in dist create index.html and link to css/main.css
