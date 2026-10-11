# DAZ Dragon 3 PowerPose Template

I made this during 2020 to quick pose my red dragon character made from [DAZ Dragon 3](https://www.daz3d.com/daz-dragon-3) figure and it's morphs add-ons for use as drawing reference. It have been update and adding more functionality since then.

The template have neck, tail, wings, abdomen, legs, feet, hands and minimal head posing control that work good enough for my use.

There are some posing functionality I want to include to the template, but I have not include it due to PowerPose bugs with Dragon 3. Such as wings and arm pose control. If I find a workaround for the issue, I'll add it in the future.

# Installation

Copy all the files to `<Your DAZ Studio Library>/data/DAZ 3D/DAZ Dragon 3/Base/Tools/PowerPose/`.
Then run DAZ Studio and navigate to menu bar, select `Window` -> `Panes (Tabs)` -> `PowerPose`, then drag the PowerPose window to the left tabs group.

# DAZ Studio PowerPose bugs

PowerPose have some bugs with Dragon 3 figure. These are bugs I encounter while making this PowerPose template.

* PowerPose template will sometimes map the arm to wing, hand to wing-hand, fingers to toe if it assigned to Node or Node Group.
* It have trouble adjusting the bone rotation with asymmetry bone sliders, it will snap to 0 value instead of "0 value" that calculated from minimal/maximum rotation limit. Can see this bug when assign `rWingForearm` to Node.
