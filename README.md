# Build a Responsive Site With Bootstrap

-   how to make our bootstrap vanilla website stand out
-   tackling the blog page from the bootstrap course and then deploying it somewhere
-   desmitifying deployment

## Footer

-   sticking the footer at the bottom of the page; we use the [sticky footer example](http://getbootstrap.com/examples/sticky-footer/) from the bootstrap webpage
-   the example comes with a fixed width footer of 60px; we need to change that to 180px
-   we also change the background-colour and color
-   padding will give some space for breathing
-   it's not ideal to set the width manually as the site looses responsiveness
-   we need to set a height for small and medium screen and another for large screen
    -   we use a media query for that

## De-Bootstrapying Container

-   we want to personalize the container a bit better
-   the container is too wide; it would look better to reduce the `max-width` of the `.container`
-   the page still feels too bootstrapy
-   we can still change the color of the lead, change the font color of the lead and change button settings
-   [Google fonts](https://www.google.com/fonts) is a great source for fonts
    -   we'll use Open Sans

## Blog Page

-   we make a copy of `index.html` to `blog.html` in a production environment we would have the header and footer on separate files, but in this case we have pure html
-   we remove the main content section from the `index.html`
-   the blog is laid out such that we'll have a main section occupying 8 columns and a sidebar occupying 3 columns with one column breathing space
-   in order to give some character to the webpage we can add some icons from [font awesome](http://fontawesome.io/?ref=FreeSourceLab)
    -   how to position the rocket icon on the side bar? We can use the `pull` classes
-   We'll add an archive section below the About section as well as a Subscribe section
-   The main section:
    -   to test the main section we add text from [robot ipsum](http://www.robotipsum.com/)
    -   the author, comment and tags go on an unordered list right beneath the title; we use the `list-inline` class

## Hosting

-   uploading the site to an ftp site
-   we can use Github pages to host our site
