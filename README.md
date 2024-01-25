# progressiveWebApplication-TextEditor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/progressiveWebApplication-TextEditor/blob/main/LICENSE)

## Description
This application is a web based web application where a user can create code snippets or notes with or without a connection to the internet. A user can retrieve saved notes and code snippets once connected to the internet. Using the integrated service worker interface and Cache API's, the application will remain functional offline. This application will allow a user to interact with the application while remaining offline.



## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [URL Link](#url_link)
- [Repository](#repository)
- [Questions](#questions)


## Installation
- This application will require multiple npm dependency packages.
* npm install express (express.js)
* npm install --save-dev webpack (Webpack)
* npm install webpack-dev-server --save-dev (webpack-dev-server)
* npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
* npm install babel (Babel)
* npm install --save-dev css-loader (CSS-loader)
* npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
* npm npm install idb (IndexedDB)

## Usage
1. User Story:
```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

2. Acceptance Criteria:
```md
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

3. Below is the npm run start build:
![Alt text](<Screenshot 2024-01-23 at 11.27.43 AM.png>)

4. Functional Application as deployed to Heroku:
![Alt text](<Screenshot 2024-01-23 at 11.33.08 AM.png>)

5. `Once on deployed site. A user can install the application to their local machine via the install button at the top left`
Below is the install installed PWA:
![Alt text](<Screenshot 2024-01-23 at 11.35.29 AM.png>)

6. The application with added code prior to closing application, then re-opening the application to see the same code still available.
![Alt text](<Screenshot 2024-01-24 at 5.14.08 PM.png>)

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/progressiveWebApplication-TextEditor/blob/main/LICENSE)

Copyright (c) 2024 BrianH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
MIT License

## [URL Link](https://p-w-a-text-editor-098506ebcbf2.herokuapp.com/)

## [Repository](https://github.com/GrassHopper12345/progressiveWebApplication-TextEditor)

## Questions
If you have an questions please email me at: [brian.hopper@live.com](brian.hopper@live.com).
My GitHub page is: [GrassHopper12345](https://github.com/Grasshopper12345)