Weather app
===========

Weather app for displaying the weather report from openweathermap.org using Components, Databinding, HTTP, Services, Observables, HTML5, CSS3, Responsiveness features.

OpenWeatherMap is an online service that provides weather data, including current weather data, forecasts, and historical data to the developers of web services and mobile applications. For data sources, it utilizes meteorological broadcast services, raw data from airport weather stations, raw data from radar stations, and raw data from other official weather stations. All data is processed by OpenWeatherMap in a way that it attempts to provide accurate online weather forecast data and weather maps, such as those for clouds or precipitation. Beyond that, the service is focused on the social aspect by involving weather station owners in connecting to the service and thereby increasing weather data accuracy. The ideology is inspired by OpenStreetMap and Wikipedia that make information free and available for everybody. It uses OpenStreetMap for display of weather maps.

## App features

1. Display today weather
2. Display forecast weather  
3. Display Temperature min/max (C)  
4. Display Pressure  
5. Display Wind speed (m/s)  
6. Display At (date-time)  
7. Search by city/zip code 
8. Open weather api integration 
9. Convert celsius to fahrenheit

This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.19-3.

## Prerequisites  
1. Install [Node.js®](https://nodejs.org/en/download) and npm
    
    node -v 
    
    npm -v
    
2. Install Angular cli
    
    npm install -g @angular/cli
    
3. Install node packages 
    
    cd /go/to/app/directory having package.json
    
    npm install
   
## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Run Production/QA configuration 

#build

 ng build --environment=prod --output-path=build/prod/

#shorthand

 ng b -prod --output-path=build/prod/

#serve

ng serve --environment=prod

ng serve --environment=qa

#shorthand

$ ng s -prod

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Deploying to Github Pages

Run `ng github-pages:deploy` to deploy to Github Pages.

## Further help

To get more help on the `angular-cli` use `ng --help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Angular 2 Style Guide

[Angular 2 Style Guide](https://angular.io/guide/styleguide)

## Run all the tslint and codelyzer rules

Method A - npm run lint

Method B - Windows based command with backslash

$ .\node_modules\.bin\tslint -c tslint.json  .\src\app\weather\weather.service.ts

$ .\node_modules\.bin\tslint -c tslint.json  .\src\app\*\*.ts
