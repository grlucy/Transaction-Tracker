# Transaction-Tracker

Deployed at XX

## Description

An online/offline PWA that tracks account balance, withdrawals, and deposits. It can be downloaded and used online or offline due to the inclusion of an app manifest and service worker. Data entered in offline mode is stored client-side in IndexedDB, then stored server-side in MongoDB once online again. The app also uses compression to optimize performance.

| Technologies used:                                                                         |
| ------------------------------------------------------------------------------------------ |
| Node.js, Express, MongoDB, Mongoose, IndexedDB, JavaScript, Chart.js, HTML, CSS, Bootstrap |

## Demo

![Transaction Tracker Demo](/public/icons/icon-192x192.png)

## Installation

Open the root directory in terminal and enter:

```sh
npm install
```

```sh
npm start
```

## License

© 2020 Gina Lucy

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
