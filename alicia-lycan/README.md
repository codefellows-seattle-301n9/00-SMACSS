##### How did you determine which rules should be placed in each new CSS file?

If followed SMACSS best practices as we we're instructed in the docs. For base.css I added styles for overall font and background color that apply to main or body elements. For layout.css I aded classes and descendants such as header, footer, nav, and aside; anything pertaining to general positioning on the page, including classes and ids. For modules.css I used for smaller components on the page such as elements like list items, images, and paragraphs; each have classes and descendant selectors.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not refactor any of the existing CSS as it followed SMACSS best practices. I would add mobile-first design if I did any additions or refactoring to the CSS in the future.