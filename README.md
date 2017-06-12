# Colouring Periodic Graphs and Tilings of the Plane

This is an independent research project I worked on under the supervision of [Dr. Gary MacGillivray](http://www.math.uvic.ca/faculty/gmacgill/) in the spring of 2016 for UVic's MATH 498. We plan on publishing it eventually (when I have some time to go back and visit Victoria, likely).

From a high level, this paper talks about a special class of graph called a **periodic graph**. These are infinite graphs with countably many vertices and edges. In layman's terms, these graphs are those where you

1. Pick a finite graph you think is cool
2. Draw an infinite grid (of however many dimensions you want)
3. Stick a copy of your graph of choice in each cell
4. Draw edges between the copies of each graph (if you want)

The only thing that's tricky here is (4). If you draw one edge between two cells, you have to do the same thing in every *other* cell as well.

For example, say we have *v1, v2, v3,...,vn* as our vertices in our *finite* graph. Now, let's look at some cell and say, its rightmost neighbouring cell. If we draw an edge between *v1* in the first cell and *v1* in the second cell, then we have to do that *for every cell and its rightmost neighbour*. The result will be an infinite path through the graph. (Go ahead and try it with something simple like a triangle!)

This paper shows a couple results to do with the decidability of colouring these kinds of graphs. For example, we might want to know if a periodic graph admits periodic *colourings*. We might also want to know if it's possible to 3-colour a periodic graph. Also, these things look kind of like tilings, and tilings are cool, so we show the relationship between tilings of the plane and colouring these graphs.
