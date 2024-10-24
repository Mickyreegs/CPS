# Cork Percussion School Website ReadMe Document

Welcome, all!  

This document aims to explain the who, what, why, and how of this website.
To begin, the site can be found at [Cork Percussion School](https://mickyreegs.github.io/CPS)

## Cork Percussion School

This website was designed for a percussion school in Cork, Ireland.  The aim was to create an eye catching website that will keep users engaged with the use of information, audio, and visual stimulus.  The website is user-friendly and is targeted towards drummers of all levels - Beginner, Intermediate, and Advanced.  The hope is that users generate a sense of excitement and wish to begin their drumming adventure with Cork Percussion School.  The only thing to do then is to go to the contact page and submit your details for a callback.

## Initial Design - Wireframe

## General Features

### Responsive Design
The website was designed using the Mobile First principle and enlarges based on screen size.

![Am I Responive website Image revealing responsiveness across various screen sizes](../CPS/assets/readme-images/Am%20I%20Responsive.JPG)

### Consistent Navigation Bar & Footer
The header of the site contains both the Logo and Navigation Bar, which is responsive to various screen sizes.  The footer has links to X, YouTube, Instagram & Facebook and is also consistent across the 3 pages.  The design is intuitive, allowing easy access to each page and social media site for the user, and employing a consistent design across all pages of the webite.

![Navigation bar image from Cork Percussion School webite](../CPS/assets/readme-images/NAV%20Bar.JPG)

![Navigation bar image from Cork Percussion School webite](../CPS/assets/readme-images/Footer.JPG)


## The Home Page
Upon opening the home page, you immediately see a photograph of a drum kit in black and white, which includes a quote in the overlay text.  It is an eye catching display with nicely contrasting overlay text to draw the user in. 

![Black and white image of a drum set](../CPS/assets/readme-images/pexels-h-thanh-131149238-11018964.jpg)

Beneath the image, we see the CPS Information section.  This gives the user information and background on the school.

![CPS Info section giving info on the school and classes](../CPS/assets/readme-images/CPS%20Infor%20Section.JPG)

## The Drum Classes Page
This page displays the classes and times that certain drum styles are taught during the week.  

![Drum classes table](../CPS/assets/readme-images/Table.JPG)

The overlay text continues on this page with a new drummwer quote.  Users get an idea of the schedule, but also of each individual drum style thanks for short descriptions and audio.  The audio enables the use of controls, and the track is initially muted. All of this is to give the user a more informed view of the courses and drum styles on offer.

![Audio samples & style description](../CPS/assets/readme-images/Samples%20&%20Description.JPG)

The background is split between screen sizes.  An image of an orange drum kit is used for smaller devices, but this is switched to a red kit in a studio for devices of 768px and above.  This was due to the fact that the smaller image was stretching too much and did not look as good on larger screens.  It also adds another layer of design that can be appreciated by users on different screen sizes.

![Background image below 768px](../CPS/assets/readme-images/Drum%20Classes%20-%20Smaller%20Screens.JPG)

![Background image below 768px](../CPS/assets/readme-images/Drum%20Classes%20-%20Larger%20Screens.JPG)

## The Contact Page
The Contact page encourages users to get in touch with the school and to choose their preferred drum style for specialisation.  These are listed as radio buttons on the form.

![User contact form](../CPS/assets/readme-images/Form.JPG)

Below the form, there are 4 further boxes with contact info - Address, Phone, Opening Hours, and Supplies.  The Supplies box has a link to the Thomann website, specifically their drum page.  The overlay text continues on this page with a new drummwer quote.  

![Contact details and supplies info](../CPS/assets/readme-images/Contact%20Details.JPG)

The background of a snare drum with drum sticks completes the page.

![Snare drum image with broken drum sticks](../CPS/assets/readme-images/pexels-abednego-241687.jpg)





## Testing
All 3 pages were put through the HTML validator tool and passed:

![HTML validator checks](../CPS/assets/readme-images/HTML%20Check%20After.JPG)

The CSS cose also passed the CSS validator test:

![CSS validator checks](../CPS/assets/readme-images/CSS%20code%20validation%20-%20After.JPG)

Bugs that were discovered and fixed are as follows:
<ul>
    <li>Error 404 (HTML)</li>
    This was fixed by amending the relative filepaths in the html code pages.
    <li>Duplicate IDs (HTML)</li>
    This was fixed by removing the duplicate from the HEAD.
    <li>No Section Heading (HTML)</li>
    This was evident on the background images of all 3 pages.  It was fixed by adding a heading to each page's section and using the invisibility styling in CSS to hide it.
    <li>No P Element In Scope (HTML)</li>
    The /P tag was incorrectly placed in the section and repositioned to it's correct location.
    <li>Value Error: min-height (CSS)</li>
    The min-height element of the text boxes was not initially set and left blank in error.  This was fixed by giving them all a value of 150px.
    <li>.text-input Styling (CSS)</li>
    The background and border colours were initially set to whitesmoke.  As this clashed, the border was updated to gray in keeping with other border styles.
</ul>

![HTML errors](../CPS/assets/readme-images/Initial%20HTML%20Test.JPG)

![CSS errors](../CPS/assets/readme-images/Initial%20CSS%20Test.JPG)

![Error 404](../CPS/assets/readme-images/Error%20404.JPG)

## Known Bugs
1 bug remains on the site that we are aware of - On Safari, the audio controls do not allow the user to unmute, and so the user cannot experience the audio from each style.
We hope that in the future we can rectify this using HTML code that is compatible with Apple products.

![Safari Controls](../CPS/assets/readme-images/Safari%20Controls%20Bug.JPG)

## Deployment


## Credits
The following websites were used for informational purposes:
<ul>
    <li>Drum Set Tips - https://drumsettips.org/bossa-nova-drum-style-latin-drum-set-beats/#:~:text=The%20Bossa%20Nova%20bass%20line,it%20as%20a%20Brazilian%20Clave.</li>
    <li>Wikipedia - https://en.wikipedia.org/wiki/Funk#:~:text=Funk%20drumming%20creates%20a%20groove,of%20fills%20(as%20they%20can)</li>
    <li>Wikipedia - https://en.wikipedia.org/wiki/Jazz_drumming#:~:text=Jazz%20drumming%20is%20the%20art,and%201980s%2Dera%20Latin%20jazz.</li>
    <li>BetaMonkey - https://www.betamonkey.com/a-closer-look-at-blues-drum-loops-and-blues-drumming-styles/#:~:text=Playing%20deep%20in%20the%20pocket,exactly%20where%20the%20groove%20is.</li>
    <li>Stack Overflow - https://stackoverflow.com/</li>
    <li>W3 Schools - https://www.w3schools.com/</li>
    <li>Free Code Camp - https://www.freecodecamp.org/</li>
    <li>Daisie Blog - https://blog.daisie.com/drums-for-folk-practical-guide-expert-tips/</li>
    <li>Wikipedia - https://en.wikipedia.org/wiki/Heavy_metal_drumming#:~:text=With%20roots%20in%20blues%20rock,guitar%2Dand%2Ddrum%20sound.</li>
    <li>X8 Drumming - https://www.x8drums.com/blog/reggae-drumming/</li>
    <li>Freddy Charles Music - https://freddycharlesmusic.com/blogs/news/rock-drumming-for-beginners-how-to-play-rock-on-drums#:~:text=One%20of%20the%20defining%20features,pulse%20that%20permeates%20the%20music.</li>
</ul>

The following websites were used for audio and visual purposes:
<ul>
    <li>Wikiloops - https://www.wikiloops.com/tracks/Drums.php?scope=2</li>
    <li>Font Awesome - https://fontawesome.com/</li>
    <li>Google Fonts - https://fonts.google.com/</li>
    <li>Favicon - https://favicon.io/emoji-favicons/drum/</li>
    <li>Pexels - https://www.pexels.com/search/drumming/</li>
</ul>

The following projects were used as a reference guide to build this website:
<ul>
    <li>Love Running - Code Institute Essentials Project</li>
</ul>
