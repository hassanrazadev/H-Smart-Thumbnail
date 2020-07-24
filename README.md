# H-Smart-Thumbnail
H-Smart-Thumbnail is a creative slider jQuery image Thumbnail plugin that enables the user to preview large images in a tooltip-style carousel popup when you click the thumbnail image.
### Getting Started
#### Installation
in browser

     <link href="/path/to/h-smart-thumbnail.css" rel="stylesheet">
     <script src="/path/to/jquery.js"></script>
     <script src="/path/to/h-smart-thumbnail.js"></script>
#### Usage
Stack your images in `div` like

    <div class="h-smart-thumnail">
	    <div><img class="h-smart-thumb" data-file="realfile.jpg" src="thumbfile.jpg"></div>
    </div>
Call H-Smart-Thumbnail plugin

    $('.h-smart-thumnail').hSmartThumbnail();

#### Options
    $('.h-smart-thumnail').hSmartThumbnail({
      navbutton: true, // enable/disable allbutton
      nextbutton: true, // enable/disable next/prev arrow
      rotatebutton: true, // enable/disable rotate button
      closebutton: true, // enable/disble close button
    });

#### Demo
![enter image description here](https://github.com/HaxxanRaxa/H-Smart-Thumbnail/raw/master/demo.png)
