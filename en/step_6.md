## Handling mobile and tablet screens

Nowadays, a lot of people browse websites on their phones or tablets. It is important to make sure that your webpages look great on all types of device. The CSS ```@media``` rule is a great way to create responsive web designs.

--- task ---

In this project, some mobile devices have a problem using ```background-attachment: fixed```. Add the following to the end of your CSS file to turn off the parallax effect for mobile devices.

```css
/* Turn off parallax scrolling for tablets and phones as it is not supported */
@media only screen and (max-device-width: 1024px) {
    .cd-logo, .layer-cake, .kitchen-equipment, .cake-ingredients, .bowl-of-cakemix, .cake-in-oven, .decorated-cake {
        background-attachment: scroll;
    }
}
```

--- /task ---

--- collapse ---
---
title: More about the CSS @media Rule
---

The ```@media``` rule is used to apply different styles to your webpage depending on the type of device being used and its settings. It can be used to check:
+ the width and height of the viewport
+ the width and height of the device
+ the orientation of the device (whether it is in landscape or portrait mode)
+ the screen resolution

It's a great way to create tailored style sheets for screens of all sizes.

For more information on what you can do with the @media rule, see [dojo.soy/css_media_rule](http://dojo.soy/css_media_rule).

--- /collapse ---
