# REalityCheck

Prerequisites for Windows/Ubuntu:
1. Download node.js "node-v10.17.0-x64.msi" from https://nodejs.org/dist/latest-v10.x/
2. Follow the instructions after opening the installer in the downloaded folder.
3. Download the "expo app" onto your phone.

Extra steps for School Computers:
1. Requires sudo admin privelliges to download needed packages including Node JS.
2. Download the package for expo as well using sudo.
3. Can then proceed to starting the app component.

Starting the app:

1. Make sure you have node.js installed, then type into the command-line (npm install -g expo-cli).
2. This will download the npm package, and may take a while.
3. Once the installation is finished, type into the command-line "expo start".
4. This will open a new tab on your internet browser.
5. Wait for the command-line to show a QR code. Once this pops up, go to your browser and select the "tunnel" option. Another QR code will show up.
6. You may have to wait until it says "Tunnel ready" to do this.
7. Using your phone's camera app, scan the Tunnel QR code. You'll be prompted to open the Expo app which will then show the output of the React Native code.
8. This should open our app!

Troubleshooting:

1. If there is a connection error, make sure you have wifi turned on and are connected to it. Also make sure the expo is fully loaded. (Tunnel ready, QR code shows)..
2. If there is a 500 dependency error, you may be missing some packages. Type into the command-line "expo install package-name", replacing "package-name" with the package the dependency requires.
3. Final note: We want to make it clear that React Native and Expo are very unpredictable and inconsistent, and it is likely possible
that our app may not work on your end. We will turn in the source code as instructed and for your reference, but it is highly recommended
that we be allowed to present a live demo or a video demo.
