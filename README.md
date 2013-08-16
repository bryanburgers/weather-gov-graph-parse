# weather.gov graph parser

Parse data from weather.gov's weather graph.

## Usage

Require the module.

```
var gp = require('weather-gov-graph-parse');
```

Fetch and parse the weather graph.

```
gp(pos.latitude, pos.longitude, function(err, data) {
	// data is an array of data points
});
```

Or fetch and parse the weather graph, promises style.

```
gp(pos.latitude, pos.longitude).then(function(data) {
	// data is an array of data points
});
```
