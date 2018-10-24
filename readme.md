# Earthworm
[Visit the site now!](https://alexwebbb.github.io/earthworm/)

Earthworm is a visualization of Google's Elevation API utilizing D3. Each time you drag the box, the view on the graph will update. Each point on the graph represents the elevation at that point in the view, which is represented by the box on the map. Imagine a grid of points where the elevation has been sampled, that is what you are looking at. The view is constructed by making a series of path requests to the Elevation API perpendicular to the plane of the graph, ie sampling the elevation at intervals along the path, constructing the aforementioned grid. The red line represents the closest edge of the box, while the blue line depicts the furthest edge of the box. The bottom of the graph always represents the lowest elevation in the box, so you could say that Earthworm "crawls" along the surface of the earth. Clicking the rotate buttons will rotate the plane of view 90 degrees, resulting in a different query and view.

![A view of the website utilizing a large view](http://res.cloudinary.com/execool/image/upload/v1512385296/earthworm/readme-img.png "The Website in Action")

## Tech Used

+ HTML

+ CSS

+ JavaScript

+ jQuery

+ Bootstrap

+ D3
