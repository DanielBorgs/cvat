---
title: 'Annotation with polylines'
linkTitle: 'Polylines'
weight: 3
description: 'Guide to annotating tasks using polylines.'
aliases:
- /docs/manual/advanced/annotation-with-polylines/
- /docs/annotation/tools/annotation-with-polylines/
---
It is used for road markup annotation etc.

Before starting, you need to select the `Polyline`. You can set a fixed number of points
in the `Number of points` field, then drawing will be stopped automatically.

![Highlighted "Polyline" button with open "Draw new polyline" window](/images/image085.jpg)

Click `Shape` to enter drawing mode. There are two ways to draw a polyline —
you either create points by clicking or by dragging a mouse on the screen while holding `Shift`.
When `Shift` isn't pressed, you can zoom in/out (when scrolling the mouse wheel)
and move (when clicking the mouse wheel and moving the mouse), you can delete
previous points by right-clicking on it.
Press `N` again or click the `Done` button on the top panel to complete the shape.
You can delete a point by clicking on it with pressed `Ctrl` or right-clicking on a point
and selecting `Delete point`. Click with pressed `Shift` will open a polyline editor.
There you can create new points(by clicking or dragging) or delete part of a polygon closing
the red line on another point. Press `Esc` to cancel editing.

![Example of annotation with several polylines](/images/image039_mapillary_vistas.jpg)

### Scaling, Rotating, and Mirroring

**Bounding Box Edit Mode (Scaling and Rotation)**
To scale or rotate a shape as a whole, rather than editing individual points:
1. Select the shape.
2. Press `S` or click the **BBox edit mode** button on the Object Sidebar.
3. A bounding box will appear around the shape.
   - **Scale:** Drag any of the bounding box corners or edge handles to resize the shape.
   - **Rotate:** Click and drag the rotation handle (the point extending from the bounding box) to rotate the shape around its center.
4. Press `S` again to exit the bounding box edit mode.

**Mirroring Shapes**
You can mathematically mirror a shape across its center axis:
- **Mirror horizontally:** Press `Shift+H` or select **Mirror horizontally** from the object's action menu in the sidebar.
- **Mirror vertically:** Press `Shift+V` or select **Mirror vertically** from the object's action menu in the sidebar.