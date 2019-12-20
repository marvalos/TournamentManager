### Project 3 Starter Kit

1) Forked from create-react-app, create-react-express, 08-Ins-MERN, and react-passport-exampl

## Installation
1) Install .NET Framework 2.0
2) Install Python 2.x, and add to PATH.
3) Add the following to your .env: 
        1) GOOGLE_CLIENT_ID=
        GOOGLE_CLIENT_SECRET=
        NODE_ENV=

## Note
* In order to set the google authentication up, you must register your app @ [https://console.developers.google.com](https://console.developers.google.com) & set `GOOGLE_CLIENT_ID` & `GOOGLE_CLIENT_SECRET` as environmental variables
* In development mode (i.e. `npm run dev`), OAuth google callback is not being proxied to the google servers. Therefore in order to test the google OAuth on your local machine do the following:
1) `npm run build`
2) `npm run prod`
