# [[ ✩ DOTS BY DIZZY  ✩ ]]

**A minimal but stylish Rofi App Launcher**
___________________________________________________________________


:dizzy: Designed to be toggled open/closed from Polybar

:dizzy: Remains as a banner image and a search bar until typing

:dizzy: Displays 3 rows when typing into search bar

___________________________________________________________________
> [!IMPORTANT]
> **Required**
> - Rofi
___________________________________________________________________


![Rofi](001a.png)
![Rofi when Typing](001b.png)


___________________________________________________________________

> [!TIP]
> You can edit the config to toggle from your own preferred task bar, this one is used by Polybar.
> 
> Be aware of rofi-toggle.sh if not using Polybar
>
> 
> Additionally, you can change cat3.png to your own desired image,
> 
> just make sure it's large enough ! Or it will look weird :smiley_cat:
>
> You alternatively change the size of the box in launcher.rasi under window width.
>
> :cat:

___________________________________________________________________

If you are also using Polybar, here is my Rofi Launcher Polybar Module:


**App Launcher - Rofi**


```[module/arch]
type = custom/script
exec = ~/.config/polybar/scripts/rofi-toggle.sh
tail = true
click-left = rofi -show drun -theme ~/.config/rofi/launcher.rasi &
label-foreground = ${colors.accent}
label-padding = 1
label-font = 6
```


___________________________________________________________________

:heavy_minus_sign: Add a [module/rofi] or module / whatever you choose to name the module


:heavy_minus_sign: Add rofi or whatever you chose to name it to your Polybar bar module.

___________________________________________________________________


> [!IMPORTANT]
> :star: ! Make sure to review the official documentaion ! :star:
> 
> Rofi documentaion included below !  :two_hearts:



___________________________________________________________________


# OFFICIAL DOCUMENTATION



### ROFI REPO:

:link: 
[Rofi Repo Git Clone](https://github.com/davatorium/rofi)

 
### ROFI DOCUMENTATION:

:link:
[Official Documentation](https://davatorium.github.io/rofi/)
___________________________________________________________________
