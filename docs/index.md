---
title: "Adding Media Layers in ArcGIS Online"
layout: "home"
description: "This tutorial will cover how to 'georeference' a raster image through media layers in ArcGIS Online."
staff:
    - name: Nick Field
      link: https://library.utoronto.ca/staff/nick-field
created_date: 2024-03-15
permalink: "/"  #! Remove this if not the homepage
---

# Adding Media Layers in ArcGIS Online

This tutorial will cover how to 'georeference' a raster image through media layers in ArcGIS Online.

Georeferencing is the name given to the process of transforming a scanned map or aerial photograph so it appears “in place” in GIS. By associating features on the scanned image with real world x and y coordinates, the software can progressively warp the image so it fits to other spatial datasets. In this example, a historic Toronto map will be georeferenced using a dataset of city streets so we can see what existed on the site of Robarts Library before it was built.

While it falls under georeferencing in ArcGIS Pro, in ArcGIS Online, it is called a ‘media layer’. It is important to note that media layers are intended for quick visual overlays only, and it is recommended that any more complicated georeferencing be done in ArcGIS Pro. Please see instead our [tutorial on georeferencing in ArcGIS Pro.](https://mdl.library.utoronto.ca/technology/tutorials/how-georeference-images-arcgis-pro)

For a quick overlay of an image however, ‘media layers’ may be what you are looking for.

If you are new to ArcGIS Online, you may also find these tutorials helpful:

* [ArcGIS Online Information, Tutorials, and Workshops](https://mdl.library.utoronto.ca/technology/tutorials/arcgis-online-information-tutorials-and-workshops)
* [Introduction to ArcGIS Online](https://mdl.library.utoronto.ca/technology/tutorials/introduction-arcgis-online)

**Steps:**

[Adding Media](#adding)  
[Repositioning Media](#repositioning)  
[Overlay Manipulation of an Image](#overlay)  
[Side-by-side Manipulation of an Image](#side)  
[Using the Layer](#usinglayers)  
[Saving](#saving)

Adding Media
------------

1. To add a media layer, all that is required is the image you would like to use. For the purpose of this tutorial, please download the [sample scanned map](https://maps.library.utoronto.ca/workshops/MediaLayersTutorial.zip) and save it to a location where the files can be used.

2. To begin, open an untitled map in ArcGIS Online. You can do this by selecting **Map** from the top menu in ArcGIS Online.

<img src='{{ '/assets/images/Media%20Layer_Adding%20Media_002a_0.png' | relative_url }}' alt='ArcGIS Online University of Toronto homepage. There is a red box around the Map button. ' title='' width='1723' height='1116' />

<img src='{{ '/assets/images/Media%20Layer_Adding%20Media_002b.png' | relative_url }}' alt='An untitled map in ArcGIS Online.' title='' width='1395' height='1219' />  
 

3. From there, select **Add > Add media layer**. Please note that currently this feature only supports JPG and PNG images smaller than 10MB.

<img src='{{ '/assets/images/Media%20Layer_Adding%20Media_003.png' | relative_url }}' alt='In the side menu, the add button is selected and the Add media layer is surrounded by a red box. ' title='' width='398' height='397' />  
 

4. You can then select an image from your device, or drag and drop a file. Select **Your Device**. Navigate to where you saved the image and press **Open**.

<img src='{{ '/assets/images/Media%20Layer_Adding%20Media_004a.png' | relative_url }}' alt='The add media pop-up. There is a red box around Your device. ' title='' width='511' height='426' />

<img src='{{ '/assets/images/Media%20Layer_Adding%20Media_004b.png' | relative_url }}' alt='In the computer menu, the image v2-1910-172 is highlighted.' title='' width='841' height='672' />  
 

Once you select a file, it will take you to the media layer editor. The image should appear over your map, at 50% transparency.

<img src='{{ '/assets/images/Media%20Layer_Adding%20Media_005.png' | relative_url }}' alt='An overlay of image v2-1910-172 over a map of the world. The image is at 50% transparency.' title='' width='1397' height='1272' />

5. Now that the image has been added, we can begin to move and manipulate it.

Repositioning Media
-------------------

First, let's move it closer to the actual area.

1. To reposition the image closer to the intended site, **select the search button**. From there, you can input an address. For Robarts, please type: **130 St. George Street Toronto**.

<img src='{{ '/assets/images/Media%20Layer_Repositioning%20Media_001a.png' | relative_url }}' alt='A map in ArcGIS Online with an imaged overlaid on top. The search bar is highlighted. ' title='' width='1423' height='1008' />

The search bar will suggest an address for you. Select the correct one. This will take you to the approximate location of the site.

<img src='{{ '/assets/images/Media%20Layer_Repositioning%20Media_001b.png' | relative_url }}' alt='In a search bar, the words 130 st. george street toronto are surrounded by a red box. The same address below is also circled by a red box. ' title='' width='364' height='294' />

2. In the pop-up, select **Reposition media here**.

<img src='{{ '/assets/images/Media%20Layer_Repositioning%20Media_002.png' | relative_url }}' alt='In the pop-up, the reposition media here button is selected. ' title='' width='622' height='229' />

This will resize your image closer to the desired area.

<img src='{{ '/assets/images/Media%20Layer_Repositioning%20Media_002b.png' | relative_url }}' alt='An overlay of image v2-1910-172 over a map of 130 St. George Street' title='' width='613' height='626' />

3. If you would like to change your base map, you can select the set of arrows from the bottom right-hand corner. This will then bring up various options.

<img src='{{ '/assets/images/Media%20Layer_Repositioning%20Media_003.png' | relative_url }}' alt='A button with two arrows is selected. There are base map options open. ' title='' width='377' height='738' />

Let's leave the base map for now.

Overlay Manipulation of an Image
--------------------------------

1. There are various ways that you can change the image, the first of which is by manually altering the image. When you add the media layer, the map will automatically add it as an overlay image.

2. To scale the image, select any of the orange boxes in the corners to drag the image bigger or smaller. Please note that if you would like to keep the image aspect ratio locked, you must hold **shift** as you resize the image.

<img src='{{ '/assets/images/Media%20Layer_Overlay_002.png' | relative_url }}' alt='An overlay of image v2-1910-172 over a map of 130 St. George Street. The corners of the selection box are highlighted. ' title='' width='1893' height='1191' />

3. To rotate the image, grab and drag the orange circle at the bottom of the image.

<img src='{{ '/assets/images/Media%20Layer_Overlay_003.png' | relative_url }}' alt='An overlay of image v2-1910-172 over a map of 130 St. George St. The rotation circle at the bottom of the image selection is highlighted. ' title='' width='709' height='779' />

4. From here, you can manually manipulate the image to match up with the map below. When you are done, it should look something like this.

<img src='{{ '/assets/images/Media%20Layer_Overlay_004.png' | relative_url }}' alt='An overlay of image v2-1910-172 is lined up with the base map below.' title='' width='1739' height='1119' />

***Note:*** If you want a reminder of shortcuts that are available in the media editor, on the top left-hand side there are a set of tips.

<img src='{{ '/assets/images/Media%20Layer_Overlay_002b.png' | relative_url }}' alt='The tips button is highlighted. A list of ArcGIS Online shortcuts are in a pop up. ' title='' width='403' height='414' />

 

Side-by-side Manipulation of an Image
---------------------------------------

1. An additional method for using a media layer is to use control points in order to manipulate the map. To begin, please select **Side-by-side** in order to change the view of the map.

<img src='{{ '/assets/images/Media%20Layer_SidebySide_001.png' | relative_url }}' alt='The Side-by-side button is highlighted. ' title='' width='1739' height='1278' />

2. The side-by-side view should provide you with the scanned map on the left, and the ArcGIS Online map on the right. Both maps should have four control points that you can then move.

<img src='{{ '/assets/images/Media%20Layer_SidebySide_002.png' | relative_url }}' alt='The map image is on the left. On the right is the base map. There are four control points on both images. ' title='' width='2022' height='1216' />

3. Once the maps have loaded, move the control points to line up with the four outer intersections on the map.

<img src='{{ '/assets/images/Media%20Layer_SidebySide_003a.png' | relative_url }}' alt='Four control points are lined up on four intersections in both the base map and the image. ' title='' width='1618' height='1093' />

Luckily this image had midpoints on all intersections. We can use them here to more closely line up our map.

<img src='{{ '/assets/images/Media%20Layer_SidebySide_003b.png' | relative_url }}' alt='Two control points are placed on line intersections. There are red boxes around both points. ' title='' width='2022' height='1216' />

4. When you are satisfied with where the image is, select **Update and Close** in order to save the layer.

<img src='{{ '/assets/images/Media%20Layer_SidebySide_004a.png' | relative_url }}' alt='There is a red box around the Update and Close button. ' title='' width='2023' height='1209' />

At the end, it should look something like this.

<img src='{{ '/assets/images/Media%20Layer_SidebySide_004b_0.png' | relative_url }}' alt='The map image is fully opaque. There is a menu with the layer information. ' title='' width='2024' height='1136' />  
 

Using the Layer
---------------

1. If you would like to further edit the layer after updating, you can select **Edit Placed Media**. It will then take you back to the Overlay/Side-by-side image editor.

<img src='{{ '/assets/images/Media%20Layer_Using%20the%20Layer_001.png' | relative_url }}' alt='There is a red box around the Edit Placed Media button. ' title='' width='1742' height='1149' />

To work on other layers, you can close the layer information by selecting the **X** in the top right-hand corner.

<img src='{{ '/assets/images/Media%20Layer_Using%20the%20Layer_002.png' | relative_url }}' alt='In the properties menu, the top X is selected. ' title='' width='397' height='1143' />

3. If you have exited out of the layer to work on other layers, you can also get back into the media layer by selecting **Layers > Show Properties > Edit Placed Media**.

<img src='{{ '/assets/images/Media%20Layer_Using%20the%20Layer_003_0.png' | relative_url }}' alt="Under the layers menu, the image's layer is selected. Show properties is selected underneath. " title='' width='468' height='317' />

<img src='{{ '/assets/images/Media%20Layer_Using%20the%20Layer_003b.png' | relative_url }}' alt='In the properties menu, the Edit Placed Media button is selected. ' title='' width='423' height='793' />  
 

 

Saving
------

1. Once you are satisfied with your image, you can save your map. In order to save, select the folder icon from the left-hand menu and select **Save As**.

<img src='{{ '/assets/images/Media%20Layer_Saving_001.png' | relative_url }}' alt='In the left hand menu, the save menu is open. Save As has been selected. ' title='' width='455' height='668' />

From there, it will take you to a pop-up menu in order to name and save your map.

<img src='{{ '/assets/images/Media%20Layer_Saving_002.png' | relative_url }}' alt='The save pop-up menu. The title and save button have been highlighted. ' title='' width='514' height='537' />

And that's it!

Additional Resources
--------------------

* [ArcGIS Online: Information, Tutorials, and Workshops](https://mdl.library.utoronto.ca/technology/tutorials/arcgis-online-information-tutorials-and-workshops)
* [Accessing Online GIS Classes in Esri Academy](https://mdl.library.utoronto.ca/technology/tutorials/how-access-online-gis-classes-esri-academy)

Technique: [Georeferencing](https://mdl.library.utoronto.ca/technique/georeferencing) | Tools: [ArcGIS Online](/taxonomy/term/69) | Data Format: [Raster](https://mdl.library.utoronto.ca/data-format/raster)
