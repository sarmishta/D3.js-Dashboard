# D3.js-Dashboard
Visualization of FreeCodeCamp 2017 Survey Dataset

This dashboard is a visualization of [freeCodeCamp 2017 survey dataset](https://www.kaggle.com/fccuser/the-freecodecamp-2017-new-coder-survey#2017-fCC-New-Coders-Survey-Data.csv)

## World Distribution - Attended Bootcamps

This visualization is an overview which shows the distribution of people who attended bootcamps accross the world. 
Larger the size of the circle, more the number of people who attended bootcamps, you can hover onto the circle to view the count.

## Distribution of Field of Employment of those who attended the bootcamp

This visualization is a detailed view of the world Distribution.
Click on the country and you will see a bubble chart for the particular country.

## Resouces, Podcasts and Events - Overview

This visualization shows the subcategories of resources, podcasts and events of people who follow them.
The larger the size of the circle, the more number of people use them.

## How to run?
Open index.html file 

If you call D3’s csv, tsv, json, etc. functions to load data from a file and try to directly access the file, it won’t work.

Error: XMLHttpRequest cannot load file:///.../the_file.csv. Cross origin requests are only supported for protocol schemes: http, data, chrome, chrome-extension, https, chrome- extension-resource. Solution:

● Run a local python server → python -m SimpleHTTPServer

● Use Firefox directly

