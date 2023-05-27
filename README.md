City Scenerio.

I have used Lines, Polygons, Triangles and Quads to build this project. I have considered 7 
horizontal backgrounds in my project. The horizontal backgrounds are of Quads shape. The
backgrounds names are:
1. Sky
2. Greenery
3. Grass Pathway Left
4. Road
5. Grass Pathway Right
6. River Shore
7. River
[ 1 ] In “Sky” background, there are 7 mountains or 7 parts of a mountain which is made of 
Triangles shape. 4 clouds are made of Polygon Shape. There are also 6 birds. The birds are 
made of Lines. Each bird is drawn of 4 Lines.

[ 2 ] In “Greenery” background, I have added 3 types of buildings which are in front of the 
mountain. The leftmost building is an apartment building, in the center a hospital and the rightmost 
building is a school.

Apartment building: It’s made of total 13 Quads and 3 Lines. The footpath in front 
is made of 3 Quads. 

Hospital: It’s made of total 25 Quads and 1 Lines. The footpath in front is made of 1 
Quads. 

School: It’s made of total 15 Quads, 2 Triangles and 3 Lines. The footpath in front 
is made of 3 Quads. 

[ 3 ] Then we have the “Grass Pathway Left”. I have placed 10 small trees in it with the help of 
Lines and Triangles. Every small tree took 1 Lines and 3 Triangles.

[ 4 ] The “Road” comes afterwards. There are 11 road surface markings that were made of only 
Lines.

[ 5 ] Then we have the “Grass Pathway Right” which is identical to the “Grass Pathway Left”.

[ 6 ] “River Shore”.

[ 7 ] In the “River” I have added 1 large boat and 2 small boats. 

Large Boat: It’s made of 2 Quads, 1 Triangles and 1 Lines.
Small Boats: It’s made of 2 Quads, 1 Triangles and 2 Lines.

Note: Sun, Cars were made later.

glutKeyboardFunc(keyboard) is used to toggle between day and night. By pressing "d", it the scenery changes to night time and by pressing "a", the scenery changes back to day time. "Esc" key quits the running window.

glutMouseFunc(handleMouse) is used to accelerate cars. Left click starts the "White car" and right click starts the Red Car"

glutSpecialFunc(handleSpecialKeypress) is used to move boats. "->" key moves the rightside facing boats to the right. and "<-" key moves the leftside facing boats to the left.

Sunrays, Clouds, Birds are automated from the start.
