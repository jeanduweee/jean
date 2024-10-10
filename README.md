
  "name": "altstore-github",
  "version": "1.1.1",
  "description": "Generate AltStore repository from Github releases",
  "main": "index.js",
  "scripts": {
    "prestart": "if [ ! -d node_modules ]; then npm install; fi",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "bin": {
    "altstore-github": "index.js"
  },
  "keywords": [
    "altstore",
    "github"
  ],
  "author": "osy",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/osy/altstore-github/issues"
  },
  "homepage": "https://github.com/osy/altstore-github",
  "repository": {
    "type": "git",
    "url": "https://github.com/osy/altstore-github.git"
  },
  "dependencies": {
    "@octokit/rest": "^17.1.3",
    "convict": "^5.2.0",
    "express": "^4.17.1"
  }
