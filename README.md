# BBAOEngine

SHAPE CREATION
Keys Words :
"custom" / "c"
"preset" / "p"
"read custom file" / "rc"

It Is Recommended That You Use "read custom file" Or "rc" To Create Your Own Shape
It Is The Easiest And Fastest Way To Do So

It Is Recommended That You Create A Folder To Store Your ".txt" Files
To Create Your Shape You Must Create 3 ".txt" Files :
vertices.txt
indices.txt
colors.txt

VERTICES.TXT
You Must Input Raw Decimals ( Recommended In Rows Of 3 ) XYZ To Plot Points

INDICES.TXT
Indices Connect Vertices To Create Triangles
Shapes In GLFW Are Made With Triangles
You Must Input Raw Decimals ( Recommended In Rows Of 3 ) Using The Index Number Of Vertices ( Index Number Starts At ) To Connect The Vertices And Create Triangles

COLORS.TXT
Colors Color The Vertices
You Must Input Raw Decimals ( Recommended In Rows Of 3 )

EXAMPLE
Vertices :
-0.5 0.0 0.5 // Index Number : 0 ( Bottom Left Of A Triangle )
0.5 0.0 0.5 // Index Number : 1 ( Bottom Right Of A Triangle )
0.0 1.0 0.5 // Index Number : 2 ( Peak Of A Triangle )

Indices : 
0 1 2 // Connects Index Numbers ( 0 1 2 ) To Create A Triangle

Colors :
1st Decimal Is RED ( R ), 2nd Decimal Is GREEN ( G ), 3rd Decimal Is BLUE ( B )
0.0 0.0 0.0 // Black ( Since This Is At Index 0, It Colors The First Vertex As Its Index Number Is 0 )
0.0 0.0 0.0 // Black ( Since This Is At Index 1, It Colors The Second Vertex As Its Index Number Is 1 )
0.5 0.5 0.5 // Grey ( Since This Is At Index 2, It Colors The Third Vertex As Its Index Number Is 2 )

PRESET
Current Presets Are :
Pyramid
Cube
Rhombus
Slope

It Is Recommended That You Create Your Own Shapes So You Can Learn And Know What You Are Doing

CUSTOM
This Is An Extremely Harder Way To Create 3D Shapes
You Plot Vertices Directly In The Terminal
You Input Indices Directly In The Terminal
You Input Colors Directly In The Terminal
Created Shapes Are Not Permanent
It Is Not Recommended That You Use This Method ( This Was The Old Way Of Allowing Users To Create Their Own 3D Shapes )
