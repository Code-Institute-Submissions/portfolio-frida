# Portfolio

### Fridas Portfolio
(Milestone Project 1 for Code Institute)

This is a website created for Frida Lindstrom to showcase her skills and previous work as a Full Stack Web Developer. The goal of the website is to connect site owner with possible employers to get hired.

## UX

### User Stories

-   As a user I want the site to be easily navigated and the information provided easily understood.
-   As a user I want to easily find the wanted information about Frida, download her cv och or the means to contact her. 

### Site Owners Stories

 - As a site owner I want the user to easily navigate the site and locate the information they seek. 
 - As a site owner I want to show myself in best light possible to get hired by potential employers visiting the site.

## Design

Home Page layout consisting of a hero-image, following a white background with black font throughout for the following sections.  
The color scheme continues on the colors of blue and yellow found in the hero-image to keep the colors and light theme of the site consistent throughout.
Font used throughout the site is Playfair Display which is used consistently through the whole site with Serif as back up font. 
### Wireframes

-   Main Section - [View](assets/wireframes/index.png)
-   About Me Section - [View](assets/wireframes/about.png)
-   My Work Section - [View](assets/wireframes/work.png)
-   Contact Me Section - [View](assets/wireframes/contact.png)

## Features

- Responsive Design throughout website.

### Existing features
- Feature 1 - Navigation Bar - By choosing the different headlines in navigation bar (Home, About, Work, Contact, CV) the user will be transported to the selected part on the site. 
- Feature 2 - Work Section - The user can choose to view another project by pressing the webiste-logo in each of the different sections and the website chosen will be opened in a new browser (currently only the portfolio website, where the user is transported to beginning of page when clicking on link, is a posssible choice but developer will add projects from the course when they are finished) 
- Feature 3 - Contact Form - The user can fill in name, email and message to site owner.
- Feature 4 - The user can view site owners CV in a pdf-format which when clicking in CV link will open in a new browser. 
### Future features to implement
- Collapsible navigation bar when site is viewed on mobile devices (requires Javascript-knowledge).
- Add links to future projects from course in the Work section.
- Add links to site owners personal profile pages in Github, Instagram and LinkedIn. (At the moment the user will be transported to the respective website start page.)

### Libraries and Frameworks

- [Balsamiq Wireframes]([[https://balsamiq.com/wireframes/](https://en.wikipedia.org/wiki/Balsamiq#Balsamiq_Wireframes)) was used to help create mockup and create UX-design for website
- [Google Fonts]([https://fonts.google.com/](https://fonts.google.com/)) was used to import font Fairplay Display which is used as the font throughout the website with Sans Serif as backup font.
- [Font Awesome]([https://fontawesome.com/](https://fontawesome.com/)) was used for the icon to download CV and for the icons to the social media links in the footer.
- [GitHub](https://github.com/) was used to store the projects code after being pushed from Git.
- [Gidpod](https://www.gitpod.io/) was used for version control by using the Gitpod terminal to commit and push to Github.
- [StackEdit](https://stackedit.io/) was used for help with learning markdown language for readme-file.

### Languages

- [HTML5](https://en.wikipedia.org/wiki/HTML5.com)  
- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)


## Testing

- Html-code tested with W3C Markup Validator, view result [here](https://validator.w3.org/nu/?doc=https%3A%2F%2Ffridalindstrom.github.io%2Fportfolio-frida%2F)

- CSS-code tested with W3C CSS Validator, view result [here](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Ffridalindstrom.github.io%2Fportfolio-frida%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Responsiveness of website was checked using [Am I Responsive?](http://ami.responsivedesign.is/)

[Google Dev Tools Lighthouse](https://developers.google.com/web/tools/lighthouse) was run to check accessibility of page.
Changes done after first test; comprised profile-photo to 186kb from 418kb to make site load faster.

### Link Testing 

#### Navigation bar 
- Clicking on About in Navigation bar takes the user down to the About-section.
- Clicking on Work in Navigation bar takes the used to the Previous Work-section.
- Clicking on Contact in Navigation bar takes the user to the Contact Form section.
- Clicking on Home in Navigation bar takes the user back to the beginning of page when user is located further down on page.
- Clicking on CV in Navigation bar opens up the CV in PDF-format in a new browser tab.

#### About Section
- Link to Code Institute is working, viewer is transferred to Code Institutes website in a new browser tab.

#### Work Section
- When clicking on the headline to Portfolio in Work section the user will be directed to a new browser containing the CV in PDF-format. 

#### Contact Form
- Typing in name, email and message and pressing send, being directed to new window. 
- Typing in wrong email address message will pop up that email is not correct. 
- When leaving field for name empty an error message will display that field is required.
- When leaving field for email empty an error message will display that field is required.
- When leaving field for message empty an error message will display that field is required.

#### Footer
- Clicking on the CV download icon in Footer will open a new browser tab showing the CV in a PDF-format.
- Clicking on the Github icon the user will go to the Github homepage in a new browser (will later add site owners profilepage but it is in private mode for now).
-  Clicking on the LinkedIn-icon the user will go to LinkedIn homepage in a new browser (will later add site owners profilepage but is private mode for now).
-  Clicking on the instagram icon the user will go to Instagram homepage in a new browser (will later add site owners profilepage but keeping it in private mode for now).

#### Further Testing

-The Website was tested on Google Chrome, Internet Explorer and Safari browsers.
-The website was tested on mobile devices Iphone SE, Iphone 8, Motorola G7+, Samsung Galaxy S9, Huawei P30. 

## Deployment

### GitHub Pages
1. On GitHub, navigate to the site's repository.
2. In the repositorys site, click on **Settings**, it is located on the right in the menutab of the repository. 
3. Once clicked to Settings, on the site scroll down to "GitHub Pages", click on **Source** drop-down menu and select publishing source (Main).
4. A new menu pops up to the right of the source drop down menu, select **/roots** in the menu and then press **Save** to the right.
5. To find the site address scroll down again on the Settings page and the address will be located under the same headline; "Github Pages". 
6. The site will take a short while until it is working properly. If it is not working straight away try adding /index.html to the address in browser and that should work. 

## Credits

### Content

All content was written by the developer.

### Code 

- Tutorial help and code for contact-form from w3schools, view tutorial [here](https://www.w3schools.com/howto/howto_css_contact_form.asp)

- Information, help and code for media queries was found at css.tricks, view [here](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)

- As the developer I have chosen to base the website entirely on Html and CSS  (without Bootstrap) to focus solely on learning to build a website based on CSS Flexbox since I felt inadequate in my skillset in CSS and wanted to learn the base of CSS before adding and relying too heavily on Bootstrap. To learn more of Flexbox I have used this [ video tutorial](https://www.youtube.com/watch?v=FTlczfR82mQ&list=PLDyQo7g0_nsUjf046cCHKJ16U1SoXrElZ&index=6) from Youtube to gain better understanding and knowledge along with this [article tutorial]([https://css-tricks.com/snippets/css/a-guide-to-flexbox/](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)) from css-tricks.com.

### Media

- Hero image from Burst Shopify - View link [here](https://burst.shopify.com/photos/office-work-tools-on-the-white-desk?c=computer)

- Profile photo was created by the developer.

### Acknowledgements

- To my mentor Can for helpful feedback.


