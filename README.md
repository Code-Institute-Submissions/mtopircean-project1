
# Romanian Orthodox Church Kilkenny and Waterford webpage

The website was created as support for the Romanian Orthodox Community in Kilkenny, Waterford and surrounding areas to connect with the members of the community, inform them about the Church`s activity, schedule, location and events.

In addition to connecting the community, it`s purpose is also to offer an area where interested people can access media on Orthodoxy and the Orthodox Church, as well as media material from community events.



## Website structure description
Website is structured into 4 main pages:
1. Home:
* provides a main image and text section which at the moment redirects user to our contact details, but in the future will provide an area to redirect to any location will be considered of interest
* schedule and events section which will provide details on Service dates, location as well as the different activities happening in the community
* quote of the month

2. About:
* provides a short description of the community as well as links to the contact and schedule section

3. Media:
* structured based on a timeline format will provide a source of media material split by month; in order to navigate, for resolutions above px, users can make use of the fixed timeline format on the left side of the page

4. Contact:
* provides a contact form in which users can input their data and submit in order to receive notifications based on areas of interest
* also provides a section which contains 2 map areas set for the alternate locations of the church; user can use them to launch Google Maps navigation
## About development process
Website developed using github, gitpod, codeanywhere.
Devtools also used to support CSS development.
89 total commits on the 24th of April 2023.
## Logo and other non-code elements
Website logo was design using font awesome.
For fonts, technology used was google fonts.
For photos data source was Pexels and https://www.zamfirphoto.com/, a local community photographer.
Website also uses iframes for videos and maps from google and youtube.
Video description text in media page is taken from the each of the relevant youtube links.

## Test and Debugging
Code and website tested with:
* w3.org/2002/01/spellchecker for spelling errors; errors where fixed
* validator.w3.org for code errors; errors where fixed 
* jigsaw.w3.org/css-validator/ for css code errors; errors where fixed
* wave.webaim.org for accessibility issues; majority of issues and recommendations implemented without affecting website functionality and theme

Debugging:
* error in using the timeline on Media page; when clicking on a specific month the page started to transition between different sections without reaching the required location; error found as code was duplicated by mistake, duplicate removed and error fixed;
* fixed footer was sitting on top of last video in media section; error fixed by adding a bottom margin to the video sections
* navigation menu too large for small media devices; beside resizing, the home button converts into a home icon on smaller devices
* when using the W3C validator I have encountered: "The frameborder attribute on the iframe element is obsolete"; error fixed by removing the frameborder element from iframe
## Credits
Photography used from Pexels and https://www.zamfirphoto.com/, a local community photograph.
Basic code inspiration taken from the Love Running Project in order to design the submit button on the form in the Contact page, on adding the font awesome and google font link.
## Display size optimization
Website is optimized for different sizes:
* from 1200px wide and down
* from 954px wide and down
* from 800px wide and down
* from 600px wide and down: 
    * with first major structural change representing the removal of the timeline section from the media page
    * introduction of a restyled navigation menu
* from 425px wide and down
* from 361px wide and down
## Authors

Marius Topircean is an aspiring webdeveloper who initiated it`s journey in coding with this first project.

My contact details are:

Email: mtopircean@yahoo.com

Phone: +353857642212

Slack: Marius Topircean

Github: mtopircean

