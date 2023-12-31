<h1 align="center"><em>b</em>Boulder Website</h1>
Created for the purpose of advertising <em>b</em>Boulder; a fictional indoor bouldering centre that also focuses on maintaining physical wellbeing. The website will showcase the facilities through images/videos, provide useful information regarding the location and services available.
<br>

#### [View the live project here](https://dalefielding.github.io/b-boulder/)

![A mock-up image of my bBoulder project](assets/resources/b-boulder-project-mock-up.png "A mock-up image of my bBoulder project")




## User Experience (UX)

-   ### User Stories/Visitor Goals
    * As a user, I would like to see information relating to services available.
    * As a user, I would like to see information relating to classes available.
    * As a user, I would like to view prices for the above.
    * As a user, I would like to access contact information for the company.
    * As a user, I would like to access the location of the company.
    * As a user, I would like to see imagery relating to safety information.

-   ### Client Objectives
    The company bBoulder would like:
    *  A website built that will promote their business and encourage visits to their centre.
    * They have asked for a website that is responsive, functional and professional.
    * They would like it to be aimed at the general public of all ages, as there are virtually no restrictions in terms of age regarding bouldering at their facilities.
    * They have a focus on wellbeing and injury prevention so would like this to be made clear in the content. 

-   ### Developer Objectives 
    * To design and build a site that meets the client’s objectives and factoring in what a user would want from this site.
    * To ensure that the website meets all accessibility requirements, allowing anyone to use the site regardless of their abilities/needs.
    * To carry out other manual testing on each page and with other device sizes.
    * To carry out testing using validators and google lighthouse in order to minimise any warnings or errors that the site may contain.
    * To fix any bugs that there might be in the site.


### Design
* #### Strategy 
    Is based on users stories, visitor goals, client objectives and developer objectives; As above.
* #### Scope
    I have listed the possible features below and ranked 1-5 in level of importance/relevance to user needs (1 being most important and viable/feasible):
    * Classes for children and adults (1). 
    * Location/map (1).
    * Site navigation (1).
    * Accessibility (1).
    * Social networking information and links (1).
    * Wellbeing services; Ice baths, osteopathy, stretching/warm up/cool down area (1).
    * Logo (1).
    * Slogan (2).
    * Booking information (2).
    * Safety information (2).
    * Images/gallery (2).
    * Background image (2).
    * Video footage (3).
    * Fully functional calendar for booking (4).
    * Animated climber that climbs up and down on the side of the page when scrolling (5).
    * Bar to indicate current level of busyness (5).

Following research and review of scope, I had decided not to include:
* The animated climber - I believe this would distract from the content, would require levels of JavaScript that are outside of the project scope and would take up more time than appropriate for the value provided.
* Bar to indicate current level of busyness - this would require levels of JavaScript that are outside of the project scope currently, and do not feel it is entirely necessary as far as user/client needs are concerned. 
* Fully functional calendar for bookings - again this will require JavaScript that is outside the scope of this project at this time. The client has not indicated that this is an expectation as they generally have a just turn up policy.

I have included the remaining features within the site; implemented with HTML, CSS, JS and Bootstrap.

* #### Structure:
    - Consistency: 
        - Navigation to each page of the site will be displayed inline (by wording) on the top of each page when in desktop/tablet view. This will be reduced into a nested list for the mobile view and will expand to block view when the hamburger icon is clicked.
        - Social networking will be displayed in the form of icons at the bottom of each page, and will open in a separate tab when clicked.        
        - Content, imagery will have the same consistent flexible Bootstrap grid style across all pages.
        - Animations etc will act consistently across all pages.
    - Predictability/Learnability: 
        - Content will appear and operate in predictable ways, based on usual site interactions.
        - Accessibility; making text readable and understandable, providing text alternatives/captions for screen readers etc. 
        - Semantic HTML will be used throughout.
        - Clicking on the logo will direct to the homepage.
    - Visibility:
        - All elements will be made visible on all devices where appropriate, discoverable and will include content hinting.
    - Feedback:
        - Hover events for each link.
        

* #### Skeleton:
    * Habits and conventions; users will navigate through the site by scrolling down the pages, through links in the navbar, media within the pages, icons and links within the footer (at the bottom).


  * ##### Wireframes:
    Initial designs created on paper then by using Adobe Powerpoint.

    *   [Initial Sketches](/assets/resources/initial-sketches.png "Link to initial sketches image file")
    <br>
    * [Initial Home Page Wireframes](assets/resources/initial-home-page-wireframes.png "Link to initial home page wireframes image file")
    <br>
    * [Initial Home Page Wireframes With Design Ideas](assets/resources/initial-home-page-wireframes-with-style.png "Link to initial home page wireframes with style image file")
    <br>
    * [Initial Home Page Wireframes Chosen Design](assets/resources/initial-home-page-chosen-style.png "Link to initial home page chosen style image file")

    I progressed to using Figma and developed further by including layouts for the other pages and arrows to demonstrate navigation to these pages:

    Mobile Wireframes:
    ![Mobile Wireframes](assets/resources/mobile-wireframes.png "Link to mobile wireframes image file")
    <br>
    Desktop Wireframes: 
    ![Desktop Wireframes](assets/resources/desktop-wireframes.png "Link to desktop wireframes image file")

    All of these designs can be viewed more closely by visiting my figma page below:

    [Figma Wireframes Designs Page](https://www.figma.com/file/9Ioehs6ELzng3FZX2CQiR8/Page-Wireframes-for-bBoulder-Climbing-Centre-Site?type=design&node-id=21-1157&mode=design&t=Xg50D9xzmFzjb80e-0 "Link to Figma Wireframe Designs Page")
    <br>
    ![Preview snippet of Figma Designs Page](assets/resources/figma-page-preview.png "Preview snippet of Figma Designs Page")

* #### Surface:
    * ##### Habits and conventions
        * Users will navigate through the site by scrolling down the pages, through links in the navbar, media within the pages, icons and links within the footer (at the bottom).
    * ##### Typography
        * I have chosen the [Poppins](https://fonts.google.com/?query=poppins "link to Poppins google font") google font for the headers on my site as I felt this was a clear, readable font that was also pleasing to the eye. After researching, I have found a couple of other google fonts that complement this nicely; [Gravitas One](https://fonts.google.com/specimen/Gravitas+One?preview.text=bBoulder&query=Gravitas+One "link to Gravitas One google font") for the logo, and [Vollkorn](https://fonts.google.com/?query=vollkorn "link to Vollkorn google font") for the general content.

    * ##### Colour Scheme:
        I have chosen to go with a colour palette that represents the feeling of the experience that the company offers:
        - Orange (HEX #d46333); fun, happiness, dynamic. 
        -  Green (HEX #3da369); renewal, healing, harmony.
        
        I had initially gone for a much darker green (#04861E) then I actually wanted in order to pass the contrast check. However when playing around to achieve a more preferable green, I noticed the new green does pass when using large text for the foreground; which is my only intention for this green on the site.

        I will also be using white, black and grey as neutral colours/shades for typography and background sections.

        I used a contrast checker on webaim.org to ensure that the colour scheme meets the Web Content Accessibility Guidelines for readability. 

## Features
* Responsive on all device sizes.
* Meta descriptions to improve SEO.
* Semantic elements, alt attributes and sr attributes to assist with accessibility/screen readers. 
* Logo that directs to the home page.
* Navigation is sticky to ensure it is always accessible at the top of the page. It has links with active status and underline when hovered over.
* Navigation changes to hamburger menu for medium size devices and below.
* Offer banner displays towards the top until scrolled down the page.
* Background images scale to always fit the full width of the page.
* Background banner changes between two different designs depending on device type.
* Footer displays; opening times, quick links, icons for social media and a location icon that directs to google maps. The footer links include a colour transition in keeping with the navigation colour. The layout of the footer adjusts to suit the type of device. 

* About page contains: 
    * Safety information.
    * Video showcasing bouldering facilities.
    * Four images showcasing bouldering facilities.
* Wellbeing Focus contains:
    * A statement relating to the company's wellbeing focus.
    * Three images that relate to the facilities on site that assist with wellbeing, including a description for each one.
* Classes page contains: 
    * An accordion which has each of the classes that are on often, which expands when clicked to give a description about each one.
    * Safety information included in this page also; in case the user has decided not to visit the about page.
* Pricing page contains: 
    * Confirmation that registration and joining is free and that customers can just turn up on the day.
    * Four tables which confirm the prices for each service; bouldering sessions, classes, wellbeing facilities and equipment hire. There is also the inclusion of email contact details for osteopathy, to find out availability for bookings.

## Future Implementations
* An error page, used to indicate if a user has tried to access an incorrect path within the domain.
* A fully functional calendar for making booking for osteopathy and potentially classes as well. This will respond to the user, to inform them whether or not the booking was successful.

## Testing 

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors or warnings in the project.

### W3C Markup Validator - Results:
* [Home page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdalefielding.github.io%2Fb-boulder%2F) 
* [About page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdalefielding.github.io%2Fb-boulder%2Fabout.html) 
* [Wellbeing Focus page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdalefielding.github.io%2Fb-boulder%2Fwellbeing-focus.html)
* [Classes page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdalefielding.github.io%2Fb-boulder%2Fclasses.html) 
* [Pricing page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdalefielding.github.io%2Fb-boulder%2Fpricing.html)

### W3C CSS Validator - Results:
* [External stylesheet (style.css)](https://jigsaw.w3.org/css-validator/validator)

#### Page Errors/Warning Summary:
* Home page
    * Encountered no issues.
* About page
    * There was an error due to px measurements being used for height and width of the video. <br>Fixed by deleting px in those measurements.
    * There was an error due to an alt attribute being included in the video. <br>Fixed by removing that.
* Wellbeing Focus page
    * Encountered no issues.
* Classes page
    * Encountered no issues.
* Pricing page
    * There were errors due to scope attributes being included with the td elements, with suggestion to include these on the th elements instead. <br>Fixed this by deleting the scope attributes from the td elements. Scope attributes were already included within the th elements.
    * There were warnings due to table rows not being the same column count as the first rows, and a warning to say that the table section lacks a header. These issues were because I had tried to use the table header to span the title of the table. <br>Fixed this by removing the tr and th elements for the tables and replacing them with H4 tags above the tables.
* External stylesheet (style.css)
    * When putting in the page URI for the webpages it came up with 16 parsing errors relating to the bootstrap CDN.
    * However when using direct input and pasting in my external CSS file, there are no errors.<br>  There were however some warnings for the below: 
        > URI : TextArea<br>
        > 214
        -moz-transition is a vendor extension<br>
            > 215
        -webkit-transition is a vendor extension<br>
            > 216
        -o-transition is a vendor extension<br>
            > 253
        -moz-transition is a vendor extension<br>
            > 254
        -webkit-transition is a vendor extension<br>
            > 255
        -o-transition is a vendor extension<br>
    
    I have left those in, as this was taught in the codeinstitute course material (one of the videos). 

### Developer Mistake After Testing: 
* I had carried out a number of tests, but then decided to add the navigation element and alert banner within the header elements for better semantics. 
* I did not believe at the time that this would have an impact on the functionality of position of the navbar, and chose at the time not to retest.
#### Steps to Fix:
* I realised later on that the navbar was no longer sticky at the top of the page, which was not intended.
* I had managed to fix this by moving the class sticky-top to the header instead of the navbar.
* However I noticed on mobile devices that when I scrolled down the page, part of the navigation would disappear off the screen. 
* After doing some research and trying out a few potential solutions, I came across a discussion on Stack Overflow that helped me solve the issue. This involved including ‘height=device-height, minimum-scale=1.0 + target-densitydpi=device-dpi’ to the viewport meta tag.
#### Follow up action:
* I understand the importance of always testing when changes are made and to never assume.
* I have retested each page/css with validators, there are no changes to the above outcome as all pages/css still pass with no errors.
* I have updated the subsequent tests below. 


### Google Lighthouse:

* #### Mobile results
    * Home page<br>
    ![Home page - Mobile](assets/resources/home-page-mobile-lighthouse-test.png "Home page mobile view")
    * About page<br>
    ![About page - Mobile](assets/resources/about-page-mobile-lighthouse-test.png "About page mobile view")
    * Wellbeing Focus page<br>
    ![Wellbeing Focus page - Mobile](assets/resources/wellbeing-focus-page-mobile-lighthouse-test.png "Wellbeing Focus page mobile view")
    * Classes page<br>
    ![Classes page - Mobile](assets/resources/classes-page-mobile-lighthouse-test.png "Classes page mobile view")
    * Pricing page<br>
    ![Pricing Page - Mobile](assets/resources/pricing-page-mobile-lighthouse-test.png "Pricing page mobile view")

* #### Desktop results 
    * Home page<br>
    ![Home page - Desktop](assets/resources/home-page-desktop-lighthouse-test.png "Home page desktop view")
    * About page<br>
    ![About page - Desktop](assets/resources/about-page-desktop-lighthouse-test.png "About page desktop view")
    * Wellbeing Focus page<br>
    ![Wellbeing Focus page - Desktop](assets/resources/wellbeing-focus-page-desktop-lighthouse-test.png "Wellbeing Focus page desktop view")
    * Classes page<br>
    ![Classes Page - Desktop](assets/resources/classes-page-desktop-lighthouse-test.png "Classes page desktop view")
    * Pricing page<br>
    ![Pricing Page - Desktop](assets/resources/pricing-page-desktop-lighthouse-test.png "Pricing page desktop view")

* #### Changes made due to issues flagged by Google Lighthouse

    * Added alt images and sr attributes where appropriate throughout webpages.
    * Changed webpage images to be avif files instead of jpeg; for better compression.
    * Included meta description tags for better search engine optimization.
    * Added smaller background images to the home page, that are then used instead of the larger images when viewing on smaller devices. 

* #### Further improvements to implement: 
    * To eliminate render-blocking images; to save on load time in pages.
    * Serve static assets with an efficient cache policy; to speed up site use on repeat visits.
    * Smaller image file sizes for mobile view for Wellbeing Focus page and About page; to save on load time.

### Other Testing
* Testing on other browsers:
    * Google Chrome. 
    * Microsoft Edge. 
    * Firefox. 
* Google Developer tools
    * I have continuously tested and played around with many different resolutions, to ensure there is no unexpected behaviour.
* Devices:
    * Google Pixel. 
    * Samsung S10. 
    * Dell Inspiron (Windows 11).
* Other users
    * My partner Laura Gibbons has tested the site herself on her Google Pixel.

#### Unexpected Results

Company slogan text alignment:
* Expected:
    * To remain centred within the banner on all devices.
* Testing:
    * Initially tested using various different preset/manual resolutions in Google Developer tools.   
    * Later tested on a couple of mobile devices.
* Result:
    * In landscape and mobile dimensions, I noticed the company slogan text within the banner does not align with the centre of the banner as intended:
    * The banner had narrowed due to being stretched by the narrow height.
    * The text had shifted above and outside of the banner.
    * In portrait on mobile devices. 
* Fix: 
    * I added a media query for orientation landscape. Made the height auto, the width 100%, aligned text to center, padding to 0, and reduced the font size to fit better within the banner. 
    The text is now aligned much better within the banner.

Background Images:
* Expected:
    * To appear on all browsers/devices.
* Testing:
    * With Google Developer tools, browsers and devices that are listed above.
* Result:
    * Appeared on all aside from Microsoft Edge.
* Fix:
    * I carried out some research online and was surpised to learn that avif files are not supported by Microsoft Edge. 
    * Research also indicated that webp files are much better supported.
    * I converted the avif files into webp and updated the paths in my code. 
    * Retested each page with the testing methods mentioned above. 
        

### Bugs
* Company Slogan Text within the banner. 
    * The banner background on the home page is made up of two triangles.
    * I have found it challenging to align the text due to the design of the webpage. This is because the layout changes from being aligned with the top triangle part of the banner background (div), to the center of both of the triangles when viewed on smaller devices.
    * As the slogan text is contained within the top triangle div, I can align this perfectly when the required alignment is bottom right of this div. However when the requirement is for the slogan text to be centred between the two triangles, the text shifts around and does not remain perfectly centred.
    * This fits okay in the device views that I have tested, and resolutions tested by playing around on Google Developer tools.
    * Potential fixes for this:
        * To research and implement JavaScript that can change the HTML dynamically so that a further div can be added in the middle of the two triangles; to which the text is centred.
        * To consider using one banner background design to be used throughout all device views.

-   ### Testing User Experience (UX) Section
	- #### User Stories
        * As a user, I would like to see information relating to services available. 
	        * Pass - This is located within the wellbeing focus page and the pricing page.
        * As a user, I would like to see information relating to classes available.
            * Pass - This is located within the classes page and the pricing page.
        * As a user, I would like to view prices for the above.
            * Pass - This is located within the pricing page.
        * As a user, I would like to access contact information for the company.
            * Pass - This is located within the footer and contact detail for osteopath is included within the pricing page.
        * As a user, I would like to access the location of the company.
            * Pass - This is located within the footer.
        * As a user, I would like to see imagery relating to safety information.
            * Pass - There are clear safety instructions included within the classes page and the about page.

    - #### Client Objectives 
        *  A website built that will promote their business and encourage visits to their centre.
            * Pass - I believe I have designed and built a website that does promote and would encourage visits.
        * They have asked for a website that is responsive, functional and professional.
            * Pass - I believe this does meet their expectation on this.
        * They would like it to be aimed at the general public of all ages, as there are virtually no restrictions in terms of age regarding bouldering at their facilities.
            * Pass - I believe I have opted for a design that is appropriate to all ages.
        * They have a focus on wellbeing and injury prevention so would like this to be made clear in the content.
            * Pass - This is included in detail within the wellbeing focus page, in the about page, and hints of this in the home page. 

    - #### Developer Objectives
        * To design and build a site that meets the client’s objectives and factoring in what a user would want from this site.
            * Pass -  as noted in the previous two sections
        * To ensure that the website meets all accessibility requirements, allowing anyone to use the site regardless of their abilities/needs.
            * Pass - I have included alt tags, sr attributes, semantic elements, readable fonts/font sizes and have taken into account contrast.
        * To carry out other manual testing on each page and with other device sizes.
            * Pass - This has been completed.
        * To carry out testing using validators and google lighthouse in order to minimise any warnings or errors that the site may contain.
            * Pass - This has been completed.
        * To fix any bugs that there might be in the site.
            * Fail - Unfortunately this has not passed (in my opinion); see [Bugs](#Bugs).


## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

* [Bootstrap 5.3.2:](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness of all pages.
* [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on the social media links in the footer.
* [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the chosen fonts that were used throughout the webpages.    
* [Git](https://git-scm.com/)
    - Git was used for version control to commit to Git and Push to GitHub.
* [GitHub:](https://github.com/)
    - GitHub is used to store the project’s code after being pushed from Git.
* [Visual Studio Code](https://code.visualstudio.com/)
    - Visual Studio Code was used as the IDE for the project.
* [Adobe Powerpoint](https://www.microsoft.com/en-gb/microsoft-365/powerpoint)
    - Adobe powerpoint was used to create the initial designs/wireframes. 
* [Figma](https://www.figma.com/login?is_not_gen_0=true) 
    - Figma was used to add the initial wireframes/designs to a workspace, then to complete further wireframes for mobile and desktop pages.
* [Photoshop:](https://www.adobe.com/ie/products/photoshop.html)
    - Photoshop was used to resize images for the initial designs and to save elements from Figma into individual files.
* [Pixelied](https://pixelied.com/convert/jpg-converter/jpg-to-avif)
    - Pixelied was used to convert some of the jpg images into avif files.
* [Cloudconvert](https://cloudconvert.com/avif-to-webp) 
    * Cloudconvert was use to convert the avif files into webp files.


## Other References

### Articles

* [Stack Overflow discussion that helped me fix responsiveness on mobile devices](https://stackoverflow.com/questions/60511542/css-sticky-position-not-working-properly-on-mobile)

* #### Typography
    * [Creatopy font pairings article](https://www.creatopy.com/blog/google-font-pairings/)
    *  [Vev.design font pairings article](https://www.vev.design/blog/google-font-combinations/#:~:text=Poppins%20%2B%20Vollkorn,a%20header%20or%20body%20copy)

## Code

### Templates 
*  [Bootstrap Library](https://getbootstrap.com/docs/5.3/getting-started/introduction/ "link to Bootstrap Docs").
    * Has been used through the project to assist with making the pages responsive. 
    * I have used some template code from Bootstrap documentation, such as the navbar to ensure responsiveness and a functioning collapsible menu. Also the tables in pricing.html and the accordion in classes.html.
    * I have made amendments to these in order to suit the chosen design for the website.

### Tutorials
* Used to understand how to place the two background images as desired for the homepage - 
[Youtube Tutorial](https://www.youtube.com/watch?v=iC6hzjR1luY "link to Youtube tutorial").

* Footer layout inspired by the codeinstitute resume project - 
[Codeinstitute Link](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/b51f7b8b815c4bcd9979d2281b6d97a9/ "link to Codeinstitute resume project").

* Tutorial used to implement CSS variable colours - 
[CSS Tricks](https://www.w3schools.com/css/css3_variables.asp "link to CSS variable colours tutorial").

* Used to understand how to create a triangle shape for the coloured banner - 
[CSS Tricks](https://css-tricks.com/snippets/css/css-triangle/ "link to CSS tricks tutorial").

### Media

* #### Home page
    * Background image of woman climbing is from <a href="https://www.freepik.com/free-photo/cheerful-woman-climbing-wall-gym_5576896.htm#query=climbing%20indoor&position=0&from_view=search&track=ais">Freepik</a>.
    * Background image of man climbing is from <a href="https://www.freepik.com/free-photo/man-doing-his-self-care-ritual_20935535.htm#query=person%20in%20bath&position=5&from_view=search&track=ais#position=5&query=person%20in%20bath">Freepik</a>.

* #### About page
    * Video of bouldering facilities is from <a href="https://www.pexels.com/video/athletes-climbing-a-wall-7591810/">Pexels</a>.<br>
    * Image of climbers looking at each other is from <a href="https://www.freepik.com/free-photo/medium-shot-friends-climbing-wall_44983886.htm#query=climbing%20indoor&position=25&from_view=search&track=ais">Freepik</a>.
    * Image of man climbing facing away is from <a href="https://www.freepik.com/free-photo/full-shot-woman-climbing-wall_44983705.htm#query=climbing%20indoor&position=37&from_view=search&track=ais">Freepik</a>.
    * Image of woman climbing facing out is from <a href="https://unsplash.com/photos/man-in-black-and-white-crew-neck-t-shirt-and-black-shorts-standing-on-brown-concrete-RwjeAb3lXQo"> Unsplash</a>.
    * Image of woman climbing side on <a href="https://www.freepik.com/free-photo/professional-female-climber-bouldering-wall-indoors_26471812.htm#query=climbing%20indoor&position=0&from_view=search&track=ais">Freepik</a>.

* #### Wellbeing Focus page
    * Image of women using stretching equipment is from <a href="https://www.freepik.com/free-photo/two-young-fit-women-training-gym_20757869.htm#query=stretching%20area&position=13&from_view=search&track=ais">Freepik</a>.
    * Image of woman receiving osteopathy is from <a href="https://www.freepik.com/free-photo/professional-female-physiotherapist-giving-shoulder-massage-blonde-woman_1318975.htm#query=osteopatie&position=8&from_view=search&track=ais">Freepik</a>.
    * Image of woman relaxing in water is from <a href="https://www.freepik.com/free-photo/woman-relaxing-spa_3513036.htm#page=5&query=person%20in%20bath&position=43&from_view=search&track=ais">Freepik</a>.

## Deployment

### Cloning the repository
* On GitHub.com, navigate to the main page of the repository.
Above the list of files, click  Code.

* Copy the URL for the repository.
To clone the repository using HTTPS, under "HTTPS", click .
To clone the repository using an SSH key, including a certificate issued by your organisation's SSH certificate authority, click SSH, then click .
To clone a repository using GitHub CLI, click GitHub CLI, then click .

* Open Git Bash.
Change the current working directory to the location where you want the cloned directory.
Type git clone, and then paste the URL you copied earlier.
git clone (insert URL)

* Press Enter to create your local clone.

    Instructions obtained from GitHub docs, further instructions can be found through the link below:<br>
    [Cloning a repository - GitHub docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

## Acknowledgements 
* Mitko Bachvarov - My Code Institute Mentor for helpful feedback.

* Rob Mclaughlin - My tutor at Code Institute for their support and lectures.

* Laura Gibbons - My partner for her user feedback; suggesting a light offer banner would better suit the webpages.

