# js-dev-env
Buildingf a JavaScript Development Environment

Create github repository
Editor
.editorconfig
Install node and npm
Add package.json
npm install

Install Node Security Platform -> npm install -g nsp
nsp check

Set Up Development Web Server -> create buildScripts/srcServer.js (using express)
Create src/index.html

Sharing Work-in-progress -> localtunnel, ngrok, Surge, now
Sharing with using localtunnel -> lt --port 3000	or	lt --port 3000 --subdomain cory

Automation -> npm Scripts 
	npm start -s // -s silence

Transpiling -> set up Babel
	create .babelrc

Bundling -> Webpack
	create webpack.config.dev.js
	change srcServer.js
