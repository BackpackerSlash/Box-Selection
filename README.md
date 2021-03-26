# Box-Selection
An Extension for GDevelop5 that enable RTS style box selection

Draw a Box with a Shape Painter Object. 
Place a shape Painter object inside the scenes you want to Draw.
"Draw the Shapes relative to the object position on the scene" needs to be unchecked.
"Clear the rendered image between each frame" needs to be checked.
Selectable Objects should have ther Origin point at the Center.
On left click release, if a Box was drawn:
For Objects that are more then half inside the drawn Box, the Variable "Selected" of Object is set to 1
For Objects that are NOT more then half inside the box, the Variable "Selected" of Objects is set to 0
A left Click without drawing the box, will unselect all objects, exept the Object under the Cursor, unless the Ctrl key is pressed.
Multi-Selection by holding the Ctrl key.

Reserved Variables :
Scene Variables: "StartX" / "StartY" / "EndX" / "EndY" / "drawing"
Object Variable: "Selected"

remarks:
When the Boolean Variables are released to Version 106 of Gdevelop the Object Variable "selected" should be changed to Boolean.

_______________________________________________________________________________________________________________________________

Version 1.1 Update:

For Objects that are more then half inside the drawn Box, the Variable Boolean "Selected" of Object is set to TRUE
For Objects that are NOT more then half inside the box, the Variable Boolean "Selected" of Objects is set to FALSE

Reserved Variables :
Scene Variables: "StartX" / "StartY" / "EndX" / "EndY" 
Scene Variable Boolean: "drawing"
Object Variable Boolean: "Selected"

remarks:
Boolean Variables added! Requires GDevelop version 106b or later
