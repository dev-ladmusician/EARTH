# WEB PROGRAMMING FINAL PROJECT
open source for the amount of use ur smart switch.
<br>
get the amount of use graph reactive html code library for iot smart switch.
<br>
# GETTING STARTED
<br>
The folks over at usual user graciously provide CDN support for EARTH's CSS and JavaScript. Just use these CDN links.

script CDN
```bashS
<!-- Latest compiled and minified JavaScript -->
<script src="http://goo.gl/6LkTGZ"></script>
```
css CDN
```bashS
<!-- Latest compiled and minified CSS -->
<link href="http://goo.gl/DNfV9J" rel="stylesheet">
```
<br>
Start by adding a div to your page that will contain your chart
```bashS
<div id="myChart"></div>
```
<br>
Next add a script block to the end of your page, containing the following javascript code:
```bashS
new Earth.Chart({
  // api key for user
  apiKey: '{test_my_key}',
  // target div tag id
  targetId: 'myChart',
  // filter
  data: {
    from: 2016-01-01,
    to: 2016-06-01
  },
  // chart type
  type: 'circle'
});
```



<br>
# DEMO

