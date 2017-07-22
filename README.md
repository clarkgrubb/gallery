# Overview

Create an HTML gallery for images.

# Install

    $ curl https://raw.githubusercontent.com/clarkgrubb/gallery/master/gallery > /usr/local/bin/gallery
    $ chmod +x /usr/local/bin/gallery

# Use

Tagging images is optional:

    $ gallery --tag flower 01.jpg
    $ gallery --tag dog 02.jpg 03.jpg

Create the gallery and view in the browser:

    $ gallery .
    $ open index.html
