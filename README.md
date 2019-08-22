# HW-Wireframe

## My final version: 
![alt text](img/HW-Wireframe.png "What the final layout looks like.")

## About the project:
  * For our first homework assignment, we had to make a replica of a basic wireframe. We were given the following specs:

  * Needs to have:
    * Header
    * Nav
    * Aside (With a Heading)
    * Section (With a Heading)
    * Article (With a Heading) contained within the Section
    * Headers contained within the Article
    * Paragraph contained within the Article


  * CSS should have styles for each of the following elements:
    * Body
    * font-family: 'Arial', 'Helvetica Neue', Helvetica, sans-serif;
    * color: '#777'
    * background: '#777'
    * width: '960px'
    * font-size: '18px'
  
  * Header, Nav, Section, Aside, and Footer
    * background: '#ebebeb'

  * Article
    * color: '#ebebeb',
    * background: '#777'

  * h1 and p
    * color: '#777',
    * background: '#ebebeb'

  * The width of the section should be:

    * section: 495px

## Techologies used to build:
  * HTML
  * CSS
  * CSS Grid Generator Tool

## Methodology:
  I made a 5 div grid. Header, nav, section, aside and footer are the main divs. Then I nested a 1 column / 1 row grid inside of the section div and placed article in that. Additionally, I nested another 2 row / 1 column grid inside of the article div to place h1-2-3 and p in each of the respective rows.

  I did make the width of my body 960px and the width if my section 495px as requested in the specs. From there, I just eye-balled everything else mainly utilizing margin to push the divs around.

## Acknowledgments:
  I have been playing around with CSS grid in the weeks leading up to Bootcamp. I've used this site to stucture my practive pages previously.
  * https://cssgrid-generator.netlify.com/