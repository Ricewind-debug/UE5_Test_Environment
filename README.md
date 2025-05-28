Scope of project

Attempt to build a 2D platformer in Unreal Engine 5 (UE5) - current version 5.5.4.

Setting up a 2D platformer within UE5;
  
  Within a new project open edit, plugins, search for Paper2D and enable it (you may need to restart the app)
  
  Once this is installed right click the content browser and add a new file for the Textures, import all textures for testing. 
  Right click the content browser and add in a Tile Set - within this you can add in the textures previously imported on the right hand side along with changing the size to 16x16 pixels.
  Right click the content browser and add in a Tile Map - using the tile set on the left hand side of the Tile Map add in the set you previously created.  
    You can now extend the sizing of the map to a larger high and width along with changing the pixel size to 16x16 (from 32).
    Using this you can now draw out the map for testing. 

  Once this is done again right click on the content browser and add in a new Blueprint Class - within the class window open the extension at the bottom and search for Paper2D
    Paper2D has its own prebuilt character with movement scripts (currently i couldnt get this working but it might be linked to input mapping for the project). 

This should be a good place to start the project. 
