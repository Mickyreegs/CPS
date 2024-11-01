# Cork Percussion School Website ReadMe Document

Welcome, all!  

This document aims to explain the who, what, why, and how of this website.
To begin, the site can be found at [Cork Percussion School](https://mickyreegs.github.io/CPS)

## Cork Percussion School

This website was designed for a percussion school in Cork, Ireland.  The aim was to create an eye catching website that will keep users engaged with the use of information, audio, and visual stimulus.  The website is user-friendly, easily navigated, and is targeted towards drummers of all levels - Beginner, Intermediate, and Advanced.

As a prospective percussion student,  I want to navigate this site to learn more about the school and the classes on offer so that I can make an informed decision as to whether or not I will pursue education in percussion.  I can get info on the school from the home page.  I can get info on classes and styles on the drum classes page.  I can get info on how to contact the school on the contact page.

## Initial Design - Wireframe
The initial design idea was one where an image dominates the screen but the page is easily navigated and contains the info relevant to that page.  Each page contains a large background image, with informational text and audio placed below the image.  Inspirational quotes will be layered on top of the image, along with a table of classes on the classes.html page and a form on the contact.html page.

### Wireframe of the index.html page
![Wireframe image of the index.html page](../CPS/assets/readme-images/Wireframe%20index.PNG)

### Wireframe of the classes.html page
![Wireframe image of the classes.html page](../CPS/assets/readme-images/Wireframe%20classes.PNG)

### Wireframe of the contact.html page
![Wireframe image of the contact.html page](../CPS/assets/readme-images/Wireframe%20contact.PNG)

## General Features

### Responsive Design
The website was designed using the Mobile First principle and enlarges based on screen size.

![Am I Responive website Image revealing responsiveness across various screen sizes](../CPS/assets/readme-images/Am%20I%20Responsive.JPG)

### Consistent Navigation Bar & Footer
The header of the site contains both the Logo and Navigation Bar, which is responsive to various screen sizes.  The footer has links to X, YouTube, Instagram & Facebook and is also consistent across the 3 pages.  The design is intuitive, allowing easy access to each page and social media site for the user, while employing a consistent design across all pages of the webite.

![Navigation bar image from Cork Percussion School webite](../CPS/assets/readme-images/NAV%20Bar.JPG)

![Footer image from Cork Percussion School webite](../CPS/assets/readme-images/Footer.JPG)


## The Home Page
Upon opening the home page, you immediately see a photograph of a drum kit in black and white, which includes a quote in the overlay text.  It is an eye catching display with nicely contrasting overlay text to draw the user in. 

![Black and white image of a drum set](../CPS/assets/readme-images/pexels-h-thanh-131149238-11018964.jpg)

Beneath the image, we see the CPS Information section.  This gives the user information and background on the school.

![CPS Info section giving info on the school and classes](../CPS/assets/readme-images/CPS%20Infor%20Section.JPG)

## The Drum Classes Page
This page displays the classes and times that certain drum styles are taught during the week.  

![Drum classes table - Days and times](../CPS/assets/readme-images/Table.JPG)

The overlay text continues on this page with a new drummer quote.  Users get an idea of the schedule, but also of each individual drum style thanks for short descriptions and audio.  The audio enables the use of controls, and the track is initially muted. All of this is to give the user a more informed view of the courses and drum styles on offer.

![Audio samples & style description](../CPS/assets/readme-images/Samples%20&%20Description.JPG)

The background is split between screen sizes.  An image of an orange drum kit is used for smaller devices, but this is switched to a red kit in a studio for devices of 768px and above.  This was due to the fact that the smaller image was stretching too much and did not look as good on larger screens.  It also adds another layer of design that can be appreciated by users on different screen sizes.

### Below 768px
![Background image below 768px](../CPS/assets/readme-images/Drum%20Classes%20-%20Smaller%20Screens.JPG)

### Above 768px
![Background image above 768px](../CPS/assets/readme-images/Drum%20Classes%20-%20Larger%20Screens.JPG)

## The Contact Page
The Contact page encourages users to get in touch with the school and to choose their preferred drum style for specialisation.  The user is required to select a style from a dropdown list.  

![User contact form](../CPS/assets/readme-images/Form.JPG)

Below the form, there are 4 further boxes with contact info - Address, Phone & email, Opening Hours, and Supplies.  The Supplies box has a link to the Thomann website, specifically their drum page.  The overlay text continues on this page with a new drummer quote.  

![Contact details and supplies info](../CPS/assets/readme-images/Contact%20Details.JPG)

The background of a snare drum with drum sticks completes the page.

![Snare drum image with broken drum sticks](../CPS/assets/readme-images/pexels-abednego-241687.jpg)

## Testing
### Code Validation
All 3 pages were put through the HTML validator tool and passed:

![HTML validator checks](../CPS/assets/readme-images/HTML%20Check%20After.JPG)

The CSS cose also passed the CSS validator test.  There was one warning - "Imported style sheets are not checked in direct input and file upload modes".  This was my import from Google Fonts and is an expected warning:

![CSS validator checks](../CPS/assets/readme-images/CSS%20code%20validation%20-%20After.JPG)

### Functional Testing
<table>
    <tr>
        <th>Action</th>
        <th>Expected Behaviour</th>
        <th>Pass/Fail</th>
    </tr>
    <tr>
        <td>Page URL</td>
        <td>Deployed page to open</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>NAV Bar</td>
        <td>NAV bar directs user to correct page</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>NAV Bar - Highlighted Page</td>
        <td>NAV bar highlights the page the user is currently on</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>Page Responsiveness</td>
        <td>Pages are responsive to mobile, tablet and desktop users</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>NAV Bar Menu</td>
        <td>Menu dropdown disappears for larger screens</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>Social Media</td>
        <td>Social media links work and open in new page</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>External Links</td>
        <td>External website links work and open in new page</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>Audio Files</td>
        <td>Audio controls operate correctly and play files</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>User forms - Input Fields</td>
        <td>Input fields are marked as required and operate as expected</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>User forms - Dropdowns</td>
        <td>Dropdown lists are marked as required and operate as expected</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>Relative Filepaths</td>
        <td>All relative filepaths function correctly to display correct content</td>
        <td>Pass</td>
    </tr>
    <tr>
        <td>Physical Test</td>
        <td>Website tested on users and their various devices</td>
        <td>Pass</td>
    </tr>
</table>

### Browser Performance
All three pages performed well on the below browsers:
<ul>
    <li>Google Chrome</li>
    <li>Microsoft Edge</li>
    <li>Mozilla Firefox</li>    
    <li>Safari</li>
</ul>
The Mozilla Firefox audio controls are not as aesthetically pleasing as they are in Chrome and Edge.

### Lighthouse Checks
Lighthouse was used to test the performance of the pages.  All pages scored over 90 on all 4 headings with the exception of the classes.html mobile test.  This got 84/100 for performance.  This was due to the 8 audio files included on the page for the user experience.  It is my intention to improve this with the use of smaller files in the future.  See all results below:

![Lighthouse test on mobile device for index.html](../CPS/assets/readme-images/Lighthouse%20Mobile%20Index.JPG)

![Lighthouse test on desktop for index.html](../CPS/assets/readme-images/Lighthouse%20Desktop%20Index.JPG)

![Lighthouse test on mobile device for classes.html](../CPS/assets/readme-images/Lighthouse%20Mobile%20Classes.JPG)

![Lighthouse test on desktop for classes.html](../CPS/assets/readme-images/Lighthouse%20Desktop%20Classes.JPG)

![Lighthouse test on mobile device for contact.html](../CPS/assets/readme-images/Lighthouse%20Mobile%20Contact.JPG)

![Lighthouse test on desktop for contact.html](../CPS/assets/readme-images/Lighthouse%20Desktop%20Contact.JPG)

### Bug Fixes
Bugs that were discovered and fixed are as follows - Screenshots are added below:
<ul>
    <li>Error 404 (HTML)</li>
    This was fixed by amending the relative filepaths in the html code pages.
    <li>Duplicate IDs (HTML)</li>
    This was fixed by removing the duplicate from the HEAD.
    <li>No Section Heading (HTML)</li>
    This was evident on the background images of all 3 pages.  It was fixed by adding a heading to each page's section and using the invisibility styling in CSS to hide it.
    <li>No P Element In Scope (HTML)</li>
    The /P tag was incorrectly placed in the section and repositioned to it's correct location.
    <li>Element without attribute must not be empty (HTML)</li>
    Label was added to the form and option with value "" had text of Choose From The Following: added to it.
    <li>Value Error: min-height (CSS)</li>
    The min-height element of the text boxes was not initially set and left blank in error.  This was fixed by giving them all a value of 150px.
    <li>.text-input Styling (CSS)</li>
    The background and border colours were initially set to whitesmoke.  As this clashed, the border was updated to gray in keeping with other border styles.
</ul>

![HTML code errors](../CPS/assets/readme-images/Initial%20HTML%20Test.JPG)

![HTML code errors on form](../CPS/assets/readme-images/HTML%20error%20dropdown.JPG)

![CSS code errors](../CPS/assets/readme-images/Initial%20CSS%20Test.JPG)

![Error 404](../CPS/assets/readme-images/Error%20404.JPG)

## Known Bugs
1 change was made during testing - On Safari, the audio controls do not allow the user to unmute, and so the user could not experience the audio from each style.
To rectify this, the muted option was removed from the HTML code so all users could hear the audio regardless of browser.

![Safari audio controls](../CPS/assets/readme-images/Safari%20Controls%20Bug.JPG)

## Deployment
The site was deployed through GitHub.  The steps taken were:
<ul>
    <li>Go to settings</li>
    <li>Select pages and apply "Deploy from branch" on the Source dropdown</li>
    <li>Our branch is set to "main" with "/root" as the folder</li>
</ul>

![GitHub Deployment](../CPS/assets/readme-images/Deployment.JPG)

The site can be reached at https://mickyreegs.github.io/CPS/

![GitHub Deployment site](../CPS/assets/readme-images/Deployment%202.JPG)

A point to note:
<ul>
    <li>It was noted by my mentor that my commit messages were inconsistent to begin with.  Some messages began with a capital letter while other were all in lower-case.  Also, it was highlighted that I was not using the imperative on all commit messages.  From that point on, all messages stared with a capital letter and used the imperative sentence structure.  As a result, the version control, and quality of messages, improved.</li>
</ul>

## Credits
### The following websites were used for informational purposes:

[Drum Set Tips](https://drumsettips.org/bossa-nova-drum-style-latin-drum-set-beats/#:~:text=The%20Bossa%20Nova%20bass%20line,it%20as%20a%20Brazilian%20Clave.)

[Wikipedia - Funk Drums](https://en.wikipedia.org/wiki/Funk#:~:text=Funk%20drumming%20creates%20a%20groove,of%20fills%20(as%20they%20can))

[Wikipedia - Jazz Drums](https://en.wikipedia.org/wiki/Jazz_drumming#:~:text=Jazz%20drumming%20is%20the%20art,and%201980s%2Dera%20Latin%20jazz.)

[Wikipedia - Heavy Metal Drums](https://en.wikipedia.org/wiki/Heavy_metal_drumming#:~:text=With%20roots%20in%20blues%20rock,guitar%2Dand%2Ddrum%20sound.)

[BetaMonkey - Blues Drums](https://www.betamonkey.com/a-closer-look-at-blues-drum-loops-and-blues-drumming-styles/#:~:text=Playing%20deep%20in%20the%20pocket,exactly%20where%20the%20groove%20is.)

[Stack Overflow - General Queries](https://stackoverflow.com/)

[W3 Schools - General Queries](https://www.w3schools.com/)

[Free Code Camp - General Queries](https://www.freecodecamp.org/)

[Daisie Blog - Folk Drums](https://blog.daisie.com/drums-for-folk-practical-guide-expert-tips/)

[X8 Drumming - Reggae Drums](https://www.x8drums.com/blog/reggae-drumming/)

[Freddy Charles Music - Rock Drums](https://freddycharlesmusic.com/blogs/news/rock-drumming-for-beginners-how-to-play-rock-on-drums#:~:text=One%20of%20the%20defining%20features,pulse%20that%20permeates%20the%20music.)


### The following websites were used for audio and visual purposes:

[WikiLoops - Audio Tracks](https://www.wikiloops.com/tracks/Drums.php?scope=2)

[Font Awesome - Header Tags](https://fontawesome.com/)

[Google Fonts](https://fonts.google.com/)

[Favicon - Head Icon](https://favicon.io/emoji-favicons/drum/)

[Pexels - Background Images](https://www.pexels.com/search/drumming/)

### The following projects were used as a reference guide to build this website:

[Love Running Essentials Project](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main/8.1-testing-and-validation)