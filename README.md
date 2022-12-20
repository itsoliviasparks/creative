# Creative 🖌️
<a href="https://itsoliviasparks-creative.netlify.app">Live Site</a>

## About
Creative was an exercise in taking a given design deck and translating it into HTML & CSS using Sass.

## Development Process
- To build, I started with semantic HTML markup, keeping in mind accessibility web standards
- From there, I worked into Sass. Starting with key overarching styles, then adding more specific styling to target smaller elements
- In order to ensure the project was well organized, I utilized multiple HTML files & Sass partials:
    - 1 HTML file for the home page, blog, and contact page
    - In terms of Sass:
      * One partial for all font-family & colour variables
      * Another for key setup styles (inc. fonts, wrappers, & broad, overarching styles)
      * I then worked into one partial per each HTML file
      * I also pulled out header & footer styles into their own partials as they applied to all pages of the site
      * And finally, I opened a partial for media queries

## Challenges & Successes
- The navigation menu was my biggest challenge while developing.
After a lot of trial and error, I was able to execute it successfully, using just HTML & CSS, which is also why I consider the nav bar my biggest success!
Well executed menus are vital to the user experience and I’m happy I was able to provide the user a seamless experience on all screen sizes.
  - Building the core desktop navigation menu was fairly straightforward.
  - The challenge came when translating the design into a hamburger style menu for mobile.
  - My vision for the mobile nav was to have the Creative logo on the top left hand corner and the search, shopping, & menu toggle icons on the right.
    Which, when clicked, would open up a menu for site navigation.
  - My first attempt at building this was unsuccessful.
    I struggled to re-arrange the elements from their desktop view to a completely re-arranged mobile view.
  - After playing around with re-arranging the elements, re-looking at previous hamburger menus I’d developed on past projects, and doing a few googles, I decided the best way to execute was to write markup for two different menus: one for desktop view & one for mobile.
    Then, using visibility: hidden & visible in the media queries, I’m was able to set the correct menu for each screen size. 
  - Overall this project was a success! I was able to add a few tools to my web dev tool belt & I’m proud to have created a site that is true to the original design deck.
