# gulp-eugen

## About
![alt text](https://raw.githubusercontent.com/MorrisDa/gulp-eugen/master/img/eug.png)

gulp-eugen is a gulp file. 
gulp-eugen process all the ```.html``` files inside a folder you choose and inline all the assets in single ```.html``` files. 
The result is a bundled file with all resources (css, js, etc.) included in its source. No need for network requests. <br/>
Useful for generating interactive and portable web pages.

## What it does
The gulp-eugen parses an html file and find all the css, js, fonts, images. Then it process all those assets in order to inline them in a single html file.
The resulting .html file should work like the non-bundled version. 

## Hints
Easy to use, no configuration required. 

## Usage
First install dependencies (```npn instamm```), then do:

```$ gulp eugen --src=path/to/website --dst=bundle```

That will create inside ```bundle``` folder as many  ```.html``` files as where in the ```website``` folder. 
