# Code-Refactor
This web page exercise demonstrates code refactoring to improve efficiency and accessibility
## First, in the html file:
- Changed the div with class header to a header element
- Inside the header, changed the div to a nav to make it have a semantic tag. 
- Also in the header, removed the ul element and list items.  Only the a elements are needed
  in the nav element.
- The Lead Generation target was a broken link becasue it did not have an id in the target - added the id for it.
- Replaced the three separate classes for the three navigation links with one class because they are all the same.
- For the three benefits, the classes for styling all had the same properties.  Combined them into one called benefit-styles, which also eliminated redundancy for the h3 and img elements