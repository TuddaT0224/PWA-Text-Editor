# PWA Text Editor


<p align="center">
<img src="client/src/images/logo.png">
</p>


## Description
This application is a web text editor that allows you to create notes or code snippets. You should be able to access it with or without internet also it follows the PWA criteria.

[Link to Heroku Application]()
[URL of the GitHub repository](https://github.com/TuddaT0224/PWA-Text-Editor.git)

## User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

## Acceptance Criteria
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
* npm install express (express.js)
* npm install --save-dev webpack (Webpack)
* npm install webpack-dev-server --save-dev (Webpack-dev-server)
* npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
* npm install babel (Babel)
* npm install --save-dev css-loader (CSS-loader)
* npm install concurrently --save (run multiple commands concurrently)
* npm install idb
* npm install

## Usage
npm run start
This animation demonstrates the application functionality:
![Alt Text](![Untitled_ Jul 13, 2023 11_28 PM](https://github.com/TuddaT0224/PWA-Text-Editor/assets/123923383/0aac32a0-2160-4ebf-8d3d-87195d85d97b)

This image shows the application's manifest.json file
![Alt Text]( ![Screenshot 2023-07-13 232334](https://github.com/TuddaT0224/PWA-Text-Editor/assets/123923383/80ed423c-fb7e-4975-a19e-f916a75ad5f2)

This image shows the application's registered service worker:
![Alt Text](![Screenshot 2023-07-13 232347](https://github.com/TuddaT0224/PWA-Text-Editor/assets/123923383/51750aeb-daed-4b8f-b54c-9298c1ee0e5b)

 This image shows the application's IndexedDB storage:
 ![Alt Text](![Screenshot 2023-07-13 232559](https://github.com/TuddaT0224/PWA-Text-Editor/assets/123923383/4ae25e38-678d-4615-af5c-a2e7dc43c094)


## Contributing
Author: Trezz Tillman

## Questions
If you want to contact me:
email: trezzt0224@gmail.com
github: https://github.com/TuddaT0224


