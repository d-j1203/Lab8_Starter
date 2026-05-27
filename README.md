# Lab8-Starter
https://d-j1203.github.io/Lab8_Starter/

## How are graceful degradation and service workers related?

Graceful degradation is the idea of building an app with the full, modern experience in mind and then making sure it still works just less when conditions get worse, like a slow or missing network connection. Service workers are one of the main tools that make this possible on the web. They sit between the app and the network, cache resources during normal use, and then transparently serve those cached responses when the network is unavailable or unreliable. So instead of the page breaking entirely when a user goes offline, the service worker steps in and lets the app continue functioning with the data it already has, degrading the experience gracefully rather than failing outright.
