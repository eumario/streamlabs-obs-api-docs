# Streamlabs-OBS API documentation


[Streamlabs-OBS](https://github.com/stream-labs/streamlabs-obs) Has API for interacting with the application. You can use this API to speed up some UI actions or for writing drivers for any kind of remote controllers.

[GOTO DOCUMENTATION PAGES](https://stream-labs.github.io/streamlabs-obs-api-docs/docs/index.html)

This repo also includes a simple web-interface for [Streamlabs-OBS](https://github.com/stream-labs/streamlabs-obs) that you can use as an example to start working with the API. This web-interface demonstrates some basic features like switching between scenes, show/hide, mute/unmute sources.
 
 [Launch web-interface](https://stream-labs.github.io/streamlabs-obs-api-docs)

![Screenshoot1](https://raw.githubusercontent.com/stream-labs/streamlabs-obs-api-docs/master/screenshots/screen1.png)

# How to connect web-application to Streamlabs-OBS
* Remote connections are disabled by default. To enable it go to `Settings->Remote Control` and click on the QR-Code
* [Launch web-interface](https://stream-labs.github.io/streamlabs-obs-api-docs)
* click `connect` button on the top of the page


The web-interface also includes a simple console for testing direct API requests
![Screenshoot1](https://raw.githubusercontent.com/stream-labs/streamlabs-obs-api-docs/master/screenshots/screen2.png)

# How to run this app on the local machine
* clone the repo
* install the web-interface application via `npm install`
* run `npm start` to start simple HTTP server
* open one of the suggested URLs in a browser

