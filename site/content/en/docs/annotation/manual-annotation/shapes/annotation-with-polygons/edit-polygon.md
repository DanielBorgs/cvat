---
title: "Edit polygon"
linkTitle: "Edit polygon"
weight: 4
aliases:
- /docs/manual/advanced/annotation-with-polygons/edit-polygon/
- /docs/annotation/tools/annotation-with-polygons/edit-polygon/
---

To edit a polygon you have to click on it while holding `Shift`, it will open the polygon editor.

- In the editor you can create new points or delete part of a polygon by closing the line on another point.
- When `Intelligent polygon cropping` option is activated in the settings,
  CVAT considers two criteria to decide which part of a polygon should be cut off during automatic editing.
  - The first criteria is a number of cut points.
  - The second criteria is a length of a cut curve.

  If both criteria recommend to cut the same part, algorithm works automatically,
  and if not, a user has to make the decision.
  If you want to choose manually which part of a polygon should be cut off,
  disable `Intelligent polygon cropping` in the settings.
  In this case after closing the polygon, you can select the part of the polygon you want to leave.

  ![Setting for Intelligent polygon cropping](/images/image209.jpg)

- You can press `Esc` to cancel editing.

  ![Example of editing a polygon shape and canceling editing](/images/gif007_mapillary_vistas.gif)

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