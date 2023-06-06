# fixedImages
Code for fixed background images

The provided code is an HTML document that sets up a fixed background effect for different sections on the page. Here's a breakdown of how it works:

1. The HTML structure consists of several sections (`div` elements) with different classes: `e-with-fixed-bg`, `first`, `second`, and `third`. These sections represent different parts of the page.

2. Each `e-with-fixed-bg` section contains a background wrapper (`bg-wrap`) and a content container (`e-container`).

3. Inside the `bg-wrap`, there is a `bg` element. This element serves as the background image container.

4. The CSS styles define the appearance and positioning of the elements.

5. The `.black` class is applied to `div` elements to create black sections that act as dividers between the main sections.

6. The `.e-with-fixed-bg` class sets the position of the section to `relative`, which is important for the fixed background effect.

7. The `.bg-wrap` class creates a clipping container for the background image. It is set to the full size of the section using `width: 100%` and `height: 100%`.

8. The `.bg` class is the actual fixed background element. It is positioned fixed at the top-left corner of the viewport and covers the entire section. The `background-image` property is used to set the background image for each section.

9. The `.e-container` class is responsible for centering the content within each section using flexbox (`display: flex`, `align-items: center`, `justify-content: center`).

The result is a page with multiple sections, each having a fixed background image. The content within each section is centered vertically and horizontally.

To see the effect in action, you can copy the provided code into an HTML file and open it in a web browser.

