# Travel App

A travel app, combining all of your Front End skills into an amazing capstone project for your portfolio. Utilize multiple APIs to present a user with all they need to know about their trip.

## Installating and Running the app

Run `npm install` in the terminal to get the packages required

## Pre-Requesties:
- Make sure you populate the `.env-CHANGEME` file with appropriate values.
- RUN `npm start` to boot up the application.

## API's used

- [Geonames](https://www.geonames.org/export/web-services.html)
- [Weatherbit API](https://www.weatherbit.io/account/dashboard)
- [Pixabay](https://pixabay.com/api/docs/)

## Chosen Suggestions to Make My Project Stand Out

* Allow the user to remove the trip.
* Use Local Storage to save the data so that when they close, then revisit the page, their information is still there.
* Incorporate icons into forecast.

## Directory Structure

``` 
Travel-App/
├── dist
│   ├── icons
│   ├── images
│   ├── index.html
│   ├── main.css
│   ├── main.js
│   ├── precache-manifest.942e51818dfed78a66ff7c318de9186d.js
│   └── service-worker.js
├── package.json
├── package-lock.json
├── README.md
├── src
│   ├── client
│   │   ├── app.js
│   │   ├── icons
│   │   ├── images
│   │   ├── js
│   │   │   ├── calculateDaysToGo.js
│   │   │   ├── formHandler.js
│   │   │   ├── getGeonameData.js
│   │   │   ├── getPixabayImages.js
│   │   │   ├── getWeatherBitData.js
│   │   │   ├── renderHTMLTemplate.js
│   │   │   ├── renderSavedTrips.js
│   │   │   └── validateUserInput.js
│   │   ├── styles
│   │   │   ├── _base.scss
│   │   │   ├── _card.scss
│   │   │   ├── _footer.scss
│   │   │   ├── _form.scss
│   │   │   ├── _header.scss
│   │   │   ├── index.scss
│   │   │   ├── _main.scss
│   │   │   ├── _resets.scss
│   │   │   └── _variables.scss
│   │   └── views
│   │       └── index.html
│   ├── controllers
│   │   └── storeController.js
│   ├── server
│   │   └── index.js
│   └── __tests__
│       ├── formHandler.spec.js
│       ├── server.spec.js
│       └── validateInput.spec.js
├── webpack.dev.js
└── webpack.prod.js

13 directories, 166 files
```

## Author
[Rajshree Nema](https://github.com/Rajshree98)