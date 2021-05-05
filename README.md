# [Budget-Tracker](https://polar-ocean-72761.herokuapp.com/)


[![GitHub License](https://img.shields.io/badge/License-orange.svg)](Develop/License/MIT.md)
<!-- [![GitHub Test](https://img.shields.io/badge/Test-blue.svg)](#test) -->
<!-- can put technologies here as shield icons and their versions -->


## Description 

Budget Tracker is a progressive web application that allows the user to add and subtract funds onile or offline. 
Additionally, the application allows the user to visualize a graph of their total spendings in a day over a period of time. 

This project enabled me to gain a better understadning of looking at pre-existing code and analyzing where the connections
need to be made in order for it to make it a progressive web applciation.Through this program I learned to work in IndexedDB as well as the use of Manifest, Service Worker, and CacheAPI. 


## Table of Contents

* [Description](#Description)
* [Technologies](#technologies)
* [Application](#Application)
* [Demonstration](#demonstration)
* [Installation](#installation)
* [Instructions](#instructions)
* [Acknowledgements](#acknowledgements)
* [Questions](#questions)

## Technologies

* JavaScript
* Bootstrap
* [Web app manifests](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json)
* [Service Worker](https://developers.google.com/web/fundamentals/primers/service-workers)
* [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
* Node.js
* npm
* HTML
* CSS
* [MongoDB](https://docs.mongodb.com/)
* [Mongoose](https://mongoosejs.com/)
* Heroku
* Express 

## Application 

![Finished Product](./public/images/image.png)

## Demonstration 

<!-- ![Application Demo](./public/assets/video.gif) -->


## Installation

The following installations are needed for this package:
1. npm init 
2. npm i  
3. npm install node
    
Once in the correct directory (server.js), run "node server.js"

## Instructions

These are instructins & tips for anyone who wants to build this app or a similar app as practice:

* Using MongoDB

1. Make sure to start MongoDB in your terminal prior to running the application

* Using Web app manifests

Web app manifests are part of a collection of web technologies called progressive web apps (PWAs), which are websites that can be installed to a device’s homescreen without an app store. Unlike regular web apps with simple homescreen links or bookmarks, PWAs can be downloaded in advance and can work offline, as well as use regular Web APIs.
The web app manifest provides information about a web application in a JSON text file, necessary for the web app to be downloaded and be presented to the user similarly to a native app.

1. Create a manifest.webmanifest in a public folder and populate it with information about your images 
2. Add a link to index.html (<link rel="manifest" href="manifest.webmanifest">)
3. If you have seed data run the following, npm init > npm run seed > npm start

* Using Service Worker

A service worker (similar to AppCache) is a script that your broswer runs in the background, separate from a web page, and allows for a user to use their application offline. 

1. Create a service-worker.js file in the public folder.
2. Copy and analyze the code I have in my service-worker.js file


* Using IndexedDB

IndexedDB is a low-level API for client-side storage of significant amounts of structured data, including files/blobs. 

1. Create a db.js file in the public folder
2. Copy and analyze the code I have in my db.js file 


## Acknowledgements

* UW Coding Bootcamp instructional team and classmates
    * test files already provided
    * skeleton of html files already provided
    * htmlRenderer.js already provided
* [Bootstrap](https://getbootstrap.com/docs/4.1/getting-started/introduction/)


## Questions 

If you have any questions, please contact me on:
GitHub at [avaarm](https://github.com/avaarm)
Email at [Emma](mailto:avaarm95@mail.com)
