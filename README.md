# UDVARTANA SPORTS THERAPY & MASSAGE CLINIC
<p>
    This website has been developed as a platform for attracting new clients to a planned, future business venture
    (namely a Sports Massage and Complementary Therapy Clinic), to provide clients and the business owner with an
    online therapy booking service, but also as the first entry into a website portfolio, that may attract potential 
    clients in similar fields (for the author).
</p>


## UX
<p>
    In order to establish what clients might expect from a sports therapy and massage clinic, a number of members of 
    the general public were canvassed and asked to select 3 words from a list of 10
    and order them according to how they felt that these words described sports massage therapy.
    Alliteration was used to provide an immediate sense of flow, ease and continuity.
</p>
<p>
    A number of members of the general public were canvassed and asked to select 3 words from a list of 10
    and order them according to how they felt that these words described sports massage therapy.
    I used alliteration to provide an immediate sense of ease and continuity.
</p>

## Features
<p>
    The overall green colour scheme and use of plant imagery were selected to reinforce the ideas of vitality, health,
    and relaxation.  In addition, the <a href="https://www.amazon.com/Color-Design-Workbook-World-Graphic/dp/1592534333">Color Design Workbook</a> by Sean Adams, et. al.
    (2008, p.28) suggests that the positive symbolism attached to the colour include healing, growth, success and youth.
</p>
<p>
    The lack of a navbar and collapsed menu were chosen to provide a feeling of space and freedom.  The use of cards and card
    layers (with muted shadows) provide a subtle three-dimensional effect, while supporting the sense of space. 
    At the same time, however, they also break up, what would otherwise be a large amount of whitespace.  They also 
    compartmentalise subjects into relevant areas making the site easier to navigate and understand.
</p>
<p>
    The mouse icon changes to a pointer when hovering on clickable items, and buttons shift up on hover and down when pressed
    to provide the user with positive feedback.

    As weel as those features mentione above, the pop out navigation menu and footer navigation menu use the same animation, and
    overall these features should help provide the user with a sense of continuity.
</p>
<p>
    The whole experience is designed to be effortless.
</p>


### Existing Features
* The hamburger / pop out navigation menu allows all users to quickly navigate through the site.
* The _Learn more &rarr;_ text button allows the inquisitive user to quickly navigate to the relevant section on the **Therapies** page.
* The _BOOK NOW_ button provides users a method of quickly navigating to the **Bookings** page.


### Planned Features
With no *Back End*, the bookings page does not function.  It is planned that further developments will include
a fully-functioning calendar that:

..* links to a diary-style page, with available times, etc. (_colour coded_)
..* notifies the therapist of a booking
..* provides customers with the option to select the therapist of their choice
..* allows customers to block book appointments

Should sufficient interest be shown, it may be possible to allow clients to:
..* pay online (particularly for block bookings)
..* purchase gift vouchers online


<h2>Technologies Used</h2>

Languages used:
1.  HTML
2.  CSS & SCSS
3.  BOOTSTRAP
4.  <a href="https://nodejs.org/en">Node.js</a> was used to compile the SCSS file to CSS 
    (see <em> <a href="README.md#deployment">Deployment</a></em> below)

<a href="https://tinyjpg.com">tinyjpg.com</a> and
<a href="https://tinypng.com">tinypng.com</a> to compress images // Faster loading time

<h2>Testing</h2>
<h3>Cross-Device Compatability</h3>
<p>The website was tested in the device toolbar of Chrome's Devtools, on:
    * Galaxy S5
    * iPhone 5/SE
    * iPhone 6/7/8
    * iPhone X
    * iPad
    * iPad Pro
    and live tested on desktop (22" monitor with 1920x1080 resolution), laptop(17" monitor 1920x1080 resolution) and mobile (Samsung A40) environments.
</p>

All hover items, buttons, etc. were thoroughly tested using the *forced element state* tools.

<h3>Cross-Browser Compatability</h3>
<p>The website was tested in the following browsers:
    * Google Chrome
    * Firefox
    * Opera
    * Internet Explorer 11
</p>

<p>The website was also tested in Lunascape 6, using the following engines:
    * Gecko
    * Trident
    * Webkit
</p>

<h2 id="deployment">Deployment</h2>

The node modules folder has been removed in order to reduce download size.
In order to alter the code and re-compile the css, it will be necessary to:
1. run an 'npm install' command in a console (after navigating to the main root directory)
2. run an 'npm run compile:sass' command in a console

The script has a 'watch' function and automatically updates on saving the code.


<h2>Credits</h2>

<h3>Content</h3>
<p>
    I owe a great deal to Jonas Schmedtmann and his 
    <a href="https://www.udemy.com/course/advanced-css-and-sass">Advanced CSS Course</a> on Udemy.
    By following his course, I have learned how to compile Sass, and use variables and mixins.</br>
    I am particularly indebted to him for my website's navigation menu, my use of the 
    checkbox hack and pseudo-classes, as well as the 'center-screen' mixin.
    (see his 'Natours' project on <a href="https://github.com/jonasschmedtmann/advanced-css-course/tree/master/Natours">GitHub</a>)
</p>
<p>
    Where possible, I have endeavoured to adapt the code to satisfy my own particular tastes, or the requirements of the project,
    rather than blindly copy it.  In some instances, however, I found no better way of realizing my vision
    in code; the 'center-screen' mixin, for example, is 100% Schmedtmann.
</p>
<p>
    Other resources that have proven exceedingly useful, include:
    * w3schools
    * Mozilla Developer Network
    * Stack Overflow
    * freecodecamp
    * Get BEM
    * Code Institute (of course)
    * Fellow students and the Slack channels
</p>
<p>
    In all instances, where I have sought solutions to problems, I have read how others have approached the problem,
    taken inspiration and attempted to find my own way.  In so doing, I hoped to learn something.
</p>

<h3>Media</h3>

Favicon created at <a href="https://favicon.io/favicon-converter/">favicon.io</a>


HOMEPAGE
<ul>

<li>
    Header image:- 
    Photo by <a href="https://unsplash.com/@scottwebb">Scott Webb</a> 
    from <a href="https://unsplash.com/photos/hDyO6rr3kqk">Unsplash</a>
</li>

<li>
    Massage Therapies main image:- 
    Photo by <a href="https://burst.shopify.com/@ndekhors?utm_campaign=photo_credit&amp;utm_content=Free+Female+Relaxing+At+Spa+Image%3A+Stunning+Photography&amp;utm_medium=referral&amp;utm_source=credit">Nicole De Khors</a> 
    from <a href="https://burst.shopify.com/spa?utm_campaign=photo_credit&amp;utm_content=Free+Female+Relaxing+At+Spa+Image%3A+Stunning+Photography&amp;utm_medium=referral&amp;utm_source=credit">Burst</a>
</li>

<li>
    Detox Therapies main image:- 
    Photo by <a href="https://pixabay.com/users/stevepb-282134/">Steve Buissinne</a>
    from <a href="https://pixabay.com/photos/honey-sweet-syrup-organic-golden-1006972/">Pixabay</a>
</li>

<li>
    Anti-Cellulite Treatment main image:- 
    Photo by <a href="https://www.freepik.com/nensuria">Nensuria 
    from <a href="https://www.freepik.com/free-photos-vectors/people">www.freepik.com</a>
</li>

<li> 
    Customer Feedback image 1:-
    Photo by <a href="https://www.pexels.com/@pixabay">Pixabay</a> 
    from <a href="https://www.pexels.com/photo/smiling-woman-wearing-black-shirt-and-pink-button-up-blazer-157741/">Pexels</a>
</li>

<li>
    Customer Feedback image 2:- 
    Photo by <a href="https://unsplash.com/@ldhai">Leonel Hernandez Arteaga on Unsplash</a>
    from <a href="https://unsplash.com/photos/jns8BPueAgU">Unsplash</a>
</li>
</ul>

<!-- 
About Us Background Image
Photo by <a href="https://unsplash.com/@pgreen1983">Paul Green on Unsplash</a>
from <a href="https://unsplash.com/photos/5lRxNLHfZOY">Unsplash</a>

About Us image 1
Photo by <a href="https://unsplash.com/@betoframe">Humberto Chavez</a> 
from <a href="https://unsplash.com/photos/FVh_yqLR9eA">Unsplash</a>





THERAPIES PAGE
Background image
Photo by <a href="https://burst.shopify.com/@matthew_henry?utm_campaign=photo_credit&amp;utm_content=Browse+Free+HD+Images+of+Flat+Lay+Of+Autumn+Leaves+Changing+Color&amp;utm_medium=referral&amp;utm_source=credit">Matthew Henry</a> from <a href="https://burst.shopify.com/leaves?utm_campaign=photo_credit&amp;utm_content=Browse+Free+HD+Images+of+Flat+Lay+Of+Autumn+Leaves+Changing+Color&amp;utm_medium=referral&amp;utm_source=credit">Burst</a> -->


<h3>Acknowledgements</h3>
