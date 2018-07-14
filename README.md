# FireAuthBase

## Description

Base for Angular projects running with a Firebase back-end.

## Local setup

* Clone the project in a local repository: `git clone https://github.com/estellepicq/FireAuthBase.git`
* Run `npm install` to install node modules

## Firebase setup

* Follow the steps described in the [Firebase documentation](https://firebase.google.com/docs/web/setup)
* Replace the Firebase config by your own in the following files: `./src/environments/environment.ts` and `./src/environments/environment.prod.ts`
* Allow the following sign-in methods in the [Firebase console](https://console.firebase.google.com/): Email/Password (and enable link authentication), Google and Facebook.
> Note: You will need to create a [Facebook app](https://developers.facebook.com/apps/) and configure it in Firebase console.

## Usage

* Run `ng serve`
* Navigate to `http://localhost:4200/`
