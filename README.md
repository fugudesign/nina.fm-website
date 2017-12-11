# nina.fm-website

The index.html file will attempt to include a env.js file from the root.
You can use it to overide javascript variables for development purposes as follows :

```javascript
var auth_server_url = "http://my_auth_server_url";
var stream_url = "http://my_stream_url";
var track_info_url = "http://flux.nina.fm:8000/json.xsl";
var mountpoint = '/stream';
```

## Setup

```
npm install
```

## Build for prod

```
gulp sass
```