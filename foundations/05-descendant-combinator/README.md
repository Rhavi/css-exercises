# Descendant Combinator
Understanding how combinators work can become a lot easier when you start playing around with them and see what exactly is affected by them versus what isn't.

The goal of this exercise is to apply styles to elements that are descendants of another element, while leaving elements that *aren't* descendants of that element unstyled.

You can use either type or class selectors for this exercise; use whichever you may feel you want to practice with more. The HTML file is set up (so no need to edit anything in it) such that any combination of selectors will work, so if you're feeling adventurous you can even try combining a type *and* class selector for the descendant combinator.

The properties you need to add are:

* Only the `p` elements that are descendants of the `div` element should have a yellow background, red text, a font size of 20px, and center aligned.

## Desired Outcome
![desired outcome](./desired-outcome.png)


### Self Check
- Do the elements that contain the text "This should be styled" have the correct styles applied?
- Do the elements that contain the text "This should be unstyled" have no styles applied?

<!-- other combos that would work
.container p
div .text
div p
.container .text

[+]heres how to setup the css links[+]
for a basic htm element, notting should be added:
element_name{}

in order to target a class you need a peroid before the name
.class_name{}

to target an Id you need to place a hashtag at the start of the id name
#ID_Name{}

when you want to affect multiple items put a comma between the selectors
element_name, #ID_name{}
this will affect anything with either of these options

when you want to target a specific collection of traits they need to be in the selector field without a comma
element_name .class_name #ID_Name{}
this will target anything that has these options in this order, since its so specific it will supercede other options
-->
