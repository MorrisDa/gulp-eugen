# gulp-eugen

## About
<img src="https://raw.githubusercontent.com/MorrisDa/gulp-eugen/master/img/eug.png" width="300"/>

gulp-eugen is a gulp file. 
gulp-eugen process ```.html``` files and inline all the assets in single ```.html``` files. 
The result is a bundled file with all resources (css, js, etc.) included in its source. No need for network requests. <br/>
Useful for generating interactive and portable pages.

## What it does
The gulp-eugen parses html files and find all the css, js, fonts, images. Then it process all those assets in order to inline them in a single html file.
The resulting .html file should work like the non-bundled version. 

## Hints
Easy to use, no configuration required. 

## Usage
First install dependencies (```npm install```), then do:

```$ gulp eugen --src=path/to/website --dst=bundle```

That will create inside ```bundle``` folder as many  ```.html``` files as where in the ```website``` folder. 

## Ak
Thanks to Eugen for developing this tool

