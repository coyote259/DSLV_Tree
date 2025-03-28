# DSLV_Tree
Do secondary development based on Tree Control Toolkit V1.0.0 , the declaration of the original library can be found at the end of this document.


## Supported LabVIEW versions
2023Q3 and above<br>
If you need support for an earlier version of LabVIEW, please open it in 23Q3 or above and save it as a previous version you need.

## Supported Features
- Support switching the selection status of an item by clicking on the tree item checkbox
- Support querying/traversing the selected status of tree items, judged by the checkbox
- Support multi-state representation of tree items, identified by bold if and different colors

## Possible application scenarios
- Need to select the desired items in the tree menu display
- Different identifiers are needed to represent the current target state

![CheckboxDemo](https://github.com/coyote259/DSLV_Tree/blob/main/assets/CheckboxDemo.gif)

## How to use this lib
Clone or Download this sourecode, copy the DSLV_Tree folder(including the DSLV_Tree.lvlib and the dependecy VIs) to any other where you need them.

# HERE IS THE ORIGINAL README
Tree Control Toolkit V1.0.0

Copyright © 2007, Norman J. Kirchner, Jr.<br>
All rights reserved.<br>
Norman J. Kirchner, Jr.

Author:<br>
Norman J. Kirchner, Jr<br>
NJKirchner@hotmail.com

Distribution:<br>
This code was downloaded from the LAVA Code Repository: http://forums.lavag.org/downloads.html


Description:<br>
Package to provide smart tree functionality without assumption of type of data (ie, file paths or others)<br>
Gives ability to modify contents, extract information and control the branches.<br>
A good understanding of how the LV tree truly operates as a fancy multi-column listbox is very useful although not required.<br>
An expample program if not present on the forums, will be in place soon.

Dependancies:<br>
LV version above base package


Support:<br>
If you have any problems with this code or want to suggest features:<br>
http://forums.lavag.org/index.php?showtopic=####<br>
The above link will be available after your submission has been approved. After you get this link, come back, edit this file and resubmit with the updated link.<br>

Change Log:<br>
1.0.0: Initial release of the code.


License:
This code is distributed under the GNU Lesser General Public License
