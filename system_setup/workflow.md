## Workflow

An effective workflow will allow you to both:  

* build a larger variety of custom profiles
* build profiles quicker

As mentioned in [System Setup](system_setup/system_setup.md), I use:

* [Bluestacks 5](#Bluestacks-5)
* [Windows Magnifier](#Windows-Magnifier)
* [Rainmeter](#Rainmeter)
* [PowerToys Color Picker](#PowerToys-Color-Picker)
* VSCode

## Bluestacks 5

![image](https://github.com/user-attachments/assets/12ff0065-a528-4a69-b3be-0d3c232aed26)

There's a lot of settings that you can tweak, but the relevant ones for building profiles are:

#### Performance Tab

* Frame rate: `60`

#### Display Tab

* Display Resolution: `Landscape`, `1920 x 1080`
    * Generally any 16:9 resolution will maximize the screen area that the profile canvas occupies
    * Depending on the screen resolution of your PC and other tools you want open, you can increase/decrease.

## Windows Magnifier

![image](https://github.com/user-attachments/assets/ab9f9d20-a4d4-40f5-b235-d385dd79d0de)

* Using the built in Magnifier and setting a level with `WIN +` or `WIN -` zooms in on the cursor.
* There's 3 modes, but the default fullscreen mode is what I use the most often.
* At the highest magnification levels, you can align objects with single-pixel percision.
    * Using a mouse rather than a touch allows you to cleanly release objects and not have a finger in the way.

## Rainmeter

![image](https://github.com/user-attachments/assets/a1bffa66-b28b-4eca-9772-788f8d0d1a38)

* Rainmeter is a utility that lets you create custom widgets on Windows.
* I use it to show guidelines or shapes to trace out.
* The simplest way to display an image is with this code:

```
[Rainmeter]
Update=-1

[MeterName]
Meter=Image
ImageName=16_9_spiral.png
H=450
PreserveAspectRatio=1
```

* Place your image file in the same skin directory as the `.ini` and update its `ImageName` and `H=` values in the `.ini`.
* In the Manage Rainmeter screen, I set the following Skin options:
    * Position: `Stay topmost`
    * Transparency: `0%` to `50%` depending on use case
    * ☑️ Click through
    * ☑️ Draggable
    * 🟦 Keep on screen
    * ☑️ Save position
    * 🟦 Snap to edges
 * With `Click through` enabled, you have to click out of Bluestacks, then CTRL + Click + Drag to move the image.
 * This prevents the guides from accidentally being moved while moving objects.
 * As a bonus, lines in the `.ini` with a `#` in front will be treated as comments, so I save symbols and text for my profile here to easily copy-paste them.

## PowerToys Color Picker

![image](https://github.com/user-attachments/assets/ec6658ca-aaf7-4ebb-894b-ce306de46a1a)

* The Color Picker allows you to quickly copy, adjust, and paste colors from anywhere on the screen.
* This is helpful when establishing a color palette or for matching object colors.
* A website which can [calculate variations or complementary colors](https://colorkit.co/color/c0baec/) can be helpful too.

## Visual Studio Code

![image](https://github.com/user-attachments/assets/3d296789-8c76-4aa0-baf5-25b167629e69)

* It's nice to have a text editor with a dark theme and syntax highlighting for modifying Rainmeter files.
* I tend to save code snippets and commonly-used symbols in a text file as well.
* As mentioned in [@sunnisu's Custom Profile Guide](https://docs.google.com/document/d/1QuoVLw477ax07gcBDnvVHX4EncSNXYAl-m3w8V-2EGw/edit?usp=sharing), the `︶` character is useful when making freeform art and cutouts.
* I always have that one available with `<#FFF><scale=1.0>︶`, which does coloring and stretching.
