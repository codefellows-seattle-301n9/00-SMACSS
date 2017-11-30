##### How did you determine which rules should be placed in each new CSS file?

After reading the SMACSS website, i put any selectors that were reusable into the modules.css file, such as: li, p, hr selectors that i saw were used several times in the html page. As for the layout.css, i put selectors that i saw were modifying the high-level sections, such as: nav, aside, article, .recipe, and footer section.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

The only things i changed was i combined '.date, aside img, #logo img' selectors into 1 selector since they shared the same value of the same property.
