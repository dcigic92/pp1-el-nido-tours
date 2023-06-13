# El Nido Tours

**A website created for a fictional tour agency inspired by real tours in El Nido, Philippines.**

![am I responsive screenshot](assets/images/readme/responsive-screenshot.jpg)

***[Live website](https://dcigic92.github.io/pp1-el-nido-tours/index.html)*** created by **Dino Cigic**.

***

## Contents

- [Technologies Used](#technologies-used)
- [Testing](#testing)
    - [Manual testing](#manual-testing)
    - [CSS Validation](#css-validation)
    - [HTML Validation](#html-validation)
    - [Google Lighthouse](#google-lighthouse)
    - [Resolved bugs/issues](#resolved-bugsissues)
- [Deployment](#deployment)
- [Credits](#credits)
    - [Images](#images)
    - [Content](#images)
    - [Code](#code)
- [Acknowledgements](#acknowledgements)

***

## User experience

### Project goals
- To create a website which is going to present our tours to our customers and where they can find all the info they might need.
- To eliminate the need for our customers to come to our office until the very beginning of the tour.

### User stories
- As a user, I want to be able to see all the tours and all the attractions that each tour offers.
- As a user, I want to be able to see all the important info about tours before I decide to book my tour.
- As a user, I want to be able to book my tour online.
- As a user, I want to be able to find contact info easily and contact the agency if I have any queries.

## Design

### Colours
Black, white, burlywood and saddlebrown are only colours used in this project.
![Palette](assets/images/readme/palette.png)

### Typography
In this project I used google fonts. *Fjala one* font used for headings and menu, *Lato* font used for the body text.

### Site Structure
The website consists of 4 main pages and 2 confirmation pages that are intended only for feedback to the user after submitting booking or contact form.

## Technologies Used
- HTML
- CSS
- Javascript
- Git
- Github
- Visual Studio Code
- W3Schools
- Stack Overflow
- Chrome DevTools
- Google fonts
- Google maps
- Font Awesome
- Favicon.io
- Convertio.co
- Coolors.co

## Testing

### Manual testing

- User testing
    - Tested by 3 persons to get some general feedback.

- Devices
    - Tested on 5 different devices.

- Browsers
    - Tested in Google Chrome, Firefox and Microsoft Edge.

- Responsiveness
    - Tested on all available devices in Chrome DevTools.

### CSS Validation
CSS code was validated with the W3C Jigsaw CSS Validation Service and no errors found.
<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>

### HTML Validation
HTML code of each page was validated with the W3C Markup Validation Service and no errors found.
- [index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdcigic92.github.io%2Fpp1-el-nido-tours%2Findex.html)
- [about.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdcigic92.github.io%2Fpp1-el-nido-tours%2Fabout.html)
- [booking.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdcigic92.github.io%2Fpp1-el-nido-tours%2Fbooking.html)
- [contact.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdcigic92.github.io%2Fpp1-el-nido-tours%2Fcontact.html)
- [booking-confirmation.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdcigic92.github.io%2Fpp1-el-nido-tours%2Fbooking-confirmation.html)
- [contact-confirmation.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdcigic92.github.io%2Fpp1-el-nido-tours%2Fcontact-confirmation.html)

### Google Lighthouse

- index.html
![Google Lighthouse index page](assets/images/readme/index-lighthouse.jpg)

- about.html
![Google Lighthouse about page](assets/images/readme/about-lighthouse.jpg)

- booking.html
![Google Lighthouse home page](assets/images/readme/booking-lighthouse.jpg)

- contact.html
![Google Lighthouse home page](assets/images/readme/contact-lighthouse.jpg)

- booking-confirmation.html
![Google Lighthouse home page](assets/images/readme/booking-confirmation-lighthouse.jpg)

- contact-confirmation.html
![Google Lighthouse home page](assets/images/readme/contact-confirmation-lighthouse.jpg)

### Resolved bugs/issues

- Html code for the menu for small screen sizes which I took from other website (mentioned in the credits) was causing bad SEO performance so I modified it. Icon for the menu was inside anchor element which had *href* attribute with *"javascript:void(0);"* as a value, I replaced anchor element with span element and kept only *onclick* attribute.

- Button *more info* was causing bad SEO performance so had to rename it to *about tours* to get better performance even though I prefered first option.

- Confirmation pages were not covering full screen on some devices, header, main content and footer together with margins didn't have enough height so on some screens there was white space under the footer. I had to put fixed height for main content to be sure to cover whole screen for every device even though I would prefer it without fixed height.

## Deployment

To deploy the website I used GitHub pages and followed these steps:

1. Open your *repository*.
2. Click on *settings* in the *navigation menu*.
3. Under *code and automation* choose *pages*.
4. Select the *main branch* and *save*.
5. Refresh a few times and the link to your website should appear shortly.

## Credits

### Images 

- [Unsplash](https://unsplash.com/)
    - [Photo](https://unsplash.com/photos/xmw-2dMRH3Y) by [Ehmir Bautista](https://unsplash.com/es/@ehmirbautista) - Header image
    - [Photo](https://unsplash.com/photos/qXcl3z7_AOc) by [Adam Navarro](https://unsplash.com/ko/@adamnavarro_) - Tour A image
    - [Photo](https://unsplash.com/photos/JcLgfW2pccc) by [Rona Lao](https://unsplash.com/es/@ronalao) - Tour B image
    - [Photo](https://unsplash.com/photos/is-iq9wqMWw) by [Cris Tagupa](https://unsplash.com/es/@cjtagupa) - Tour C image
    - [Photo](https://unsplash.com/photos/DvyEkhT3RUU) by [Toa Heftiba](https://unsplash.com/@heftiba) - Tour D image

- [Flaticon](https://www.flaticon.com/)
    - [Image](https://www.flaticon.com/free-icon/island_4617266) by [smashicons](https://www.flaticon.com/authors/smashicons) - favicon

- [Coolors.co](https://coolors.co/) - Used to create pallete image for the readme file.

### Content

- A lot of text taken from [GetYourGuide](https://www.getyourguide.com/) and edited
    - [Tour A](https://www.getyourguide.com/el-nido-l974/el-nido-island-hopping-tour-a-lagoons-and-beaches-t217227/)
    - [Tour B](https://www.getyourguide.com/el-nido-l974/el-nido-island-hopping-tour-b-cudognong-cave-more-t228373/)
    - [Tour C](https://www.getyourguide.com/hidden-beach-l104676/el-nido-island-hopping-tour-c-hidden-beaches-shrine-t219591/)
    - [Tour D](https://www.getyourguide.com/el-nido-l974/el-nido-hidden-beaches-and-lagoons-boat-hopping-tour-d-t229222/)

- All icons for the footer, about page and contact page were taken from [Font Awesome](https://fontawesome.com/).

### Code

- HTML, CSS and JavaScript code for the menu for small screen sizes was copied from [here](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_topnav) and modified.
- How to display an unordered list in two columns found [here](https://stackoverflow.com/questions/14745297/how-to-display-an-unordered-list-in-two-columns).
- Snook’s variant of using rem for font sizing found [here](https://www.sitepoint.com/understanding-and-using-rem-units-in-css/).

## Acknowledgements

- I would like to thank my mentor **Akshat Garg** for his feedback and valuable advice.
- I would also like to thank **Alan Bushell** our cohort facilitator and slack community, especially former students whose projects were inspiration for writing readme file.