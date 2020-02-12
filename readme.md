# Solar Calculator
### A single-page web application for mapping potential solar installation locations. 

Built with React/NextJS and Mapbox GL JS.  

Some bootstrapping configuration copied from [volle.io](https://github.com/volleio/volleio.github.io). 
Typings for @mapbox/mapbox-gl-geocoder adapted from [use-strict](https://gist.github.com/use-strict/b7363cf9ffbfd0f65582f708d4c22e67).



## TODO:

✅ Add Mapbox GL JS module  

⬜ Add geocoder input (search and fly to location)  

⬜ Create 'drawing' mode  
> ⬜ Allow adding of geopoints on mouse click  
> ⬜ Connect geopoints with lines  
> ⬜ Create shaded polygon when closing line (clicking on first line)  

⬜ Calculate area of polygon  

⬜ Design initial algorithm for calculating nominal power of a solar installation based soley on polygon area  

⬜ Design & implement UI for displaying solar power calulation  

⬜ Make basic improvements to UX to make it clear how to use the application  

⬜ Create test plan & test in Chrome, Firefox, Chrome on Android, Safari? (no iOS devices)

⬜ Research most practical way of improving solar installation power calculation  

⬜ Deploy application (github.io?)

... Nice-to-haves ...

⬜ Improved UI & UX, designed in Figma  

⬜ Allow adding multiple solar installation polygons  

⬜ Automated testing 

⬜ Add inputs for landscape tilt & orientation. Update polygon's surface area and solar installation power calculations. 

⬜ Add polygon height input and extrude the shape
> ⬜ Combine with previous item to show tilt of object?
