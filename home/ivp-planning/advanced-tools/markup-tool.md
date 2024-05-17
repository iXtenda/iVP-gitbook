# Markup Tool

The markup tool is an easy to use function of iVP that can be used to annotate issues or highlights inside your project and improve communication with colleagues and clients.

For better understanding and training we created a iVP YouTube Tutorial where you can find a detailed information for the markup tool.

{% embed url="https://youtu.be/DYKIYcZMrVE" %}
How to use the markup tool
{% endembed %}

## Placement:

The markup tool can be activated by clicking the markup icon in the [2D-panel toolbar](../user-interface/the-2d-panel.md#the-toolbar-of-the-2d-panel).

![](../../../.gitbook/assets/markup\_icon.jpg)

As soon as the tool is active, a small markup icon will follow the mouse cursor to indicate that you are in the markup mode.

![](../../../.gitbook/assets/markup\_cursor.jpg)

To create a markup, **left click on a position** in the [2D-panel](../user-interface/the-2d-panel.md) or [3D-panel](../user-interface/the-3d-panel.md). A blue markup (a pin resembling a map location marker) will appear that marks the spot where you clicked and functions as an interactable highlight point.

![](../../../.gitbook/assets/markup\_placement.jpg)

The placed markup will be added to the [hierarchy](../user-interface/the-machine-list.md) and can be used like any other object. It can be [renamed and grouped in folders](../machines/renaming-objects-and-folders.md), [set in/visible](../user-interface/hierarchy-panel.md#hideunhide-objects), set to be [un/locked](../user-interface/hierarchy-panel.md#lockunlock-objects) and [recolored](../machines/highlighting-objects.md).

## Editing a Markup:

After placing a markup, the [properties panel](../user-interface/the-properties-panel.md) will show the default options to [move an object](../machines/move-objects.md#moving-objects-via-the-info-panel) and foremost a section to edit the selected markup.

![](../../../.gitbook/assets/markup\_properties.jpg)

## The default fields:

* Default: the general information of a markup regarding
    * _**Name:**_ the name of the object which [can be changed](../machines/renaming-objects-and-folders.md) at any time
    * _**ID:**_ the unique ID of the object which is generated when the markup is [placed](../machines/first-steps-with-3d-object.md) in the [2D-](../user-interface/the-2d-panel.md) or [3D-panel](../user-interface/the-3d-panel.md); the ID is unchangeable 
    * _**Author:**_ the author of the markup, per default "Planner"; this information is unchangeable and independent from the object name
    * _**Created:**_ exact time and date when the markup was created; this information is unchangeable
* Transform: the panel containing information of the markup regarding
    * _**Dimensions:**_ the dimensions of the object; this information is only changeable by changing the [scale](../machines/scale-objects.md)
    * _**Position:**_ the position of the object, changing this will [move the object](../machines/move-objects.md#moving-objects-via-the-info-panel)
    * _**Scale:**_ the [scale](../machines/scale-objects.md) of the object; use with caution!
    * _**Rotation:**_ the [rotation](../machines/scale-and-rotate-objects.md) of the object
* Markup: the panel containing information about the markup regarding
    * _**Priority:**_ a Priority can be set for each individual markup, which helps with sorting markups in the [markups panel](../user-interface/markups-panel.md) and works great if combined with [recoloring](../machines/highlighting-objects.md)
        * _**Low:**_ set the priority of the selected markup to low
        * _**Medium:**_ Set the priority of the selected markup to medium (default)
        * _**High:**_ set the priority of the selected markup to high
    * _**Status:**_ the status of a markup can be set and this information will be reflected in the [markups panel](../user-interface/markups-panel.md).
        * _**Open:**_ Set the status of the selected markup to open (default)
        * _**Closed:**_ set the status of the selected markup to closed
    * _**Description:**_ the description of the selected markup

## Conversation with Markups:

In addition to the description of a markup, it is possible to **add information to a markup without creating a new one**.

The conversation section contains all text entries and screenshots made by users using the markup tool.

![](../../../.gitbook/assets/conversation.jpg)

## Using Conversations:

The conversation tab can be opened by **clicking on the corresponding markup** and will be shown in the lower part of the [properties](../user-interface/the-properties-panel.md).

|                                                                           |                                                                                                                                                                                                                                                                                                              |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![](../../../.gitbook/assets/conversation\_reply.jpg)                      | Input field for text to be shown in the conversation below
|
| ![](../../../.gitbook/assets/conversation\_send\_text.jpg)                 | Sends text to be shown in conversation below (alternatively press **Enter** in the input field ) 
|
| ![](../../../.gitbook/assets/conversation\_create\_screenshot.jpg)         | Replaces the [3d-view](..user-interface/the-3d-panel.md) with a panel that lets you [take and edit screenshots](/markup-tool.md#taking-a-screenshot-in-conversations)
|
| ![](../../../.gitbook/assets/conversation_text.jpg)                        | After sending a text it will be shown in a chat with date/time of the text and who posted it; to delete a text, click the small bin icon
|
| ![](../../../.gitbook/assets/conversation\_screenshot.jpg)                 | After [creating a screenshot](#taking-a-screenshot-in-conversations) it will be shown with the date and time it was posted; to delete a screenshot from the conversation, click the small bin icon
|
| ![](../../../.gitbook/assets/conversation\_screenshot\_reply.jpg)          | Reopens the panel to [create a screenshot](#taking-a-screenshot-in-conversations) and will post a new screenshot in the conversation after confirming
|

## Taking a screenshot in Conversations

After you press the Button **Create Screenshot**, the [3d-view](../user-interface/the-3d-panel.md) will be replaced with a panel that offers the possibility to take and edit screenshots.

![](../../../.gitbook/assets/markup\_screenshot\_panel.jpg)

You can use the 3d-view to [change the content of the screenshot](../getting-started/moving-the-camera.md) until it fits your need.

![](../../../.gitbook/assets/markup\_screenshot\_panel\_buttons.jpg)

When you are ready to take the screenshot, you have the option to confirm or cancel the screenshot. To do so, use **the buttons in the upper right corner of the screenshot**.

![](../../../.gitbook/assets/markup\_screenshot\_panel\marking\_bar.jpg)

|                                                                           |                                                                                                                                                                                                                                                                                                              |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_color.jpg)        | Change the color of the brush
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_brush.jpg)        | Use a brush to scribble directly onto the screenshot; change the size of the brush by clicking the small triangle in the corner 
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_eraser.jpg)       | Use an eraser to delete scribbles on the screenshot; change the size of the eraser by clicking the small triangle in the corner
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_clear.jpg)        | Delete all scribbles on the screenshot; does not delete the screenshot itself!
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_undo.jpg)         | Undo the last action (painting or erasing), or redo the last action
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_confirm.jpg)      | Confirm the screenshot and send it to the conversation, or cancel the screenshot 
|