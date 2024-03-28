# Path Tool

The path tool is an easy yet remarkably powerful feature of Planning that can be utilized for quick measurements as well as advanced highlighting. In its various forms it can also expedite the creation of complex ground markings, [fences](fence-tool.md#creating-a-fence) and [rooms](the-room-tool.md#creating-a-room).

{% embed url="https://youtu.be/wfdVZQ76_F0" %}
How to use the path tool
{% endembed %}

## Path creation, lengths and angles

The path tool can be activated either by clicking on the path tool icon in the [2D-panel toolbar](../user-interface/the-2d-panel.md#the-toolbar-of-the-2d-panel), or by pressing its shortcut, "P", on your keyboard.

![](../../../.gitbook/assets/iVP_guide_path_tool_menu.jpg)

After activation, a small path icon will follow your curser, indicating that you are in the path mode.

![](../../../.gitbook/assets/iVP_path_tool_mouse_icon.jpg)

To create a path, **left-click on a position** in the [2D-panel](../user-interface/the-2d-panel.md). A small circle will appear, marking the spot of the click and functioning as the first measurement point. When the mouse is moved after the click, a line will appear between the measurement point and the mouse pointer. To set a new measurement point, simply **left-click on another position** in the [2D-panel](../user-interface/the-2d-panel.md).

![](../../../.gitbook/assets/iVP_path_tool_draw_path_line_new.jpg)

During the creation process of the path, each line and corner will automatically display its length or angle.

![](../../../.gitbook/assets/iVP_path_tool_daw_path_angle_new.jpg)

To complete a path, you can either press **Enter** or **double-click on the last measurement point** set. Upon completion, the path is saved as a permanent object that can be adjusted or deleted in the [hierarchy panel](../user-interface/hierarchy-panel.md)

{% hint style="info" %}
If the path contains three or more measurement points, it will automatically be closed after creation (the first and the last measurement points will be connected automatically).
{% endhint %}

![](../../../.gitbook/assets/iVP_path_tool_draw_path_panel_new.jpg)

The path creation can be canceled at any time by pressing the **Escape key**. This allows for quick measurement of distances or angles without creating a permanent path.

## Path editing

Existing paths can be selected by **clicking on the path name** in the [hierarchy panel](../user-interface/hierarchy-panel.md), as well as the [2D-panel](../user-interface/the-2d-panel.md) & [3D-panel](../user-interface/the-3d-panel.md).

To add new points to a selected path, **right-click on a line** and then click on **add point**.  

![](../../../.gitbook/assets/iVP_path_tool_draw_path_right_click_line_new.jpg)

To delete a point, **right click on the point** and then click on **"Delete"**.

![](../../../.gitbook/assets/iVP_path_tool_delete_point.jpg)

To move points, simply **drag them** with the **left mouse button**.  
Points can also be seleceted and moved individually, either in the [2D-panel](../user-interface/the-2d-panel.md) or the [3D-panel](../user-interface/the-3d-panel.md).

### Editing Path Distance and Angles

Existing paths can be further edited to adjust the individual lengths between corner points. To do so, select one of your corner points and edit either the "Distance to previous point" or "Distance to next point" options.

![](../../../.gitbook/assets/iVP_path_tool_edit_corner_distance.jpg)

Additionally, you can edit the individual axis angles of a path. The blue line that gets displayed once a path point is selected serves as the global Y-axis, providing a better reference point when adjusting your angles.  
The angles are measured based on the line between two points, where one of these points is the current point and the other is either the previous or the next point. The angle is formed between this line and global Y axis (blue line).

![](../../../.gitbook/assets/iVP_path_tool_edit_axis_distance.jpg)
## Measurement display options

You can toggle the display of **edge lengths**, **angle** and **area** information for each path by right-clicking on them and selecting the corresponding option in the context menu.

![](../../../.gitbook/assets/iVP_path_tool_context_menu.jpg)

Alternatively it is possible to hide or show all lengths or angles by changing the entry in the measurement section of the [properties panel](../user-interface/the-info-panel.md) and subsequently clicking on **edge lengths**, **angles** or **area**.

![](../../../.gitbook/assets/iVP_path_tool_properties_window_2d.jpg)