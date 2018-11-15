## Parallax scroll

Now let's add the parallax effect to our web page. 

--- task ---
In your 2nd CSS rule-set, add the property ```background-attachment``` and give it the value ```fixed```.
--- /task ---

--- task ---
Change the ```min-height``` property if you want to adjust the size of the gap between text sections. Experiment with different sizes and choose a value between 0% and 100% that you like.
--- /task ---

--- task ---
You can also add the ```opacity``` property if you would like to change the transparency of the divs. Again, try some values between 0.1 and 1.
--- /task ---

If your last section is too short and some of the picture is still showing when you scroll all the way to the bottom of the page, add a rule-set to make that section's ```min-height``` 100%.

Here is how your second rule-set might look after this step.
```css
  .cd-logo, .kitchen-equipment {
  position: relative;
  background-position: center;
  background-repeat: no-repeat;
  background-color: #642580;
  background-size: cover;

  background-attachment: fixed;
  min-height: 50%;
  opacity: 0.7;
}
```

image of the project at this point.