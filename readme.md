# Earthworm
[Visit the site now!](https://alexwebbb.github.io/earthworm/)

Earthworm is a visualization of Google's Elevation API utilizing D3. Each time you drag the box, the view on the graph will update. Each point on the graph represents the elevation at that point in the view, which is represented by the box on the map. Imagine a grid of points where the elevation has been sampled, that is what you are looking at. The view is constructed by making a series of path requests to the Elevation API perpendicular to the plane of the graph, ie sampling the elevation at intervals along the path, constructing the aforementioned grid. The red line represents the closest edge of the box, while the blue line depicts the furthest edge of the box. The bottom of the graph always represents the lowest elevation in the box, so you could say that Earthworm "crawls" along the surface of the earth. Clicking the rotate buttons will rotate the plane of view 90 degrees, resulting in a different query and view.

![A view of the website utilizing a large view](http://res.cloudinary.com/execool/image/upload/v1512385296/earthworm/readme-img.png "The Website in Action")

The Google Elevation API allows one to make path requests, providing elevation and coordinates based on the start and end points you provide, at intervals along the path. For example, if I specify 10 points, it will provide 10 coordinates along the path, evenly spaced, with the first and last coordinates corresponding to the start and end points of the path. I am doing this along the edges of the box, so for example there is a path at the bottom edge of the box, and then a path one interval closer to the top of the box, for a total of 5 paths, with the last path being at the top of the box. I am utilizing the corners of the google map box as the source of data to supply to the elevation path request.

## Tech Used

+ HTML

+ CSS

+ JavaScript

+ jQuery

+ Bootstrap

+ D3
