# Text-Editor

## Description

This is a text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancies in case one of the options is not supported by the browser. The application is functional offline.

To complete this, I used webpack, a module bundler for JavaScript that simplifies front-end web development to bundle JavaScript, and the webpack's HTMLWebpackPlugin to generate an HTML page.  IndexedDB and idb a small wrapper that makes it easier to implement IndexedDB CRUD methods to add the ability to store structured data to the browser. Workbox to add offline functionality. Finally, I added a manifest.json to make the app installable. 

## User Story

AS A developer <br>
I WANT to create notes or code snippets with or without an internet connection <br>
SO THAT I can reliably retrieve them for later use

## Installation

1. Clone the Repository on to your machine.
2. Open the terminal and ensure you are in the right file path.
3. Run the command ```npm install``` to download the packages.

## Sample Images

### manifest.json

![image](/images/manifest.png)

### service worker

![image](/images/service%20worker.png)

### indexedDB

![image](/images/indexDB.png)


## Deployed Site

https://evening-caverns-38375.herokuapp.com/

