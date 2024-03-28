# Virtual Cameras

iVP has the ability to record virtual dolly shots built in. By setting up virtual cameras it is possible to produce simple videos in minutes. If your objective are more advanced, absolute photo-realistic recordings, please have a look at our rendering software iVP CGI or [contact us](https://www.ixtenda.com).

{% hint style="info" %}
If you want work with virtual cameras regularly, it would probably be helpful to make use of the different [layouts](../user-interface/layouts.md) iVP offers.
{% endhint %}

## Adding new virtual cameras:

To add new cameras, first open the [virtual camera panel](../user-interface/virtual-camera-panel.md) by clicking on its icon on the [top bar](../user-interface/the-top-bar.md).

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_camera\_panel\_icon.jpg)

In the virtual camera panel, simply click on the "Add camera" button.

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_camera\_panel\_add\_camera.jpg)

The new camera will now appear in the hierarchy panel and is ready for setup.

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_machine\_list\_panel.jpg)

Alternatively, it is also possible to create a new virtual camera that will positioned to match the current [3D-panel](../user-interface/the-3d-panel.md) view (position and rotation of the camera will be set automatically). To do so, click on the "Add current camera view" icon on the [toolbar of the 3D-panel](../user-interface/the-3d-panel.md#the-toolbar-of-the-3d-panel).&#x20;

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_3D-panel\_add\_adjusted\_camera\_icon.jpg)

## Setting camera position and rotation:

Virtual cameras behave like regular objects when it comes to [position ](../machines/move-objects.md)and [rotation](../machines/scale-and-rotate-objects.md). As other objects, they appear in the 2D- and 3D-panel and can be [moved around](../machines/move-objects.md) or [rotated](../machines/scale-and-rotate-objects.md) in the same way.

{% hint style="info" %}
It is also possible to [move](../machines/move-objects.md) or [rotate](../machines/scale-and-rotate-objects.md) several cameras at once. To do so, simply [select](../machines/selecting-and-moving-objects.md) multiple cameras before you make changes in the [2D-](../user-interface/the-2d-panel.md)or [3D-panel](../user-interface/the-3d-panel.md).
{% endhint %}

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_objects.jpg)

Furthermore, a virtual camera can be manipulated by its values in the [info panel](../user-interface/the-info-panel.md) after it has been selected.

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_position.jpg)

{% hint style="info" %}
To set up exactly the desired perspective, it is possible to [display a cameras output](virtual-cameras.md#displaying-the-output-of-a-virtual-camera) live.
{% endhint %}

## Displaying the live output of a virtual camera:

The output of a virtual camera can either be viewed in the [virtual camera panel](../user-interface/virtual-camera-panel.md) or in the [3D-panel](../user-interface/the-3d-panel.md). To achieve the latter, toggle the camera mode of the [3D-panel](../user-interface/the-3d-panel.md) by **clicking on the small camera icon** at the left end of the [3D-panel toolbar](../user-interface/the-3d-panel.md#the-toolbar-of-the-3d-panel).

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_3D-panel\_camera\_mode\_icon.jpg)

The icon will change to indicate the mode change and it will be possible to **select a camera from the drop-down** list next to the icon.

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_3D-panel\_camera\_mode\_dropdown.jpg)

{% hint style="info" %}
While the output of a camera is displayed in the 3D-panel, the regular [camera movement](../getting-started/moving-the-camera.md) is not possible. However, is it possible to switch back to the regular camera mode of the 3D-panel by clicking on the icon at the left end of the [3D-panel toolbar](../user-interface/the-3d-panel.md#the-toolbar-of-the-3d-panel) again.
{% endhint %}

## Setting up virtual dolly shots:

After [setting up position and rotation of the virtual cameras](virtual-cameras.md#setting-camera-position-and-rotation), it is necessary to specify the transitions between the cameras and the timeline which defines which camera will be displayed at what time later on in the rendered video.

The first way to adjust the default settings for each camera is to **adjust the respective values in the** [info panel](../user-interface/the-info-panel.md) after the virtual camera in question has been selected. Hereby, the values have the following meaning:

* **Camera index:** defines, when the camera will be rendered - the higher the index, the later the camera will be positioned in the timeline that defines the order of the shots in the video later on
* **Field of view:** defines the area the camera is able to render - higher values result in a "wider" perspective&#x20;
* **Blend in:** how the transition to this camera will look like
  * Cut:
  * EaseInOut:
  * EaseIn:
  * EaseOut:
  * HardIn:
  * HardOut:
* **Blend time:** how long the transition to this camera will take
* **Hold time:** how long this cameras perspective will be visible in the video later on

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_blend\_settings.jpg)

The second, however limited way to alter the camera settings is to do it via the [camera list panel](../user-interface/camera-list-panel.md) which can be opened by clicking on its icon on the [top bar](../user-interface/the-top-bar.md#icons).

![](<../../../.gitbook/assets/iVP\_virtual\_cameras\_camera\_list\_icon (1).jpg>)

In the [panel](../user-interface/camera-list-panel.md), it is possible to adjust the camera index, hold time and blend in (= "Nr.", "Hold", "Fade").

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_camera\_list\_panel\_camera\_settings.jpg)

If you want to exclude cameras you set up from the final video without [deleting](../machines/delete-objects.md) them, you can do so by clicking on the check marks of the cameras in the [camera list panel](../user-interface/camera-list-panel.md).

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_camera\_list\_panel\_camera\_selection.jpg)

## Recording virtual dolly shots:

After [setting up](virtual-cameras.md#setting-up-virtual-dolly-shots) a virtual dolly shot, it can be rendered into a video by **clicking on the record button**. The clip will then be rendered and saved in your video folder.

{% hint style="info" %}
Currently it is not possible to set an individual output folder or change the file format of the clip.
{% endhint %}

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_camera\_list\_panel\_record\_icon.jpg)

## Renaming cameras:

Virtual cameras can be [renamed like objects](../machines/renaming-objects-and-folders.md). Additionally, they can be renamed in the [camera list panel](../user-interface/camera-list-panel.md) that can be opened by clicking on its icon on the [top bar](../user-interface/the-top-bar.md#icons).

![](<../../../.gitbook/assets/iVP\_virtual\_cameras\_camera\_list\_icon (1).jpg>)

![](../../../.gitbook/assets/iVP\_virtual\_cameras\_camera\_list\_panel\_camera\_rename.jpg)

## Deleting cameras:

Virtual cameras can be [deleted like objects](../machines/delete-objects.md).
