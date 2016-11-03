# **zoomove-polymer** Element

A polymer element to use zoomove jquery plugin

## Using **zoomove-polymer** Element in your Project

Install this using bower

```
$ bower install zoomove-polymer --save-dev
```

Add the element element using html imports

```
<link rel="import" href="../zoomove-polymer.html">
```

And you can now use the tag as follows,
```

<zoomove-polymer
  image-path="images/example.jpg"
  image-cover="false">
</zoomove-polymer>


<zoomove-polymer
  image-path="images/example.jpg"
  image-scale="5">
</zoomove-polymer>


<zoomove-polymer
  image-path="http://lorempixel.com/600/600/animals/"
  image-cover="true">
</zoomove-polymer>

```
### Available attributes

1. **image-path**	-	The url of the photo to be displayed.
2. **image-scale**	-	Sets the zoom size that should be applied to the image.
3. **image-move**	-	Choose whether the image should move with the mouse move
4. **image-over**	-	With 'over' it is possible to define whether the image may be above
5. **image-cursor**	-	Define the cursor pointer or default


## Contributing (Issue/PR)

For contributing feel free to create an issue or raise a PR.


## MIT LICENSE

Copyright 2016

Saket Kumar  saki007ster@gmail.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
