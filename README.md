# Lab8-Starter

I worked on this lab alone. 

## GitHub Pages URL
[https://thirteenframes.github.io/Lab8_Starter/](https://thirteenframes.github.io/Lab8_Starter/)

Installing on a phone creates an app on the home screen.

## Graceful Degradation and Service Workers

Graceful degradation means that when some features fail, the entire app doesn't stop working. 

Service workers, as used in this lab, aim to prevent the app from completely failing when the user's network connection fails. 

For example, if the user loses connection while on the page, and refreshes the page, the service worker 
catches the network error and displays the cached recipes. This means that instead of a 'no internet connection' page being shown, the existing recipes are shown, keeping some parts of the page still working. 