# Room Tool

The room tool can be used to quickly generate room without the need to work with single room elements or manual corrections after dimension changes.

{% hint style="info" %}
The room tool is a special variant of the [path tool](path-tool.md). We recommend to read the [path tool ](path-tool.md)section of this manual first.
{% endhint %}

## Creating a room:

Rooms are based on measurements which can be created with the [path tool](path-tool.md). Afterwards, every path can be turned into a room by **changing the type ** under the Measurments foldout of the [properties](../user-interface/the-properties-panel.md) that is displayed as soon as a path is [selected](path-tool.md#path-selection-and-editing).

![](../../../.gitbook/assets/iVP\_fence\_tool\_create\_room.jpg)

Alternatively, it is possible to **right click** on the desired path, followed by a **click on "Room"**. This will convert the path into a fence as well.

![](../../../.gitbook/assets/iVP\_fence\_tool\_right\_click\_menu\_to\_room.jpg)


## Editing the room shape:

The shape of a room can be changed by [editing the path](path-tool.md#path-selection-and-editing) the room is based on. After changes, the room will automatically be adjusted to the new dimensions.

## Doors and pass-troughs:

It is possible to add doors or pass-troughs to rooms which will automatically be adapted when the room changes. To add one, right **click on a path point** of a selected path in the [2D-panel](../user-interface/the-2d-panel.md) and choose **"Door"** or **"Pass-through"** from the appearing menu.

![](../../../.gitbook/assets/iVP\_fence\_tool\_fence\_right\_click\_point\_options.jpg)

Doors are always placed on the right side of the path point and have a fixed width.

![](../../../.gitbook/assets/iVP\_room\_tool\_room\_door.jpg)

Pass-troughs have a flexible width, they always span from the selected point to the next point on its right side.

![](../../../.gitbook/assets/iVP\_room\_tool\_room\_pass-trough.jpg)

## Room customization:

Rooms can be customized in various ways under the Measurments foldout of the [properties](../user-interface/the-properties-panel.md) if 'Type' has been changed to room. Options are:

* Wall visibility, material and dimensions
* Window visibility, dimensions, spacing and offset
* Ceiling visibility, material and depth
* Floor visibility, material and height

{% hint style="info" %}
If the material chosen for the room seems to have a regular pattern that is visually unsatisfying, you can activate the "Texture Detiling" option in the [graphic settings](../settings/graphic-settings-panel.md). This will reduce the pattern effect.
{% endhint %}

![](../../../.gitbook/assets/iVP\_fence\_tool\_create\_room.jpg)

![](../../../.gitbook/assets/iVP\_room\_tool\_room\_customizations.jpg)
