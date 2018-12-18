# Menu Widget JS-script with Links

Menu Widget JS-script | Сan be added on any website with jQuery | Separate settings for links, centering and theme

demo: [http://vh152449.eurodir.ru/web-widget-demo](http://vh152449.eurodir.ru/web-widget-demo)

![Screenshot](Screenshot.jpg)

## Instruction

On the localhost:

- **npm install** 
- **npm start** 

then open browserify generated local url

On the web:

- host the **dist/assets** folder on the web
- use any your website or host the demo site (dist/index.html & dist/site-sample-assets)
- insert **widget code** in the demo

## Widget code

Insert this <script> code in the end of the <body> section on your web site:

![ScreenshotScript](ScreenshotScript.jpg)

you can use settings params, where

- **center** can be "true" or "false", true - will center left and right urls bars
- **theme** can be "dark" and "light", for dark and light appearance
- **left** and rigth links - put the link names and urls, also make dropdowns with links

## JS-Widget script & its demo page Boilerplate

Widget boilerplate uses Gulp, Webpack, Browserify, PostCSS, Stylus, jQuery, ES6 with babel polyfill
