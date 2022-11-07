# NETFLIX UI Clone By Ankita Roy

## DEMO LINK - https://netflix-clone-ankitaroy.web.app

## Build

To build yoou need to install NodeJs. and run

### `npx create-react-app my-app`

Delete everything except node_modules and download the files as zip and extract to root directory or just use 
`git clone https://github.com/Ankitaroy0810/-netflix-clone-\`

then deploy localhost server in dev mode by the following commmand

### `npm run`

Browser will launch. If everything is working as expected, you can deploy into any server. I'll show you the steps for hosting it onto firebase server. Install using the following command

### `npm install firebase`

To deploy now use the following command to login to firebase

### `firebase login`

Login into your Google account in the browser window that pops up

Now to setup hosting service you have to use the following command

### `firebase init`

Are you ready to proceed? Yes

Which Firebase features do you want to set up for this directory? Press Space to select features, then Enter to confirm your choices. Hosting: Configure files for Firebase Hosting and (optionally) set up GitHub Action deploys

In "Please select an option for using an existing project" You can choose an existing project or create a new one from terminal.
Proceed as you like and follow the prompts to select the project

What do you want to use as your public directory? build

Configure as a single-page app (rewrite all urls to /index.html)? Yes

Set up automatic builds and deploys with GitHub? No (Or yes if you wish to do so)

File build/index.html already exists. Overwrite? Yes (if prompted)

Now let's create the production build by using thwe following command

### `npm run build`

And finally deploy the build to firebase using the followinf command

### `firebase deploy`

You will get a hosting URL in the end. Congratulations on deploying your own netflix clone.

`Built for DevSprint :: WebDev Track '22. Also using TMDB APIs. You can replace the the API key with yours in /src/request.js`
