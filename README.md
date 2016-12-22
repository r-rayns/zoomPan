# zoomPan

zoomPan is a basic Angular.js custom directive that zooms and pans as you move the cursor over the image. I have tried to keep the code as minimal as possible so it can be easily adapted. Demo can be found here: http://rrayns.co.uk/zoomPanDemo/demo.html

## Installation

To use download and place the zoomPan directory into your working directory and include the script and style sheet in your markup.

## Usage

Basic usage could look somthing like so:
```http
<html ng-app="zoomPanApp">

<head>
	<script src="js/zoomPan.js"></script>
	<link href="css/zoomPan.css" rel="stylesheet" type="text/css">
</head>

<body>
	<zoom src="./imageURL.jpg" frame="example1" img="image1" zoomlvl="1.5"></zoom>
```
In this example the image url is placed directly into the directive but this could easily come from a binding defined elsewhere. 
Three other properties are also set;

* frame - provide a unquie identifier to be attributed to the image containter †
* img - provide a unquie identifier to be attributed to the actual image †
* zoomlvl - provide a scale to zoom by, default 2.5

† These are mandatory properties 

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

1.0: Initial Commit

## Credits

Robert Raynsford (r.raynsford@gmail.com)

## License

MIT License

Copyright (c) [2016] [Robert Raynsford]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
