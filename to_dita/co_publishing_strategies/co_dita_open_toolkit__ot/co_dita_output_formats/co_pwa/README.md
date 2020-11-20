---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Progressive web application

Progressive web application \(PWA\) is a technology, originally proposed by Google, that combines the best of web and mobiles apps. Think of it as a responsive website that is also reachable when you're offline after you visited it once in online mode. Each time you go online again, it downloads the latest version of the website making it available when you're offline again. This makes it an ideal solution for your documentation. You can build an online knowledge base for your documentation with installation and user guides, but at the same time a technician who is not always online can use the knowledge base whenever they are offline repairing a machine. We can build this application on top of the responsive webhelp from Oxygen XML.

## Requirements

You need the following software and files to build a PWA:

* **serviceworker.js**

  A service worker is a JavaScript file that added to the root folder of your website that is responsible for intercepting network requests, caching or retrieving resources from the cache and delivering push messages.

* **manifest.json**

  The manifest file is a JSON file that tells the browser about your Progressive Web App and how it should behave when installed on the user's desktop or mobile device. A typical manifest file includes the app name, the icons the app should use, and the URL that should be opened when the app is launched.[1](./#fn_o2x_lgl_flb)

* **Google Workbox**

  This is a set of libraries and Node modules that make it easy to cache assets and take full advantage of features used to build PWA.[2](./#fntarg_2)

* **npm**

  npm is the world’s largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.[3](./#fntarg_3). We need this technology to run the Google Workbox commands.

1 [https://developers.google.com/web/ilt/pwa](https://developers.google.com/web/ilt/pwa)[2](./#fnsrc_2) [https://developers.google.com/web/tools/workbox](https://developers.google.com/web/tools/workbox)[3](./#fnsrc_3) [https://www.npmjs.com/](https://www.npmjs.com/)

