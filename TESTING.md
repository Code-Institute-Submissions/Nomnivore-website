<h1 align="center">Nomnivore</h1>

---

## Code validators

-   [W3C Markup Validator](https://jigsaw.w3.org/#validate_by_input) was used to test the html files on syntax errors.

### index.html

<h4 align="center"><img src="/assets/readme-images/html-check-index.png"></h4>

### contact.html

<h4 align="center"><img src="/assets/readme-images/html-check-contact.png"></h4>

### over-kim.html

<h4 align="center"><img src="/assets/readme-images/html-check-over-kim.png"></h4>

### recepten.html

<h4 align="center"><img src="/assets/readme-images/html-check-recepten.png"></h4>


-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) was used to test the css file on syntax errors.

### style.css

<h4 align="center"><img src="/assets/readme-images/css-validation.png"></h4>

## Tests of the user stories from User Experience (UX) section

### First Time Visitor Goals

1. As a First Time Visitor, I want to learn about what Nomnivore / Kim is and does.

    1. The hero image, as well as the hero text give a good quick idea of what kim does.
    2. The welcome text expands on this.
    3. The about kim and recipe sections alow the user to find more information.

2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.

    1. The navbar gives easy acces to the different pages of the site. the fact that it sticks to the top allows for easy navigation
        regardless of the users location on the site.
    2. All clickable links have an animation on them to indicate to the user that there is an action associated with it.
    3. The navbar indicates the location on the site by changing the color of the current active link.
    4. The navbar changes to a hamburger menu on mobile.

3. As a First Time Visitor, I want to look for testimonials to find out how skilled Kim is.

    1. Testimonials are front and center on the main page, giving the first time visitor an immediate idea of Kim's skill level.
    2. The about kim and recipe sections alow the user to find even more information on the skills Kim posesses.

4. As a First Time Visitor, I want to locate her social media links to see her products and events.

    1. The social icons are located in the footer, which is always shown by sticking to the bottom of the screen.
    2. Also the social icons have a prominent place on the contact page.
 

### Returning Visitor Goals

1. As a Returning Visitor, I want to find my preferred way to get in contact with Kim with any questions I may have.

    1. The first thing u see on the main page is the contact button, so you're always not more than a click away from getting in ontact with Kim.
    2. The social icons are visible on all pages in the footer, wich sticks to the bottom of the screen.

2. As a Returning Visitor, I want to find recipies for deliscious pastry.

    1. These are easily accessible through the navbar.

### Frequent User Goals

1. As a Frequent User, I want to check to see if there are any newly added recipies.

    1. The latest recipe will be on top of the recipe page.
    2. As mentioned with future features, visitors could be notified by mailing list.
        


## Responsiveness tests

All pages were viewed and tested on the folowing devices in landscape and portrait mode:

- Moto g4             360*640 (in chrome dev tools)
- Galaxy S5           360*640 (in chrome dev tools)
- Pixel 2             411*731 (in chrome dev tools)
- Pixel 2XL           411*823 (in chrome dev tools)
- Iphone 5/SE         320*568 (in chrome dev tools)
- Iphone 6/7/8        375*667 (physical device)
- Iphone 6/7/8 Plus   414*736 (in chrome dev tools)
- Iphone X            375*812 (in chrome dev tools)
- Ipad                1024*768 (physical device)
- Ipad Pro            1366*1024 (in chrome dev tools)
- Surface Duo         540*720 (in chrome dev tools)
- Galaxy Fold         280*653 (in chrome dev tools)
- Responsive desktop  1900*1080 (physical device)
- Responsive desktop  1366*768 (physical device)

### The following aspects were checked:

All images rendered as expected. No pixelation or streched images were found.
Layouts were displaying as they should.
No content was obstructed by broken layout or backgrounds.
All the links in the navigation worked.
Also the links to email and telephone numbers worked correctly.

### Issues found:

On the Galaxy fold in portrait mode some of the layout broke.
This was easily corrected by changing the media query from 320 px to 250px.

## Browser tests

- The site and all links were tested natively in the following browsers on windows 10
    - Chrome Version 87.0.4280.88 (64-bits)
    - Opera 68
    - Firefox 84 (64-bits)
    - Edge Version 87.0.664.66 (64-bits)

-   For Safari testing the site and links were tested on:
    - Physical devices, namely an ipad mini and an iphone 8.
    - On [Browserstack](https://live.browserstack.com/) to simulate an apple desktop device running Big Sur and Catalina.

-   For Internet explorer the site and links were tested on:
    - On [Browserstack](https://live.browserstack.com/) to simulate a windos machine running win8.1 with Internet Explorer v11.

### The following aspects were checked:

All images rendered as expected. No pixelation or streched images were found.
Layouts were displaying as they should.
No content was obstructed by broken layout or backgrounds.
All the links in the navigation worked.
Also the links to email and telephone numbers worked correctly.

---

## Bugs

-   Hero image was not displaying with the correct white overlay by default. Added a linear gradient overlay to fix this.
-   Footer layout broke when adding href to the copyright text. Corrected by changing text to show copyright logo and adding col-xs-auto in stead of col-ms-auto.
-   Header layout broke on smaller screens. added media query to .navbar-brand h1 to reduce font size.
-   Unable to create space between recipies on large screens and losing padding on smallest screens. Solved by adding a col-12 inside the col-lg-6.
-   Z-index on the contact-info wasn't working. adding a position relative fixed the issue.
-   Social icons on mobile did not show in one row. Adjusted margins.
-   On the Galaxy fold in portrait mode some of the layout broke. This was easily corrected by changing the media query from 320 px to 250px.
-   The last recipe was partially hidden beneath the footer. Fixed by minor margin adjustment on all screensizes.
-   E-mail subject not displaying correctly. Forgot questionmark.


[Click here to go back to the readme file.](https://github.com/JorisPaarde/Nomnivore-website/blob/master/README.md)