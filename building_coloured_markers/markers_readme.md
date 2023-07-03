> # Coloured Markers
With the correct CSS colors, webpages can be aesthetically pleasing to readers. 

> ## Objective
- How to use the `three methods` of adding `flat` coloring:  
    - The First One is **`Hex`** method, which is a common way of applying coloring  to elements. _(e.g green = `#00ff00`)_
    -  The Second being **`RGB`** coloring method: which is each red, green, and blue value is a number from 0 to 255. _(e.g red =`rgb(255, 0, 0)`)_
    - And The Third **`HSL`**; _hue, saturation, lightness_, method, which accepts 3 values: a number from 0 to 360 for `hue`, a percentage from 0 to 100 for `saturation`, and a percentage from 0 to 100 for `lightness` _(e.g blue = `hsl(240, 100%, 50%)`)_
-   How to apply  `gradient` and `transition` to elements:
    -   ` Gradient` is one color transitioning into another. 
    -   The  `linear-gradient` function gives you control over the `direction`and `transition` along a degree line, and which colors are used.
    -   The syntax is `linear-gradient(gradientDirection, color1, color2, ...);` and  `gradientDirection` is the direction of the line used for the transition  while `color1` and `color2` are color arguments (it can be any coloring method).
    - `Color-stops` allow you to fine-tune where colors are positioned along the gradient line. Either `px` or `percentages` units can be used in this case after the color.
-   How to blur elements with `Opacity` or the using `alpha` channel:
    -   `Opacity` is how opaque(transparent) an element is.
    -   This can be controlled with `values` ranging from `0`(0%) to `1.0`(100%) (_e.g. 50% transparency would equal to `opacity: 0.5;`_)
    -   The `Alpha` channel is added at the of a `color method` to replace the `opacity`
    - This can be done with an `a` for  `rgb` and `hsl`(_e.g. `rgba(.,.,.,0.5)`/`hsla(.,.,.,0.5)` for 50% `opacity`_) or `numbers(0-100)` to `hex`. 
-   How to Add `Shadow` to elements with `box-shadow` property  

> ## Reference
Click [Learn CSS Colors by Building a Set of Colored Markers, Completed](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-css-colors-by-building-a-set-of-colored-markers/step-1) to follow along

Live Preview | [Coloured Markers]()