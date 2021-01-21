# svelte app

This is a project that can be used as a template (fork it). It is based on an app that was imported from Github. There are some bugs. Disreguard what is showing in the webview window as it won't update when code changes are made. However, expanding the window by clicking the expand icon (square with an upwards pointing arrow) next to the edit url one (a pen) will open a new browser tab that will show the current state of the app and will update when changes are made.

## Running the app
Click the ** start ** button OR type the following command in the terminal window and press enter. This will start the server and run the app.

```bash
npm run dev
```
Live reload may or may not work. Reloading the output in the new tab after changes have been made will work though. The restart button may need to be clicked to update changes.

Using Ctrl + c in the terminal window will stop the built-in development server.

## Creating a build version
To create a build version of the app run the following command in the terminal window.

```bash
npm run build
```
The ** bundle.js ** and ** bundle.css ** will be rebuilt according to your code changes.
** global.css ** can be used to set global styles. You can edit the title and description of your app in the ** index.html ** file. The favicon can be swapped for something more specific to your app, and the description and name fields in ** package.json ** file can be edited to suit your app. Adding dependencies to the package.json file will cause them to be imported when the app is run or built.

## Deploying to the web
The simplest way is to get a Netlify account, and populate a new site by dragging and dropping the ** public folder ** into the upload area at the bottom of the new site window. You will need to download the repl first, then unzip it to get to the public folder.

Another way is to create a repo on Github and "push" this to a Netlify app. Read up on how to do this on the Netlify site.
