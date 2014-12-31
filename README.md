# Git Markdown Editor using Node Webkit

## Prerequisite
  - Install [Node JS](http://nodejs.org/)

## How to?

### Run
  - Download/Clone this project
  - Install [Node WebKit](//github.com/rogerwang/node-webkit)
    - Command: `npm install nodewebkit` - or - for global install `npm install nodewebkit -g` ( `-g` stands for global)
  - Install [CSS](//github.com/reworkcss/css)
    - Command: `npm install css`
  - Install [jQuery](//github.com/jquery/jquery)
    - Command: `npm install jquery`
  - Install [Mark Down](//github.com/evilstreak/markdown-js)
    - Command: `npm install markdown`
  - Create a `package.json` file in this folder.
  
    Code:
    ```javascript
     {
        "name": "git-markdown-editor-nodewebkit"
      , "main": "index.html"
      , "description": "Git Markdown Editor NodeWebkit"
      , "scripts": {
        "start": "nodewebkit"
      }
      , "window": {
         "toolbar": false
       , "width": 800
       , "height": 800
      }
     }
    ```
  - Run `npm start`
