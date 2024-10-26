## How to do Backgrounds

When building a custom profile, the first step is usually to establish a background or canvas.  
There's a few ways to do this, but I'd like to highlight 3 simple approaches that I often use:

* [Solid Color Background](#Solid-Color-Background)
* [Images as Background](#Images-as-Background)
* Patterns as Background

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
