ShapeShift

ShapeShift is a puzzle game played on a 3x3 grid. Each cell of the grid may be empty or contain a shape,
and the object of the game is to eliminate all shapes from the grid.

In order, to eliminate shapes you must select cells by using the following keys:
|R|T|Y|
|F|G|H|
|V|B|N|
After by selecting the cell, you trigger the effect of the shape in that cell.
There are four different shapes, +, x, ■, and ◆. Here are there effects on the grid:
  +++++++++++++++++
       BEFORE
      | | | |
      | |+| |
      | | | |

       AFTER
      | |x| |
      |x| |x|
      | |x| |
  +++++++++++++++++
  xxxxxxxxxxxxxxxxx
       BEFORE
      | | | |
      | |x| |
      | | | |

       AFTER
      |+| |+|
      | | | |
      |+| |+|
  xxxxxxxxxxxxxxxxx
  ■■■■■■■■■■■■■■■■■
       BEFORE
      | | | |
      | |■| |
      | | | |

       AFTER
      |■| |■|
      | |+| |
      |■| |■|
  ■■■■■■■■■■■■■■■■■
  ◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆
       BEFORE
      | | | |
      | |◆| |
      | | | |

       AFTER
      | |◆| |
      |◆|x|◆|
      | |◆| |
  ◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆

If a shape enters a grid already occupied by another shape, then those shapes combine to form something new. Sometimes,
the shapes may cancel out altogether leacing nothing remaining in the cell. That is how you eliminate shapes from the grid.
Below is a list of all the shape combinations:
  + AND + => x
  + AND x => empty
  + AND ■ => empty
  + AND ◆ => ■
  x AND x => +
  x AND ■ => ◆
  x AND ◆ => empty
  ■ AND ■ => +
  ■ AND ◆ => empty
  ◆ AND ◆ => x

The game is divided into a series of stages or levels, and each level is slightly more difficult than the previous one. After clearing
all the shapes on a grid, the player may progress to the next level by pressing the RIGHT ARROW key. Players are awarded a score depending
on how quickly the level is completed. Harder levels often earn the player more points. In total, there are 20 levels.

Here are a couple of other useful keys for the player:
SPACE => starts the game
0 => restarts the level
Q => quits the game
U P => the letter U followed by the letter P advances the player to the next level and subtracts points from the score.