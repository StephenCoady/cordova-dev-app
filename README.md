## Cordova Dev App

### Pre-requisites

cordova:
```
npm i -g cordova@8.1.2
```

A local copy of the Aerogear javascript sdk:

```
git clone git@github.com:aerogear/aerogear-js-sdk.git
cd packages/sync
npm run build
npm link .
```

This repo consists of two parts, the server and the mobile app (cordova).

### Running the server

```
cd ./server
docker-compose up -d
npm install
npm run start
```

### Running the App

#### Web View:

```
cd ./app
npm install
npm run start
```

#### iOS

```
cd ./app
npm install
npm run start-ios
```

#### Android

```
cd ./app
npm install
npm run start-android
```
