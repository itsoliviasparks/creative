# Creative 🖌️
<a href="https://itsoliviasparks-creative.netlify.app">🔗 Live Site</a>

## Project Purpose & Goal
Creative is an exercise in taking a given design deck (located in `given-design-deck`) and translating it into HTML & CSS using Sass. Note that many links are dead. A fully functional website was not the focus of this project, instead, my focus was on creating a pixel-perfect replication of the design deck.

## Tech Stack
Sass & HTML

## Development Process
- To build, I started with semantic HTML markup, keeping in mind `accessibility web standards`
- From there, I worked into Sass. Starting with key overarching styles, then adding more specific styling to target smaller elements
- In order to ensure the project was well organized, I utilized multiple HTML files & Sass partials:
    - 1 HTML file for the home page (`index.html`), blog (`blog.html`), and contact page (`contact.html`)
    - In terms of Sass:
      - The `_var.scss` file contains all font-family & colour variables
      - `_fonts-general-styles.scss` includes styling for fonts, wrappers, & overarching styles
      - There is one Sass partial per each HTML file: `_home.scss`, `_blog.scss`, & `_contact.scss`
      - I also pulled out header styles (`_header-menus-hero-image.scss`) & footer styles (`_footer.scss`) into their own partials as they applied to all pages of the site
      - And finally, I opened a partial for `_media-queries.scss`

## Problems Solved & Lessons Learned
The navigation menu was my biggest challenge while developing.
After a lot of trial and error, I was able to execute it successfully, which is also why I consider the nav bar my biggest success!

  Building the core desktop navigation menu was fairly straightforward. The challenge came when translating the design into a hamburger style menu for mobile.

  My vision for the mobile nav was to have the Creative logo on the top left hand corner and the search, shopping, & menu toggle icons on the right.

  My first attempt at building this was unsuccessful. I struggled to re-arrange the elements from their desktop view to a completely re-arranged mobile view.

  After playing around with re-arranging the elements, re-looking at previous hamburger menus I’d developed, and doing a few googles, I decided the best way to execute was to write markup for two different menus: one for desktop view & one for mobile.

  Then, using `visibility: hidden` & `visible` in the media queries, I’m was able to set the correct menu for each screen size!
