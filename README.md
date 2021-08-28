# Code-Refactor
This web page demonstrates code refactoring to improve efficiency and accessibility.  Originally there was a lot of repetition in the css code.  Duplicated code was consolidated.  HTML code was changed as necessary to allow refactoring.
## Link to the published page on Github:
https://cchampness.github.io/Code-Refactor/ 
## First, in the html file:
- Changed the div with class header to a header element
- Inside the header, changed the div to a nav to make it have a semantic tag. 
- Also in the header, removed the ul element and list items.  Only the a elements are needed
  in the nav element.
- The Lead Generation target was a broken link becasue it did not have an id in the target - added the id for it.
- Replaced the three separate classes for the three navigation links with one class because they are all the same.
- For the three benefits, the classes for styling all had the same properties.  Combined them into one called benefit-styles, which also eliminated redundancy for the h3 and img elements

## Second, in the css file:
- Made the header display type flex to allow good positioning of the nav element.
- Used justify-content space-between in the header and h1 to get good positioning of the h1 and nav.
- Brightened up "seo" inside the Horiseon header to make it stand out becasuse it's a really col pun (I thought so anyway).
- Removed redundant rules according to the way the classes were consolidated in the html code.
## Here is a Screenshot of the website:
![plot](refactor.gif)