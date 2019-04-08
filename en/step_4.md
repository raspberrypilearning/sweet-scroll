## Add captions

Next, include image headings by adding some caption boxes.

![Image of project after current step](images/AfterStep4.png)

--- task ---
+ First, add a `div` element **inside** the `cd-logo` div. Give the new `div` the class name `caption`.

+ Then add a `span` tag around the text you want as your heading.

This HTML code adds a heading in the `div` with the class name `cd-logo`:

```html
  <div class="cd-logo">
    <div class="caption">
      <span class="border" >RECIPES WITH CODERDOJO</span>
    </div>
  </div>
```

You should see the heading text without any styling.

![Image of caption without styling](images/CaptionNoStyle.png)

--- /task ---

Next, add some CSS rules to style your new elements.

--- task ---
Add a rule-set for the new `div` element called `caption`.
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
Add a rule-set for the new `span` element called `border`.
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

