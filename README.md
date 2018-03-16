# Bootstrap 4

### What's New?
- With version 4, Boostrap has moved from LESS to Sass. Sass lets you customize and override certain things in Boostrap like colors and breakpoints.
- The default font measurement has been changed from `px` to `rem`, and the root font size is back up to 16.
- The introduction of **Reboot**, which is a normalizing template, to make sure your site looks the same across all browsers.
- More classes that use responsive breakpoints. Similarly, there are new breakpoints. There's now `SM`, `MD`, `LG`, and a new one `XL`. There is no longer the `col-xs` breakpoint, so now you would just use `col`.
- **New Components**
  - Most of the existing and new components of Boostrap now have heavy integration with Flexbox
  - One totally new component is called **Cards**, which is replacing Panels, Thumbnails, and Wells
  - No more use of Glyphicons
### Cards
- There are a lot of classes that handling styling in **Cards**
  - You create a `<section></section>` for each card, and give it a class of `card`
  - You can use the `card-title` & `card-subtitle` classes for the header(s) of your card.
  - You can use the `card-text` class for the main body of text in your card.
  - It's a good idea to wrap all of your text, excluding the image, in a class called `card-block`. This will add some padding to the sides, so the text isn't butting up against the borders of the card.
  - Use the `card-img` and `img-fluid` for the images inside your card.
