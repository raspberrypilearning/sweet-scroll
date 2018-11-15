## Getting started

--- task ---

Open the starter project.

--- collapse ---
---
title: I'm using Trinket online
---

Open the Sweet scroll starter trinket at dojo.soy link

--- /collapse ---

--- collapse ---
---
title: I'm using an offline editor
---

Download the Sweet scroll starter files from dojo.soy link and open them in your editor. For help writing HTML and CSS offline visit: https://codeclubprojects.org/en-GB/resources/webdev-working-offline/

--- /collapse ---

--- /task ---

 You should see some pieces of content in div elements, in the HTML file. The empty divs are assigned background images in the CSS file using the property ```background-image```.

--- task ---

Let's add another div with an image of some kitchen equipment.
Add a ```div``` element to the bottom of your page (keep it inside the ```<html>``` tags) and use a helpful class name, e.g., ```.kitchen-equipment```.

--- /task ---

--- task ---

+ Now, in the ```style.css``` file, add a new CSS rule-set for your div that includes the link to the image you would like to display.
```css
  .kitchen-equipment {
    background-image: url("equipment-picture.JPG";
  }
```
--- /task ---

--- task ---

+ Finally add your class name to the list of selectors for the second rule-set in your CSS file. This will apply all these property and value pairs to your new background image.
```css
  .cd-logo, .kitchen-equipment {
  position: relative;
  background-position: center;
  background-repeat: no-repeat;
  background-color: #642580;
  background-size: cover;
  min-height: 100%;
}
```

--- /task ---

--- task ---

Add more divs with pictures or text. 

hints?

I'm going to include a list of the equipment I need when I'm baking a cake.

--- /task ---

image of trinket at this step.