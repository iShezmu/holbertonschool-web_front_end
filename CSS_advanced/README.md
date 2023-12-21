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
