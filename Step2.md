# Place markers on the map with custom images


## Adding a position marker using map object of Interactive maps API
- Provide the position for all the delivery locations and delivery vehicle

```javascript
        // Get your current position from wego.here.com
          var destinations = { 
            "destination1": {lat: 12.96677,lng: 77.75164}, 
            "destination2": {lat: 12.85677, lng: 77.83164},
            "destination3": {lat: 12.99677, lng: 77.63164},
            "destination4": {lat: 12.86677, lng: 77.73164},
            "destination5": {lat: 12.95677, lng: 77.83164},
            "destination6": {lat: 12.84677, lng: 77.63164},
            "destination7": {lat: 12.87677, lng: 77.74164},
            "destination8": {lat: 12.95677, lng: 77.78164},
            "destination9": {lat: 12.96677, lng: 77.83164},
            "destination10":{lat: 12.95677, lng: 77.73164},
            "truck": {lat: 12.80677, lng: 77.93164}
            }; 
```

- Edit the centre location on the map to see from trucks perspective

```javascript
        // Get your current position from wego.here.com
        var map = new H.Map(
              document.getElementById('mapContainer'),
              defaultLayers.vector.normal.map,
              {
                  zoom: 12,
                  center: destinations.truck,
              });
```

- Add a folder named img inside the folder Interactive_Map_With_HERE
- Inside the folder img, save the image you want as the icon for truck and homes
- You can also download the ones I used for [home](img/home.png) and [hospitals](img/truck.png)
- Add the following code before </script> tag


[![Foo](/img/s3.png)](/Step3.md) 

