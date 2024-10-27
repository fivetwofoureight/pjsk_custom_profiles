## How to do Backgrounds

When building a custom profile, the first step is usually to establish a background or canvas.  
There's a few ways to do this, but I'd like to highlight 3 simple approaches that I often use:

* [Solid Color Background](#Solid-Color-Background)
* [Images as Background](#Images-as-Background)
* [Patterns as Background](#Patterns-as-Background)

## Solid Color Background

* This approach will make the entire background 1 color.
* First, create a text object with this text:

```
<scale=15><mark=#000000>a
a
a
a
a
a
```
![image](https://github.com/user-attachments/assets/d323cd0e-5d81-404c-b769-759bb1e2eecc)

* Set the [hex color code](https://htmlcolorcodes.com/), which is `#000000`, to your desired color

![image](https://github.com/user-attachments/assets/791e3549-ea96-452b-a88e-d7bd62f9e671)

* Set the `Font Size` slider to the maximum and the `Line Spacing` slider to the minimum

![image](https://github.com/user-attachments/assets/50bef690-cf40-4106-8e38-14f291e1b9eb)

* You now have a solid background to start building your profile on.

  ![image](https://github.com/user-attachments/assets/d42aa4ef-dab1-469e-84ab-de6c6a1e567e)

## Images as Background

* This approach creates a more lively background but also targets readability.
* First, place your desired image.

![image](https://github.com/user-attachments/assets/70a2be38-0c98-4954-858a-532eb5c2c5ae)

* Create a text object with this text:

```
<scale=15><mark=#000000AA><alpha=#00>a
<alpha=#00>a
```

![image](https://github.com/user-attachments/assets/1b5aad86-50d2-4564-ba46-cb4cac4e3c2c)

* Set the [hex color code](https://htmlcolorcodes.com/), which is `#000000`, to your desired color
    * When targeting foreground-background separation and readability, it's often effective to use Black `#000000` or White `#FFFFFF`
    * Some other good options are available using a [Color Picker](/system_setup/workflow.md#PowerToys-Color-Picker) or [palette generator sites](https://colorkit.co/color/b8778d/)
* Set the [hex opacity code](https://davidwalsh.name/hex-opacity), which is `AA`, to your desired opacity

![image](https://github.com/user-attachments/assets/3dcc712b-fad8-401f-9c43-9a291bdf843e)

* Set the `Font Size` slider to the maximum and the `Line Spacing` slider to the lowest value without overlapping the lines

![image](https://github.com/user-attachments/assets/414ea328-4798-45c6-99b7-28c63f377b87)

* Duplicate the layer twice and line them up so there is no visible overlap

![image](https://github.com/user-attachments/assets/ebc2b537-1e35-4f7a-b4ac-2487c724da50)

* You now have an image background but can still have readable text.

![image](https://github.com/user-attachments/assets/763f6af8-a29d-4748-bf7c-82e22e6019ce)

## Patterns as Background

* This cute background is often seen across custom profiles and works with any color scheme
* First, create a text object with this text:

```
<scale=60><mark=#000000AA><alpha=#00>a
```
![image](https://github.com/user-attachments/assets/5ae5ed5f-c568-49ab-adbc-d07ffefe1962)

* Set the [hex color code](https://htmlcolorcodes.com/), which is `#000000`, to your desired color
* Set the [hex opacity code](https://davidwalsh.name/hex-opacity), which is `AA`, to your desired opacity

![image](https://github.com/user-attachments/assets/5f78f61f-e3c3-4c8d-a767-407622d0f8e6)

* Set the width of the line using `Font Size`
* Duplicate the lines and arrage them to form the horizontal stripes

![image](https://github.com/user-attachments/assets/f63afe60-299e-410c-876d-ad40b4066b4a)

* Duplicate the lines again, turning them vertically, and adjust the hex color, hex opacity, and width if desired

![image](https://github.com/user-attachments/assets/35908cf4-f7fb-4b6f-8c5f-14351aff8d1b)

* Create a text object with this text:

```
<scale=60><#000000AA><cspace=-1em>__
```

* Set the [hex color code](https://htmlcolorcodes.com/), which is `#000000`, to your desired color
* Set the [hex opacity code](https://davidwalsh.name/hex-opacity), which is `AA`, to your desired opacity
* Set the outline color to Black, White, or a similar color to the line.
* Set the thickness of the line using `Font Size` and set `Display` to the centered option.

![image](https://github.com/user-attachments/assets/79030693-b2e4-4bf2-851f-a9bf151ddc99)

* Duplicate, rotate, and arrange however you like.

![image](https://github.com/user-attachments/assets/4b9bd168-ccbc-4477-94db-b031da563c92)

* You can use the [Solid Color text object](#Solid-Color-Background) to add a base color as well.
* Now you have a patterned background that works well with photos, notebooks, and decorations.

![image](https://github.com/user-attachments/assets/737bb31c-83cc-4b86-b9ea-88a3dd9b8e83)

