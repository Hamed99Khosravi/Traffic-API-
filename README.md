# Traffic-API-
What is the Traffic API?
The Traffic API is a suite of web services designed for developers to create web and mobile applications around real-time traffic.
Here you can see some different types of traffic API provieded in (https://developer.tomtom.com/traffic-api) and (https://platform.neshan.org/apis) .Each of which has its own application.
a)Flow Segment Data :
This service provides information about the speeds and travel times of the road fragment closest to the given coordinates.

It is designed to work alongside the Flow Tiles to support clickable flow data visualizations.
With this API, the client side can connect any place in the map with flow data on the closest road and present it to the user.
Required parameters must be used or the call will fail.These parameters include baseURL,versionNumber,style,zoom,format,key and point.

b)Raster Flow Tiles :
The TomTom Traffic Raster Flow Tile service serves 256 x 256 pixel or 512 x 512 pixel tiles showing traffic flow.
Required parameters include baseURL,versionNumber,style,zoom,format,x,y ans apikey.

c)Traffic inciden details :

The Incident Details service provides information on traffic incidents which are inside a given bounding box or whose geometry intersects with it.
Required parameters include baseURL,versionNumber,bbox and key.

 d)Distance Matrix API :
 It is designed to get the distance and time between the matrix from the start and end points. All distances and times are calculated by considering the best route based on the current traffic situation.
 Required parameters include origins and destinations .
 
 for furthur  information please visit https://developer.tomtom.com/traffic-api and (https://platform.neshan.org/apis.
 
