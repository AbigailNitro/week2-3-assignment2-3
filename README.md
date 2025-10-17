In the html file, the entire website is contained within a Grid Box, which is why
a thin black line can be seen around the edges. I made the navigation bar and the footer
match the background to create a more seamless view. With the project cards, theyre contained
in a column based flexbox which itself is still within the gridbox.

Inside of each flexbox is another flexbox to create a little bubble in which the dropdown menu 
for additional images is placed.

at the bottom lies the one form element: a little button that sends you away to my github profile

new things needed:
    responsive features such as:
        Media queries (@media)
        Flexible images (max-width)
        Viewport units (vw, vh)
        CSS Grid or Flexbox
    make a bootstrap version with:
        Bootstrap grid system
        Bootstrap components
        Bootstrap utilities
    add to this doc:
        comparison of both docs (their approach)

BREAKPOINTS:
phone       320px - 767px
tablet      768px - 1023px
desktop     1024px+

in the main document, media queries determine the margins and padding of both flexboxes and grids.
for example, if your display is thinner than 520px, you cant see the contact menu, but past that its visible.
each image scales with your browser, with the max height being 790 or 740 depending on whether its a 
main image or sub image.
the self portrait, and the headings are similarly scaled, but with vw, the latter clamped down.
in terms of the grid box and flexboxes, theyre the same as before but with media queries to keep them a good size.

in the bootstrap version, i used the columns to recreate the grid I had made prior for the main section above the project cards. Instead of media queries i used the bootstrap screensize tags to hide the contact and project index at smaller screen sizes. I also used the bootstrap image fit to make sure the images also scale with the browser's snap points. I used the bootstrap padding to create depth with not only the project cards, but also the about me. Lastly, i used the bootstrap button to easily swap the old one with a new blue one