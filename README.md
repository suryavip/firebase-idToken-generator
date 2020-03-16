# firebaseIdTokenGenerator
Sign in and get id token. Useful when developing and debuging your own backend.

Tested runing on local server (XAMPP).

## Setup
1. Make sure you have web app for your firebase project.
1. Rename or copy `firebaseConfig.sample.js` to `firebaseConfig.js`.
1. Provide your web app `apiKey` in `firebaseConfig.js`. You can get this from web app section on Project Settings.

## Usage
1. Open `index.html` on browser. (for example: `http://localhost/firebaseIdTokenGenerator/index.html`)
1. Sign in with any method you want.
1. If sign in succeeded, you will be redirected to `signedin.html`.
1. Id token will be loaded. You can use GET (force new) button to force new id token.

## Screenshoot
![index.html page](https://github.com/suryavip/firebaseIdTokenGenerator/screenshoot/index.png)

![signedin.html page](https://github.com/suryavip/firebaseIdTokenGenerator/screenshoot/signedin.png)