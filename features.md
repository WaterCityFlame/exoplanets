display list of planets
----
- read in xml data and convert to html
- shove arbitrary html into <li> elements
- send completed html to client
- css
- base html

display detailed information on each planet (with links to rest of system)
----
- generate a ton of links computationally
- generate more html on the basis of xml
- also add comp-generated links to base of data sheet
- another design problem: data must look good +/-photo and +/- paragraph

filter it by planet and star type, number of planets, combo filters
----
- client side code to give new search results without a reload
    	- this will mean websockets
- buttons to toggle filters
- server-side application of the filters
	- higher-order function generates functions w/out crashes.
	

---------------------
this isn't all that hard. the filters are the only hard bit, and that's only one part

the potential volume of work is incredible, because of the number of planets. getting even just all significant/well doced ones more detailed shit is hard. [galleries, yes?]

