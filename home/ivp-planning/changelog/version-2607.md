---
title: Version 2607
description: Changelog of version 2607
---

## Version 2607.0.0
_2026-07-01_

### Highlights
- __Detachable Panels__ — detach panels from the Planning software.
- __Undo System__ improvements — in brief: it now works (almost) everywhere.

### Feature Updates
#### Detachable Panels
- Panels can now be detached from the software's interface. They can be dragged, sized and placed anywhere on the desktop.

#### Undo System Improvements
- We have completely revamped the __undo/redo system__
- Overall capabilities to work within every functionality of the __2D View and with the 3D View__, e.g. the __Path Tool__, __Colorization__ or __Mirroring__.
- It also affects __main interface actions__ like machine selection, sorting and duplication.
- Scaling down to the smallest unit __customization changes__ will also be affected.

#### Folders
- You can now __move folders__ on the first level of the Hierarchy to better sort your project's content.
- We have also added the ability to move the folder Pivot to the __center__ of the included objects.
- The state and customizations of machines inside folders will stay intact during __duplication__ and the loading/initialization behaviour could be haredened.

#### 2D View
- The 2D View now supports a __more accurate__ representation of intersecting machines on different heights

#### 2D Resize Tool
- The resize tool now shows a __preview__ highlighting the final size of objects that can be scaled in predefined steps, e.g. the transports.

#### Path Tool
- Fix Paths __mirrored__ on loading Plan file in some cases
- __Fences with passthroughs__: we changed the __standard working height__ of passthroughs to 1000mm.
- A new option is now available: paths can now be set to __Railing__ offering you the option to work with safety railings.

#### Camera Panel
- __Camera controls__ have been added to the external panel.
- We also included a __hint__ explaining why the camera movement is blocked in ceratain scenarios.

#### Save/Load
- We have generally hardened the __saving and loading behaviour__ of .plan files resolving issues with misconfigured concepts or missing imports.

#### DXF Re-Import and stabilization
- We have added a new functionality to __re-import__ an already existing __DXF file__ inside your concept. With this you can now easily adjust scaling and display properties without the need to delete your file from the project.
- The general __file handling__ of DXF files has been hardened and stabilized.

---

### General Bugfixes
- Resolved several issues affecting PDF export to improve reliability and output consistency.
- Fixed an issue where plan files containing embedded PDFs could, in some cases, fail to display the PDF after loading.
- Corrected the calculation of Bounds for parent objects when new child objects are added dynamically.
- Improved the performance of the Properties panel, resulting in a more responsive editing experience.
- Fixed the missing preview that could occur while reordering docked panels.
- Resolved an issue where machines with dynamic customizations were not loaded correctly when opened from a file while initially hidden.
- Fixed issues that could occur when importing .glb files, improving compatibility with a wider range of models.
- Resolved discrepancies between the 2D and 3D views to ensure more consistent visualization.
- Fixed save and load issues that could occur when working with OneDrive or other network-based storage locations.
- Improved the tracking and handling of recent files for more reliable access to recently opened projects.
- Optimized application performance across different quality settings for a smoother user experience.

---

### Machine & Asset Updates

#### Bug Fixes

- **Robot (Universal)**
  - Fixed an issue where the robot could be mirrored along the wrong axis when using vertical mirroring.

- **Stack (Universal)**
  - Resolved an issue where the workpiece material was not updated correctly under certain conditions.
  - Stabilized cases where workpieces could exhibit unintended material overhang.
  - Improved overall performance when working with Stack assets.

- **Workpiece (Universal)**
  - Optimized performance to provide a smoother editing and visualization experience.

- **Geometric Bodies**
  - Geometric bodies can now be resized correctly even after being rotated.
  - Fixed several issues affecting the rendering and handling of transparency.

- **Hedgehog V-200**
  - Resolved an issue where the protective fence could break when the machine was mirrored in certain configurations.

- **TFR, TFZ, TFB, TFW**
  - Improved performance across the machine family.
  - Added a new option to show or hide the machine feet.

- **Strap Conveyor (TFZ531)**
  - Fixed visual inconsistencies that could occur in specific customization states.

- **STORETEQ P-X00 (TLF-X12)**
  - Fixed issues affecting resizing operations when using the **2D Resize** tool.

#### Additions & Improvements

- **STORETEQ H-600**
  - Adjusted the position of the lowest shelf to the correct working height according to the official machine plans.

- **STACKTEQ G-500 (TBP 420)**
  - Support pillars can now be individually removed and repositioned, providing greater flexibility during layout planning.

- **Control Terminal (Universal)**
  - Added new display masks for **woodStore** and **woodTrans** systems.
  - Fixed an issue where display masks could appear mirrored under certain conditions.

#### Removed
- Removed SORTEQ H-200

---

### New Machines
- Signal Light
- Central Signal Light System


## Version 2607.1.0
_2026-07-08_

### Highlights
- __Properties Panel__ - more stable functionality and usability

### Feature Updates
- __PDF files__ can now be set to __four different levels of transparency__ to improve the workflow.

### General Bugfixes
- We __fixed__ issues with the __Properties Panel__ leading to performance and usability problems.
- __Hidden objects__ inside Library concepts are __not dectivated/blocked__ anymore after unpacking.
- The functionality of the __Path Tool__ has been __stabilized__ further to prevent errors with edge cases.

### Machine & Asset Updates

#### Bug Fixes

- __CENTATEQ N-510__
    - __Stabilized__ the properties and customization settings.
    - __Fixed__ some wrong __customizations__, e.g. the cooling unit.