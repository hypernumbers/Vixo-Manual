======================
VERTICAL LINE function
======================

Overview
--------

The vertical.line.H function is used to draw a vertical line of a certain height, line type and colour across W columns. This is particularly useful in delineating different sections on a web or wikipage.
 
Syntax
------

``=vertical.line.H(<width>, <type>, <colour>)``

Arguments
---------

===========     ===========================================================================
Argument        Description
===========     ===========================================================================
``H``	        An integer specifying the number of rows in which to autofill the type 
                of line required.
	
``width`` 	**Optional**. Width is the line thickness and is a positive integer in the 
                range…..
	
``Type`` 	**Optional**. Type identifies the style of the line and has the following 
                options:
                0 - "solid"
                1 - "dotted"
                2 - "dashed"
                3 - "double"
                4 - "groove"
                5 - "ridge"
                6 - "inset"
	
``Colour``	**Optional**. Colour is a colour of the form "#abc123" or "#ab1"

===========     ===========================================================================

Example
-------

Varying style illustration