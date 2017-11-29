##### How did you determine which rules should be placed in each new CSS file?

Any tags/selectors that are basic such as h1, body, input, etc. were moved into the base.css. Any layout related tags/selectors such as nav, footer, etc. were moved into layout.css. Lastly, anything more specific that would be found sitting inside 'containers' like the nav tags, I considered modules. These tended to be especially items that are selected with ID tags or are children of othe items.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I didn't find that I needed to refactor any of the CSS. Maybe if I had to troubleshoot the CSS and if I find any issues with the organization I would but so far there is no need.