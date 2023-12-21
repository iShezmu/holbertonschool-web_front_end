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
