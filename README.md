# Lee Valley

The Lee Valley Golf Club is based in Dublin, Ireland. This is where people can sign up to become members via the Sign Up page, check out the course gallery, see important information such as event times,
office & pro club opening hours and notices will be displayed here for when the course is unplayable due to unforeseeable weather conditions and other situations.

![](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/responsive-readme.png?raw=true)

# Contents

* [**Objective**](<#objective>)
* [**User Experience**](<#user-experience-ux>)
  * [**Wireframes**](<#wireframes>)
  * [**Structure**](<#structure>)
  * [**Design**](<#design>)
    * [**Colour Palette**](<#colour-palette>)
    * [**Typography**](<#typography>)
* [**Features**](<#features>)
  * [**Existing Features**](<#existing-features>)
    * [**Navigation Bar**](<#navigation-bar>)
    * [**Hero Image**](<#hero-image>)
    * [**About Section**](<#about-section>)
    * [**Parallax Image**](<#parallax-image>)
    * [**Notice & Events**](<#notice--events>)
    * [**Footer**](<#footer>)
    * [**Gallery**](<#gallery>)
    * [**Membership & Contact Page**](<#membership--contact-page>)
    * [**Event Calendar Page**](<#event-calendar-page>)
  * [**Features I would like to Implement**](<#features-i-would-like-to-implement>)
* [**Technologies Used**](<#technologies-used>)
* [**Testing**](<#testing>)
* [**Validator Testing**](<#validator-testing>)
  * [**index.html**](<#indexhtml>)
  * [**gallery.html**](<#galleryhtml>)
  * [**signup.html**](<#signuphtml>)
  * [**events.html**](<#eventshtml>)
  * [**style.css**](<#stylecss>)
* [**Deployment**](<#deployment>)
* [**Credits**](<#credits>)
  * [**Content**](<#content>)
  * [**Media**](<#media>)
* [**Acknowledgments**](<#acknowledgments>)


# **Objective**

For my portfolio project one, I intend to provide a professionally developed website for users to find out about a local golf course. The main objective is to demonstrate competency in HTML and CSS alongside showcasing attention to detail and the importance of thorough testing.

# **User Experience (UX)**

  ## **Wireframes**

  The design & wireframes for this project were produced in [Balsamic Wireframe Software](https://balsamiq.com/wireframes/). This includes design prototypes for both, smaller and larger screens. The final design does differ from the initial prototype due to design developments that occurred in the process. However, the base structure has more or less been kept in mind throughout. 
    
  ### Mobile
  ![Mobile Wireframe](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/wireframe-mobile.png?raw=true)

  ### Desktop
  ![Desktop Wireframe](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/wireframe-desktop.png?raw=true)

  ## **Structure**

  Lee Valley Golf Club is a 4 page website with each having its own navigation link at the top of the page. The [Home](https://leec313.github.io/lee-valley/index.html) page is the default loading page. The user can easily navigate to other pages via the navigation links on all device types as it is a fully responsive website. 

  ## **Design**

  ### Colour Palette

  The colour palette of the website was first thought of when I was creating the logo. I wanted something green, but not too harsh or vibrant. The below two colours were chosen because they work well together and tie in nicely with other colours that may appear throughout the site. The scheme gives off an inviting feeling and also relate to a golf course. The darker green works well on a white background or underneath white text. The lighter green works well with darker text colours. 

  ![colour palette](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/palette.png?raw=true)

  ### Typography

  The fonts I decided to go with were [Raleway](https://fonts.google.com/specimen/Raleway/) and [Lato](https://fonts.google.com/specimen/Lato/). The headings used Raleway and everything else in the body used Lato. If they were not available, they fell back to sans-serif. When Raleway is used in uppercase, the font really does fit in with the Logo I used. 

  Similarly, Lato is quite an elegant font and really looks nice on the Lee Valley website. Various font-weights and other attributes were used to give further clarity to the user throughout the site.
  
  Both fonts compliment each other exquisitely. 

# **Features**

  The Lee Valley Golf Club website includes very useful features listed below. They include many familiar aspects such as a navigation, form and gallery. The site was designed to keep User Experience as simple as possible and not to be intimidating in any way, but to be intuitive, and to promote the user to explore freely.

  ## **Existing Features**

  ### **Navigation Bar**

  The Logo on in the header is clickable and links back to the home page for enhanced UX. I created the Logo myself in Photoshop as I have some previous design experience. The golf ball texture used along with the hills, trees and flag within the design add to the experience to show that this site is truly golf related. 

  ![Logo](https://leec313.github.io/lee-valley/assets/images/lee-valley-logo.webp)

  - #### Mobile

  I decided to implement the burger style navigation menu for mobile, as this is best suited for user experience on smaller screens. The use of colors taken from the pallette of the logo compliments the style of the menu.

  ![Mobile-nav](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/mobile-nav.png?raw=true)

  - #### Desktop

  A simple menu for desktop and larger screens (over 768px wide) allows for easily viewable and accessible navigation. Using the `.active` class on the current page allows the user to see which page they are currently on via an underline.

  ![Desktop-nav](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/desktop-nav.png?raw=true)

### **Hero image**

  A picturesque hero image with an slightly transparent overlay, keeping in line with the theme's color, and some h2 and h3 headings. This includes the course name and motto. Again, this section is fully responsive as shown in the images below. 

  - ### Mobile

  ![Mobile-hero](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/mobile-hero.png?raw=true)

  - ### Desktop

  ![Desktop-hero](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/desktop-hero.png?raw=true)

### **About Section**

  This includes a h2 heading and paragraph describing the course to tell them about the amenities, location and other information. It immediately gives the user a sense of who the Lee Valley Golf Club is and encourages them to explore further.

  - ### Mobile

  ![Mobile-about](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/mobile-about.png?raw=true)

  - ### Desktop

  ![Desktop-about](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/desktop-about.png?raw=true)

### **Parallax image**

  A nice visual feature, simply added via css. This is quite eye catching for the user and ties in nicely to the homepage.

  ![Parallax](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/parallax.png?raw=true)

### **Notice & Events**

  This section allows the Administrator to add any notices/events that might be happening in the club. It includes a link to the events.html page as "View all events". I made use of flex in order to scale and align for both mobile and desktop. As seen below, under 768px screen width, the columns go from four to two and rows from one to two.

  - ### Mobile

  ![Mobile-notice](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/mobile-notice.png?raw=true)
  
  - ### Desktop

  ![Desktop-notice](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/desktop-notice.png?raw=true)

### **Footer**

  The footer includes 4 links to various social media sites. To enhance the UX, the links open in separate tabs.
  The Facebook, Twitter, Youtube and Instagram social links are there for educational purposes and navigate the user to the home page of each respected site. They would be changed to re-direct the user to the respective Lee Valley Golf Club social media if this site was deployed outside of this project.

  ![Footer](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/footer.png?raw=true)

### **Gallery**
  - The gallery provides the user with supporting images to see what the course and amenities looks like. 
  - This section is valuable to the user as they will be able to easily identify the type of course it is and how well maintained it is.
  - The gallery section is responsive so that it displays two columns for desktop and one for mobile. This was done using flex.
  - Also includes a 10 second zoom animation that kicks in on page load. I think it adds a nice effect when viewing the images.

  ![gallery](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/gallery.png?raw=true)

### **Membership & Contact Page**

  - This page will allow the user to get signed up to Lee Valley Golf Club and start their journey with as a member. The user will be able to enter their Golf Handicap (if they have one) and other optional data. The user will be asked to submit their full name and email address, which is mandatory.
  - It includes a background image layered under the form section to give a nice visual effect.
  - Upon submission of the form, the user is presented with a browser alert, thanking them for their submission. The form is not posted anywhere as it is just for educational purposes. 

  - ### Mobile

  ![Mobile-membership](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/mobile-membership.png?raw=true)

  - ### Desktop

  ![Desktop-membership](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/desktop-membership.png?raw=true)

  - The contact section on this page provides information for users in order to get in touch via phone or email. It also includes phone opening times. 

  - ### Mobile

  ![Mobile-contact](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/mobile-contact.png?raw=true)

  - ### Desktop

  ![Desktop-contact](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/desktop-contact.png?raw=true)

### **Event Calendar Page**

  - This page links a Google Calendar iframe that displays upcoming events such as golf tournaments. It's also linked to the Notice & Events section of the homepage so the user can access this page through there as well as the navigation menu.
  Again, this section is responsive to scale up to larger screens and scale down to smaller screens. Events are added via the Google Calendar of the Google Account used and the iframe is taken from Calendar Settings. 

  - ### Mobile
  
  ![Mobile-calendar](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/mobile-calendar.png?raw=true)

  - ### Desktop

  ![Desktop-calendar](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/desktop-calendar.png?raw=true)

# **Future Features**

  - ### Animation 
  
  I would like to add a scroll trigger on the About section animation on the home page. At the moment, it's just triggered on page load. I researched to only find that Javascript is needed in order to trigger the animation on scroll [as per this blog.](https://imjignesh.com/how-to-trigger-css-animation-on-scroll/)
  I could delay the animation with `animation-delay`, however this does not make much sense and does not fit in very well.

  - ### Google Calendar
  
  Would like to edit the styling of the calendar itself. I found this [Stack Overflow post](https://stackoverflow.com/questions/49306347/how-to-customize-google-calendar-with-css), that states you can use the Google APIs to edit the Calendar - [Google Dev Docs](https://developers.google.com/calendar/). If I had the skillset, I would have gone down the route, however for the purpose of this project, the default iframe works just fine.
  
  - ### Payment for Membership page

  I feel allowing the user to pay on-site would really enhance user experience. For the moment, the user will fill in the Membership signup form and wait for further outreach by the club in order to arrange payment. The onsite payment gateway would most likley increase membership and allow for a better member/club relationship.

  - ### Sign in & Booking System

  A sign in and booking system here would work really well. Similar to [BRS Member Booking](https://www.brsgolf.com/web/member-booking/), this would allow members to login to their account, check the available tee times/booking slots and choose their desired play time. It would decrease the staff needed to take bookings over the phone and have a user facing booking system and admin so that staff can manage bookings internally too. 

  - ### Testimonials 

  A testimonials section would tie in nicely with the login feature. If a member added a testimonial, their first name and profile image would display in their testimonial block along with their feedback. We would have up to four testimonials displayed across a section of one of the pages (home page and perhaps the signup page to encourage users to join).

# **Technologies Used**

  - [HTML5](https://en.wikipedia.org/wiki/HTML) - Content & structure
  - [CSS3](https://en.wikipedia.org/wiki/CSS) - Styling
  - [Favicon](https://favicon.io/) - Used to covert full sized logo to favicon size
  - [Gitpod](https://www.gitpod.io/#get-started) - Used to create and edit the website.
  - [GitHub](https://github.com/) - Used to host and deploy the website.
  - [GitBash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) - Terminal used to push changes to the GitHub repository.
  - [a11y](https://color.a11y.com/Contrast/) - Used to test the contrast and accessibility.

# **Testing**

  - Had a really tough time getting the navigation aligned correctly with flex. Was able to use resources and tutor time to figure it out to a point where I was happy. Since then, another bug crept up. The X did not appear after clicking the burger icon on mobile. I've decided to remove the css that applied the X to appear and just leave the burger icon instead when the menu is clicked open.

  - On the gallery page, the animation zoom effect was hiding part of the footer. Add `overflow: hidden;` and fixed that issue.

  ![gallery-bug](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/bug-gallery.png?raw=true)

  - Noticed there was a console error that stated: Failed to load resource: the server responded with a status of 404 () /favicon.ico:1
  This was due to no favicon being implemented and after a quick bit of research, I added the favicon and the console error disappeared.

  ![favicon-bug](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/bug-favicon.png?raw=true)

  ## Manual Testing

  * In addition to the other tests, I have conducted a manual check list for myself to carry out to make sure that everything is working as intended.

      * 

# **Validator Testing**

  ## **index.html**

  ### [The W3C Markup Validation Service](https://validator.w3.org/)

  ![html-index](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/w3html-index.png?raw=true)

  ### Lighthouse Validation

  * Mobile

  ![lighthouse-index-mobile](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/lighthouse-index-mobile.png?raw=true)

  * Desktop

  ![lighthouse-index-desktop](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/lighthouse-index-desktop.png?raw=true)

  ### **Additonal Accessibility Validation**
  [a11y](https://color.a11y.com/Contrast/) for some additional contrast testing for accessibility:

  ![index-a11y](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/validation-a11y-index.png?raw=true)

  ## **gallery.html**

  ### [The W3C Markup Validation Service](https://validator.w3.org/)

  ![html-gallery](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/w3html-gallery.png?raw=true)

  ### Lighthouse Validation

  After compressing the gallery images even further, I was able to get from a 72 lighhouse score on performance up to a 99. It shows how something so simple can make such a huge difference.

  * Mobile

  ![lighthouse-gallery-mobile](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/lighthouse-gallery-mobile.png?raw=true)

  * Desktop

  ![lighthouse-gallery-desktop](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/lighthouse-gallery-desktop.png?raw=true)

  ### **Additonal Accessibility Validation**
  [a11y](https://color.a11y.com/Contrast/) for some additional contrast testing for accessibility:

  ![gallery-a11y](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/validation-a11y-gallery.png?raw=true)

  ## **signup.html**

  ### [The W3C Markup Validation Service](https://validator.w3.org/)

  ![html-signup](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/w3html-signup.png?raw=true)

  ### Lighthouse Validation

  * Mobile

  ![lighthouse-signup-mobile](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/lighthouse-signup-mobile.png?raw=true)

  * Desktop

  ![lighthouse-signup-desktop](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/lighthouse-signup-desktop.png?raw=true)
  

  ### **Additonal Accessibility Validation**
  [a11y](https://color.a11y.com/Contrast/) for some additional contrast testing for accessibility:

  ![signup-a11y](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/validation-a11y-signup.png?raw=true)

  ## **events.html**

  ### [The W3C Markup Validation Service](https://validator.w3.org/)

  ![html-events](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/w3html-events.png?raw=true)

  ### Lighthouse Validation

  * Mobile

  ![lighthouse-events-mobile](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/lighthouse-events-mobile.png?raw=true)

  * Desktop

  ![lighthouse-events-desktop](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/lighthouse-events-desktop.png?raw=true)


  ### **Additonal Accessibility Validation**
  [a11y](https://color.a11y.com/Contrast/) for some additional contrast testing for accessibility:

  ![events-a11y](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/validation-a11t-events.png?raw=true)

  ## **style.css**

  Passed [The W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) with no errors:

  ![w3-css](https://github.com/leec313/lee-valley/blob/main/assets/images/validation-images/validation-css.png?raw=true)

# **Deployment**

## To Deploy the Project

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

  The live link can be found here - https://leec313.github.io/lee-valley/

  ![deploy](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/deployment.png?raw=true)

## To Fork the Repository 

- A copy of the GitHub Repository can be made by forking the GitHub account. This copy can be viewed and changes can be made to the copy without affecting the original repository. Take the following steps to fork the repository;

  1. Log in to **GitHub** and locate the [repository](https://github.com/leec313/lee-valley).
  2. On the right-hand side of the page inline with the repository name is a button called **'Fork'**, click on the button to create a copy of the original repository in your GitHub Account.

  ![fork](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/fork.png?raw=true)

# **Credits**

  ## **Content**
  
  * [Font Awesome](https://fontawesome.com/) for all icons
  * [TinyPNG](https://tinypng.com/) for compressing gallery page images
  * [DEV Community](https://dev.to/jungjungie/create-a-navbar-with-css-flexbox-2leh#:~:text=Apply%20Flexbox%20to%20Your%20Navbar,%2C%20it's%20the%20.), [W3 Schools](https://www.w3schools.com/howto/howto_js_mobile_navbar.asp) & [Logrocket](https://blog.logrocket.com/create-responsive-mobile-menu-with-css-no-javascript/#:~:text=There%20are%20many%20techniques%20available,on%20a%20device's%20screen%20size.) - Used all three resources to create my own version of a responsive navigation header section with flex
  * Used the following link in order to add Google Calendar to events.html: [Google Calendar Help](https://support.google.com/calendar/answer/41207?hl=en)
  * Fonts used - [Raleway](https://fonts.google.com/specimen/Raleway/) & [Lato](https://fonts.google.com/specimen/Lato/)
  * [Balsamic Wireframe Software](https://balsamiq.com/wireframes/) for initial design layout

  ## **Media**

  * [lee-valley-logo.png - Logo - created by myself using Photoshop](https://raw.githubusercontent.com/leec313/lee-valley/main/assets/images/lee-valley-logo.webp)
  * [hero.webp - Hero image - Pexels](https://www.pexels.com/photo/cottage-on-grassy-hill-near-golf-course-under-cloudless-blue-sky-6871281/)
  * [parallax.webp - Parallax image on home page - Pexels](https://www.pexels.com/photo/titrist-golf-ball-near-golf-hole-54123/)
  * [signup.webp - Signup page background - Unsplash](https://unsplash.com/photos/I2bCx_tzwh8)
  * [notice.webp - Notice boxes on home page - Pexels](https://www.pexels.com/photo/a-person-putting-a-golf-ball-with-tee-on-green-grass-6542389/)
  * [responsive-readme.png - Used in readme to preview the site on all screen sizes](https://ui.dev/amiresponsive)

  ### **Gallery page images**

  * [gallery1.webp - 1st image - Unsplash](https://unsplash.com/photos/uy5ZEqUOscs?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
  * [gallery2.webp - 2nd image - Unsplash](https://unsplash.com/photos/_dYkmRgqHqo)
  * [gallery3.webp - 3rd image - Unsplash](https://unsplash.com/photos/5yxJpt_TcAo)
  * [gallery4.webp - 4th image - Unsplash](https://unsplash.com/photos/GpkYK-92VPg)
  * [gallery5.webp - 5th image - Pexels](https://www.pexels.com/photo/green-leaf-trees-on-grass-field-914682/)
  * [gallery6.webp - 6th image - Pexels](https://www.pexels.com/photo/bridge-clouds-club-countryside-209982/)
  * [gallery7.webp - 7th image - Pexels](https://www.pexels.com/photo/man-sitting-on-black-and-gray-golf-cart-1325723/)
  * [gallery8.webp - 8th image - Unsplash](https://unsplash.com/photos/4DJF2yZGZVs)

  # **Acknowledgments**

  This website was completed as part of the Full Stack Software Development (E-commerce Applications) course at [Code Institute](https://codeinstitute.net/). It is my Portfolio Project 1 and has taught me an amazing amount in such a short period of time. I feel a whole lot more confident when it comes to desining, building and testing in the areas of HTML & CSS. The Code Institute Slack Community and my group in particular has been excellent in supporting me, along with the tutors available online. 