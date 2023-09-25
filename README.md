# PWA Text Editor

## Description
This text editor is a single-page application that meets the PWA criteria featuring a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline and has the option to install. 

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Link](#link)
* [Built With](#built-with)
* [License](#license)
* [Questions](#questions)  
  
## Installation
Use the deployed application link to open the text editor in the browser. Click on the install button to download the web application as an icon on your computer.

In the terminal from the root directory, run the command: `npm install` to install the dependencies. Once installed, enter `npm run start` to have the application start the back end and serve the client. Open http://localhost:3001 to run the application.

## Usage
Create notes or code snippets on the text editor. The entered content will be saved and retrieved with IndexedDB storage when reopening the text editor after closing it. 

Click on the install button to download the appliation on your device to use offline. When loading the web application, you can view the registered service worker using workbox.

The following images show the application's `manifest.json` file, registered service worker, and IndexedDB storage:

![Screenshot of text editor manifest file](/assets/images/te-manifest.png)

![Screenshot of text editor service worker](/assets/images/te-service-worker.png)

![Screenshot of text editor IndexedDB storage](/assets/images/te-indexedDB.png)

## Link
Deployed application link on Heroku: [Text Editor](https://sleepy-sands-88033-b97d0cebd814.herokuapp.com/)

## Built With
- [Javascript](https://developer.mozilla.org/en-US/docs/Web/Javascript)
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
- [Webpack](https://webpack.js.org/)

## License
None

## Questions
Please email me with any questions or visit my GitHub profile using the links provided below.
* GitHub: [suzyhan](https://github.com/suzyhan)
* Email: [suzyahan@gmail.com](mailto:suzyahan@gmail.com)