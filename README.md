# SASS Test
_epicodus week 3 solo project_
_by Chris K Johnson_

### Two-Day Project Thoughts and Feedback section
#### Design
We (my pair and I) drew out a wireframe sketch of two designs for mobile-first, tablet, and desktop views. Working from the top down we created a design that had both graphic-oriented information (hero) as well as main content areas for the majority of the information (body panels, p elements) using graphical elements along the way to break up the content.
#### Architecture
We attempted to follow the 7-1 Sass architecture, but found ourselves having to delete several of the partial folders because our site was too small to incorporate them. Then we struggled with where some of the styling would go, ex: would styling an 'a' element be saved into typography partial file, or would it be components? It displays as text sometimes, but is also used to make buttons and images and sections hyperlinked. We also debated at length how often and how intensely variables
and mixins should be used. I didn't want to use any programming for code only used once, however we ended up using variables/mixins for most things in the end and it was the right decision because some of those things ended up being used twice after all, and even when something wasn't used more than once it made our code more readable as a whole.
#### Sass Usage
| Goal | Sass |
|:------:|:-------:|
| Logically separate styling into distinct and modular sections | use imports to combine separate scss files into a single 'main.scss' file |
| Keep padding and margin consistent across layout elements | Use extends to apply basic styling to layout/container elements |
| Use a consistent color theme throughout the site | Declare color variables to be used as a palette |
| Add special color tints/shades/mixes for hover states and other special cases from chosen color palette variables | Create variations of colors using functions to adjust current color scheme |
| Reset default browser styling | Use a mixin that includes browser specific prefixes for box-sizing property |
| media queries: we need em | store media query information for various screen sizes in mixins and include those mixins within style definitions for components with responsive styles  |
| Use sass nesting to keep things organized | Utilize nesting up to a maximum of 4 selectors deep, and DRY features such as the ampersand for element states ie hover. |
### New Approach
* Use more variables and mixins.
* Use extend at least once.
