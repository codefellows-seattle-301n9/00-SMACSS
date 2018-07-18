##### How did you determine which rules should be placed in each new CSS file?

I put only the most general rules in the base.css file. For the rules that apply to large sections of the page (the nav, logo, paragraph, recipe, aside), I used the layout.css file. For smaller subsections I used the modules file.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did a little bit. The recipe had many CSS rules grouped together, some for positioning and others to change the text. I moved the text rules to the modules file, because I felt they didn't really fit into the overall page layout.
