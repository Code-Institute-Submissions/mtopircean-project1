
# Romanian Orthodox Church Kilkenny and Waterford webpage

The website was created as support for the Romanian Orthodox Community in Kilkenny, Waterford and surrounding areas to connect with the members of the community, inform them about the Church`s activity, schedule, location and events.

In addition to connecting the community, it`s purpose is also to offer an area where interested people can access media on Orthodoxy and the Orthodox Church, as well as media material from community events.

Once the website will be published online, it will be donate to the Church and will become communities official webpage.
## CONTENT
* [Scope](#scope)
* [User Experience](#user-experience)
* [Deployment](#deployment)
* [Technologies](#technologies)
    * [Programing Languages](#programing-languages)
    * [IDE](#ide)
    * [Other](#other)
* [Design](#design)
    * [Wireframes](#wireframes)
    * [Theme](#theme)
    * [Color Selection](#color-selection)
    * [Font and text style](#font-and-text-style)
    * [Imagery](#imagery)
    * [Features](#features)
    * [Accessability](#accessability)
    * [Display size optimization](#display-size-optimization)
* [Testing and Validation](#testing-and-validation)
    * [HTML](#html)
    * [CSS](#css)
    * [Accessability Test](#accessability-test)
    * [Lighthouse](#lighthouse)
    * [Spellcheck](#spellcheck)
    * [Fixed bugs](#fixed-bugs)
    * 
* [Credits](#credits)
    * [Code Used](#code-used)
    * [Video](#video)
    * [Photography](#photography)
    * [Other](#other)
* [About Author](#about-author)
## Scope
Website was created with 3 main Objectives:
1. Inform the current community about Church Schedule, Events and make available usefull media content.
2. Become a tool of support for new visitors with a desire to connect and become part of the community.
3. Establish an online presence for the Orthodox Romanian Church in the Kilkenny and Waterford areas.
##  User Experience
#### First Time Visitor Target:
1. Provide a source of information and support on Orthodoxy related topics.
2. Enable a point of connection with the community by providing updated information on schedule and events as well as allowing the user to connect with the community via facebook and a contact form.
3. Provide location instructions for Church`s 2 main location.


####  Returning Visitor Target:
1. Continue to be informed about Service-Schedule.
2. Find out more about upcoming events.
3. Continue to consume media targeted to support users religious journey.
4. Provide media content from comunities events.

#### Frequent Visitors Target:
1. Use the website as the official tool of information about the community and the church.

## Deployment

Deployment of the website was used with GitHub Pages support.
Deployed website can be visited at the [link](https://mtopircean.github.io/project1/)

To deploy using GitHub pages:

* Login or Sign Up to GitHub.
* Open the project repository.
* Click on "Settings" on the navigation bar under the repository title.
* Click on "Pages" in the left hand navigation panel.
* Under "Source", choose which branch to deploy. This should be Main for newer repositories (older repositories may still use Master).
* Choose which folder to deploy from, usually "/root".
* Click "Save", then wait for it to be deployed. It can take some time for the page to be fully * * deployed.
* Your URL will be displayed above "Source".



## Technologies

#### Programing Languages:
1. HTML
2. CSS


#### IDE:
1. GitHub: mainly to deploy workspace, website and store database, but used to write small pieces of code and deploy the 404 page.
2. CodeAnywhere: support to write code and deploy via git to GitHub.
3. GitPod: support to write code and deploy via git to GitHub.

#### Other:
1. Pexels: support with photo data.
2. Font Awesome: support with icon for logo and social media icon.
3. Google Font: support with font used for the website text.
4. Youtube: video`s in media section deployed as iframes with Youtube code.
5. Google Maps: maps in contact section deployed as iframes with Google Maps code.
6. Balsamiq: support with wireframe creation.
7. Google DevTools: support with CSS styling, troubleshouting and responsive design development.
8. Lighthouse: performance testing .
9. W3C Spell Checker: spelling checks.
10. WAVE Web Accessibility Evaluation Tools: for accessibility evaluation.
11. CSS Validation Service: for CSS code evaluation and troubleshouting.
12. W3C Markup Validation Service: for HTML code evaluation and troubleshouting.
## Design
The general design idea was to: 
* Maintain a clean direction with clearly identifiable and accesible areas even when resizing into small screen areas; this was considered in order to address also the different age profiles of the audience.
* Inspire a religious theme through proper use of fonts, colors and images.
* High impactfull hero image in order to highlight the size of community and the extremly beautifull enviorement used for service.
* Use a cusomizeble design proposal that can resize into smaller sizes without creating a high level of complexity.

#### Wireframes
In order to support development, wireframes where created for each individual page in Balsamiq.

* Home:
![Alt text](/readme/wireframe/home-page-wf.jpg)
* About:
![Alt text](/readme/wireframe/about-us-page-wf.jpg)
* Media:
![Alt text](/readme/wireframe/media-page-wf.jpg)
* Contact:
![Alt text](/readme/wireframe/contact-page-wf.jpg)
* Form submit redirect page:
![Alt text](/readme/wireframe/redirect-page-wf.jpg)
* 404 Customized page:
![Alt text](/readme/wireframe/404-page-wf.jpg)

#### Theme
Theme of the website was thought in a way that it would address:
* The religious aspect through use of neutral, clear and clean fonts and style and by using strong religious themed photos and other media content.
* Through use of the underline on the menu items, to push also the Romanian National thematic direction.
* Clear and clean design in order to address all targeted users.
* Provide a message easy to understand and easy to access.
* Highlight key elements: schedule, events, location, media content, facebook link.
* Provide a direction that is easy to be followed and implemented in various screen sizes/devices.

#### Color Selection
Color selection done in order to be aligned with the thematic of the website and to provide sobriety while maintaining clarity and accessability for all.
A splash of color was added by the introduction of the menu decorations representing the Romanian national colors. Choice was taken in order to again support the websites thematic.
![Alt text](/readme/other/color-pallete.jpg)


#### Font and text style
Text and font used are consistent across the website with variances in regards of style and size.
Font used was taken out of Google Fonts and is name bitter:
![Alt text](/readme/other/bitter-font.jpg)

#### Imagery
Hero image was taken by a local photographer called [Zamfir Constantin](https://www.zamfirphoto.com/). Image was shared by him in order to support building communities website.
Other images in about page where taken from [Pexels](https://www.pexels.com/) which offer a free for commercial use collection of photography.

#### Features

* GENERAL:
Website contains 6 pages from which 4 are visible and accessabile from main menu and another 2 are a reaction to a users action.
Menu and Header strucutre remains the same but changes in design with different screen size resolutions.
I`ve created 2 menus:
    * one that is used for resolution above 600px, which is the standard menu.
    * one that is used for resolutions under 600px which transforms the HOME menu setion into a font-awesome house logo.
On both menus, the text data changes to same color as underline when hoverd over.
![Alt text](/readme/other/header-resizing.jpg)

Footer information remains the same across all pages and screen resolutions and have a fixed position containing a facebook link for communities facebook page.
![Alt text](/readme/other/footer.jpg)


* HOME: 
Contains 4 main section:
    * Hero image with a text section on a blured background linked to the About section.
    * Schedule Schedule and Events which share the same height and sit side by side under Hero image; intention is that the website will allow to build additional blockers in the same format; porpouse of this 2 sections is to inform on schedule activities.
    * Quote of the month section.

* ABOUT:
Contains 2 main sections:
    * Information about the community with links to different sections of the website: contact, schedule, location.
    * Image section which in desktop mode is positioned on right and in mobile moves to bottom of the page above footer.

* MEDIA:
Contains 3 main section:
    * A timeline feature that allows for the user to select a specific month and the webpage will move to the media info for that particluar month; position of timeline remains fixed and for resultions under 600px disapears completly due to realestate availability.
![Alt text](/readme/other/timeline-feature.jpg)

    * Description section that details the objective of the page.
    * Media data strucured by month and connected to the timeline feature; each media data contains a description of the presented content; media data used was implemented throguh iframe functionality  based on Youtube created links;

* CONTACT:
Contains 2 main sections:
    * Contact form which collects the main user contact data(first and last time as well as the email data), allows the user to select his interest areas on which he wants to be notified on, and the submit button; submit button changes color once hovered over.
    * Maps for Church`s 2 locations which allows the user, if opened on a mobile device, to open in Google Maps and navigate; map data was implemented through iframe functionality based on Google Maps created links

* FORM REDIRECT:
Page visible only when submit button in form page is pushed. Page acts as a temporary redirect page that will confirm form was submitted and notify user will be redirected to main page in 10 seconds.

* 404 PAGE:
Page designed in order to provide 404 customized message and experience.


#### Accessability
From an accessability perspective, my goal was to create a clean website with data easy to read, positioned in a relevant maner in the page for the user.
I`ve achieved this by:
* Writing semantinc HTML
* Correct selection of text size and font in order to contrast well with the other elements of the page.
* Selection of photos used based on high resolution, good contrast.
* As majority of photos where implemented as background, titles where used in order to replace alt attributes

Another area I was mindfull of was that all of the consideration above where not lost when using the website in lower resolutions.


#### Display size optimization
![Alt text](/readme/other/responsive-view.jpg)
Several size options where used when developing the responsive design.
Please see bellow a list and the main areas of impact when implemented:

* from 1200px wide and down: Mostly reszing of different elements but without major structural changes.
* from 954px wide and down: Elements moved into a stacked format on all pages in order to display correctly, one elements per full page withth. The other change is the resizing and positioning of Menu under Logo.
* from 800px wide and down: Mostly reszing of different elements but without other major structural changes.
* from 600px wide and down: Home menu replaced with font-awesome home icon by hidding the standard menu and moving to the second variant optimized for mobile. The other major change is the removal of the timeline feature in the media page, change done due to reduced realestate on lower size devices.
* from 425px wide and down: Mostly reszing of different elements but without other major structural changes.
* min resolution tested was for Iphone SE, but verified that resolutions under la Galaxy Fold still behave well with major change being a shift in menu structure to a stacked version.



## Testing and Validation
The website was tested for funtionality and design using the main used browsers: Mozilla, Chrome, Edge, Safari.
There where also other external tools listed in the section Technologies that where used to ensure correct website 
and code behaviour.
A formator was also used in order to clean and arrange code.

#### HTML
Tested all pages using W3C validator.
Several errors identified in all pages and corrections made like for ex:
* missing lang attribute and doctype in 404 page
* duplications of containers or double used closing container commands

Issues identified and corrected until bellow pass mark was reached:
![Alt text](/readme/testing/html-test.jpg)

#### CSS
Tested CSS code using W3C validation service.
Several error identified, majority around using commands not valid or doubled: background-color same as border color for ex.

Issues are fixed and corrected, the only item still open is the imported style sheet:
![Alt text](/readme/testing/css-validator.jpg)


#### Accessability Test
Accesibility test was done using Wave Report generator for each of the pages.
There where several issues identified which where corrected, mostly due to font color used on Menu. Media and About page initialy used a white text color on a yellow background. This was corrected with the final version currently in place and errors fixed.

There are 3 errors still in place:
* 2 impacting all pages due to icons being used with a link to a page associated. Since the icons don`t have text, errors where not fixed but they should not impact user experience as very suggestive.
* 1 error impacting the form redirect page(page after submission) and this is due to the redirect function of the page.
![Alt text](/readme/testing/accessability-test.jpg)

#### Lighthouse
#### Spellcheck
#### Fixed bugs

## Credits
#### Code Used:
Youtube and Google Maps iframe code used for Maps in Contact page and Videos in Media page.
Style on submit button in the contact form was inspired from the structure of the submit button from the Love Running Project.

#### Video:
Video sources where taken from YouTube:
* April video: GreekOrthodoxChurch YouTube Channel
* March video: Adoration of the Cross Youtube Channel
* February video: Greek Orthodox Metropolis of Detroit Youtube Channel
* January video: Matt Whitman Youtube Channel
#### Photography:
* Home page Hero Image: credit to [Zamfir Constantin](https://www.zamfirphoto.com/)
* Contact page photos: sourced from [Pexels](https://www.pexels.com/)

#### Other
* Deployment instructions in GitHub copied from kera-cudmore / earth-day-hackathon-2022 readme file.

* Inspiration on Readme structure taken from  kera-cudmore / earth-day-hackathon-2022 readme file, testing file.


## About Author
Marius Topircean is an aspiring webdeveloper who initiated it`s journey in coding with this first project.

My contact details are:

Email: mtopircean@yahoo.com

Phone: +353857642212

Slack: Marius Topircean

Github: mtopircean
Linkedin: [Marius Topircean](https://www.linkedin.com/in/marius-t-7b5592124)