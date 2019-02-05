# The Monkees 1960's rock band (Milestone Project | Code Institute)

## [Link to my website](https://matthewhopwood.github.io/the-monkees-project/) 

The aim of this project was to create a user-friendly and eye-catching website, that would instantly induce a positive emotional reponse from the target audience. 
This is purely a front-end (static) website (with the exception of the modal), so there was more of an emphasis on the custom styling. The website uses a particular selection of colors that would
make the audience feel like they are viewing these pages in the 1960's (had that been possible!).

The website has the main purpose of providing the target audience with multiple ways of experiencing and interacting with the 1960's rock band.
This includes:
* Reviews - To allow new followers to get a feel of what the band is like, and older followers the chance to relate with other people.
* About Us - To give a brief explanation of who the band is comprised of, and how they were formed.
* Upcoming Events - To allow the target audience a remote method of obtaining tickets to future shows, in addition to being an information board for the dates/locations of the band.
* Gallery - A section of pictures and individual information for each band member so the audience can build a more personal relationship with the band.
* Media - To showcase the media that The Monkees are a capable of providing.
* Booking - To give the target audience a chance show their appreciation of the band by giving them work and chance to socialise and deepen that personal relationsip even further.

## UX

This website is designed for The Monkees, with the target audience being their fans, as well as any new and potential followers. The Monkees wanted this site
designed in a way that it could; be a showcase for some of their best music over the past years and a platform for any future releases as it becomes available.

It is also important for the band that any details regarding their upcoming events and availability, are to be publicised and announced on an ever growing
platform - to further spread their influence across the UK.

Finally, The Monkees made a special request to include social links to their Facebook, Twitter and Youtube pages in particular, as they are in the process
of creating a social media presence.

The website that has been created accommodates for all of the elements that the customer wanted to achieve and surpasses even those goals.
A mobile first appoach was used as the majority of todays internet browsing is done through mobile, with the website being fully responsive to multiple resolutions (browers sizes)
and a wide range of mobile devices from the Iphone5/SE throught to the Ipad pro.

Before undertaking full blown development of the project, I took advantage of a free trial wireframe package called 'MarvelApp'. I used this to create
mock-ups for both a general desktop and mobile-sized device. You can see all of these by following the link to my wireframes folder below:

[Wireframes Folder](https://github.com/MatthewHopwood/the-monkees-project/tree/master/assets/wireframes)

## Features

### Existing Features

###### Feature No.1 - Navbar
- There is a Logo that acts as a navigation button that takes the user back to the landing page.
There is also nav'bar' of buttons that can be used to easily navigate through the whole site. 
  
###### Feature No.2 - Navbar-Burger-Icon
- This feature has the same functionality as the navbar, allowing for easy navigation through the website,
but on smaller screen devices.

###### Feature No.3 - Footer
- This contains a bar of all the social icons related to the customer, with links directly to their social media.
There is also an extra button of navigation to assist with the postive user experience.

###### Feature No.4 - Home-Page
- This is an information page, with an optional button to an external site where you can 'learn more'.
There is also an events section with ticket buttons.

###### Feature No.5 - Ticket Modal
- The ticket buttons on the home page open a modal, that is is included in the index.html. There are 2 modals
with the second aimed at smaller screen sizes, using the 'select' input type.

###### Feature No.6 - Gallery-Page
- This features a collection of photos of the band as a group and individual band members, along with a brief explanation of each member.

###### Feature No.7 - Media-Page-Video
- The video will autoplay upon visiting the media page, and has a wealth of controls for a positive user experience,
including play/pause/volume etc.

###### Feature No.8 - Media-Page-Audio
- There are three audio files that have been converted into audio players with multiple controls for a positive user experience.

###### Feature No.9 - Booking-Page
- This page is comprised of a form element with multiple 'required' inputs, as well as an abundance of helper
text and placeholders to improve the user-friendly experience.

###### Feature No.10 - Hover Pseudo Classes
- These classes have been included throughout the whole website to make static and uninteresting elements, more interactice
and aesthetically pleasing.


### Features Left to Implement

###### Feature No.1 - Back-End System
- To allow communication from the modal and form elements to the servers, for payments and dynamic content etc.

###### Feature No.2 - Audio-Player 
- To allow a playlist of songs to autoplay/loop/shuffle.

###### Feature No.3 - WorldWide Coverage
- The website currently only uses an 'upcoming events UK' section, however this could be extended to other countries
and possibly worldwide.

## Technologies Used

##### HTML5
- Used to create the html document and the layout of the webpage using a semantic structure. This code will be found in a .html file.

##### CSS3
- Used to create custom styling for each of the elements within the html document. Usually found in a external .css file.

##### JQuery  - http://code.jquery.com/
- This is a small, fast JavaScript library that was used specifically for adding js functionality to the modals and burger-icon.

##### Bootstrap - https://getbootstrap.com/docs/3.3/
- This front-end framework has multiple sections including CSS, components and JavaScript - which were all used within my code.

##### Google Fonts - https://fonts.google.com/
- Used to include different font styles and font weights in the website. Specifically Indie Flower and Exo with a range of 100 - 700 font weights.

##### Font Awesome - https://fontawesome.com/
- Used to include meaningful and representative images/icons to the website. E.g a ticket icon on the events page. 

##### Hover.css - https://cdnjs.com/
- Used in an earlier version of the landing page, which was then scrapped later in development. It was used to add an interactive hover style
when hovering over the navbar buttons.

##### Git/GitHub - https://github.com
- Git was used as the version control system for commiting code to a local repository and pushing the code to a remote repository (in this case GitHub).

## Testing
The testing of the website was carried out all the way through the project using the dev tools within the browser. Then after
the website was 'complete' I carried out a complete functionality test across all the devices within the dev tools and browser size up to 1920x1080.

Testing was done using:
- Google Chrome dev tools on resolutions of 1920x1080, 1024x768, 800x480.
- Samsung S9 (actual phone) - portrait & landscape.
- Iphone 6 (actual phone) - portrait & landscape.
- Ipad - portrait & landscape.

##### Mobile first approach and Responsive design
It is important to mention that as it was being developed with a mobile-first approach in mind, that all of the css is aimed at the smallest device which is the Iphone5/SE
with a resolution of 320x568. 

Using the Bootstrap grid system and media queries I was able to extend the css to target more specific screen sizes - more specifically the standard bootstrap breakpoints.
As well as testing each new feature across all of the devices within the dev tool, I was testing the responsiveness at the the breakpoints using: min-width media queries (mobile-first).

The website is tested to be fully responsive with the breakpoints:
- min-width: 768px (sm)
- min-wdith: 992px (md)
- min-width: 1200px (lg)
 
##### Some common issues I had during testing
- padding had to be reduced on some elements as screen sizes increased.
- widths of images had to be increased as screen sized increased - all image widths were set using % so took up too little space when occupying a col-md-4 column.
- extra margins and paddings were declared in containers by mistake by myself and had to be altered / removed during final testing / changes.
- applying background-colors to inline / inline-block elements instead of block elements, so missing large amounts of color where it should be.

For the final testing of my code I put both the HTML and CSS throught the W3C validators.
- https://validator.w3.org/ HTML.
- https://jigsaw.w3.org/css-validator/ CSS.

The CSS came back with no errors found.

The HTML came back with a few errors, some that I managed to correct, however some errors require the use of JavaScript such as polyfill. This is outside of the scope of this project critera so I have left these errors.

## Deployment

To deploy my project I used the git version control system to add my code to the staging area. I then commited the final version of my project to the local repository, finally pushing the code to the remote repository, which is located in GitHub. 

Before doing this I had to create a repository on GitHub and once I had pushed the code using git, I then used GitHub pages (gh-pages) to publish my site.

You can run this code locally by downloading the repository on GitHub - this can be done by pressing the green button that says 'Clone or download' and the select 'download as zip', then you would extract the files so they can be opened in a local IDE.

GitHub website  - https://matthewhopwood.github.io/the-monkees-project/

## Credits
#### Content
- The text used for the 'Past Reviews' section on the 'Home' page was copied from the comments section on a specific YouTube video - https://www.youtube.com/watch?v=xvqeSJlgaNk.

- The text used for the 'About' section on the 'Home' page was copied from https://en.wikipedia.org/wiki/The_Monkees.

- The text used for the 'Band Members' section on the 'Gallery' page was copied from multiple sources, see below:
   
     https://en.wikipedia.org/wiki/Davy_Jones_(musician)
     https://en.wikipedia.org/wiki/Micky_Dolenz
     https://en.wikipedia.org/wiki/Michael_Nesmith
     https://en.wikipedia.org/wiki/Peter_Tork

- The event dates and locations that are found in the 'Upcoming Events UK' on the 'Home' page are made up.

#### Media

As part of the project I was provided with some assets that can be found at  https://github.com/Code-Institute-Org/project-assets
Below I will list assets I used from the above repository:

##### Images

- assets/images/dj.jpg
- assets/images/mn.jpg
- assets/images/monkees.jpg
- assets/images/pt.jpg

##### Audio 

- assets/media/Clarksville.mp3
- assets/media/DaydreamBeliever.mp3
- assets/mdeia/SteppingStone.mp3
 
##### Video

- assets/media/TheMonkees.mp4

I then used some of my own assets which I acquired through the google images advanced search engine, where the chosen images were filtered for by usage rights.
The filter chosen for all of my images was 'labelled for re-use'. Below I will list the additional assets I included:

##### Images

- assets/own-images/clarksville-cover.jpg
- assets/own-images/cover1.jpg
- assets/own-images/cover4.jpg
- assets/own-images/cover6.jpg
- assets/own-images/daydreamBeliever-cover.jpg
- assets/own-images/group1.jpg
- assets/own-images/group2.jpg
- assets/own-images/group3.jpg
- assets/own-images/group4.jpg
- assets/own-images/md3.jpg
- assets/own-images/steppingStone-cover.jpg

#### Acknowledgements
The inspiration for the general design of my website are mini-projects completed through code-institute. Examples of these can be found below:

- https://matthewhopwood.github.io/resume-project/
- https://matthewhopwood.github.io/bootstrap-responsive/

I also had an issue with equal heights columns with a responsive design, I found a fix online and implemented it into my css file.
The code is: 
        
        <
        .row [class*="col-"] {
            margin-bottom: -99999px;
            padding-bottom: 99999px;
        }
        
        .row {
            overflow: hidden;
        }
        >
Which can found at https://stackoverflow.com/questions/19695784/how-can-i-make-bootstrap-columns-all-the-same-height?fbclid=IwAR0su0KGrEtR7v1WdMKVi8t2bOE3DGLILug7oCn0wCAk1J55ERSp1e2MPFE