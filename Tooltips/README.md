# How to use

Open the "tooltips.css" file and copy its contents. Open AO3 and hover over "Hi, \[username\]!" and click "My Dashboard". Click the "Skins" link on the lef-hand side. Click on "My Work Skins", then "Create Work Skin". Enter whatever you want in the "Title" field, then paste the code you copied into the large "CSS" field. Change whatever you want here (change the tooltip text, add more, etc.) then click "Submit".

Because AO3 doesn't support the content: attr() function you will have to make a new css class for every different tooltip you want to make, so I don't recommend using this for longer works.

Now you can make a new work, or edit an existing work. The HTML functions as follows:

```<span class="hunder">hover me!<span class="c1 hoverbox"></span></span>```

The "hunder" class gives the words encompassed in the span element the dotted underline and signifies what you can hover over to trigger the tooltip. "c1" is for the tooltip text: so you would change it for every different tootip. You can use anything you want, but for example I changed it to "c2", "c3", "c4", etc. Finally, "hoverbox" is what styles the tooltip, so make sure you leave it in for every tooltip.

Feel free to play around with the code and style it differently, if you'd like. You can take a look at the "example.html" file if you need a better understanding of how it works.
