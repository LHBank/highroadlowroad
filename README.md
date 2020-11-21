<p align="center">
    <img src="assets/img/HRLRLogo.jpg" alt="HRLR_logo">
</p>

# High Road Low Road

## Description

Welcome to High Road Low Road, an online resource website which has been designed to the highlight the spectacles a vacation to
could include. It utilises Google Maps in order to visually provide the user an understanding of the attractions, sights and accommodation 
which may be beneficial on a trip to rural or urban Scotland.

## Deployment

This website has been deployed to Github pages and can be accessed by [clicking here.](https://lhbank.github.io/highroadlowroad/)

The steps I took in order to deploy this site to GitHub pages were as follows:

* I first selected the chosen repository, in this case "HighRoadLowRoad".
* I then selected the 'Settings' tab, seen above the contents list of the repository.
* Scrolling down to the GitHub Pages subheading near the bottom of the page.
* When clicking on the dropdown menu box, and changing the option from "none" to "Master Branch".
* Once this page has automatically refreshed on changing this option, scroll down to the same Github
Pages subheading, which now has a green highlighted box, confirming that the site has been published.

## User Experience (UX)

## User Stories

### First Time Visitor Goals
* As a new user to the site, I want to be able to visit the site and understand its main purpose.
* As a new user to the site, I want to be able to navigate easily through the site to find specific content regarding the site's purpose.
* As a new user to the site, I want to have the option to visit social media sites, related to HighRoadLowRoad.

### Returning Visitor Goals
* As a returning user to the site, I want to be able to contact the proprietor and for any issues or further ideas regarding a vacation to Scotland.
* As a returning user to the site, I want to understand the designation of the colour coded markers with those of the markers on the interactive map.

### Frequent User Goals
* As a frequent user of the site, it is important that I be able to check for more recent testimonials published on the site, about the service HighRoadLowRoad
provide, as well as their presence and reputation within travel and tourism.

## Design 

### Colour Scheme
The colour theme chosen to style the included content was generated by Coolors. The colour palette was sampled against the animated logo,
and resulted in 'Persian Green' for the "HighRoad" portion of the name, and 'Maximum Yellow Red' for the "LowRoad" portion. This theme was then
carried on throughout, with highlighted words carrying emphasised intonation, in 'Light Coral'.

### Typography
All font styles were extracted from Google Fonts. The title, HighRoadLowRoad, has been formatted with the font 'Montserrat Subrayada'. Throughout 
the site, a consistent implementation of only two fonts were used. 'Raleway' was used against all heading and subheading elements, and 'Montserrat 
Alternates' against the text content and navigation links. Sans Serif was used as a substitute where the aforementioned custom fonts were not supported 
by selected browsers or devices.

### Imagery
With imagery being vital for user experience, original images owned by William Marjoribanks, were applied as background images. They could be altered
using a custom radio button, within the lower footer of the site. This was not kept in local storage, as the site was not prioritised as a themeable site, 
however was included to give the option of rural and urban imagery, likely to be seen whilst travelling throughout Scotland. 

On scrolling, the background images, were set to a fixed position, of the browser window - excluding of course the scrollbar - to give the illusion that 
the text content was moving <em>around</em> the images.

### Wireframes
The wireframes created at the beginning of the project and used as a reference throughout are situated in a dedicated folder entitled ['wireframes'](...), 
at the same level as the homepage, 'index.html'. It contains screenshot images, for both the Mobile, Tablet and Desktop viewport screen sizes, due to the use
of Bootstrap, and the prioritisation on Mobile-first devices.

# Features
* Interactive Google Map.
* Interactive links to related social media networks and subscription.
* Contact Form.

# Technologies Used
* [ScrollReveal](https://unpkg.com/scrollreveal) - This open source project listed in deployed GitHub pages, allowed elements with in each section of the site
  to respond to the user scrolling down the page for the first time. The elements would enter the browser window from different viewpoints. This was used with Javascript
  and kept in a separate Javascript file from that of the Google Maps syntax, for clarity.

## Languages Used
* HTML5
* CSS3
* Javascript - Used within various key elements of the site, including: Navbar, Collapse, Dropdown Menu, Carousel, Buttons. It was also used for the animated elements of
the site, such as: the Animated Site Logo and Scroll Reveal Utility.
* Google API used in line with Javascript to create an interactive element which displayed image markers, representing locations 
throughout Scotland.

## Frameworks, Libraries & Programs Used
* [Bootstrap 4.5](https://getbootstrap.com/) - Bootstrap was utilised as a framework for CSS used throughout the site.
* [Popper.js](https://popper.js.org/) - Used for the navigation elements on Carousel elements used on the site.
* [jQuery](https://jquery.com/) - Used as a Javascript library by Bootstrap.
* [GitHub](https://github.com/) - GitHub was utilised for version control of the site.
* [Gitpod](https://www.gitpod.io/) - Gitpod was used over the duration of this site, as a virtual workspace environment.
* [WireframeCC](https://wireframe.cc/) - This service was utilised to create sample wireframe guides to structure the content to be displayed on the site.
* [Google Fonts](https://fonts.google.com/) - Google Fonts was chosen to supply all fonts used throughout the site.
* [Font Awesome](https://fontawesome.com/) - FontAwesome was used for icons used in footer.
* [Materialize](https://materializecss.com/) - Materialize was used for the 'Hamburger' menu item at the top of the page.
* [Coolors](https://coolors.co/) - This service, was used to generate a colour palette which would be used against all elements in a consistent theme throughout
  the site.
* Lightroom 4 - Pre-installed photography editing software used to compress the images used throughout the gallery pages.
* [TinyPNG](https://tinypng.com/) - was used to further compress all images used throughout the site.
* [Formspree.io](https://formspree.io/) - This tool was used to enable the user to contact the author/owner of the site, via a contact form on the Contact page.
* [Figma](https://www.figma.com) - This application was used to create an animated SVG which used Javascript on initial loading of site only.
* [ScrollReveal](https://unpkg.com/scrollreveal) - This open source project listed in deployed GitHub pages, allowed elements with in each section of the site
  to respond the the user scrolling. The elements would then enter the browser window from different areas. This was used with Javascript.

# Testing

## Testing User Stories from User Experience (UX) Section

### First Time Visitor Goals
* As a first time user, I was able to see that the site used strong imagery to highlight key attractions within Scotland.
* As a first time user, I was able to navigate with ease throughout the site using the navbar at the head of page, to each
dedicated section and had options which linked to third party sites.
* As a first time user, I was able to click on the social media links in the contact section of the site, via dedicated logos which I 
recognised immediately.

### Returning Visitor Goals
* As a returning user, I was able to click on colourful customised interactive markers on the map, placed in the "Adventure" section of the site, and understand 
their relevance. This made for ease of use, and was familiar on how to control the map for my own purposes.
* As a returning user, I was able to send a message to the owner of HRLR to ascertain more information about a recommended attraction, advertised on the 
featured Google Map.

### Frequent User Goals
* As a frequent user of the site, I was able to to access features of the site, which were inline with local government guidelines regarding COVID19. These features
include the points of interest and markers displayed on the Google Map.
* As a frequentt user of the site, I liked the functionality of the interchangeable background images, which portrayed the different landscapes to be experienced, from
rural to urban, and would like to see more options in the future. I would also like the option to purchase these images as prints.

## Further Testing

### Scalability
Ideas to further develop the site seamless use, and better user experience, would be to include radio buttons, which, using Javascript could
interact with the Google Maps API. For example, labelling two radio buttons: "City Life" and "Rural Life", then, when selecting the respective 
button, the relevant markers would appear on the Google Map.

### Speed Testing
To measure the speed of the site's loading, I used GTMetrix. [Clicking on this link](https://gtmetrix.com/reports/lhbank.github.io/3LRBMkon/), 
will open a new window with the report attached to HighRoadLowRoad.

# Credits

## Media

[Am I Responsive](http://ami.responsivedesign.is/?url=https%3A%2F%2Flhbank.github.io%2Fhighroadlowroad%2F#) - This tool had been utilised to demonstrate 
the responsiveness that can be expected across various screen devices. In addition to using [Am I Responsive](http://ami.responsivedesign.is/?url=https%3A%2F%2Flhbank.github.io%2Fhighroadlowroad%2F#),
the site across personal mobile devices in Opera, Safari and Chrome, and found the responsiveness to be the same.

<img src="wireframes/responsive.png" width="500">

## Content
The process for me to create a functioning site, inclusive of Javascript, required a great deal of extra research into understanding how to best 
serve the site's purpose. This meant watching various tutorials and reading varied and detailed documentation for inspiration. The following were used:

* [Animated site-logo tutorial](https://www.youtube.com/watch?v=vJNVramny9k)
* [Scotch.io](https://scotch.io/) - assisted in breaking down aspects of Javascript into more digestible parts.
