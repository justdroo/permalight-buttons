Hello Dan & Bryce!

I decided not to adjust my CodePen so that you could continue to reference that as part of my interview. However, I did want to make some adjustments to my code so I could play around with SCSS a little bit more. The following are changes and additions I made.

1. Reorganized file structure.
 - Based on an article from 2013 I found on the SASS website: http://thesassway.com/beginner/how-to-structure-a-sass-project
 - Since it was such a small file I decided not to create a whole modules folder and instead kept them housed in one file
 - Same thing for partials, I could have split them out even more but based on the size of the project I thought this was okay

2. Fixed shadow and border irregularity on initial (gray) button
  - I ended up having to add the extra div, which at the end of the day made things quite a bit simpler to deal with
  - Border issue was not nearly as hard as I thought it would be: https://css-tricks.com/public-service-announcement-careful-with-your-nested-border-radii/

3. Created a secondary branded button based on Permalight colors and fonts from website

4. Created a flat button that was closer to the Permalight design.
  - Based off of mobile view after clicking on dropdown menu
  - Button has hover and click events (CSS only)
  - Home button and X button have hover and click events (CSS only)

Additional Notes:
- The flat button SCSS file might appear more nested than necessary... that's because it is. I was practicing nesting style rules so I may have gone a little overboard.
