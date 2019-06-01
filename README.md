# The Smoking Rolo Sideshow Offial Website

Stream One Project: User-Centric Frontend Development - Code Institute

This website is to promote Indie Rock band The Smoking Rolo Sideshow, and to keep fans of the band updated on news such as tours and new music releases; as well as to provide background information on the band to potential new fans who are just discovering them, and to provide them with easy access to the band's videos and back catalogue of music.

A Japanese version of the page has also been included, as the band's record sales were high in both the UK and Japan, where they have a large following and their music is very popular.

A live desktop demo can be found [here](https://sianjade.github.io/smoking-rolo-sideshow-website/).
 
## UX
 
The main aim of this website was to compile and display all relevant information about the band in a clear, contemporary fashion, and in a way that is simple for the user to navigate and digest.

I wanted to ensure that users who visited the site - whether they were long time fans of the band, or had only recently discovered them and were looking to learn more about them - would be able to find specific, relevant information easily and quickly. I achieved this by breaking the site up into clearly defined sections and adding links in the navbar that would allow them to jump to the particular section on the page they are looking for, making it simple for users to find the specific information they were looking for without having to traverse the entire site in order to find this information.

The Music section of the site also allows users to download each track for offline listening should they wish to do so. Social media links for the band are also included in the footer section so that users can follow these in order to keep up to date with the band's activity and any news.

## Features

### Existing Features

The site uses FancyBox 3 to display thumbnails of images in the Gallery section of the website in order to showcase each of the images in a compact and contemporary looking format, whilst allowing users to click and expand to a larger, full screen view of a specific image they wish to see, rather than having to cycle indiviually through every image - as would be the case if a Bootstrap carousel had been used for the Gallery insted.

The site also makes use of Bootstrap's card deck component in order to display the band's music, with an image of the album art each song is featured on so as to add more visual appeal than if the songs were listed in a text only form or by using the <audio> tag by itself, as an image cannot be added to the audio tag, but an image and audio can be added to a Bootstrap card.

The site also implements Bootstrap's tooltips when the flag buttons used in the navbar that allow the user to switch between the English and Japanese versions of the site are hovered over, in order to make clear what the buttons do if they are clicked.

### Features Left to Implement

In future versions of the website, I would like to add a social media aggregator so that any posts or updates posted across the band's various social media accounts would all appear together in one, easy to locate place on the website, and update in real time as new social media posts are made, so that users of the site can see all of the band's social media activity together in one place.

## Technologies Used

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
    - The project uses **HTML5** as the main coding language.

- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - The project uses **CSS3** in order to style the HTML5 and Bootstrap elements and components.

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
    - The project uses some light **JavaScript** in order for the Bootstrap tooltips to properly function.

- [Bootstrap (ver 4.3.1)](https://getbootstrap.com/)
    - The project uses the **Bootstrap 4** grid and components in order to acheive a responsive layout.

- [FancyBox 3](http://fancyapps.com/fancybox/3/)
    - The project uses **FancyBox 3** to acheive a modern and responsive image gallery.

- [Online Convert](https://image.online-convert.com/convert-to-svg)
    - The project required **Online-Converter.com** in order to convert the PNGs used for the heading of each section into SVG format.

- [Google Translate](https://translate.google.com/)
    - The project required **Google Translate** to ensure that the Japanese version of the page was written correctly.

- [FontAwesome](https://fontawesome.com/icons?d=gallery)
    - The project uses **FontAwesome** for icons such as the hamburger menu and social media icons.

## Testing

In order to test that the site was fully responsive across a multitude of device sizes, I used the **device toolbar** that can be found in Google Chrome's **developer tools** and applied each different screen size to both the English and Japanese versions of the website in order to ensure that they displayed correctly on each screen size. I also ran the site on FireFox, Internet Explorer, and Microsoft Edge in order to make sure that all features of the site - such as the glow on hover with buttons and clickable items - worked across various different browser types.

When testing the site on IOS devices, I discovered that the Bootstrap table used in the Tour Dates section of the site did not correctly function - sideways scrolling was not possible and do on smaller IOS devices it was not possible to access the **tickets** buttons beside each date. In order to overcome this issue, I decided to collapse the table on small devices via a CSS media query. This solved the issue of the table not working on IOS devices, however, as the `td:before` position had to be set to `absolute` in order to display correctly, this meant the collapsed table was sitting **behind** the transparent overlay that had been placed over the background image in order to make the page's text more legible against the background. In order to solve this issue, I decided to remoe the transparent overlay altogether and simply darken the background image using photoshop and use this darkened image as the background image in order to eliminate the need for the transparent overlay, thus eliminating the problem of the collapsed table sitting behind it instead of on top of it.

On Internet Explorer, I discovered that the Music section of the site is squashed horizontally - the album art images are slightly elongated, and the <audio> elements overlap one another slightly, although they do still function as intended. This section displays correctly across all other browsers I have tested, however, and I am currently attempting to devise a way to solve the horizontal compression issue on Internet Explorer.

## Deployment

This website is hosted using GitHub Pages and has been deployed from the master branch - this allows the deployed site to automatically update with any new commits made to the master branch. The main landing page is named `index.html` in order to ensure that it would be correctly deployed to GitHub Pages.

In order to deploy the site to GitHub Pages, I first clicked the **settings** tab on the GitHub repository for the site, from there I scrolled down to the **GitHub Pages** section of the setting tab and changed the **Source** from 'none' to 'master branch' - this deployed the site to GitHub pages and provided me with a link to the hosted page, which I then added to the description of the repository.

Should you wish to run this application locally, simply click the green **clone or download** button in the [GitHub repository for the project](https://github.com/SianJade/smoking-rolo-sideshow-website), and then type `git clone` followed by the clone or download link into your terminal.


## Credits

### Content
- All content in the About section of the site was written by the band's vocalist and lyricist, Ben Greener.

### Media
- All images and audio files used in this project belong exclusively to The Smoking Rolo Sideshow, who granted me access and permission to use these within the website. The embedded YouTube video is from the band's official YouTube channel, which they also gave me permission utilize in the project.

### Acknowledgements

- The CSS used to override Bootstrap's form focus colour can be found on [Tutorial Republic](https://www.tutorialrepublic.com/faq/how-to-change-bootstrap-default-input-focus-glow-style.php).
- The CSS used to override Bootstrap's tooltip background and arrow colour can be found on [Stack Overflow](https://stackoverflow.com/questions/36143382/re-color-tooltip-in-bootstrap-4).
- The CSS used to remove Bootstrap's default active button outline I adapted from answers found on [Stack Overflow](https://stackoverflow.com/questions/31379175/bootstrap-button-on-click-showing-default-colour).
- The CSS used to collapse the Tour Date table on small devices can be found on [CSS Tricks](https://css-tricks.com/responsive-data-tables/).