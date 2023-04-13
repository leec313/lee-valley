# **Testing**

  - Had a really tough time getting the navigation aligned correctly with flex. Was able to use resources and tutor time to figure it out to a point where I was happy. Since then, another bug crept up. The X did not appear after clicking the burger icon on mobile. I've decided to remove the css that applied the X to appear and just leave the burger icon instead when the menu is clicked open.

  - On the gallery page, the animation zoom effect was hiding part of the footer. Add `overflow: hidden;` and fixed that issue.

  ![gallery-bug](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/bug-gallery.png?raw=true)

  - Noticed there was a console error that stated: Failed to load resource: the server responded with a status of 404 () /favicon.ico:1
  This was due to no favicon being implemented and after a quick bit of research, I added the favicon and the console error disappeared.

  ![favicon-bug](https://github.com/leec313/lee-valley/blob/main/assets/images/readme-images/bug-favicon.png?raw=true)

  ## Manual Testing

  * In addition to the other tests below, I have conducted a manual check list for myself to carry out to make sure that everything is working as intended.

      ## Testing Process
| Test                | Action                   | Success Criteria  |
| -------------       |-------------             | -----|
| Homepage      | Navigate to website URL  | Page loads, not shwoing errors |
| Links            | Checked every link to make sure they were working including the nav links   | Pages load successfully to correct path |
| Form validation  | Enter data into all input fields | Form doesn't submit until correct data is entered, error message shows if incorrect/missing |
| Form submission | Complete each form and submit | Form successfully submits, browser alert shown |
| Responsiveness | Resize viewport window with Chrome Dev Tools. Use [Responsive Design Checker](https://www.websiteplanet.com/webtools/responsive-checker/) to test various mobile, tablet and large screen sizes | Page layout remains intact and adapts to screen size as intended |
| Accessibility | Navigate the site with keyboard and screen reader | Tab index works in correct order, website is navigable, content/aria-labels read aloud |
| Browser compatibility | Test links, layout, appearance, functionality and above Tests on Chrome, Safari, Firefox and Edge. | Website looks and functions as intended and passes all tests above

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

  After compressing the gallery images even further, I was able to get from a 72 lighhouse score on performance up to a 92/96. It shows how something so simple can make such a huge difference.

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

  After compressing the signup.webp image, the score went from a 78 to a 98.

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