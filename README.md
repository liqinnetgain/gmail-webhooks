# Mail to webhooks

[![Node](https://img.shields.io/badge/Node-v12.14.1-green.svg)](https://nodejs.org/fr/)
[![Google Api](https://img.shields.io/badge/GoogleAPI-v39-blue.svg)](https://developers.google.com/gmail/api/quickstart/nodejs)

This script was created to send webhooks when emails are received from a given list.

## Summary

- [Installation Guide](#install)
- [Built With](#build)
- [Authors](#author)
- [License](#license)

### Installation Guide <a id="install"></a>

- You first need to create a google account...
- Then go to the [Google Developper Console](https://console.developers.google.com/) and create a new Project
- After this, you can add to the project the Gmail API in the library tab.
- And create an Oauth2 client ID in credentials (Application type : Other)
- Then, download the json file to your project root and rename it `g-credentials.json`
- Make sure to complete the `storage.json` file before to run
- And finally, you can run `npm install` and `node index.js` in the Windows cmd

### Built With <a id="build"></a>

- [Node.js](https://nodejs.org/fr/) - server
- [Discord.js](https://discord.js.org/) - Primary module

### Authors <a id="author"></a>

* **Theo-dev** - *Initial work* - [read more](https://github.com/theo-dev)
* **YeyPiz** - *Initial work* - [read more](https://github.com/YeyPiz)

### License <a id="license"></a>

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
