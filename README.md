# PWA-Text-Editor-Refractor

## URL
https://pwa-text-editor-refractor.herokuapp.com/ 

## Description

This project is a text editor web application that allows the user to create code snippets without an internet connection.
The user is presented with a text editor page where they can create code.
The integrated service worker and Cache API's ensure that the application will remain fully functional and save the user's creations.
The user can download the web application as an icon on their desktop.

## Summary

```
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
```

## Installation

npm i -y
npm run start

## Usage

This is a note taking website where the user can take notes and create a list of notes.

![PWA-Text-Editor-Folder-Structure](assets/images/PWA-Text-Editor-Folder-Structure.JPG)

![PWA-Text-Editor-Terminal](assets/images/PWA-Text-Editor-Terminal.JPG)

![PWA-Text-Editor-JATE](assets/images/PWA-Text-Editor-JATE.JPG)

![PWA-Text-Editor-Dist](assets/images/PWA-Text-Editor-Dist.JPG)

![PWA-Text-Editor-Desktop-Icon](assets/images/PWA-Text-Editor-Desktop-Icon.JPG)

![PWA-Text-Editor-App](assets/images/PWA-Text-Editor-App.JPG)

![PWA-Text-Editor-Manifest](assets/images/PWA-Text-Editor-Mainfest.JPG)

![PWA-Text-Editor-Service-Worker](assets/images/PWA-Text-Editor-Service-Worker.JPG)

![PWA-Text-Editor-IndexedDB](assets/images/PWA-Text-Editor-IndexedDB.JPG)

## Credits

N/A

## License

Please refer to the LICENSE in the repo.
