# File creator with CLI

This project use to create select name and extension file in current directory that execute script.

## Instructions

### Install

**Global**
```
npm install -g mugan86/file-creator-cli
```
**Local**
```
npm install mugan86/file-creator-cli
```
* Add in **package.json**
```
...
"scripts": {
    "creator": "./node_modules/.bin/creator"
},
...
```
### Use
```
creator             // If install with global
npm run creator     //If install with local
   _   _   _   _     _   _   _   _   _   _   _     _   _   _   _     _   _   _
  / \ / \ / \ / \   / \ / \ / \ / \ / \ / \ / \   / \ / \ / \ / \   / \ / \ / \
 ( F | i | l | e ) ( c | r | e | a | t | o | r ) ( w | i | t | h ) ( C | L | I )
  \_/ \_/ \_/ \_/   \_/ \_/ \_/ \_/ \_/ \_/ \_/   \_/ \_/ \_/ \_/   \_/ \_/ \_/
  What is the name of the file without extension? example
? What is the file extension?
  .java
  .kt
  .txt
❯ .xml
  .rb
  .js
  .php
  .css
  .ts
Well done! File created at /cli-node/example.xml
```