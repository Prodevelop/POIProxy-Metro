POIProxy-Metro
==============

A multi-platform tiles viewer of Points of Interest with photo from POIProxy services tagged as photo services (Flickr, Panoramio, Picasa, Instagram, ...)

##Live demo

http://app3.prodevelop.es/poiproxy-metro/app

##How to build a development workspace of POIProxy-Metro

***Pre-requisites***

* NodeJS
* NPM

***Clone this repo***

`git clone https://github.com/Prodevelop/POIProxy-Metro.git`

***Execute this on the root folder***

`npm install`
`bower install`

## Important

***Grunt - Bower - Requirejs***

There has been noticed a clear incompatibility among the latest versions of mentioned components so that distribution folder will not run properly. 

Requirejs does not inject our own modules in the single concated and minimized js file.

Development: it works fine (grunt hazmagia)
Distribution: fails

## Screenshots

<img height=400 src="https://raw.githubusercontent.com/Prodevelop/POIProxy-Metro/master/img/poiproxy-tileviewer01.png" />
