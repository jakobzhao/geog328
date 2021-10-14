# Lab 3: Asynchronous GeoJSON Data Loading and Visualization

**Instructor:** Bo Zhao, 206.685.3846 or zhaobo@uw.edu

**Due:** Oct 29th, by 11:59pm | **Points Available** = 50

In this lab, we will exercise on loading geoJSON data asynchronously and visualize the data as table and map. Loading geospatial data will be frequently implemented in a Web or Mobile GIS. This lab will prepare you for this fundamental skill. With it, you can conduct more advanced geospatial analyses upon the loaded dataset. More specific, you will load two pieces of geojson data - one is a point format for the global distributed earthquakes, the other is a polygon format for all the counties in Japan. Once the data were loaded, the earthquake data will be shown in a table on the left of the window screen. The table can also sorted by the earthquake magnitude. The earthquake and the county boundaries can be plotted to the map on the right of the window screen. The map is built upon the mapbox library. At the end of this lab, you will be asked to create a web page in the same function but use another pieces of geospatial data. 

![](img/screenshot.png)

## 1. Create a new GitHub repository

Like the previous two labs, you need to create a new repository to complete this lab. We recommend you **give your repository a more descriptive name** instead of  using "geog495_lab03". 

Once the repository is created, please create a `readme.md` file, an `index.html`, an `earthquake.html`, and another `assets` folder to the root of this repo. In the directory for Lab 3, we saved two geojson files in the folder [assets](assets). Please move these two files to the assets folder of the newly build repository.

Now, the repository should follow the file structure below:

```powershell
[your_repository_name]
    │index.html
    │earthquake.html
    │readme.md
    ├─assets
    │      earthquakes.geojson
    │      japan.json

```

> **Note:** Before loading the data, I encourage you to evaluate these two pieces of geojson data. To do so, you can see whether these two files can be visualized correctly on [https://geojson.io](https://geojson.io).

![](img/geojsonio.png)

> evaluate geojson data on geojson.io


## 2. Web content structure

To begin with, you need to create the skeleton of your html page. As we planed, this page will show a table of earthquake in a side panel on the left and a map of earthquakes on the right. Considering the general graphical user interface design, we create the skeleton of the html page as below.

```html
<!DOCTYPE html>
<html lang="en-US">
 <head>
 </head>
 <body>
    <main id="container">
        <div id="side-panel">
        </div>
        <div id="map"></div>
    </main>
 </body>   
<html>    
```

in the head element, we will include the mapbox library for map making, title, character set, an internal css holder. So, the `head` element looks as below.

```html
<head>
    <meta charset="utf-8">
    <title>Earthquake List</title>
    <meta name="viewport" content="initial-scale=1,maximum-scale=1,user-scalable=no">
    <link href="https://api.mapbox.com/mapbox-gl-js/v2.5.0/mapbox-gl.css" rel="stylesheet">
    <script src="https://api.mapbox.com/mapbox-gl-js/v2.5.0/mapbox-gl.js"></script>
    <style>
    </style>
</head> 
```

 The table is actually nested in the side panel on the left. There are three columns for each record, including `id`, `magnitude`, and `Timestamp`. On the top of the side panel, we show the name of this application and a button for sorting the table. To the end of parsing this html, we will run a piece of JavaScript snippet to load the data and implement the visualization. Therefore, a `script` element is added to the end of the `body` element. So, the `body` element should look as below.

 ```html
 <body>
    <main id="container">
        <div id="side-panel">

            <h2>Earthquake List</h2>
            <button>Sort by Magnitude</button>

            <table>
                <tr>
                    <th>id</th>
                    <th>magnitude</th>
                    <th>timestamp</th>
                </tr>
            </table>

        </div>
        <div id="map"></div>
    </main>
    <script>
    </script>
</body>
 ```

## 3. Style the html Page

Now that the skeleton of the html page was created, we will then add some css properties to style the html elements. In the style element in the head, we will add the following css properties.

```css
body {
    margin: 0;
    padding: 0;
}

#container {
    display: flex;
    height: 100vh;
    flex-direction: row;
    align-items: stretch;
}
```

These two selectors can make the main viewport of this html page can occupy the full window.


```css
#side-panel {
    flex-basis: 500px;
    overflow-y: scroll;
}

#map {
    flex-grow: 1;
}
```

Then we divide the main viewport to two parts, the side-panel on the left, while the map on the right. We use **flex display** to arrange these two elements. Flex is frequently used display strategy, it can responsively determine the size of space, and then extend or shrink the flex boxes. To apply the flex strategy, we need to declare the display property as flex for the container element of the designed flex boxes. In our cases, they are the side panel and the map.

```css
button {
    margin-bottom: 10px;
}
```
This button will keep a `10px` margin to the element at its bottom.

```css
table {
    border-collapse: collapse;
    border-spacing: 0;
    width: 100%;
    border: 1px solid #ddd;
}

th,
td {
    text-align: left;
    padding: 16px;
}

tr:nth-child(even) {
    background-color: #f2f2f2;
}
```

These properties will determine the style of the table. Notably, with tr:nth-child, the even rows in the table can be selected and their background color become a little grayer. Accordingly, the style for even rows and odd rows would be different.


![](img/even-rows.png)


## 4. Create a map instance

Now that the html page skeleton and the style have been determined, we will then create dynamic objects and increase interactivity.

We will use mapbox to create the map application. You wil need to apply for a mapbox access token from its official website. 

Once you obtain your own access token, please define a token at the beginning of the Javascript code.

```javascript
mapboxgl.accessToken = 'pk.eyJ1IjoiamFrb2J6aGFvIiwiYSI6ImNpcms2YWsyMzAwMmtmbG5icTFxZ3ZkdncifQ.P9MBej1xacybKcDN_jehvw';
```

Then, create a map object,  assign the container property to the right placeholder of the map. A base map layer is needed, in this lab, we choose the satellite imagery layer. In MapBox, each public-facing layer will have a unique style url. For satellite imagery, the url is 'mapbox://styles/mapbox/satellite-v9'. In addition, you need to also properly place the map and center the map. In this lab, the map is placed to the center of Japan. As shown in the code snippet below.

```javascript
let map = new mapboxgl.Map({
    container: 'map', // container ID
    style: 'mapbox://styles/mapbox/satellite-v9', // style URL
    zoom: 5.5, // starting zoom
    center: [138, 38] // starting center
});
```


## 5. Load GeoJSON asynchronously




## 6. Add Map Layers

## 7. Generate Table

## 8. Sort the Table



Now you should have a good understanding of how this website template works!

## 3. Deliverable

For your lab deliverable, we would like to ask you to convert your markdown wiki page for lab 1 to a website. After you finish making your website, please upload it to your newly created github repository and turn on the GitHub Pages function, so that we can take a look at your website without using a local web server. Feel free to use the template that we went through in Section 2. You can also create your own website if you want, as long as it is well organized.

We expect the followings for your deliverable:

- Create a new GitHub repository. (3 pts)

- The GitHub Pages function is enabled (we can see your website by visiting `http://[your_github_username].github.io/[your_repository_name]/index.html`). (3 pts)

- The navigation bar is well designed and responsive (try adjust the `max-width` value to make it suit your navigation bar content) (6 pts)

- The navigation bar color, the `hover` color, and the `active` color should be changed based on your preference. (6 pts)

- For the webpage content, you should adopt at least 3 more customized styles following the instructions from [W3Schools How TO - Code snippets for HTML, CSS and JavaScript](https://www.w3schools.com/howto/). For example, you can [add a fullscreen video as the background of your home page](https://www.w3schools.com/howto/howto_css_fullscreen_video.asp), or [create a summarizing table for your topic](https://www.w3schools.com/howto/howto_css_table_zebra.asp), just like what you often see in a Wikipedia entry. Also, if you want to redesign some of your webpages, feel free to do so! (Two example templates here are 1) [Meet The Team Page](https://www.w3schools.com/howto/howto_css_team.asp) and 2) [Section Counter](https://www.w3schools.com/howto/howto_css_section_counter.asp)) Be creative and feel free to edit the information on your wiki page based on the customized element you choose! (21 pts)

- At least one multimedia element, for example, an image or a video (You should keep an eye on the size of the multimedia element you put, as you don't want it to be much larger than your window size). (6 pts)

- Please make sure the internal structure of the files in your repository is well organized. For example, it may be similar to the file structure below. (5 pts)

  ```
  [your_repository_name]
      │index.html
      │html2.html
      |html3.html
      │readme.md
      ├─css
      │      main.css
      ├─img
      │      xxx.jpg
      └─js
             main.js
  ```



## Acknowledgement

The code for the website template is adapted from [How To Create a Responsive Top Navigation Menu (w3schools.com)](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp).



References:
- [Zebra Striped Table](https://www.w3schools.com/howto/howto_css_table_zebra.asp)
- [Sort a Table](https://www.w3schools.com/howto/howto_js_sort_table.asp)
- [async and await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await)