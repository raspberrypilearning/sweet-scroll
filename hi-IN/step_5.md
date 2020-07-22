## चुनौती: अधिक अनुभाग(sections) जोड़ें

--- challenge ---

लंबन स्क्रॉलिंग(Parallax scrolling) का उपयोग करके अपनी विधि में अधिक अनुभाग जोड़ें।

--- hints --- --- hint ---

आप जो कुछ जोड़ सकते हैं, सामग्री, तैयारी, या खाना पकाने के निर्देश पर अनुभाग, उसके लिए यहाँ कुछ विचार हैं।

--- /hint --- --- hint ---

याद रखें कि आपके पास पहले से ही अपने वेब पेज पर अनुभाग हैं जो लंबन स्क्रॉलिंग का उपयोग कर रहे हैं, इसलिए सोचें कि आपको कितने नए CSS नियम-सेट की आवश्यकता है।

--- /hint --- --- hint ---

आप कई चयनकर्ताओं(selectors) के लिए CSS नियम-सेट का फिर से उपयोग कर सकते हैं। नियम-सेट के चयनकर्ता(selectors) सूची में अपने नए अनुभाग जोड़ें, जिसमें `background-attachment: fixed;` शामिल है।

फिर, अपने नए अनुभागों में परिप्रेक्ष्य चित्र को शामिल करने के लिए नए नियम-सेट जोड़ें।

```css
.cd-logo, .kitchen-equipment, .cake-ingredients {
  position: relative;
  background-position: center;
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-color: #642580;
  background-size: cover;
  min-height: 50%;
}

.cd-logo {
  background-image: url("CoderDojo.png");
  min-height: 100%;
  background-size: auto;
}

.kitchen-equipment {
  background-image: url("utensils.JPG");
}

.cake-ingredients {
  background-image: url("ingredients.JPG");
}
```

--- /hint --- --- /hints ---

--- /challenge ---
