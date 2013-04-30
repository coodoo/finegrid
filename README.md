Finegrid
=========

Finegrid is a "drop-in" grid system replacement for Twitter Boostrap and Zurb Foundation which provides more fine-grained layout control for phone, tablet and desktop screen sizes.

About
-----

Grid system is a great help when laying out web pages but most popular css frameworks have a hard cut-off point at around 640px - 780px, below this point each column occupies 100% width of the row, which results in vertical stacking of each content block.

This is fine and convenient for most use cases until you want to have more fine-grained control over each layout for phone/tablet/desktop.

Finegrid allows you to set different width to each element for phone, tablet and desktop screen sizes by providing small, medium and large style settings.

It's also super easy to change the cut-off point by modifying each @media criteria, just have a look at the source. 

Comparison
---------------

###With hard cut-off limit

#### ▼Desktop layout
![Mou icon](http://f.cl.ly/items/1l0t1N2P1v1A1Q0N0l1N/traditional-desktop.png)

#### ▼Mobile layout
![Mou icon](http://cl.ly/image/2a2y0d173j1B/traditional-mobile.png)

(all content blocks are forced to be vertically stacked, no way to fine tune the layout)

###Finegrid provide flexible layout options

#### ▼Mobile layout

![Mou icon](http://f.cl.ly/items/1a1u3j0z363a1C3V0c2a/finegrid-medium.png)

(by providing small, medium and large options, you can fine tune the layout for tablet and mobile phones, as seen here the layout for tablet in landscape mode)

Usage
---------------

Just include ```finegrid.css``` after foundation.css or bootsrap.css.


#### Notice
Finegrid come in un-uglified for easier reading purpose, I assume you have your favorite uglifying program in place to do the job before deployment, right ? If not, have a look at [compass](http://compass-style.org/) ;-)


Example
--------------------

See ```example.html```.

Info
--------------------
Created by Jeremy Lu ([@thecat](https://twitter.com/thecat))

Feel free to use, pull requests warmly welcomed too.

jeremy [at] pubulous.com


License
-------

[MIT License](http://cheeaun.mit-license.org/).

