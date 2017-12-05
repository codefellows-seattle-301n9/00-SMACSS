##### How did you determine which rules should be placed in each new CSS file?

Answer:<br>
In general, I followed the outline provided in the "General Guidelines" (i.e. base.css should include body and main styling, layout.css should include header, footer, nav, aside, etc.)


##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

Answer:<br>
Yes! For some reason, when I switched styling into different files, it threw my layout off.  I needed to adjust the following:

-NAV display: the social media icons were no longer displaying correctly, plus margins were messed up

-h2: font-family for "Chocolate Pizza" wasn't displaying correctly. it wasn't grabbing the h1 so added an id to it

-Recipe Background Img: spend sometime trying to fix this but still not fixed
