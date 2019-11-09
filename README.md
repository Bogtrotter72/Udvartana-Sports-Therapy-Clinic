# UDVARTANA SPORTS THERAPY & MASSAGE CLINIC

This website design was inspired by a family friend who has a home business.
It was also inspired by the desire to attract a potential client and as the initial entry into a portfolio that may attract
prospective employers.

Both I and a family friend are therapists and have discussed becoming self-employed. This website would support us should we wish to realise that dream.
Having discussed pro bono work with a potential client, they immediately asked for an example of my work; I now have something to show.

Finally, the site demonstrates my ability to code using front-end technologies.


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


## Features
The lack of a navbar and collapsed menu were chosen to provide a feeling of space and freedom.

The mouse icon changes when hovering on clickable items, and the buttons shift (up on hover and down when pressed). These aim to provide the user with positive feedback. 
The pop out navigation menu and footer navigation menu use the same animation, and overall these features should help provide the user with a sense of continuity.

The whole experience is designed to be effortless.


### Existing Features

The homepage features a *Learn more &rarr;* text button and *BOOK NOW* button which provide quick access for both *uninterested user* and *interested user* to relevant areas.
The *BOOK NOW* button remains a strong feature throughout.

The fixed hamburger / pop out navigation menu and footer navigation menu allow all users to quickly navigate through the site.

The initial positioning of the opening headings and their animation is designed to subtly suggest that Udvartana gives rise to feelings of
revitalization, repair and relaxation. 


<a href="https://tinyjpg.com">tinyjpg.com</a> and <a href="https://tinypng.com">tinypng.com</a> were used to compress images and improve loading times.


### Planned Features
With the addition of JavaScript functionality, it is envisaged that further developments will include a fully-functioning calendar that:

* allows users to change months
* links to a diary-style page, with available times, etc. (_colour coded_)
* notifies the therapist of a booking
* provides customers with the option to select the therapist of their choice
* allows customers to block book appointments

Should sufficient interest be shown, it may be possible to allow clients to:
* pay online (particularly for block bookings)
* purchase gift vouchers online


<h2>Technologies Used</h2>

Languages used:
1.  HTML
2.  CSS & SCSS
3.  BOOTSTRAP
4.  <a href="https://nodejs.org/en">Node.js</a> was used to compile the SCSS file to CSS 
    (see <em> <a href="README.md#deployment">Deployment</a></em> below)

## Testing
### Cross-Device Compatability

The website was tested in Blisk, on a variety of devices, including:
* Samsung Galaxy S5
* iPhone 5/SE
* iPhone 6/7/8
* iPhone X
* iPad
* iPad Pro
and live tested on desktop, laptop and mobile devices.

Font sizes and the positioning of items were tested in both portrait and landscape orientations.
All hover items, buttons, etc. were thoroughly tested using the *forced element state* tools.


### Cross-Browser Compatability
The website was tested in the following browsers:
* Google Chrome
* Firefox
* Opera
* Internet Explorer 11

The website was also tested in Lunascape 6, using the following engines:
* Gecko
* Trident
* Webkit


### General Testing
The final *style.css* file was passed through the <a href="https://jigsaw.w3.org/css-validator/">W3C CSS Validation Service</a>.
All HTML files were passed through the <a href="https://validator.w3.org/">W3C Markup Validation Service</a>.
The files passed with no errors.


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

Favicon created at <a href="https://favicon.io/favicon-converter/">favicon.io</a>


HOMEPAGE
* Header image:- 
Photo by <a href="https://unsplash.com/@scottwebb">Scott Webb</a> 
from <a href="https://unsplash.com/photos/hDyO6rr3kqk">Unsplash</a>


* Massage Therapies main image:- 
Photo by <a href="https://burst.shopify.com/@ndekhors?utm_campaign=photo_credit&amp;utm_content=Free+Female+Relaxing+At+Spa+Image%3A+Stunning+Photography&amp;utm_medium=referral&amp;utm_source=credit">Nicole De Khors</a> 
from <a href="https://burst.shopify.com/spa?utm_campaign=photo_credit&amp;utm_content=Free+Female+Relaxing+At+Spa+Image%3A+Stunning+Photography&amp;utm_medium=referral&amp;utm_source=credit">Burst</a>


* Detox Therapies main image:- 
Photo by <a href="https://pixabay.com/users/stevepb-282134/">Steve Buissinne</a>
from <a href="https://pixabay.com/photos/honey-sweet-syrup-organic-golden-1006972/">Pixabay</a>


* Anti-Cellulite Treatment main image:- 
Photo by <a href="https://www.freepik.com/nensuria">Nensuria 
from <a href="https://www.freepik.com/free-photos-vectors/people">www.freepik.com</a>


* Customer Feedback image 1:-
Photo by <a href="https://www.pexels.com/@pixabay">Pixabay</a> 
from <a href="https://www.pexels.com/photo/smiling-woman-wearing-black-shirt-and-pink-button-up-blazer-157741/">Pexels</a>


* Customer Feedback image 2:- 
Photo by <a href="https://unsplash.com/@ldhai">Leonel Hernandez Arteaga on Unsplash</a>
from <a href="https://unsplash.com/photos/jns8BPueAgU">Unsplash</a>


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
