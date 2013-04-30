FineGrid
=========

FineGrid is a light-weight responsive grid system which provides fine-grained layout controls across screens.

It can be used on it's own or acts as a "drop-in" replacement for Twitter Bootstrap and Zurb Foundation.

FineGrid is heavily based on Foundation with similar syntax and usage.

Why ?
-----

Grid system is of great help when laying out web pages but most popular css frameworks have a hard cut-off point at around 640px - 780px, below that point each column occupies 100% width of available space, which results in vertical stacking of each content block.

This is fine and convenient for most use cases until you want to have more fine-grained control over each layout for phone/tablet/desktop.

FineGrid allows you to assign multiple style sets to each element that can be used according to different screen sizes.

A quick syntax sample looks like this:

	<div class="small-12 medium-6 large-9 columns">
		<p>
			content
		</p>
	</div>

You assign different sizes to the div element according to media query result. 

Here's another example, you tell the div element to hide when on mobile phone:

	<div class="small-0 medium-6 large-9 columns">
		<p>
			content
		</p>
	</div>

As you can see, by being able to assign multiple style sets to one element, you enjoy the benefits of grid system but also maintain flexibility.

Key Benefits
---------------

* Three cut-off points
	1. phone: 0-480px (phone portrait and landscape)
	2. tablet: 480-1024 (tablet portrait and landscape)
	3. desktop: 1024-~ (desktop)

* You can easily change the criteria for each cut-off points or add new ones by modifying each @media criteria, just have a look at the source and you will get a hang of it.

* Can hide element by setting small/medium/large-0 which is easier to understand the intention.


Comparison
---------------

###With hard cut-off breakpoint you always got two layouts

#### ▼Desktop layout
![](http://f.cl.ly/items/1l0t1N2P1v1A1Q0N0l1N/traditional-desktop.png)

#### ▼Mobile layout
![](http://cl.ly/image/2a2y0d173j1B/traditional-mobile.png)

(all content blocks are forced to be vertically stacked, no way to fine tune the layout)

###FineGrid provide flexible layout options on different screen sizes

#### ▼Mobile layout

![](http://f.cl.ly/items/1a1u3j0z363a1C3V0c2a/Finegrid-medium.png)

(by providing small, medium and large options, you can fine tune the layout for tablet and mobile phones, as seen here the layout for tablet in landscape mode)

How to use ?
---------------

Just include ```finegrid.css``` after foundation.css or bootsrap.css.


#### Notice
FineGrid come in un-uglified for easier reading purpose, I assume you have your favorite uglifying program in place to do the job before deployment, right ? If not, have a look at [compass](http://compass-style.org/) ;-)


Example
--------------------

See ```example.html```

Info
--------------------
Created by Jeremy Lu ([@thecat](https://twitter.com/thecat))

jeremy [at] pubulous.com.

Feel free to send me questions, bug reports or pull requests.


License
-------

[MIT License](http://cheeaun.mit-license.org/).

