# Project: Advanced CSS

*   0. Let's get some images!
    - Download 10 high resolution images that look as close to the final product that you’re going to make.

*   1-style.css
    - When scrolling is triggered on the html element itself, we’d like the behavior of the scroll to be as fluid as possible.

*   2-style.css
    - Based on `styles/1-style.css`, create the following declarations:
      - For the `body`, set the foreground color value to `#161616`
      - For all anchor elements, set the foreground color value to `#161616`
      - All elements with the class `visually-hidden` should have their display to `none`
      - All elements with the class `card-category`, should have their foreground color set to `#D73953`
      - All elements with the class `section-tagline` should have their foreground color set to `#D73953`

*   3-style.css
    - Target the `root` element and define the following custom properties:
      - `color-primary` set to `#d73953`
      - `color-black` set to `#090909`
      - `color-white` set to `#ffffff`
      - `color-light-grey` set to `#f3f3f3`
      - `color-dark-grey` set to `#353535`
      - `text-color` set to `color-black`
    - Revisit the `section-tagline` and `card-category` declarations and reset their color to `color-primary`
    - Revisit the `body` and anchor declarations and reset their color to `text-color`

*   4-style.css
    - Targeting the `root` element, create 2 custom font-family properties `font-family-base` and `font-family-title` with the same list of fonts:
      - set the first choice font as `Helvetica Neue`
      - set the second choice font as `Helvetica`
      - set the third choice font as `Arial`
      - set the last choice font as `sans-serif`
    - Set `body`‘s font-family to `font-family-base`
    - Create a new declaration targeting all 6 levels of heading tags
      - set its font-family to `font-family-title`

*   5-style.css
    - Targeting the `root` selector, create the following custom properties:
      - `font-size-small` set to `1.2rem`
      - `font-size-medium` set to `1.6rem`
      - `font-size-large` set to `1.8rem`
      - `font-size-x-large` set to `2.3rem`
      - `font-size-xx-large` set to `4.8rem`
    - All fonts in the `html` element should be at `62.5%` of their normal size
    - Any fonts in the `body` should have their sizes set to `font-size-medium`

*   6-style.css
    - Targeting the `root` element, create the following custom properties:
      - `font-weight-regular` set to `400`
      - `font-weight-bold` set to `700`
    - Set the boldness of fonts in the `body` to `font-weight-regular`
    - Set the boldness of fonts in the headings to `font-weight-bold`

*   7-style.css
    - Add `Open Sans` as the first choice font for `font-family-base`, with the previous fonts shifted down accordingly
    - Add `Raleway` as the first choice font for `font-family-title`, with the previous fonts shifted down accordingly

*   8-style.css
    - Targeting `root`, create the following custom properties:
      - `line-height-small` set to `1.2`
      - `line-height-base` set to `1.5`
      - `line-height-big` set to `1.8`
    - Set the minimum height of line boxes in the `body` to `line-height-base`

*   9-style.css
    - Style the anchor elements so the text isn’t decorated with anything

*   10-style.css
    - Create a new custom property `section-header-align` and set it to `center`
    - Just above the `section-tagline` declaration, create a new declaration targeting the class `section-header`
      - Set horizontal alignment of that class with `section-header-align`

*   11-style.css
    - Create a custom property `section-tagline-transform` and set it to `uppercase`
    - Targeting the `section-tagline` class:
      - Set the family of fonts to `font-family-title`
      - By using the property `section-tagline-transform`, transform the text
      - Set the weight of fonts to `font-weight-bold`

*   12-style.css
    - Create the following custom properties:
      - `section-title-margin` set to `0`
      - `section-title-color` set to `color-black`
    - Just above the `section-tagline` declaration, create a new declaration targeting the `section-title` class
    - Set the family of fonts to `font-family-title`
    - Set the font size to `font-size-xx-large`
    - Set the font weight to `font-weight-bold`
    - Use the `section-title-margin` to set the margin
    - Use the `section-title-color` to set the text color

*   13-style.css
    - Ensure that the declaration targeting anchor elements only targets those containing a hyperlink
    - Directly after this declaration, target the visited state for the link
      - Italicize the text
    - Directly after the visited state, target the hover state for the link
      - Decorate the links with an underline when hovering
    - Directly after the hover state, target the active state for the link
      - Set the color of the background with the variable `color-light-grey`

*   14-style.css
    - Normalize your CSS file using necolas’ normalize.css with this version.

*   15-style.css
    - Just before the styling for `html`, add a universal box sizing rule

*   16-style.css
    - After the styles for `.section-tagline`,
    - Target the `container` class and set the following:
      - `960px` wide
      - evenly distribute the margins on both the left and and right side

*   17-style.css
    - Create the following custom properties:
      - `section-padding` set to `5rem 0`
      - `section-header-padding` set to `0 0 3rem`
      - `section-body-padding` set to `0 0 3rem`
      - `section-footer-padding` set to `3rem 0 0`
      - `section-footer-align` set to `center`
      - `footer-padding` set to `5rem 0 1rem`
    - Just before the `section-header` declaration, target the class `section` and set the padding on all 4 sides to `section-padding`
    - Set `.section-header`‘s pad all 4 sides with `section-header-padding`
    - Following the `section-header` declaration, target the `section-body` class, pad all 4 sides with `section-body-padding`
    - Following the `section-body` declaration, target the `section-footer` class, pad all 4 sides with `section-footer-padding` and set the horizontal alignment with `section-footer-align`
    - At the end of your style file, target the class `footer`, pad all 4 sides of the selected element with `footer-padding`

*   18-style.css
    - Targeting the `navbar-menu` class, let it float to the right
    - For the `nav` class:
      - the margin on all sides should be set to `0`
      - the padding on all sides should be set to `0`
      - The styling on the list should not use anything
      - center align the text
    - For the `nav-item` class in `nav` class:
      - set the family of fonts to `nav-item-font-family`
      - set the boldness of fonts to `nav-item-font-weight`
      - set the size of fonts to `nav-item-font-size`
      - set the spacing between text characters to `nav-item-letter-spacing`
      - set the display to `nav-item-display`
      - set the margin on all sides to `nav-item-margin`
    - For the `nav-link` class in `nav` class:
      - set the display to `block`
      - set the padding to half of the root element for top and bottom, and equal to the root element for left and right
    - While hovering over the `nav-link` class in `nav` class, set their foreground color value to `nav-item-link-hover`
    - Create the following custom properties:
      - `nav-item-font-family` set to `font-family-title`
      - `nav-item-font-weight` set to `font-weight-bold`
      - `nav-item-font-size` set to `font-size-medium`
      - `nav-item-letter-spacing` set to 4% of the root element
      - `nav-item-display` to `inline-block`
      - `nav-item-marginto` 3 times the root element on the bottom and `0` elsewhere
      - `nav-item-link-hover` set to `color-primary`

*   19-style.css
    - Create the custom property `section-tagline-margin` set to `0`
    - Set the margins for the `section-tagline` class to `section-tagline-margin`
    - For all `ul` with the class `row`:
      - 0 margins all around
      - No padding all around
      - the list should not have any default styles at all
    - For the `col-1-3` class:
      - set the width to 33.33% of its parent
      - float it to the left
      - set its padding to half of the root element
    - For the `col-1-2` class:
      - set the width to 50% of the parent
      - float it to the left
      - set its padding to half of the root element
    - For the `footer-copyright` class:
      - No margins
      - Set the size of the fonts to `font-size-small`
      - set the foreground color to `text-color`
    - For all `ul` tag in the `footer` class, align the text to the right

*   20-style.css
    - Write a CSS rule that creates a new row after each instance of the class `row` with the following properties:
      - no content
      - displayed as a table
      - do not allow any floating elements on either side

*   21-style.css
    - Select all classes that start with `col-`
      - float them to the left
      - set their padding to half of the root element
      - Hint: be mindful of specificity
    - Remove references to these common properties for the individual `col-1-3` and `col-1-2` classes

*   22-style.css
    - Style the data-section-theme=“dark” with these rules:
      - Redefine the custom property `text-color` to the `color-white`
      - Redefine the custom property `section-title-color` to `color-white`
      - Set the background to the variable `color-black`

*   23-style.css
    - Style the `footer-address` class
      - Set the color of the text to the `text-color` property
    - Style the `social-link` class:
      - Style it so that it renders as a block element
    - Style the `social-link` class that also selects the `svg` children
      - Fill in the color of the svg children with the `text-color` variable
