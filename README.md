# nestable_revamped
making the a, forgotten, 'nestable' jQuery tool by  do what I want it to. 
To be specific, this one:
```
https://github.com/dbushell/Nestable
Nestable jQuery Plugin - Copyright (c) 2012 David Bushell - http://dbushell.com/
```
## Inital Goals -- May 2017
* 'datum()' return fxn: modeled after d3.js's datum, I wanted to make it so I could associate a json
   element with a list item. by calling this function, you are returned the json relevant to the node.
   this assumes comes with a precondition that you have the li id within the json under the key "list_id", and that
   upon init you give nestable a json array relevant to your list.
* 'dispense' class: This class adds functionality for lists that must remain constant,
   but are intended to be added to lists that do not. Styling is wholly dependent upon "dd-dispense"
* 'alert' class: This class allows the dev to know exactly where a node during/after dragging.
   goal is to be used in tandem with datum().
*  ability to port tool to bootstrap easily. the goal being a consistent css file that could be easily
   used in tandem with bootstrap with no errors.

