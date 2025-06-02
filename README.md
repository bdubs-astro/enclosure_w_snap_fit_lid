<h2>3D-Printed Enclosure w/ Snap-Fit Lid</h2>

<img src = "./docs_for_README/Fusion_logo_new.jpg" width = "160"/>

<!--
<img src = "./docs_for_README/Fusion_logo_new_v3.jpg" width = "300"/>
-->

<br>

I created a **Autodesk Fusion** design for a generic, scalable enclosure with a snap-fit lid. The design is divided into two components: *base* and *lid*.

<img src = "./docs_for_README/browser.png" width = "250"/>

**Design Features:**

- fully parametric

- snap-fit joints on the two long sides

- uses the Sweep command to create semi-circular beads and corresponding recesses

- dimensions driven by the bead radius and the width of the gap between
the lid and the base

- beads and recesses are filleted with radius equal to twice the width of the gap

- notch on each side to facilitate lid removal


<img src = "./docs_for_README/animation_screenshot.png" width = "400"/>

<img src = "./docs_for_README/lid_inverted.png" width = "400"/>

<img src = "./docs_for_README/cross-section.png" width = "400"/>

The *Display Component Colors* command found in the *Inspect* menu is extremely useful. Note that it also color codes the timeline entires, making it easier to locate the various features for editing.

<img src = "./docs_for_README/display_component_colors.png" width = "600"/>

The *Section Analysis* command found in the *Inspect* menu allows you to view cross sections through various construction planes. Once created, these will appear in the *Analysis* section of the *Browser*.

<img src = "./docs_for_README/cross-section_menu.png" width = "600"/>

*User Parameters* can be defined/modified using the *Change Parameters* command found in the *Modify* menu. You can also designate *Favorites*.

<img src = "./docs_for_README/user_parameters_screenshot_v2.png" width = "600"/>

The *Change Parameters* command can also be used to view/modify the various *Model Parameters* that are created as the design is edited.

<img src = "./docs_for_README/model_parameters_screenshot_better.png" width = "600"/>

The *Animate joint* command can be found by right-clicking on the selected joint in the *Joints* section in the browser. Here the motion limits can be defined.

<img src = "./docs_for_README/joint_analysis_menu.png" width = "600"/>
