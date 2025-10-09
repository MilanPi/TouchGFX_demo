# 4. How to create a GUI with one screen
[<-- Back to main menu](README.md)

1. Place on the canvas the first widget - a **Box**.

![](imgs/box.png)

2. Enlarge the **Box** to cover all the screen canvas - it will serve as **white background**.

3. Put on the canvas a **textArea** widget.

![](imgs/textArea.png)

4. Change the font to be a "Copper Black".

![](imgs/ChangeFontCopperBlack.gif)

4. Change text to "Screen 1" and move the **textArea** to top and center of the canvas (use automatic green **alignment guide lines**).
```
Screen 1
```

![](imgs/textAreaPosition.gif)

5. Copy-paste this textArea to produce three more textArea widdgets to create similar layout seen bellow:
> In the **Properties** panel -> **Location** put these **Y** axis coordinates:
```
100
200
300
```
![](imgs/textLayout.png)

5. Put on the canvas three circles, change their color to create similar layout seen bellow:

![](imgs/circle.png)

> Hint: Re-arange widget z-order in the Screens panel.

> Tip: use automatic green **alignment guide lines** to position circles in the middle of the textArea widget.

![](imgs/Screen1Layout.png)

6. Click on **Generate Code** button (or pres F4 key)

![](imgs/generate.png)

7. Open the project in the **STM32CubeIDE**, build the project(s) and flash the board using a **flash script**.

> see [How to build and flash TouchGFX application on STM32N6570-DK discovery board](02_How_to_build_and_flash_TouchGFX_application_on_STM32N6570-DK_discovery_board.md)

Continue with [How to use Interractions](05_How_to_use_Interractions.md)

[<-- Back to main menu](README.md)