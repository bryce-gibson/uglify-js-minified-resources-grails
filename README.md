This is a GRAILS plugin which provides minification of javascript resources using [Uglify2](https://github.com/mishoo/UglifyJS2).
It is dependent on the standard [GRAILS Resources Plugin](http://grails.org/plugin/resources)

NOTE: Plugin is still in development and has not been run against an actual web project yet (6/28/2013)

## Background
Due to the fact that the [YUI Minified Resources Plugin](http://grails.org/plugin/yui-minify-resources) has
been deprecated, I thought it would be useful to create a new javascript minification plugin based on the Uglify2
project.

I made generous use of the [coffeescript resources plugin](https://github.com/edvinasbartkus/grails-coffeescript-resources)
for examples on how to use the Rhino library.

## Usage
This plugin should automagically minify your javascript files if it is enabled.