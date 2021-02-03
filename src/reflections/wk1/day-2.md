# Day 2
Nathan Quam

---

Read Building Blocks Of Web Development > CSS and answer the following questions
1. What is a Pseudo-Class and what are some of the most common ones you think you will use
2. What is Specificity and how might you use it to your benefit?
3. What problems do you think you could run into if you over-utilized the !important feature?

1. Psuedo-Classes are like specific states or modes a class/element can be in. For example an anchor tag can have a pseudo class for when it's already been visited, when it hasn't been visited, when the cursor is hovering over it, etc. CSS can use these pseudo classes to apply different styles to the one element depending on it's current state.
2. Specificity is a value associated with CSS rules which is how specific the selector of the rule is. Different selectors have different specificity values, and whichever rule has the highest total specificity will apply it's styling to the page. (Except in the case of inline styling, and !important, both of which should not be used)
3. Using !important will forcefully overwrite any other styles, regardless of specificity or the order the stylesheets were loaded in; which goes against the entire purpose of CSS's cascading styles.

---

[Link to my CoolSite](https://nathanmquam.github.io/CoolSite/)