## Website Performance Optimization portfolio project

#### Part 1: Optimize PageSpeed Insights score for index.html

1. Optimize images using grunt responsive_images and editing image src links.

2. Move external CSS files into index.html header.

3. Async javascript links in header.

4. Setup web font loader to prevent render blocking by font load.

PageSpeed Insights score: **93/100**

#### Part 2: Optimize Frames per Second in pizza.html

**Scrolling**

1. Change pizzas loaded from 200 to 30.

2. Moved `(document.body.scrollTop / 1250)` into a new variable outside the for loop.

**Pizza Resizing**

1. Deleted variables: `oldwidth`, `windowwidth`, `oldsize`, `newsize`, and `dx`.

2. Update `newwidth` values inside switch function with percentages.

3. New `randPizzas` and `numPizzas` variables to simplify the for loop.

4. Moved `pizzasDiv` variable outside the for loop.