# Lee Valley

The Lee Valley Golf Club is based in Dublin, Ireland. This is where people can sign up to become members via the Sign Up page, check out the course gallery, see important information such as event times,
office & pro club opening hours and notices will be displayed here for when the course is unplayable due to unforeseeable weather conditions and other situations. 

RESPONSIVE MOCKUP HERE

## Features 

### Existing Features

* ### Navigation Bar

- #### Mobile

I decided to implement the burger style navigation menu for mobile, as this is best suited for user experience on smaller screens. The use of colors taken from the pallette of the logo compliments the style of the menu. 

![For mobile](https://screenshot.click/07-47-11651-59523.png)

- #### Desktop

A simple menu for desktop and larger screens (over 768px wide) allows for easily viewable and accessible navigation. Using the `.active` class on the current page allows the user to see which page they are currently on via an underline.

![For desktop](https://screenshot.click/07-45-13245-64340.png)

- __The landing page image__

- __The Footer__ 

- __Gallery__
  - The gallery will provide the user with supporting images to see what the course look like. 
  - This section is valuable to the user as they will be able to easily identify the type of course it is and how well maintained it is.

- __The Sign Up Page__

  - This page will allow the user to get signed up to Lee Valley Golf Club and start their journey with as a member. The user will be able to enter their Golf Handicap (if they have one) and other optional data. The user will be asked to submit their full name and email address, which is mandatory. 

### Features Left to Implement
  - I would have liked to add a scroll trigger on the About section animation on the home page. At the moment, it's just triggered on page load. I researched to only find that Javascript is needed in order to trigger the animation on scroll [as per this blog.](https://imjignesh.com/how-to-trigger-css-animation-on-scroll/)
  I could delay the animation with `animation-delay`, however this does not make much sense and does not fit in very well.

## Testing

  - Had a really tough time getting the navigation aligned correctly with flex. Was able to use resources and tutor time to figure it out to a point where I was happy. 
  - Since doing the above, another bug crept up. The X did not appear after clicking the burger icon on mobile. 
  >
  >
  >

### Validator Testing 

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

  The live link can be found here - https://leec313.github.io/lee-valley/

  ## Credits

  ### Content 
  
  * fontawesome.com for all icons
  * tinypng.com for compressing gallery page images
  * [DEV Community](https://dev.to/jungjungie/create-a-navbar-with-css-flexbox-2leh#:~:text=Apply%20Flexbox%20to%20Your%20Navbar,%2C%20it's%20the%20.), [W3 Schools](https://www.w3schools.com/howto/howto_js_mobile_navbar.asp) & [Logrocket](https://blog.logrocket.com/create-responsive-mobile-menu-with-css-no-javascript/#:~:text=There%20are%20many%20techniques%20available,on%20a%20device's%20screen%20size.) - Used all three resources to create my own version of a responsive navigation header section with flex
  * 

  ### Media

  * [lee-valley-logo.png - Logo - created by myself using Photoshop](https://raw.githubusercontent.com/leec313/lee-valley/main/assets/images/lee-valley-logo.webp)
  * [hero.webp - Hero image - Pexels](https://www.pexels.com/photo/cottage-on-grassy-hill-near-golf-course-under-cloudless-blue-sky-6871281/)
  * [parallax.webp - Parallax image on home page - Pexels](https://www.pexels.com/photo/titrist-golf-ball-near-golf-hole-54123/)
  * [signup.webp - Signup page background - Unsplash](https://unsplash.com/photos/I2bCx_tzwh8)
  * [notice.webp - Notice boxes on home page - Pexels](https://www.pexels.com/photo/a-person-putting-a-golf-ball-with-tee-on-green-grass-6542389/)

  ##### Gallery page images

  * [gallery1.webp - 1st image - Unsplash](https://unsplash.com/photos/uy5ZEqUOscs?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
  * [gallery2.webp - 2nd image - Unsplash](https://unsplash.com/photos/_dYkmRgqHqo)
  * [gallery3.webp - 3rd image - Unsplash](https://unsplash.com/photos/5yxJpt_TcAo)
  * [gallery4.webp - 4th image - Unsplash](https://unsplash.com/photos/GpkYK-92VPg)
  * [gallery5.webp - 5th image - Pexels](https://www.pexels.com/photo/green-leaf-trees-on-grass-field-914682/)
  * [gallery6.webp - 6th image - Pexels](https://www.pexels.com/photo/bridge-clouds-club-countryside-209982/)
  * [gallery7.webp - 7th image - Pexels](https://www.pexels.com/photo/man-sitting-on-black-and-gray-golf-cart-1325723/)
  * [gallery8.webp - 8th image - Unsplash](https://unsplash.com/photos/4DJF2yZGZVs)

  ### Wireframes
  
  #### Mobile
  ![Mobile Wireframe](https://github.com/leec313/lee-valley/blob/main/assets/images/wireframe-mobile.png?raw=true)

  #### Desktop
  ![Desktop Wireframe](https://raw.githubusercontent.com/leec313/lee-valley/main/assets/images/wireframe-desktop.png)