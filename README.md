## landing-page-creator
---
is an editor that lets you customize a certain html template (shown in the picture below on the right), which could be used to display your programming portfolio. 

The above mentioned template was my first attempt at creating something with html and css and therby obviously doesn'l live up to modern web-design standards. However this project tended out to be quite elaborate and contains more than 2000 lines of code. I did not use any JS frontend framework or library, just modern JS, Node/Express, and Tailwind CSS. 

 <br>


UI                         |Landing Page (Download)
:-------------------------:|:-------------------------:
![](views/icons/lando-ui.png "UI")  |  ![](views/icons/lando-page.png "Landing Page")

<br>

### Here is a link to the app (deployed on Heroku):
---

[https://landing-page-creator.herokuapp.com](https://landing-page-creator.herokuapp.com/)



<br>

## Installation (to run on localhost):
---
Use git to get a clone of the repository and, switch into the _landing-page-creator_ folder and type in the following (you need to have Node / NPM installed on your local machine):
```bash
npm install
npm run build
npm start
```
Now you should be able to run _Lando97_ in your browser on __localhost:8080__.

## Note
---
In case you're wondering about the massive CSS file (10MB) that the _build-css_ command creates, it's due to the fact that I've added several of the new Tailwind colors and also a few google fonts to the _tailwind.config.js_ file. Working with such a massive file could be avoided by using the new _just-in-time_ compilation supported by Tailwind version 2.1 or higher. 
<br/>
I've made this project before I started using a developement environment. That's why the folder structure is all over the place.  