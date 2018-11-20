## Add captions

Next let's add some caption boxes, to include a heading on your images.

--- task ---
+ First you will need to add a div inside the div with the background picture that you want to put a caption on. 
+ Then you should also add a ```span``` element around the text you want in your heading.
Here is my HTML code for including a caption to the first div ```cd-logo```.

```html
  <div class="cd-logo">
    <div class="caption">
      <span class="border" >RECIPES WITH CODERDOJO</span>
    </div>
  </div>
```

--- /task ---

Next you must add some CSS to style your new elements.

--- task ---
Add a rule-set for the new div element ```caption```.
```css
.caption {
  position: absolute;
  top: 40%;
  width: 100%;
  text-align: center;
}
```
--- /task ---

---task ---
Add a rule-set for the new span element ```border```.
```css
.border {
  background-color: #41BAC1;
  color: White;
  padding: 18px;
  font-size: 25px;
  letter-spacing: 10px;
}
```
--- /task ---

![Image of project after current step](images/AfterStep4.png)