# Place markers on the map with custom images


## Adding a position marker using map object of Interactive maps API
- Add a folder named img inside the folder Interactive_Map_With_HERE
- Inside the folder img, save the image you want as the icon for truck and homes
- You can also download the ones I used for [home](img/home.png) and [hospitals](img/truck.png)
- Add the following code before </script> tag

```javascript
        // create an icon for the marker. Choose any image you want. I created mine using draw.io 
            
        var homeIcon = new H.map.Icon('img/home.png'); 
            
        // Create a marker using the previously instantiated icon:
       
        var posMarker = new H.map.Marker(myPosition,{icon:homeIcon});
                
        // Add the marker to the map 

        map.addObject(posMarker);
```

[![Foo](/img/s3.png)](/Step3.md) 

