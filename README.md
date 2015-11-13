# google-map-static
Polymer custom element that allows for convenient use of the Google Static Maps API.

## Introduction
What happens if you want to just plop down a simple map? Maybe you want to have a link to a map. In fact that's exactly what I wanted to do, but I had to format the API's URL by hand. Here we are in 2015 with all these neat polyfill-based technologies and I had to write a URL by hand. How barbaric!

So I set out on a quest to write an entire custom element so that I wouldn't have to write and maintain that ugly, convoluted, error-prone URL. This element doesn't require the use of anything but raw Polymer.

One last note: **get your own API key.** Everyone is happier that way. Google, you, me, everyone. The library will still function without one, however.

## Limitations and future work
* This element only understands latitudes and longitudes right now. Support for addresses and such will be added later.
* Markers should be grouped, as allowed by the Static Maps API, to allow for shorter URLs.

## Documentation
API documentation is available from index.html, and a demo is available in the demo folder.

## License
Right now this is licensed under the Apache 2.0 license, mainly because it was on the top of the list. If anyone has any reason why I should change it, drop me a line.
