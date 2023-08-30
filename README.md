# My PWA Text Editor Project
## Description 
 I've built a web-based text editor that you can use to jot down notes and code snippets, even when you're offline. It's pretty nifty – your content is saved automatically using some database magic called IndexedDB. Plus, you can install it on your desktop for quick access, and it works offline thanks to a tech called service workers.

 [visit Heroku live site](https://pwa-textbootcamp-b2ee1a9fc8ce.herokuapp.com/)

## Installation
1. Clone this repository to your local machine.
2. Navigate to the project's root directory using your terminal.
3. Run npm install to install the required dependencies.
4. Run npm run start to start the backend and serve the client.
5. Open a web browser and navigate to the provided address to access the application.

## Usage
1. Once the application is running, you'll see the client-server folder structure in the browser.
2. Your JavaScript files are bundled using webpack to ensure efficient loading.
3. The application utilizes IndexedDB for data storage. As soon as you open the text editor, a database storage is created.
4. Write your content in the text editor. As you type, your content is automatically saved using IndexedDB.
5. If you close the editor and reopen it later, your content will be retrieved from IndexedDB, ensuring you never lose your work.
6. To enhance your experience, you can click the "Install" button to download the web application icon to your desktop.
7. The service worker, powered by workbox, registers itself when you load the application, enabling caching and offline functionality.
8. Static assets are pre-cached upon loading, ensuring smooth navigation even without an internet connection.

![demo of the gif](./Demo.gif)

## Features
* Create and save notes or code snippets with or without an internet connection.
* Utilize IndexedDB for immediate and reliable data storage.
* Application functions offline thanks to the service worker and caching.
* Install the application as a PWA for easy access from the desktop.
* Modern folder structure and webpack bundling for optimized performance.

## Technologies
* HTML, CSS, JavaScript
* IndexedDB for data storage
* Webpack for bundling
*cService worker powered by workbox for caching and offline functionality

## Contact
* GitHub: https://github.com/ssherp/
* Email: ssherpa89@gmail.com