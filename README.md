# familytree

This is a long-term project I'll be working on to document the people in my family, past and present.

I'd like to have a text description of each person along with whatever pictures are available. The next step would be then creating links and relationships between these individuals (parents/cousins/etc.)

Now how to display this? My family history is a bilingual one and so should be the result. I think relationships trump individual histories, so the first visual would be a big tree. Clicking on an individual node within the graph would then transition you to (or pop-up) the individual's profile.

It may also be fun to create a graph option using the same backend (or even have the ability to visualize in a bunch of different ways- Voronoi, circle, etc.)

# resources

## frontend
* [SO: how do you create a family tree in D3.js?](http://stackoverflow.com/questions/31245751/how-do-you-create-a-family-tree-in-d3-js)

## backend

# data structures and objects

### person

> most likely stored as a JSON object

* name (string)
* id (string) - unique identifier
* birthday (date)
* death or currently living (date or null)
* description (string)
* no_parent (bool) - would be true for any roots of the tree
* children (array of child IDs)
