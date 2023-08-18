# Vite Tutorial
Sing-a-long with "Learn Vite - Frontend Build Tool Course" by @khattakdev of freeCodeCamp.org  
ref: https://www.youtube.com/watch?v=VAeRhmpcWEQ

# Setup
```shell
$> mkdir vite-prj
$> cd vite-prj
$> npm install --save-dev vite
$> git init .
```
Add scripts to the composer.json file:
```json
{
  "scripts": {
    "dev": "vite dev",
    "build" : "vite build",
    "preview" : "vite preview --port 8080"
  }
}
```

## Dev Server
This starts a web server on a local port that monitors CSS and JS resources. 
A browser tha connects to this server will be updated in situ whenever the resources are changed.
```shell
$> npm run dev
```

## Build
This also starts a web server on a local port that uses the compiled resources.
A browser that connects to this server will _not_ be updated as when connecting to the dev server.
```shell
$> npm run build
$> npm run preview
```

# Deployment
Deploy on github pages
* run git init in project to create local repository
* make remote repository on github for project 
* push project to new repo
* add vite.config.js
* npm run build
* npm run preview

The tutorial at this point stopped being useful.  Followed the Deployment section - deploying to github pages, Vercel
and Netlify (which doesn't really benefit me at this point) - at 2x speed.  
Also zipped over config section; better, I think, to read the Vite config documentation at https://vitejs.dev/config/.


