# freecad-macro-SetParentOrigin

1) Copy the file SetParentOrigin.FCMacro to your ~/.FreeCad/Macro/ folder.
2) Start freecad,
3) open Part or Part Design workbench 
4) Create a long thin object (cube, Cone, Sketch, Pad, Cut, ...)
6) Create a Part, move the object into the Part


Use the Transform tool on the Part.
- You'll notice that the transformation handles (Red/Green/Blue arrows and balls)
  are at the orgin of the Part, which is conveniently near one of the ends of your object.
- If you need to position the other end precisely, the postion of the transform handles is inconvenient. 
- Click a vertex at the other end, select Macros -> SetParentOrigin
  (or CTRL-SHIFT-1, if available)
- the transformation handles (of the Part) move to this vertex, without moving the object or Part.


