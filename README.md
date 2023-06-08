# PWA-testEditor

  ## Description

  This is a single-page application acting as a text editor. It functions offline and can be installed as a Progressive Web Application (PWA). The app uses IndexedDB as the primary data storage mechanism, and [idb](https://www.npmjs.com/package/idb?activeTab=versions) package is used to simplify working with IndexedDB. If IndexedDB is not supported by the browser, it fallbacks to using Local Storage. [Webpack](https://www.npmjs.com/package/webpack/v/5.51.1) is used to bundle the app's assets, including JavaScript, CSS, and other static files. [Workbox-webpack-plugin](https://www.npmjs.com/package/workbox-webpack-plugin?activeTab=versions) integrates Workbox into webpack, allowing the creation of a service worker that caches static assets for offline usage. [Babel](https://www.npmjs.com/package/@babel/core/v/7.15.0) is used to transpile JavaScript code, including async/await syntax, to ensure compatibility with older browsers. The [WebpackPwaManifest](https://www.npmjs.com/package/webpack-pwa-manifest) plugin generates a manifest.json file, which provides metadata about the PWA, such as the app's name, icons, and other properties.

  ## Table of Contents
  
  - [Usage](#usage)
  - [Technologies](#technologies)
  - [Installation](#installation)
  - [License](#license)
  - [Questions](#questions)

  ## Usage

  This application is deployed at: https://pwa-text-editor01.herokuapp.com/

  * WHEN you open the text editor web application
  * THEN you find that IndexedDB has immediately created a database storage
  * WHEN you enter content and subsequently click off of the DOM window
  * THEN you find that the content in the text editor has been saved with IndexedDB
  * WHEN you reopen the text editor after closing it
  * THEN you find that the content in the text editor has been retrieved from our IndexedDB
  * WHEN you click on the Install button
  * THEN you download your web application as an icon on your desktop
  * WHEN you load your web application
  * THEN you should have a registered service worker using workbox
  * WHEN you register a service worker
  * THEN you should have the static assets pre cached upon loading along with subsequent pages and static assets

  ![ScreenShot](./assets/images/1.png)

  ![ScreenShot](./assets/images/2.png)

  ![ScreenShot](./assets/images/3.png)
  
  ## Technologies

  * [idb](https://www.npmjs.com/package/idb?activeTab=versions)
  * [Webpack](https://www.npmjs.com/package/webpack/v/5.51.1) 
  * [Workbox-webpack-plugin](https://www.npmjs.com/package/workbox-webpack-plugin?activeTab=versions)
  * [Babel](https://www.npmjs.com/package/@babel/core/v/7.15.0)
  * [WebpackPwaManifest](https://www.npmjs.com/package/webpack-pwa-manifest)

  ## Installation

  N/A

  ## License

  N/A

  ## Questions

  If you have additional questions, feel free to reach me through github or email.

  Github: https://github.com/xybai0103
  
  Email: xueyin0103@gmail.com