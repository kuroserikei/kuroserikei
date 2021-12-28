# The initial purpose
We will illustrate basic features of markdown with example.  To continue editing, click pencil icon
It is very important to click [Commit changes], otherwise the changes vanish :-( 

While we type, we are in "insert mode" because we clicked "Edit File", or in "viewing mode", after clicking "Preview".  "Commit changes" is below the viewing/editing area.
## Bullet lists and numbered list
### 3rd rank header
#### Bullet lists have items with tag [-+#][ ]
- Item A, tag -
- Item B, tag -
+ Item C, tag +, change of tags starts a new list, hence we see a larger space between lines.
+ Item D, empty line ends the list, I guess
    + item a
        + item aa
    + item b
+ Item E
We add a line after item E, it continues the item.
+ Very important item!

Now some text.  If we have an empty line between items, the effect is strange, seems to introduce double spacing between all items.
#### Numbered lists have items with tag [0-9][0-9]*[.)]
1) Item A
22. Item B
0. Item C
4) Item D
4) Item E
Text in the next line continues the item, as with bullet list

Interesting aspects.  As with bullets, there is a fixed form, item tag is a number followed by dot.
The change from ) to . or back in the tag starts new list.

The first item has the number from the tag.  Subsequent items have numbers that are incremented, and numbers in tags are ignored.
#### Nested list, sublists are indented 4 spaces, numbering is roman
1) item A
    1) item a
    2) iem b
    3) item c
    4) item d
    5) item e
    6) item f
    7) item g
2) item B
