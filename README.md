# Fav
## A simple module for parsing favicon ICO files.

to install

    npm install fav

Here's a simple usage example

````javascript
    var Canvas = require('Canvas')
      , fs = require('fs')
      , fav = require('fav')(Canvas)
      , icon = fav('favicon.ico').getLargest()

    icon.createPNGStream().pipe(fs.createWriteStream('example.png'))
````