# react_native
My first react native application

## Dependencies to install (so far)
1. NodeJS & NPM
2. Java (I think both the JDK and the JRE)

## Getting started
### With Expo CLI (link)[https://reactnative.dev/docs/environment-setup]
0. Open up the repo in your terminal and install all of the dependencies by running `$ npm i`.
1. Run `npm start` which will start the development server on you machine.
2. Make sure that the **expo client** is installed on your phone and that you are connected to the same wireless network as your computer.
3. Scan the QR-code in the terminal from your mobile app.

## Notes
* I installed the `expo-cli` package locally for this repo. Not sure if this will be an issue later, but if that is the case you can just run `npm install -g expo-cli` on your computer and then run `expo` CLI commands from any terminal. Because this is at the moment only installed for the repo folder you'll have to run the CLI from the *node_modules*. So, if you see anyone telling you to run `$ expo example_command` you'll just change that to `$ ./node_modules/expo-cli/bin/expo.js example_command`.