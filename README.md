# Find My Microwave
A mobile android gps app that helps California State University students and faculty locate useful campus resources. 

#### v1 Version 1
- Simply displays a map

1. Does not include my API key, API key can be found in v2. 

#### v2 Version 2

Definitions: 
1. Web scene - a 3D model / representation of a map hosted on a web server (in our case, arcGIS's server). 
2. Layers - layers of data that affect the image of a map or scene. Typically by adding more data points or relvant data that we want to see associated with the map. 

Functionality: Displays a web scene of CSUSB campus

1. Zack published a web scene online using arcGIS Pro found here (https://arcg.is/CSbrz0), which can be viewed using esri's app viewer here (https://csusbgis.maps.arcgis.com/apps/instant/3dviewer/index.html?appid=72fc27abcd134e38ae2a4473de2adb45). Note: it appears that the second link does not work for microsoft edge, if you encounter a similar issue, use chrome instead. 
2. It appears that we cannot simply display all the represented data that Zack made with his published web scene. We may have to manually input the same layers that zack used for his design inside of our code.

#### Current Issues
- Reimplement prior features
- Add microwave layer to map, and maybe include an option to view an image of the microwave's physical location. 


