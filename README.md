# Project Overview

The project is an optimized version of the Udacity performance optimization project - [frontend-nanodegree-mobile-portfolio](https://github.com/udacity/frontend-nanodegree-mobile-portfolio).

## Setup
Clone the project and then run the `index.html` file.
```sh
$ git clone https://github.com/debatanu-thakur/frontend-nanodegree-mobile-portfolio.git
```
## Optimizations Done
The below are the optimization steps taken to completely optimize the page:
  1. Added the required css to the index.html page
  2. Removed reference of style.css
  3. Made javscript references async and added `DOMContentLoaded` event for inline javascript.
  4. Reduced size of pizza image refered in the `index.html` page.
  5. Reduced pizza size change by calculating the layout outside of the loop and by caching the element reference in `resizePizzas()`.
  6. Scroll improvement was done in the `updatePositions()`. Cached the items in a global array and then positioned the layout calculation out of loop.


## Demo
The site is hosted in [https://debatanu-thakur.github.io/](https://debatanu-thakur.github.io/).

## License
The content of this repo are under the MIT License.
