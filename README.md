# natestrap
This is a framework that I am constantly working on. For a person that takes simple techniques and does them for you. You want to make a simple grid system? Then this will get that done with a simple attribute name with easy mathematical thinking. Along with some other things as well.

Grid control
Ok, so let's say you have three divs and want them to be spaced out across the page:

<div class='parent'>
<div class='child'>divA</div>
<div class='child'>divB</div>
<div class='child'>divC</div>
</div>


Instead of using CSS and annoying media queries, all someone has to do is input a property called 'pos' in each object like this:
<div>
<div pos='100 100 33.3'>divA</div>
<div pos='100 100 33.3'>divB</div>
<div pos='100 100 33.3'>divC</div>
</div>
The three numbers indicate media queries starting from mobile, tablet and then desktop. So each div will have a width of 100% in mobile and tablet... then divided width of 33.3% on desktop. Making all three children objects with the 'pos' property together reach 100%.
