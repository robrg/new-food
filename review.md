Review
=======

File structure
---------
* You need to clean up your file tree. There are too many files that are not used or old. Delete them
* File names should not have spaces in them. For example "chicken recepies.html" should have its space removed.
* Your CSS should be in a CSS folder, like your images
* You should take the pages out of this folder called "Food" and put them in the home directory
* index.html should be your homepage
* Commit messages need to explain what you did in that commit. Try committing more and writing relevant messages when you do

CSS
---
* all.css does not contain css - broken
* beefrecepies.css contains declared properties without a value. Like on line 7 where 'border-color' is there but has no color. Add one or delete it.
* Good use of comments in CSS
* Your CSS contains a lot of common rules. You should consider putting them together in one CSS sheet and linking each page rather than repeating yourself
* As a general rule, if you find yourself copying / repeating large chunks of code, then you fucked up.
* Try and make common classes that do the same thing. I noticed you have given each of your images an ID and given them specific styling to make them fit. Better would be to define a class that works for them all.
* In general, try avoid writing specific CSS. Try tackle as a group of objects.
* Consider how your page looks on different screen / browser sizes. I notice that when I change the shape of my browser to make it thin like a phone it fucks everything up. Consider that 50% of people use the internet on a mobile device. You can't get away with having a website that is not mobile friendly.
* ideally try and use percentages over specific pixel sizes. This will help a lot with your mobile problem.
* By setting the opacity on an element you inadvertently apply it to everything inside. I suspect you just wanted to make the background lighter - in which case you should use RGB `background-color: rgba(250, 235, 215, 0.7);`


HTML
----
* Try give classes relevant names and not just "box1", "box2", "box3" etc
* Good indentation
* p2 is not an element. this only works for header tags
* Try and not use <br> for styling
* Don't use unordered lists where they are not needed. Use them only for lists or in some cases navigation
