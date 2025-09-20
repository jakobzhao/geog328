# Geospatial Web Server II: MapBox

To learn Mpabox for web GIS, please review the following two comprehensive tutorials:

- MapBox Get Started: https://docs.mapbox.com/help/getting-started/

- MapBox Studio Get Started: https://docs.mapbox.com/studio-manual/guides/

Here are three examples of using MapBox to create geospatial web services:

- UW Map - MapBox direct url link
    https://api.mapbox.com/styles/v1/jakobzhao/ckkrb3f9o01n018nz6rdsno2w.html?title=copy&access_token=pk.eyJ1IjoiamFrb2J6aGFvIiwiYSI6ImNpcms2YWsyMzAwMmtmbG5icTFxZ3ZkdncifQ.P9MBej1xacybKcDN_jehvw

- UW Map - hosting on github using MapBox gl js library
    https://jakobzhao.github.io/geog328/modules/module06/uw.html


- UW Map as WMTS Service `optional`
    https://api.mapbox.com/styles/v1/jakobzhao/ckkrb3f9o01n018nz6rdsno2w/wmts?access_token=pk.eyJ1IjoiamFrb2J6aGFvIiwiYSI6ImNpcms2YWsyMzAwMmtmbG5icTFxZ3ZkdncifQ.P9MBej1xacybKcDN_jehvw

> **Note:** When you look at the examples of web services, please use Google Chrome inspect to look at the network traffic. You will see the requests and responses of the web services.

If you want to create your own web map with MapBox, a convenient tool is MapBox Cartogram, it can customize your map style very easily. Please visit the following links to learn more about it:

- MapBox Cartogram: https://apps.mapbox.com/cartogram
- Watch this tutorial video: https://docs.mapbox.com/help/tutorials/create-new-map-style-with-cartogram-video/

Once you have created your own map style, you can reuse it in your web map. Please refer to the [modules/module06/uw.html](uw.html) in this repository, this html file can be deployed via `Go Live` or on the cloud through visiting the url link `https://jakobzhao.github.io/geog328/modules/module06/uw.html`. Please check out this html file and learn how to code a similar html file.