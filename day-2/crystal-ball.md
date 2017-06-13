# 3D-crystal-ball

## Introduction

## Concepts/Items Covered
* Arnold Renderer
* Arnold Shaders
* Hypershade Editor
* Environmental Lighting
* nCloth

## Part I: Fortune Telling Table!
1. Create a fortune telling table using a shape from the Polygon Shelf.
2. Create a ```Polygon Plane``` from the Polygon Shelf.
3. Move the ```Polygon Plane``` upwards so that it is directly above the fortune telling table.

## Part II: Magic Cloth...
1. Currently you are in the Modeling Menu Set. Select the ```FX``` Menu Set from the dropdown at the top left corner.
2. Make sure you are in object mode and select the ```Polygon Plane``` you just created.
3. Subdivide your ```Polygon Plane``` by clicking on ```Smooth``` in the Modeling Toolkit.
3. Click on the ```nCloth``` tab on the very top bar, then select ```Create nCloth```.
4. Click on the ```Fields/Solvers``` tab on the very top bar, then select ```Gravity```.
5. Select your fortune telling table.   
6. Click on the ```nCloth``` tab on the very top bar, then select ```Create Passive Collider```.
7. At the bottom right corner, press Play in your ```Playback Controls``` to see the nCloth go!
8. Stop the animation at the point that looks best to you.

## Part III: What do you see, oh magic crystal ball...
1. Currently you are in the ```FX``` Menu Set. Select the ```Modeling``` Menu Set to get back to editing your models.
2. Edit the cloth as needed and create a crystal ball.
3. Position your crystal ball at the top of your table.
4. Assign materials to your crystal ball and table cloth using the Hypershade Editor.
5. Click on the ```Arnold``` tab and select ```Skydome```.

## Part IV: Render!
1. Look into your channel box and find the tab for your Skydome lighting. Select a ```File``` node for the ```Color``` by selecting the checkerbox.
2. Upload your HDR image.
3. Change the resolution in the channel box editor to match the resolution of the HDR image.
4. Render your scene again and the lighting should now match the lighting in the image.

## Part V: Set up the Skies!
1. Go into your Render Settings, the gear with scene icon under the Surfaces and Deform tab.
2. In the ```Arnold Renderer``` tab, click on the Environment dropdown and select the checkerbox and then "Sky Shader".
3. In your Channel Box, upload the HDR image instead of a color by clicking on the checkerbox, selecting a ```File``` node, and selecting the image.

## Stretch Goals
1. Add other items within your scene!

## Resources
Interface: http://help.autodesk.com/view/MAYAUL/2017/ENU/?guid=GUID-F4FCE554-1FA5-447A-8835-63EB43D2690B
Modeling: http://help.autodesk.com/view/MAYAUL/2017/ENU/?guid=GUID-FC45804D-80D3-4A5D-BA13-25AA86597EEA
HDR Images: http://www.hdrlabs.com/sibl/archive.html
