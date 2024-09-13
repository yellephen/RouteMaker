# RouteMaker

This is a little proof-of-concept webapp that will take a distance and from a starting location attempt to create a roughly circular route. So you could put in 5kms and your house and you'll get a random route from your place, around the neighbourhood and back to the starting location to walk or jog.

If you want to run it, you'll have to create an appsettings.json in the project directory and add your own google maps API key like as follows.

  "ApiKeys": {
    "GoogleMaps": "[apikey]"
  }

#### Some inspiration 

- https://github.com/dugwood/isochrone-isodistance-with-google-maps
- https://github.com/Spencer6497/free-shuffle