# FS Align Tools
> This is a brief guide to blender addon - Align Pivot to Edge

We hope that this simple addon will solve some tricky problems of perfectly aligning the pivot (origin) of a blender object

## A. Align pivot to one edge
Suppose we have a mesh (as below) for which we want to align the pivot to one of the edges  
<img src=docs\img\Intro01.png width=300>

1. In edit mode, we select an edge  
<img src=docs\img\Intro02.png width=300>

2. in the right click context menu ...  
<img src=docs\img\Intro03.png width=400>

3. choose Align Pivot  
<img src=docs\img\Intro04.png width=300>
 
4. X-axis of pivot will align to the edge 
<img src=docs\img\Intro05.png width=500>

5. in options menu, you can change the axis
<img src=docs\img\Intro06.png width=500>

6. .. flip direction of alignment ..  
<img src=docs\img\Intro07.png width=500>

7. or change the vertex  
<img src=docs\img\Intro08.png width=500>


*Note: Aligning pivot to one edge will align only one axis of pivot to one edge, other axis will not be aligned to any other edge*

## B. Align pivot to two edges
Suppose we have two edges perpendicular to each other and have a common vertex, and we want to align two axes of the pivot to these two edges  
<img src=docs\img\Intro01.png width=300>

1. In edit mode first select the edge to which you want to align your 'primary' axis of pivot  
<img src=docs\img\Intro11.png width=300>

2. then select the second edge (should have a common vertex with the first edge and should be perpendicular to the first edge)  
<img src=docs\img\Intro12.png width=300>

3. in the right click context menu ...  
<img src=docs\img\Intro13.png width=300>

4. choose Align Pivot .. notice X is aligned to first edge and Y to second edge
<img src=docs\img\Intro14.png width=300>
 
5. You can still change primary axis .. e.g. Y in figure below
<img src=docs\img\Intro15.png width=500>

6. and can still flip direction
<img src=docs\img\Intro16.png width=500>

7. changing vertex will have no effect in 2-edge mode

## Align two objects
1. select both object (object mode) 
<img src=docs\img\2022-04-30_13-16-47.png width=300>
2. change to edit mode  
<img src=docs\img\2022-04-30_13-15-21.png width=300>
3. select one edge from each object 
<img src=docs\img\2022-04-30_13-07-08.png width=300>
4. align object 
<img src=docs\img\2022-04-30_13-06-06.png width=300>
5. use 'other object/edge' to swap 
<img src=docs\img\2022-04-30_13-04-06.png width=300> 

## Rotate an object so that one edge replaces another edge angle
1. with single object selected in edit mode, select two edges
<img src=docs\img\220430_142327.png width=300 height=500>
2. again use the same menu item as above
<img src=docs\img\220430_142418.png width=300> 
3. notice object rotated so that old red is now parallel to old green
<img src=docs\img\220430_142503.png width=300> 

