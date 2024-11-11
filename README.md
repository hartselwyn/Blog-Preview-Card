Frontend Mentor - Blog Preview Card Solution
This is a solution to the Blog preview card challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

Table of contents
Overview
The challenge
Screenshot
Links
My process
Built with
What I learned
Continued development
Useful resources
Author
Acknowledgments
Overview
The challenge

Users should be able to:

See hover and focus states for all interactive elements on the page
View the layout in a responsive design, adjusting for both desktop and mobile screens
Screenshot


Links
Solution URL: Add solution URL here
Live Site URL: Add live site URL here

My 

Built with:
Semantic HTML5 markup
CSS custom properties
Flexbox for layout
Responsive design with media queries
Google Fonts for custom typography
Mobile-first workflow

What I learned

In this project, I reinforced the concepts of building a responsive card component and styling with CSS custom properties for consistency. I also learned to use media queries effectively to create a mobile-responsive design. Here are some specific aspects:

Media Queries: I used media queries to adjust the layout and font sizes for smaller screens, making the card width expand to 80% of the viewport on mobile devices.

css
@media screen and (max-width: 600px) {
  .card-container {
    width: 80%;
    margin-top: 10px;
  }

  .attribution {
    font-size: 11px;
  }
}

Hover Effects: Adding hover effects to the title made it more interactive, using a subtle color change when the user hovers over the title.

css
.card-container-top h1:hover {
  color: hsl(47, 88%, 63%);
}

Continued development

I plan to continue working on:

Advanced CSS animations and transitions for enhancing user interactions.
Improving mobile responsiveness by practicing more with CSS Grid and Flexbox layouts, especially for complex multi-column designs.
Using CSS variables more extensively to streamline color and typography management across multiple components.

Useful resources

MDN Web Docs on Flexbox - This helped me understand the basics and practical applications of Flexbox.
CSS Tricks Complete Guide to Flexbox - This is an excellent reference for Flexbox properties and usage, which was invaluable in creating the card layout.

Author
Frontend Mentor - @hartselwyn
Twitter - @HartSelwyn
Git-hbu - @hartselwyn

Acknowledgments
Thanks to the Frontend Mentor community for their inspiration and support.