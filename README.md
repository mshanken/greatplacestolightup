# Great Places to Light Up

A new promotional site.

## Deploying the gh-pages branch
``` npm run gh-pages
Commit your changes first
git push origin gh-pages
```

## How it works

All you need to run this project is node js.

To start just run ```npm install``` 

```npm run server``` builds the project in a docker container. Once that's done. Type this URL [http://localhost:9000](http://localhost:9000/) in your browser to check web site.

```npm run browsersync``` starts browser-sync [http://localhost:3000/](http://localhost:3000/) hit ```Ctrl + P and Ctrl + Q``` to detach.

```npm run compile``` compiles served site into static HTML in a folder "www"

```npm run gh-pages```  what this command does is compiled (if not compiled) then drops compiled files into root folder.<br>
**Note:** this comand should be used in ***gh-pages*** branch only.

