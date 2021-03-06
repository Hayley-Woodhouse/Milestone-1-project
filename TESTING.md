# Testing 

# Contents

* [1 W3C Validation](#1-w3c-validation)
    * [1.1 index.html (home) page](#11-indexhtml-home-page)
    * [1.2 booking.html page](#12-bookinghtml-page)
    * [1.3 contact.html page](#13-contacthtml-page)
    * [1.4 style.css](#14-stylecss)
* [2 Responsiveness](#2-responsiveness)
* [3 Browsers](#3-browsers)
* [4 Lighthouse](#4-lighthouse)
* [5 Testing user stories](#5-testing-user-stories)
    * [5.1 User's goals](#51-users-goals)
    * [5.2 Owner's goals](#52-owners-goals)
* [6 Bugs](#7-bugs)

# 1 W3C Validation

The html and css pages were validated using [W3S](https://validator.w3.org/) 

## 1.1 index.html (home) page

![index html validation](/assets/images/readme-imgs/index-w3c.png)

[Back to top](#contents)

## 1.2 booking.html page

![booking html validation](/assets/images/readme-imgs/book-w3c.png)

[Back to top](#contents)

## 1.3 contact.html page

*The contact.html page flagged a warning that the use of < artical > need to have a < h2 - h6 > heading. After a slight adjustment the validation was clear.

![contact html validation](/assets/images/readme-imgs/contact.w3c.png)

[Back to top](#contents)

## 1.4 style.css

*A typo displayed an error. font-size 700 was edited to font-weight 700. After the correction the validation was clear.

![style css validation](/assets/images/readme-imgs/css-val.png)

[Back to top](#contents)

# 2 Responsiveness

The sites responsive design was tested using Google Crome devTools

![responsive design](/assets/images/readme-imgs/response.png)

[Back to top](#contents)

# 3 Browsers

The website was tested on the following browsers.

* Cromebook  
    - tested well
* Firefox 

    - Image on homepage ofset on ipad screen size
* Safari
    - tested well
* Edge
    - tested well
* Opera 
    
    - Slight gap on headings due to margin on home and booking page.


[Back to top](#contents)

# 4 Lighthouse

The results from the [Google Lighthouse](https://developers.google.com/web/tools/lighthouse) performance tests are as follows.

## index.html (home) page

![index lighthouse test](/assets/images/readme-imgs/index-lighthouse.png)

## booking.html page

![booking lighthouse test](/assets/images/readme-imgs/book-lighthouse.png)

## contact.html page

![contact lighthouse test](/assets/images/readme-imgs/contact-lighthouse.png)

The performance is indicating 100 across all pages and the all other areas are in the 93-100 range. This is a good result however, further investigation into the accessibility and best practices is required.

[Back to top](#contents)

# 5 Testing user stories
The user stories helped to identify the key information and nav, layout and colour scheme aspects of the website during the design process. The following review of these stories helps to highlight the value of the features.

## 5.1 User???s goals

-	As a site-visitor I want to be able to contact the bar.

    The sites navbar has contact page for the user to find all the useful contact information. Alternatively, the foot contains a link to the bottom of the contact page and displays the map and address information.

-	As a site-visitor I want to see images of the bar to get a feel for the setting.

    The website has many images of the setting spread throughout and the websites colours represent the bars design and d??cor. 

-	As a site-visitor I want to be able to see a menu and offers.

    The menu is available as a pdf enabling the user to save, download and print.

-	As a site-visitor I want a clear map so that I???m able to find it easily.

    The map is available on the contact page and via the find us link on the footer.
 
-	As a site-visitor I want to be able to find access to reviews.

    A link to trip adviser is on the footer 

-	As a site-visitor I want to be informed of all upcoming events.

    This has been listed as a possible update.

[Back to top](#contents)

## 5.2 Owner???s goals

-	As the owner I want to attract new and revisiting customers.

    The website represents the colours and brand of the bar. It has simple layout that is easy to navigate. The accessible information contains most key of features flagged by the users??? goals. With the remaining added to feature updates. 

-	As the owner I would like the site to reflect the style and theme of the bar.

    This has been achieved by retaining the colour scheme of the bar throughout the website and adding images and a video of the setting.  

-	As the owner I would like a lot of images of the bar and staff used for familiarity.

    There have been many images of the bar already used throughout the website. However, a potential page issuing the details of the staff and their skills has been flagged as an update. 

-	As the owner I would like a booking system available. 

    The booking system is available on the booking page via the nav bar link.

-	As the owner I would like to market our brand and logo.

    The favicon and brand colours are featured heavily over the website. With an update to include the name logo within the navbar so it continues over all pages.

[Back to top](#contents)

# 6 Bugs

### footer layout
- The footer has one row with two columns. Each coloum contains links. when the page as set to a mobile device the footer columns stacked ontop of each other creating two rows.
    - This was fixed by addeding a width pecentage of 100%           divided between the two coloums.

### Hero image (index page)
- The hero image changed position and reduced in quality when viewed through smaller devices.
    - Using crop tools to edit the image for each sreen size enabled me to select the best view point and retain the image. A media query set to display the differing cropped image at new screen sizes.

### Section tag
- A semantic section tag was added to the spaces withing the html pages that didnt have text. This was highlighted in the w3c validation.
    - removing the section tag resolved the issue

### index page hero image
- The image would not appear when device screen size reduced.
    - The media query redirected well but the path to the image needed correcting

### contact page images
- The image would not appear when device screen size increased.
    - The media query redirected well but the path to the image needed correcting

### index page hero image
- The image to replace the video was missing on the mobile screen size.
    - The media query redirected well but the path to the image needed correcting

## Unresolved 

* Trip adviser icon

The trip adviser icon is unavalible as a font awesome link. A temporary icon was used. In an update the icon would be inneed of being changed immediatatly.

![incorrect icon](/assets/images/readme-imgs/temp-icon.png)

* Form layout on booking.html

 The form presented a poblem when using the bootstrap grid system for its responsive functionality. The table elemants created an overlaped when margins were used. A temporary fix was to add blank roow to the columns to impose a "gap". With more time a this would have been tieded using more extensive css.

 ![miss aligned form](/assets/images/readme-imgs/b-form.png)

[Back to top](#contents)
