# Documentation

## About

This project contains an html page which renders a Google Map. 
The map is responsive and on-click displays information about the clicked area.

## Implementation 
We use the following dependencies:

1. angularjs plugin: https://ajax.googleapis.com/ajax/libs/angularjs/1.3.3/angular.min.js
2. ng-maps plugin: http://willleahy.info/ng-maps/#/
3. google-apis services: to https://maps.googleapis.com/maps/api/js

### Details
The angular model keeps track of the following two variables
```javascript
ref.pos //the position of the marker (coordinates)
ref.information //an object with information about the marked area
```

## Installation

1. Copy the web folder to your pc
2. Run the file with name "web/index.html"



