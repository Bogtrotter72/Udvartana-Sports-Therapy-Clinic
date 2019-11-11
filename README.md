# UDVARTANA SPORTS THERAPY & MASSAGE CLINIC

This website design was inspired by a dream.  Both my wife and I are Sports Massage Therapists and have discussed the idea of becoming self-employed. Should we ever wish to fulfill that dream, this website could help us achieve that.

Through our work, we have come into contact with others in similar fields and, having discussed my desire to also work in web design, I
approached a potential client and offered my services (pro bono, of course - in order to add something to my portfolio). They immediately asked for an example of my work; I now have something to show them.

Finally, I hope that this site demonstrates my understanding of the front-end technologies used in its creation.

## Demo
A live demo of the site can be found [here](https://bogtrotter72.github.io/Udvartana-Sports-Therapy-Clinic/).
___

![Udvartana Clinic Demo](https://res.cloudinary.com/bogtrotter72/image/upload/v1573497935/Milestone%201/Demo_xgxjvi.jpg)

___

## UX

The goal of the design was to make it as easy as possible for the user to access information about the services offered
and make an appointment.  In this two broad defintions of users were considered:
1. As a user who knows what they want, I simply wish to make an appointment as quickly as possible. (hereafter *uninterested user*)
2. As a user with an interest in complementary therapies, I would like to learn a little more about the services on offer before booking an appointment. (hereafter *interested user*)

In order to test any assumptions made by the author, about what users might expect from a sports therapy and massage clinic, a few members of 
the general public were canvassed and asked to select 3 words from a list of 10 and order them according to how they felt that these words described sports 
massage therapy.

These words form the greeting on the homepage and inform the entire design. The overall green colour scheme and use of plant imagery 
were selected to reinforce the ideas of vitality, health, and relaxation.  In addition, it has been suggested in the 
<a href="https://www.amazon.com/Color-Design-Workbook-World-Graphic/dp/1592534333">Color Design Workbook</a> by Sean Adams, et. al.
(2008, p.28) that the positive symbolism attached to the colour include healing, growth, success and youth.


A pdf of the wireframes is available [here](https://github.com/Bogtrotter72/Udvartana-Sports-Therapy-Clinic/blob/master/wireframes/Udvartana%20Clinic.pdf).


## Features
The lack of a navbar and collapsed menu were chosen to provide a feeling of space and freedom.

The mouse icon changes when hovering on clickable items, and the buttons shift (up on hover and down when pressed). These aim to provide the user with positive feedback. 
The pop out navigation menu and footer navigation menu use the same animation, and overall these features should help provide the user with a sense of continuity.

The whole experience is designed to be effortless.


### Cards
Cards, or card-like shapes are used throughout, providing a sense of continuity. They are also layered and
given shading to give a sense of depth.

### Background images
Each page has a different background image to add a touch of variety.
At the same time, they support the underlying concept of nature, vitality and health.


### Existing Features

The homepage features a *Learn more &rarr;* text button and *BOOK NOW* button which provide quick access for both *uninterested user* and *interested user* to relevant areas.
The *BOOK NOW* button remains a strong feature throughout.

The fixed hamburger / pop out navigation menu and footer navigation menu allow all users to quickly navigate through the site.

The initial positioning of the opening headings and their animation is designed to subtly suggest that Udvartana gives rise to feelings of
revitalization, repair and relaxation. 


### Planned Features
With the addition of JavaScript functionality, it is envisaged that further developments will include a fully-functioning calendar that:

* allows users to change months
* links to a diary-style page, with available times, etc. (_colour coded_)
* notifies the therapist of a booking
* provides customers with the option to select the therapist of their choice
* allows customers to block book appointments


Furthermore, in order to encourage user feedback it would be necessary to create:

* a facility for users to enter feedback (placed on the contact page)
* a new page to accommodate the increase in reviews


Should sufficient interest be shown, it may be possible to allow clients to:
* pay online (particularly for block bookings)
* purchase gift vouchers online


While social media links have been placed on the site, company identities have yet to be created.


<h2>Technologies Used</h2>

Languages used:
1.  HTML
2.  CSS & SCSS
3.  BOOTSTRAP
4.  [Node.js](https://nodejs.org/en) was used to compile the SCSS file to CSS 
    (see [*Deployment*](README.md#deployment) below)

## Testing
### Cross-Device Compatability

The website was tested in the Blisk browser, on a variety of devices, including:
* Samsung Galaxy S5
* iPhone 5/SE
* iPhone 6/7/8
* iPhone X
* iPad
* iPad Pro
and live tested on desktop, laptop and mobile devices.

Font sizes and the positioning of items were tested in both portrait and landscape orientations.
During the development stage, all hover items, buttons, etc. were thoroughly tested using the *forced element state* tools.


### Cross-Browser Compatability
The website was tested in the following browsers:
* Firefox
* Google Chrome
* Internet Explorer 11
* Google Chrome
* Microsoft Edge
* Opera


### General Testing
The final *style.css* file was passed through the <a href="https://jigsaw.w3.org/css-validator/">W3C CSS Validation Service</a>.
All HTML files were passed through the <a href="https://validator.w3.org/">W3C Markup Validation Service</a>.
The files passed with no errors.

[tinyjpg.com](https://tinyjpg.com) and [tinypng.com](https://tinypng.com) were used to compress images and improve loading times.

### Manual Testing
The website was continually tested throughout the project; initially using Google Chrome dev tools, and the later using Blisk dev tools.
It was also tested live on a desktop, laptop and mobile device.  The completed site was also presented to the initial members of the public,
to gather there feedback.

The following items were manually checked for functionality:

1. The navigation menu [all pages], as was the button and navigation link item transitions
2. The logo link to the homepage [all pages]
3. The functioning of the *Learn More* text button
4. The *Book Now* CTA button
5. That submission of the booking form without *required* fields completed failed
6. That clicking on a calendar date links to the CTA button
7. That submission of a completed booking form succeeded.
8. The footer navigation menu
9. The social media icons
10. The link to the author's wordpress site.


### Bugs
There were a number of bugs with the site on Internet Explorer 11.
* card images did not display properly (fixed)
* card height does not accept _min-height_ (fixed) 
* card text does not align centrally on the vertical (remaining)
* bookings calendar does not display correctly (code autoprefixer utilised but bug persists)

There also appears to be an intermittent bug with the booking form.
During approximately 5% of the form submission tests, when the booking form was completed correctly and submitted,
the form simply cleared and requested that the *name* field be filled out. This bug also remains.


<h2 id="deployment">Deployment</h2>
The site is hosted using GitHub pages and was deployed directly form the master branch.
The deployed site will update automatically from new commits.

During the familiarization phase with, and early experiments on, GitHub by the author, early commits were deleted.
This resulted in a substantial initial commit.
<small>Version one is held on file by the author.</small>


The node modules folder has been ignore in order to reduce download size.
In order to alter the code and re-compile the css, it will be necessary to:
1. run an 'npm install' command in a console (after navigating to the main root directory)
2. run an 'npm run compile:sass' command in a console

The script has a 'watch' function and automatically updates on saving the code.



## Credits

### Content
All the content for the therapies and customer feedback were written by the site author.


### Media

Favicon created at [favicon.io](https://favicon.io/favicon-converter/)


HOMEPAGE
* Header image:- 
Photo by [Scott Webb](https://unsplash.com/@scottwebb) on [Unsplash](https://unsplash.com/photos/hDyO6rr3kqk)

* Banner image:- 
Photo by [Scott Webb](https://unsplash.com/@scottwebb) on [Unsplash](https://unsplash.com/photos/zfBjeJR8yRk)

* Massage Therapies main image:- 
Photo by [Nicole De Khors](https://burst.shopify.com/@ndekhors) on [Burst](https://burst.shopifycdn.com/photos/female-relaxing-at-spa.jpg)

* Detox Therapies main image:- 
Photo by [Steve Buissinne](https://pixabay.com/users/stevepb-282134/) on [Pixabay](https://pixabay.com/photos/honey-sweet-syrup-organic-golden-1006972/)

* Anti-Cellulite Treatment main image:- 
Photo by [Nensuria](https://www.freepik.com/nensuria) on [Freepik](https://www.freepik.com/free-photos-vectors/people)

* Customer Feedback image 1:-
Photo by [Pixabay](https://www.pexels.com/@pixabay) on [Pexels](https://www.pexels.com/photo/smiling-woman-wearing-black-shirt-and-pink-button-up-blazer-157741/)

* Customer Feedback image 2:- 
Photo by [Leonel Hernandez Arteaga](https://unsplash.com/@ldhai) on [Unsplash](https://unsplash.com/photos/jns8BPueAgU)

* Therapies background image
Photo by [Matthew Henry](https://burst.shopify.com/@matthew_henry) on [Burst](https://burst.shopifycdn.com/photos/flat-lay-of-autumn-leaves-changing-color.jpg)

* Price List background image:-
Photo by [Anton Darius](https://unsplash.com/@thesollers) on [Unsplash](https://unsplash.com/photos/IuQKQxZs-TA)

* Bookings background image:-
Photo by [Aaron Burden](https://unsplash.com/@aaronburden) on [Unsplash](https://unsplash.com/photos/XxvXRmsH860)

* About Us background image:-
Photo by [Paul Green](https://unsplash.com/@pgreen1983) on [Unsplash](https://unsplash.com/photos/5lRxNLHfZOY)




<h3>Acknowledgements</h3>
I owe a great deal to Jonas Schmedtmann and his 
<a href="https://www.udemy.com/course/advanced-css-and-sass">Advanced CSS Course</a> on Udemy.
By following his course, I learned how to compile Sass, and use variables and mixins.

I am particularly indebted to him for the website's navigation menu, the checkbox hack and pseudo-classes, as well as the 'center-screen' mixin.
(see his 'Natours' project on <a href="https://github.com/jonasschmedtmann/advanced-css-course/tree/master/Natours">GitHub</a>)

Where possible, I have endeavoured to adapt the code to satisfy my own particular tastes, or the requirements of the project,
rather than blindly copy it.  In some instances, however, I found no better way of realizing my vision
in code; the 'center-screen' mixin, for example, is 100% Schmedtmann.

Other resources that have proven exceedingly useful, include:
* w3schools
* Mozilla Developer Network
* Stack Overflow
* freecodecamp
* Get BEM
* Code Institute (of course)
* Fellow students and the Slack channels

In all instances, where I have sought solutions to problems, I have read how others have approached the problem,
taken inspiration and attempted to find my own way.  In so doing, I hoped to learn something.




**Disclaimer**    
The content of this website is for educational purposes only.