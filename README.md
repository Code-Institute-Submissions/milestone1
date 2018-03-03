Phil Surgenor - Milestone Project 1
===

<br>

## User Centric Frontend Development
[visit the project website here](https://philsurgenor.github.io/milestone1/)


For this project, I decided to redesign a website for a charity where my father works.
You can view the original website [here](http://www.vinecentre.org).

The original website was made a long time ago and needs updating. As you can see it isn't responsive, user friendly or aesthetically pleasing.

The main thing to do was make this site accessible to as many people across as many devices as possible.

<br>

## Technologies

 - Balsamiq Mockups
 - HTML 5
 - CSS 3
 - Bootstrap 4

<br>

#### Balsamiq Mockups

The first task was to go through the old website and do a content audit, writing down all the main parts of the site an finally creating a simple sitemap to work from.
I have included the sitemap.pdf file in the wireframes folder.

I have also included wireframe mockups of the home page and programmes page in pdf format in the wireframes folder. In each of these files you will find wireframes
designed for mobile, tablets in portrait, tablets in landscape and desktops.

I chose these two pages as they were the most complicated and I wanted to be sure my ideas would work on all devices before starting development.

<br>

#### HTML 5

I wanted to keep the HTML as structured and logical as possible so that the browser would render it properly. Using semantic tags really helped with this, for example, \<nav>, \<section>, \<header>, \<footer> etc.

<br>
#### CSS 3

I used an external style sheet to keep the HTML and CSS seperate. Through the use of classes I was able to reuse some styles for simial components, for example I used .article-img for most of the main images.

The main styling techniques I used were: linear gradients, box shadow, text shadow and some animation.

I was unable to find a way on my own to style the nav-toggler as it was an SVG. I googled it and got the answer on codepen. I have left a comment in my style sheet refering to this.

<br>
#### Bootstrap 4

As Bootstrap 4 was out of beta, I decided to use it. I used it primarily for its responsive capabilities and its mobile first ethos.

<br>

## Testing

#### Human Testing

The main tests that were carried out were by hands on use of the site. This included, making sure all links worked, it was easy to navigate and made sense to the average user. I also tested its responsiveness using googles developer tools and physically testing it on my mobile and tablet devices.

<br>

#### HTML Validator

When I ran my code through the W3C HTNL validator, I realised I was using the \<img> tag wrong. I placed a closing tag throughout. I was able to rectify this mistake and commit the changes.

<br>

#### CSS Validator

After submitting my site to the W3C CSS Validator, I realised for the box shadow property I had used vendor prefixes, The validator showed that they were unknown so I deleted them.

