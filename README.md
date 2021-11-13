<h1 align="center">The Depths of Ebonshade Website</h1>

## Introduction
The Depths of Ebonshade is a site to provide all information regarding the Dungeons and Dragons campign "The Depths of Ebonshade". The site is targeted towards people who want to experience more of the niche horror Dungeons and Dragons can provide. The site will also provide additional information for any aspiring DMs who are getting into leading horror campaigns.

[View the live project here.](add link to completed project)

![Am I Responsive UX](assests/media/homepage-ux.png)


<h1 align="center">User Experience (UX)</h1>

-   ### User Stories

    -   #### First Time Visitor Goals

        * As a First Time user, I want to understand the main purpose of this site.
        * As a First Time user, I want to know this is the kind of campaign I want to run.
        * As a First Time user, I want to know the length of time the campaign will take.
        * As a First Time user I want to easily find information about the story.
        * As a First Time user, I want to gain access to the campaign.
        

    -   #### Returning Visitor Goals 

        * As a returning user, I want to find information about the characters.
        * As a returning user, I want to find information about the world.
        * As a returning user, I want to find community links.

    -   #### Frequent User Goals

        * As a Frequent User, I want to be able to access relevant information quickly.
        * As a Frequent User, I want access to character sheets.
        * As a Frequent user, I want to access the character and race stats.
        * As a Frequent user, I want access to external sources to provide a more enthralling campaign.

    -   #### Author Goals

        * As an Author, I want users to be immediately drawn into to the website.
        * As an Author, I want to promote user interaction via our social media channels.
        * As an Author, I want the campaign to be shared to gain notirotity for my further works.  


### Opportunities/Problems

|Opportunities | Importance | Viability / Feasibility
|-----|:------:|:-----:|
|**Entice the user using interactive design** | 5 | 5 |
|**Responsive site for mobile and tablet** | 5 | 5 |
|**Provide details of the campaign**  | 5 | 5 |
|**Provide ease of access to information** | 5 | 5 |
|**Encourage users to return to the site** | 5 | 5 |
|**To build a community**   | 5 | 4 |
|**Encourage users to share the campaign** | 4 | 4 |
|**Provide a single point of reference to useful external resources** | 3 | 4 |



### Wireframe mockups
To produce a basic mockup of the site layouts I used Balsamiq. 

* [Home page wireframe](assests/wireframes/homepage-wireframe.png)
* [Overview page wireframe](assests/wireframes/overview-wireframe.png)
* [Character Creation page wire frame](assests/wireframes/charactercreation-wireframe.png)
* [Contact page wire frame](assests/wireframes/contact-wireframe.png)

There were necessary deviations from the wireframe regarding copyright concerns, initally I had aimed to include a free soundcloud track that users could interact with an listen however looking further into Soundclouds copyright terms and coditions I was unsure if this would be fair use so have instead removed it and kept a clickable link that sends you straight to the soundcloud album and user as this information is important to the user, as is the case with the youtube video by How to be a Great DM. 

* [Original Soundcloud Interact](assests/media/ux-changes/soundcloud-issue.png)
* [UX of Soundcloud and Youtube link](assests/media/ux-changes/link-only.png)


### Design

Following the overall structure of the wireframes being established, I first set out to find stock images that would relate to a niche horror fantasy without compromising on the aesthetic. I needed a hero image that immediately caught the user’s focus and explained the webpage on its own. After going through unsplash and pexels for a couple of days I was able to find what matched the asthetic I was targetting on shutterstock [https://www.shutterstock.com/](https://www.shutterstock.com/g/WarmTail?searchterm=)

* [Image Collection](assests/media/image-collage.png)
* [Final Image](assests/images/hero-2560.jpg)

### Color Scheme

The image then dictated the color scheme design focus, the goal then became to have striking contrasts that mentally relate to horror but for a contrasting perspective, I needed to clear visible text as the purpose of the website is to draw the user in and give them the information they want to come back to.

By testing different rgba shades of red to match up with my hero image I chose I compared contrasting colors using [https://webaim.org/resources/contrastchecker/](https://webaim.org/resources/contrastchecker/) of which white (#FFFFFF) gave a good contrast. 

To give a container contrast for the main body of text I used a grey background color which gave a suitable contrast ratio, however later on in development this was changed to black. The black to white contrast is the highest contrast and suited the theme of the website and the goal of making the information stand out. 

* [Red Contrast Check](assests/media/ux-changes/contrast-red.png)
* [Grey Contrast Check](assests/media/ux-changes/grey-contrast.png)
* [Black Contrast Check](assests/media/ux-changes/contrast-black.png)
* [Previous Grey container](assests/media/ux-changes/grey-container.png)
* [Final Black container](assests/media/ux-changes/black-container.png)

<h1 align="center">Features</h1>


## Common Features

* ### Navigation Bar

    - The navigation bar is common across the whole site appearing on all 4 pages.
    - The navigation bar contains links to the home page, campaign, character creation and contact page to give the user simple navigation around the website.
    - The logo has been added to the navigation bar as an additional link back to the home page.
    - The logo item was imported using font awesome the choice of the logo was straight forward a d20 dice is synonymous with D&D.
    - The navigation bar is fully responsive with the nav bar change at two media sizes to give a smoother transition. 
    -  A hover over feature has been added so the users can see what navigation option they are currently selecting.
    - An active class has been set for the page the user is currently on, this is shown via a white underline beneath the text which is shown below. 

    ![Navigation bar](assests/media/ux-changes/nabar.png)

* ### Footer 

    - The footer section is common to every page across the site, the footer includes links to each social media platform, currently all these links send you straight to the main social media page as this campaign is yet to be added to these platforms excluding the discord link. The discord link sends you an invite to a server I set up.
    - The link items were imported using font awesome using the script at the bottom of the page. 
    - Included is a copyright notice including my name.

* ### Banner Title Card

    - The banner card is common to every page but the home page, this is to keep a consistant theme that is contrasted by the changing banner photos. The banner card is shown below.
    - The banner card is fully responsive with moblie devices as an issue arised with it overlapping the main body of text on each page. 

    ![Banner Card](assests/media/ux-changes/banner-card.png)

* ### Text Container

    - Each page's body of text is incased in this container it ensures the design remains consistent across the site.
    - This is made fully responsive where at 1024px the container expands to the full page width prevent the text from looking squashed in. 

    * [Container without media query](assests/media/container-without-med.png)
    * [Container with media query](assests/media/container-with-med.png)

## Home Page Features

*    ### Hero Image 
        - The home page has a hero image to width and height of the full scrren. As previously stated in the design section this is to draw the user in.
        - The hero image is fully responsive so the figure in the image remains center of the screen at all time. 
        - The hero image contains the title of the website which is contained within a fully responsive div element, this changes position and font size dependant on screen width.
        - The hero image as contains an interactive button which animates when hovered over or clicked, this is also fully responsive and caused an interesting bug which will be addressed in the bug section of this document.

![Hero Image](assests/media/hero-image-read.png)

* ### Home Page Information Section
    - Taking inspiration from the [call of duty vanguard website](https://www.callofduty.com/content/atvi/callofduty/vanguard/web/en_gb/home.html), the sections of text have been separated and style in 4 separate divs to control the position and stagger the text. 
    - Images that correlate to the banner of each page sit above their related counter part e.g. the warrior holding a torch is above "Story" the banner for the Story section is that image.
    - Learn more buttons have been added which light up when hovered over and are linked to the id of the specific section directing the user to specific sections of the site.
    - The sections are responsive under both the 1024px media query and at 768px where the sections sit one on top of the over giving a clean user interface the difference can be seen in the links below..
    - [Home page full screen](assests/media/homepage-section.png)
    - [Home page responsive](assests/media/homepage-768px.png)

## Campaign Features
* ### Page Content 
    - The main section of the campagin page is to give the user digestable information and to give a teaser to the campaign story.
    - The main section also includes information for DMs looking to branch into horror with a summary of information and links to external resources. 

![Snippet of compaign section](assests/media/Campaign-section.png)

## Character Creation Features
The purpose of this page was to be more interactive by distributing quite a lot of information in an engaging manor, for this there is a combination of drop down menus and pop-ups that the user can easily use to get the exact information they want. The purpose of this is for site retention by producing a page that has links to the external material and a more compact breakdown of the roles it becomes more convinent to visit this webpage.
* ### Inital Section
    - The inital section introduces the key feature of the capaign and give an overview of available character parameters.
    - The inital section also includes likes to the official race and class guides which are the foundations for the ones related to the campaign. 
* ### Races Section 
    - The layout is organised into a series of drop down menus using the details and summary function of CSS This gives the user the option to have just the specific information they require as opposed to an undigestable amount of text on the screen. 
    ![drop down menu evidence](assests/media/dropdown.png)
    - The details and summary elements were checked using the site [caniuse.com](https://caniuse.com/?search=details%26summary) to which it is supported by 97.4% of gobal users. 
    ![Can I Use Evidence](assests/media/caniuse.png)

* ### Classes Section 
    - Individual interactive images are used to represent each class allowing users to click on each image to reveal the description. 
    ![Class Image Layout](assests/media/classes.png)
    - A seperate interface opens changing the opacity of the background bringing full attention to the text container. When the window is closed using the close window button the user is returned to the exact same position they were previously on, the page.  
    ![Class Image Popup](assests/media/classes-popup.png)
    - The images and popups are fully responsive as shown in the images below.
    - The screen width has been lowered to 1277px for the first image.
    ![Lower Screen width for Class Images](assests/media/class-responsive-1.png)
    - The screen width has been lowered to 375px (iPhoneX width) for the second image.
    ![Mobile Screen width for Class Images](assests/media/class-responsive-2.png)
    - The screen width is at 375px to show the popup window is responsive for the third image.
    ![Mobile Screen width for Popup](assests/media/class-responsive-3.png)

## Contact Page Features

* ### Community Section
    - This section is to highlight the community aspect of the campaign and encourage users by highlighting the discord. The discord is referred to on the Main page and in each footer to achieve to goal of users returning to the site or remaining engaged with the content. 
    ![Join the Community Image](assests/media/community.png)
    - The contact form gives users the ability to contact the campaign creators for a copy of the campaign or any queries. The user is asked for full name, last name, email address and message which are all required fields.
    ![Contact Form Image](assests/media/contact.png)

<h1 align="center">Future-Enhancements</h1>

The future intention of this webpage would be to enable users to create their own characters using the webpage, share stories or images of themselves enjoying the campaign to build a bigger community.
There's currently a lack of horror themed Dungeons and Dragons campaigns and the future goal would be to produce more campaigns which would be showcased on the website. 

* First would to improve the website design further























        
