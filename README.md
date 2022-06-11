# browser
Ideas on a layout algorithm and browser

# layout engine

Ideally I want to render a layout that is a nested tree or scenegraph.

I can render to pixels, I think I can use branch and bound algorithm for sizing each element.

For simplicity I shall render textfields as if they are all independently flowing so that's a bounding box for each character.


I shall use wxWidgets and use GetTextExtents to get text size.

For coordinate to object identification I can create a tree with each stopping point of the widgets in the scene graph.
From this I can work out what widgets are highlighted and change their colour.

I can implement text highlight as a collection of moused over widgets and change their colour.

# renderer

The renderer shall be in Python and the Server shall be in Java.

