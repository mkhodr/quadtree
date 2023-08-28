# Quadtree for Nearby Point Detection

An efficient implementation of a quadtree data structure for detecting nearby points within a specified range.
The quadtree provides improved performance by reducing the time complexity to logarithmic levels, resulting in faster detection of nearby points.

## QuadTrees

A quadtree is a hierarchical data structure that divides a two-dimensional space into four quadrants, each representing a smaller portion of the space. This division allows for efficient spatial querying and searching of points. The key advantage of using a quadtree is the reduction of search time, especially when dealing with a large number of points.

## Features

-  The quadtree divides the space into smaller quadrants, reducing the number of comparisons required for point detection and improving the overall runtime.

-  Logarithmic Time Complexity - runtime proportional to the logarithm of the number of points instead of n².

-  Recursive Structure - The quadtree employs a recursive structure that simplifies the detection process by traversing through the quadrants recursively.

![](https://github.com/mkhodr/quadtree/blob/main/quadtree.png)
![](https://github.com/mkhodr/quadtree/blob/main/quadtree-zoom.png)
