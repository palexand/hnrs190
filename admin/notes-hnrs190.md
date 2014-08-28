# The MU problem

1. Alphabet - **M**, **I**, **U**
1. Axiom - **MI**
2. Rules
	* Add **U** to any string ending in **I** (xI -> xIU)
	* Double the struct after the **M** (Mx -> Mxx)
	* Replace **III** with **U** (xIIIy -> xUy)
	* Remove **UU** (xUUy -> xy)
1. _Can MI become MU in a finite number of steps?_

This is the basis of what we study in computer science.

How do we prove it?  _Find a sequence of steps_

Iterative search.  What if it doesn't terminate?