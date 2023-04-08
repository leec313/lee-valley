# Lee Valley

The Lee Valley Golf Club is based in Dublin, Ireland. This is where people can sign up to become members via the Sign Up page, check out the course gallery, see important information such as event times,
office & pro club opening hours and notices will be displayed here for when the course is unplayable due to unforeseeable weather conditions and other situations. 

![](https://raw.githubusercontent.com/leec313/lee-valley/main/assets/images/responsive.png)

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
* [**Testing**](<#testing>)
* [**Validator Testing**](<#validator-testing>)
* [**Deployment**](<#deployment>)
* [**Credits**](<#credits>)
  * [**Content**](<#content>)
  * [**Media**](<#media>)


# **Objective**

For my portfolio project one, I intend to provide a professionally developed website for users to find out about a local golf course. The main objective is to demonstrate competency in HTML and CSS alongside showcasing attention to detail and the importance of thorough testing.

# **User Experience (UX)**

  ## **Wireframes**

  The design & wireframes for this project were produced in [Balsamic Wireframe Software](https://balsamiq.com/wireframes/). This includes design prototypes for both, smaller and larger screens. The final design does differ from the initial prototype due to design developments that occurred in the process. However, the base structure has more or less been kept in mind throughout. 
    
  ### Mobile
  ![Mobile Wireframe](https://github.com/leec313/lee-valley/blob/main/assets/images/wireframe-mobile.png?raw=true)

  ### Desktop
  ![Desktop Wireframe](https://raw.githubusercontent.com/leec313/lee-valley/main/assets/images/wireframe-desktop.png)

  ## **Structure**

  Lee Valley Golf Club is a 4 page website with each having it's own navigation link at the top of the page. The [Home](https://leec313.github.io/lee-valley/index.html) page is the default loading page. The user can easily navigate to other pages via the navigation links on all device types as it is a fully responsive website. 

  ## **Design**

  ### Colour Palette

  The colour palette of the website was first thought of when I was creating the logo. I wanted something green, but not too harsh or vibrant. The below two colours were chosen because they work well together and tie in nicely with other colours that may appear throughout the site. The scheme gives off an inviting feeling and also relate to a golf course. The darker green works well on a white background or underneath white text. The lighter green works well with darker text colours. 

  ![colour palette](https://screenshot.click/08-39-16816-27729.png)

  ### Typography

  The fonts I decided to go with were [Raleway](https://fonts.google.com/specimen/Raleway/) and [Lato](https://fonts.google.com/specimen/Lato/). The headings used Raleway and everything else in the body used Lato. If they were not available, they fell back to sans-serif. When Raleway is used in uppercase, the font really does fit in with the Logo I used. 

  Similarly, Lato is quite an elegant font and really looks nice on the Lee Valley website. Various font-weights and other attributes were used to give further clarity to the user throughout the site.
  
  Both fonts compliment each other exquisitely. 

# **Features**

  The Lee Valley Golf Club website includes very useful features listed below. They include many familiar aspects such as a navigation, form and gallery. The site was designed to keep User Experience as simple as possible and not to be intimidating in any way, but to be intuitive, and to promote the user to explore freely.

  ## **Existing Features**

  ### **Navigation Bar**

  The Logo on in the header is clickable and links back to the home page for enhanced UX.

  - #### Mobile

  I decided to implement the burger style navigation menu for mobile, as this is best suited for user experience on smaller screens. The use of colors taken from the pallette of the logo compliments the style of the menu.

  The first selector, `.side-menu:checked ~ nav`, targets the `nav` element that follows the `.side-menu` checkbox when it is checked. It sets the `max-height` property to 100%, allowing the menu to be displayed.
  The second selector, `.side-menu:checked ~ .hamburger .hamburger-line`, targets the `.hamburger-line` element within the `.hamburger` container that follows the `.side-menu` checkbox when it is checked.
  The third selector, `.side-menu:checked ~ .hamburger .hamburger-line::before .hamburger-line::after`, targets the pseudo-element of the `.hamburger-line` element and display the top and bottom lines.

  ![For mobile](https://screenshot.click/08-42-78686-45687.png)

  - #### Desktop

  A simple menu for desktop and larger screens (over 768px wide) allows for easily viewable and accessible navigation. Using the `.active` class on the current page allows the user to see which page they are currently on via an underline.

  ![For desktop](https://screenshot.click/08-41-77833-9568.png)

### **Hero image**

  A picturesque hero image with an slightly transparent overlay, keeping in line with the theme's color, and some h2 and h3 headings. This includes the course name and motto. 

  ![Hero image](https://screenshot.click/07-32-91739-31511.png)

### **About Section**

  This includes a h2 heading and paragraph describing the course to tell them about the amenities, location and other information. It immediately gives the user a sense of who the Lee Valley Golf Club is and encourages them to explore further.

  ![About](https://screenshot.click/07-36-3230-82356.png)

### **Parallax image**

  A nice visual feature, simply added via css. This is quie eye catching for the user and ties in nicely to the homepage.

  ![Parallax](https://screenshot.click/07-38-87450-75547.png)

### **Notice & Events**

  This section allows the Administrator to add any notices/events that might be happening in the club. It includes a link to the events.html page as "View all events".

  ![Notice - Desktop](https://screenshot.click/08-38-49174-453.png)

  I made use of flex in order to scale and align for both mobile and desktop. As seen below, under 768px screen width, the columns go from four to two and rows from one to two.

  ![Notice - Mobile](https://screenshot.click/08-39-66419-47595.png)

### **Footer**

  The footer includes 4 links to various social media sites. To enhance the UX, the links open in separate tabs.
  The Facebook, Twitter, Youtube and Instagram social links are there for educational purposes and navigate the user to the home page of each respected site. They would be changed to re-direct the user to the respective Lee Valley Golf Club social media if this site was deployed outside of this project.

  ![Footer](https://screenshot.click/07-49-6402-79067.png)

### **Gallery**
  - The gallery provides the user with supporting images to see what the course and amenities looks like. 
  - This section is valuable to the user as they will be able to easily identify the type of course it is and how well maintained it is.
  - The gallery section is responsive so that it displays two columns for desktop and one for mobile. This was done using flex.
  - Also includes a 10 second zoom animation that kicks in on page load. I think it adds a nice effect when viewing the images.

  ![gallery](https://screenshot.click/08-39-66942-46427.png)

### **Membership & Contact Page**

  - This page will allow the user to get signed up to Lee Valley Golf Club and start their journey with as a member. The user will be able to enter their Golf Handicap (if they have one) and other optional data. The user will be asked to submit their full name and email address, which is mandatory.
  - It includes a background image layered under the form section to give a nice visual effect.

  ![Membership](https://screenshot.click/07-00-82974-39661.png)

  - The contact section on this page provides information for users in order to get in touch via phone or email. It also includes phone opening times. 

  ![Contact](https://screenshot.click/07-00-68148-72314.png)

### **Event Calendar Page**

  - This page links a Google Calendar iframe that displays upcoming events such as golf tournaments. It's also linked to the Notice & Events section of the homepage so the user can access this page through there as well as the navigation menu.
  Again, this section is responsive to scale up to larger screens and scale down to smaller screens. Events are added via the Google Calendar of the Google Account used and the iframe is taken from Calendar Settings. 
  ![Events](https://screenshot.click/08-22-84071-63806.png)

# ** Future Features**

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

# **Testing**

  - Had a really tough time getting the navigation aligned correctly with flex. Was able to use resources and tutor time to figure it out to a point where I was happy. Since, another bug crept up. The X did not appear after clicking the burger icon on mobile. I've decided to remove the css that applied the X to appear and just leave the burger icon instead when the menu is clicked open.
  - On the gallery page, the animation zoom effect was hiding part of the footer. Add `overflow: hidden;` and fixed that issue.

# **Validator Testing**

  ### **index.html**

  ### **gallery.html**

  ### **signup.html**

  ### **events.html**

# **Deployment**

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

  The live link can be found here - https://leec313.github.io/lee-valley/

# **Credits**

  ## **Content**
  
  * fontawesome.com for all icons
  * tinypng.com for compressing gallery page images
  * [DEV Community](https://dev.to/jungjungie/create-a-navbar-with-css-flexbox-2leh#:~:text=Apply%20Flexbox%20to%20Your%20Navbar,%2C%20it's%20the%20.), [W3 Schools](https://www.w3schools.com/howto/howto_js_mobile_navbar.asp) & [Logrocket](https://blog.logrocket.com/create-responsive-mobile-menu-with-css-no-javascript/#:~:text=There%20are%20many%20techniques%20available,on%20a%20device's%20screen%20size.) - Used all three resources to create my own version of a responsive navigation header section with flex
  * Used the following link in order to add Google Calendar to events.html: [Google Calendar Help](https://support.google.com/calendar/answer/41207?hl=en)
  * Fonts used - [Raleway](https://fonts.google.com/specimen/Raleway/) & [Lato](https://fonts.google.com/specimen/Lato/)

  ## **Media**

  * [lee-valley-logo.png - Logo - created by myself using Photoshop](https://raw.githubusercontent.com/leec313/lee-valley/main/assets/images/lee-valley-logo.webp)
  * [hero.webp - Hero image - Pexels](https://www.pexels.com/photo/cottage-on-grassy-hill-near-golf-course-under-cloudless-blue-sky-6871281/)
  * [parallax.webp - Parallax image on home page - Pexels](https://www.pexels.com/photo/titrist-golf-ball-near-golf-hole-54123/)
  * [signup.webp - Signup page background - Unsplash](https://unsplash.com/photos/I2bCx_tzwh8)
  * [notice.webp - Notice boxes on home page - Pexels](https://www.pexels.com/photo/a-person-putting-a-golf-ball-with-tee-on-green-grass-6542389/)
  * [responsive.png - Used in readme to preview the site on all screen sizes](https://ui.dev/amiresponsive)

  ### **Gallery page images**

  * [gallery1.webp - 1st image - Unsplash](https://unsplash.com/photos/uy5ZEqUOscs?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
  * [gallery2.webp - 2nd image - Unsplash](https://unsplash.com/photos/_dYkmRgqHqo)
  * [gallery3.webp - 3rd image - Unsplash](https://unsplash.com/photos/5yxJpt_TcAo)
  * [gallery4.webp - 4th image - Unsplash](https://unsplash.com/photos/GpkYK-92VPg)
  * [gallery5.webp - 5th image - Pexels](https://www.pexels.com/photo/green-leaf-trees-on-grass-field-914682/)
  * [gallery6.webp - 6th image - Pexels](https://www.pexels.com/photo/bridge-clouds-club-countryside-209982/)
  * [gallery7.webp - 7th image - Pexels](https://www.pexels.com/photo/man-sitting-on-black-and-gray-golf-cart-1325723/)
  * [gallery8.webp - 8th image - Unsplash](https://unsplash.com/photos/4DJF2yZGZVs)
  * [gallery9.webp - 9th image - Unsplash](https://unsplash.com/photos/Z8XlmAj65iM)