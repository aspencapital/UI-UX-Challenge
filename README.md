## Introduction
Welcome to Aspen Capital's UI-UX Engineer challenge. This assignment will help us better assess your technical and design skills. You will be given XX days to work on this. We recommend that you focus on the requirements listed below and if time permitting - work on any additional features (of your own choosing). These additional features can be new, functional pieces within the application or even relevant design artifacts (wireframe, color palettes, etc.).

## Background
Aspen Capital is a private equity firm with offices in Portland, OR and New York, NY. We utilize data and technology to enhance business insight, propel growth, transform our investment strategies and business operations, and execute industry-leading deals. For this exercise, imagine that Aspen owns several commercial real estate properties - all of which currently operate as a chain of coffee shops within the Portland metro area. The company has tasked you with designing and implementing a simple dashboard interface that will spatially display all of our commercial properties and provide access to information about each location.

## Requirements
### High Level
* Create a dashboard that plots [these (Starbucks) locations](data/coordinates.geojson) on a map - using a JavaScript mapping library of your choice.
  * Pro tip: To quickly get an idea of the data you will be working with - you can view the GeoJSON data directly in Github or if you prefer - copy/paste the raw data into an online [data viewer](https://geojsonlint.com/).
* The dashboard should display all relevant attributes that have been provided within the GeoJSON file - in both a meaningful and informative manner.
* We're looking for more than just a fullscreen map of points.
* Your application should be both intuitive and visually appealing.
* Your application should highlight your eye for design and creativity.

### Technical
* The application needs to be written primarily in JavaScript - with HTML markup and CSS stylesheets.
  * JavaScript frameworks like Angular, Vue (we currently use this at Aspen), and React are great - but not mandatory.
  * CSS preprocessors would be ideal - but are also not mandatory.
* Your code submission should demonstrate your ability and understanding of writing clear and concise JavaScript.
  * This ideally would include any asynchronous call(s) to fetch the provided commercial data.
* Your submission should also highlight your proficiency in implementing clean and resuable HTML markup and CSS styling.
* Unlike some of the starter examples below - we do not want a single HTML file with JavaScript and inline script/link tags.

## Mapping Libraries
We do not expect you to have familiarity with any of the particular libraries below. As a courtesy, we are also passing along basic GeoJSON examples created by the providers themselves - in hopes to help cut down on the initial implementation time. Feel free to use any mapping libary of your choosing - even if it's not listed here!

#### Leaflet
* [Homepage](https://leafletjs.com/)
* [GitHub](https://github.com/Leaflet/Leaflet)
* [GeoJSON Example](https://github.com/Leaflet/Leaflet/blob/master/docs/examples/geojson/geojson-example.html)

#### OpenLayers
* [Homepage](https://openlayers.org/)
* [GitHub](https://github.com/openlayers/openlayers)
* [GeoJSON Example](https://openlayers.org/en/latest/examples/geojson.html)

#### Mapbox GL JS
* [Homepage](https://docs.mapbox.com/mapbox-gl-js/api/)
* [GitHub](https://github.com/mapbox/mapbox-gl-js)
* [GeoJSON Example](https://docs.mapbox.com/mapbox-gl-js/example/geojson-markers/)

#### Other Options
* [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/3/jshelp/)
* [Google Maps Javascript API](https://developers.google.com/maps/documentation/javascript/overview)
* [CARTO.js](https://carto.com/developers/carto-js/)

## Submission
* Your submission should be accessible in a public git repository that includes a README.md with all the pertinent information of how to run your application. The expectation is that we can easily follow the steps provided and run the application without much leg/guesswork.
* If your submission does include additional artifacts that are not represented within the repository - the README should provide information on how to retrieve and access these items.
* Your challenge is due XX days after receiving an invitation to participate in this portion of the interview process.