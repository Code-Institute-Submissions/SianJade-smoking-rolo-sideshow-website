# The Smoking Rolo Sideshow Official Website

Stream One Project: User-Centric Frontend Development - Code Institute

Having an online presence is vital for the continued success and growth of any band in the modern era - with that in mind, the purpose of this website is to promote indie-rock band The Smoking Rolo Sideshow. The site will alllow fans of the band updated on news such as tours and new music releases; as well as to provide background information on the band to potential new fans who are only just discovering them, and to provide them with easy access to the band's videos and back catalogue of music. A Japanese version of the page has also been included, as the band's record sales were highest in both the UK and Japan, and they have a sizeable following in both countries and so it made sense to create a version of the site which would be accessible to this demographic, rather than potentially alienating a large portion of the band's fanbase.

A live desktop demo can be found [here](https://sianjade.github.io/smoking-rolo-sideshow-website/).

Wireframes for all device sizes for the website can be found in the [wireframes](https://github.com/SianJade/smoking-rolo-sideshow-website/tree/master/assets/wireframes) folder within the assets directory in this repository.
 
 
## UX
 
The main aim of this website was to compile and display all relevant information about the band in a clear, contemporary fashion, and in a way that is simple for the user to navigate and digest.

I wanted to ensure that users who visited the site - whether they were long-time fans of the band, or had only recently discovered them and were looking to learn more about them - would be able to find specific, relevant information easily and quickly. I achieved this by breaking the site up into clearly defined sections and adding links in the navbar that would allow them to jump to the particular section on the page they are looking for, making it simple for users to find the specific information they were looking for without having to traverse the entire site in order to find this information.

Included in the About section of the page is a small general overview of the band as a whole, before introducing each of the members individually. This general biography of the band will not only provide some additional context about the band and their origins to fans who may be interested, but it also serves as a description of the band which promoters, reviewers, and concert venues are able to copy and paste to use on their own sites for promotional purposes.

Social media links for the band are also included in the footer section, so that users can follow these in order to keep up to date with the band's activity and any news.


## User stories

### User story 1:
As a new fan who has only just discovered The Smoking Rolo Sideshow, I would like to find out more information about the band's history and its members.

### User story 2:
As a Japanese fan of the band who is not well-versed in English, I would like for there to be a version of the site that is accessible and easy for me to read and understand so that I can keep up to date with the band's tours and releases more easily.

### User story 3:
As an event organiser, I would like for there to be an easy way for me to contact the band for booking enquiries for a festival that I am currently organising.

### User story 4:
As a new fan of the band, I would like to be able to find and listen to more of their back catalogue of music, as there are only two of their songs available to listen to on YoiTube, and the band's music is not available on platforms such as Spotify or iTunes.

### User story 5:
As a long-time fan of the band, who likes to go any gigs they play local to me, I would like to be able to view and keep up to date with their upcoming tour dates so that I know in advance if they are going to be playing a show in my area.

## Features
### Existing Features

- The site uses FancyBox 3 for the Gallery section of the website in order to showcase each of the images in a compact and contemporary looking format as thumbnails, while also allowing users to click and expand to a larger, full-screen view of a specific image they wish to see; this format saves users from having to cycle individually through every image, as would be the case if a Bootstrap carousel had been used for the Gallery instead.

- The site also features a Bootstrap table in order to display the band's tour dates in a way that is clear, organised, and easy to navigate. Smaller devices required the table to be collapsed in order to eliminate the need for sideways scrolling, as it is not good UX to require scrolling along the x-axis on mobile devices.

- The site also makes use of Bootstrap's card deck component in order to display the band's music, with an image of the album art each song is featured on so as to add more visual appeal than if the songs were listed in a text only form or by using the `audio` tag by itself, as an image cannot be added to the audio tag, but an image and audio can be added to a Bootstrap card. The Music section of the site also allows users to download each track for offline listening should they wish to do so by right clicking the audio element for each song and then selecting the 'Save audio as' option from the menu which appears.

- Due to the combination of large amounts of clickable and non-clickable elements on the page, I implemented an outer glow on hover only on clickable features of the site on desktops - this makes these elements appear as though they are lighting up in order to help make more clear which elements are clickable. I also felt that this would add a more dynamic element to the site's design and style.

- In order to make the navigation links accessible to users no matter where they are on the page, the navbar makes use of Bootstrap's 'fixed-top' class in order to ensure that it is always visbible at the top of the browser window.

- All links to external websites use the `target="_blank"` attribute in order to ensure that they open in a new tab and do not open in the current tab, thus preventing the need for the use of the browser's back and forward buttons.

- The site also implements Bootstrap's tooltips when the flag buttons in the navbar - which allow the user to switch between the English and Japanese versions of the site - are hovered over, to make each the function of each button clear before they are clicked.

### Features Left to Implement

- In future versions of the website, I would like to add a social media aggregator so that any posts or updates posted across the band's various social media accounts would all appear together in one, easy to locate place on the website, and update in real time as new social media posts are made.

- In future versions of the website - to the Japanese page in particular - I would also like to add custom validation messages to the Bootstrap form used in the Booking section of the website, as currently the validation feedback messages only display in English, but it would be more user friendly for them to display in Japanese on this version of the page.

- As many band websites also feature a way for fans to purchase merchandise, in future releases of the website I would also like to add a section to the page which would feature the band's CDs available for visitors of the site to purchase should they wish to do so.


## Technologies Used

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
    - The project uses HTML5 as the main coding language.

- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - The project uses CSS3 in order to style the HTML5 and Bootstrap elements and components.

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
    - The project uses some light JavaScript in order for the Bootstrap tooltips to properly function.

- [Bootstrap (ver 4.3.1)](https://getbootstrap.com/)
    - The project uses the Bootstrap 4 grid and components in order to achieve a responsive layout.

- [FancyBox 3](http://fancyapps.com/fancybox/3/)
    - The project uses FancyBox 3 to achieve a modern and responsive image gallery.

- [Adobe Photoshop CS3](https://www.adobe.com/uk/products/photoshop.html)
    - The project required Adobe Photoshop CS3 in order to create the PNG images used for the headings of each section, the nav brand, and to re-size and re-touch images where required.

- [Google Translate](https://translate.google.com/)
    - The project required Google Translate to ensure that the Japanese version of the page was written correctly.

- [FontAwesome](https://fontawesome.com/icons?d=gallery)
    - The project uses FontAwesome for icons such as the hamburger menu and social media icons.


## Testing

- Both of the site's HTML files have been run through the [W3C HTML Validator](https://validator.w3.org/https://validator.w3.org/) and returned no errors. The validator did show some warnings for the index.html page stating that each of the individual sections lacked a heading, however this is because PNGs were used for each section heading on the English version of the page in order to keep the font in line with the font used for the band's logo, so each section does have a heading but it is not in the form of a heaing element. This was not possible to do with the Japanese section headings, though (due to the font not being compatible with Japanese characters), so heading elements were used for each section instead, thus the Japanese version of the page returned no errors or warnings.

- The site's custom CSS has been checked and validated using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) and returned no errors.

- In order to test that the site was fully responsive across a multitude of device sizes, I used the device toolbar that can be found in Google Chrome's developer tools and applied each different screen size to both the English and Japanese versions of the website. I also ran the site on FireFox, Opera, Microsoft Edge, Safari, Amazon's Silk browser, and Internet Explorer in order to make sure that all features of the site - such as the glow on hover with buttons and clickable elements - worked across various different browsers.

- When testing the site on web browsers on IOS devices, I discovered that the Bootstrap table used for the Tour Dates section of the site did not correctly function - sideways scrolling was not possible, and so on smaller IOS devices it was not possible to access the tickets buttons beside each date. In order to overcome this issue, I decided to collapse the table on small devices via a CSS media query. This did solve the issue of the table not working on IOS devices as it was now collapsed to fit the screen, so there was no longer a need to scroll sideways.

- I also discovered that on iOS and some Windows phone browsers, the SVGs used for the navbar brand and for the headings of each section did not appear on the screen. In order to resolve this issue I saved the SVG images used with the PNG file extension instead, which resolved the issue for both devices.

- The Bootstrap form used for the Booking section of the site uses the `required` attribute to ensure that all required fields are filled out, as well as the `type` attribute where applicable in order to ensure that the information being submitted in each input field is valid. In order to test this, I first attempted to submit the form without filling out the `required` input fields (such as the Name and Expected Number of Guests fields) - this brought up a validation error message informing me that those fields must be filled out in order to submit the form. Once all fields with the `required` attribute were filled in, form submission was allowed.

- In order to test that the Tel. field would only allow the input of a valid phone number, I attempted to submit the form with the Tel. field containing letters instead of numbers - initially this action was allowed by the browser, so in order to prevent this issue, I included the pattern attribute with a regex (`pattern="\d*"`) as an attribute for the Tel. field in order to allow only the input of digits here. Upon testing the Tel. field with this attribute included, the browser would only permit the input of digits within the field as intended and would disallow any other type of input in this field.

- In order to test that the email input featured in the booking form would not allow an invalid email address to be submitted with the form, I attempted to enter an invalid email address format, without the inclusion of an @ symbol in the entered address - this returned an error message asking the user to enter an email address (in future releases I would like to add a custom error message telling the user 'Please enter a valid email address) and submission of the form was disallowed by the browser. Form submission was also disallowed by the browser if the @ in the email address entered was not followed by the second part of the email address such as 'gmail.co.uk' or 'yahoo.com', etc.

- On Internet Explorer, I discovered that the Music section of the site is slightly compressed - the album art images are slightly elongated vertically, and the `audio` elements overlap one another slightly, although they do still function as intended and play the audio files. However, this section displays correctly across all other browsers I have tested; I am still engaged in finding a solution to the compression issue on Internet Explorer, so this can be addressed in a future release.

- I had hoped to add smooth scrolling to the site in order to eliminate the sudden jump to a section when a nav link is clicked, however the CSS property `scroll-behaviour: smooth` did not work, and at this current stage I am not adequately versed in JavaScript to understand how to apply a smooth scroll using it; however, in the future I will look to resolve this issue through the use of Javascript.


## Deployment
- The website is hosted via GitHub Pages and is deployed from the master branch - this is to allow the deployed site to automatically update with any new commits that are made to the master branch.
    - To deploy the site to GitHub Pages, I first clicked the settings tab on the GitHub repository for the site.
    - From here, I scrolled to the GitHub Pages section of the settings tab and changed the Source from 'none' to 'master branch'.
    - This deployed the site to GitHub Pages and provided a link to the hosted page, which I then copied and pasted into the decription of the repository for easy access.

- To run this application locally:
    - Click the green 'clone or download' button in the [GitHub repository for the project](https://github.com/SianJade/smoking-rolo-sideshow-website).
    - Copy the link provided by clicking the clipboard button to the right of the link.
    - In your terminal, type `git clone`, paste in the previously copied link, and hit return.
    - The application should now be installed on your device.


## Credits

### Content

- All written content in the About section of the site was produced by the band's vocalist and songwriter, Ben Greener.

### Media

- All images and audio files used in this project belong exclusively to The Smoking Rolo Sideshow, who granted me access and permission to use these within the website. The embedded YouTube video is from the band's official YouTube channel, which they also gave me permission utilize in the project.


### Acknowledgements

- The CSS used to override Bootstrap's form focus colour can be found on [Tutorial Republic](https://www.tutorialrepublic.com/faq/how-to-change-bootstrap-default-input-focus-glow-style.php).

- The CSS used to override Bootstrap's tooltip background and arrow colour can be found on [Stack Overflow](https://stackoverflow.com/questions/36143382/re-color-tooltip-in-bootstrap-4).

- The CSS used to remove Bootstrap's default active button outline was adapted from answers found on [Stack Overflow](https://stackoverflow.com/questions/31379175/bootstrap-button-on-click-showing-default-colour).

- The CSS used to collapse the Tour Date table on small devices can be found on [CSS Tricks](https://css-tricks.com/responsive-data-tables/).

- The outer glow on hover was adapted from code found on [CodePen](https://codepen.io/ryancolgin/pen/IBjla).