# Homework

## 16 - Forecaster

Build a simple weather app that utilizes both the Google Maps API to convert a zip code provided by the user into a set of latitute and longitude coordinates, as well as the Dark Sky API to use those coordinates to find the local weather conditions for that location.

This is the API call to use to get coordinates from a zip code:
http://maps.googleapis.com/maps/api/geocode/json?address=santa+cruz&components=postal_code:12345&sensor=false
(Where 12345 is the zipcode. The address field has a city name in it, which is ignored by the API server for this request)

### Steps to Success

#### Storyboard Tasks

* [ ] Build a table view controller that will display location information for the zipcode provided. One cell per location.
* [ ] Provide a plus button in the navbar that will open the modal view to prompt for zipcode. 
* [ ] Build a modal view controller that will prompt the user for a zip code.
* [ ] 
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]

#### Code Tasks

* [ ] Create a model object to store information about a particular location.
* [ ] Perform an asynchronous network call to ask the Google Maps API for a lat/long pair based on a given zipcode.
* [ ] 
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
