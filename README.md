# CARE - Community Action for Resources and the Environment

## Overview 

Welcome to the homepage of CARE, a Dublin based community group passionate about helping the environment, promoting sustainability and eco-friendliness. The site sets out who the group are, what they aim to achieve and how and allows members of the community to get actively involved through engagemet with social media profiles, participation in organised events and/or through application of suggested tips in their own day to day life.  

**NOTE: This group has been created for the sole purposes of creating this website to demonstrate HTML and CSS skills. The group itself and the events noted are not real.**

![Responsiveness Demo](./docs/responsive_design_screenshot.png)

## Live Site

[CARE - Community Action for Resources and the Environment](https://lw83.github.io/Project1-CARE/)

## Repository 

[https://github.com/LW83/Project1-CARE](https://github.com/LW83/Project1-CARE)
***
## Concept & Planning 

### UX

- __Audience__

- __User Stories__

- __Site aims__

### Wireframes

### Color Scheme
- To decide on the color scheme for the site, I first selected the hero-image which would make up the header across each of the pages. This image was selected from [Pxhere](https://pxhere.com/).
- Once I had decided on the image, I used [Image Color Picket](https://imagecolorpicker.com/en) to identify different colors within the image to use as the basis for font, border and icon colors within the site. 
- In order to ensure the colors selected had sufficient contrast to meet accessibility requirements, I validated the color palette using [Eight Shapes Contrast Grid](https://contrast-grid.eightshapes.com)

![Color Contrast](./docs/color_contrast_screenshot.png)

### Fonts
 - The fonts utilised are consistent across the page and are from Google fonts. 
 - They are Red Hat Display for the Logo and Navigation bar and Comic Neue for the body of the site. 
 - Sans serif has been applied as a backup font for both. 

***
## Existing Features 

### Header & Navigation

- __Hero image__

  - All pages of the site have a consistent header, a key element of which is large and striking image of Ireland which drives the color palette for the entire site and reinforces the focus of the group being an Irish based, environmentally-focused community group. 
  - In the event that the image does not load, there is also background color assigned to ensure the logo and navigation bar remain fully visible to the user. 

  ![Hero Image](./docs/fullheader.png)

- __Logo__

  - The logo sets out both the abbreviated and full name of the group and is complimented by a font awesome icon to denote the environment.
  - The font has a color of whitesmoke to contrast against the color of the hero-image whilst being complimentary to the clouds in the image and links back to the homepage across all pages of the site.

  ![Logo](./docs/logo.png)

  - The logo is fully responsive and wraps for smaller screen sizes. 

  ![Logo Tablet](./docs/logoandnavtablet.png)

- __Navigation Bar__

  - Featured on all three pages, the navigation bar includes links to the Home page, Events and Tips pages and is replicated in design and functionality across each page to allow for consistency, easy navigation and good UX.
  - This has been floated to the right of the page to align with the top of the CARE logo. 
  - The navigation links are all in whitesmoke to contrast against the color of the hero-image whilst being complimentary to the clouds in the image. The below image shows the user's current page highlighted in blue with a white border.
  - When hovered over, the links are highlighted in a lighter shade of blue to provide feedback to the user and again utilising colors from the hero-image. 
  - When visited, the links change to a shade of green again to replicate colors from the hero image and to provide feedback to the user. 
  
  ![Nav Bar](./docs/navbar.png)
  
  - An active class has also been implemented to highlight to the user the current page being viewed. 
  - The navigation bar is fully responsive, for smaller screens, the bar drops below the logo retaining its place on the right side of the screen so as not to compete for space with the logo. In addition the font-color remains white smoke to ensure sufficient contrast with the hero-image given the new placement. 
  
  ![Nav Bar Mobile](./docs/logoandnavmobile.png)

- __Favicon__

  -  A favicon has been added to show up in the title of the page and is consistent with the icon used in the logo itself. 
  
  ![Favicon](./docs/favicon.png)

### Footer

  - Similar to the header, all pages of the site have a consistent footer which has two key elements being the option to subscribe to the group's newsletter and links to the group's social media pages. 
  - Again the styling of the footer is driven by the color scheme coming from the hero-image. 
  - The newsletter subscribe button again has a hover feature to provide feedback to the user and when submitted takes the user to a thank you page. 
  - Social media links for Facebook, Instagram, Twitter and YouTube are included and all open links to the homepages of these sites in a new tab. This is for demonstration purposes only and no social media pages have been created. 
  - All social media links are represented by Font Awesome icons. 
  - Finally, the footer includes a note regarding copyright and a call-out that the site is fictional in nature. 

  ![Footer](./docs/footer.png)

### Home Page

  - The About section on the site is focused on setting out for the user who the group are, what they do and why they do it. 
  - Boxes and font awesome icons have been added to distinguish these sections.
  - This page has been kept deliberately lighter on content so as not to overwhelm a potential new user.  
  - For desktop layouts, the about boxes sit side by side in a float structure. 

  ![About on Desktop](./docs/about_desktop.png)

  - For tablet and mobile layouts, the about boxes stack on top of each other and take the full width of the page to maintain a clean and simple flow.  

  ![About on Tablet](./docs/about_tablet.png)

### Events Page

  - The Events page of the site sets out both current events planned for upcoming months and recent events that the group have organised. The current events are shown first on the page and recent events after to follow what the user would expect when looking for Event information. 
  - Current events set out the time, date and location for each event and include an image from the location to engage the user. 
  - Recent events set out date of the event and some brief information regarding the number of volunteers that turned out as well as links to Facebook and Instagram social media pages for further photos of the event. Again this is for demonstration purposes and no social media pages have been created for this purpose. 
  - The social media links all open in new tabs for the user. 
  - All images in the Events page have been compressed to improve site performance.
  - For desktop layouts, the events are organised in a row of three events with text details of the event provided underneath an image of the location. 

  ![Events on Desktop](./docs//events_desktop.png)

  - For tablet layouts, the events are stacked with the image to the left of the page and details in a box to the right of the image. The box has been added as it made for better visual respresentation under this structure and was inkeeping with the other pages and the utilisation of boxes. 

  ![Events on Tablet](./docs/events_tablet.png)

  - For mobile layouts, the events remain stacked but the text for the event moves underneath the image and the box is removed to simplify the visual effect for smaller screen sizes. 

  ![Events on Mobile](./docs/events_mobile.png)

### Tips Page

  - The Tips page of the site provides a list of tips for the user to implement in different aspects of their day to day life. This is arranged by area to faciliate the user focusing on a specific aspect such as Shopping or Garden. It provides handy tips ranging from the very small to more substantial that a user can implement based on what suits their individual lifestyle and preferences. 
  - Consistent with the structure of the homepage, the tips have been organised into boxes with relevant font awesome icons applied to help differentiate each box for the user. 
  - Some fun has been added in to the comments to lighten the content and help to engage the user. 
  - Within the tips page, there is also a link to a Panda reference guide for recycling which open in a new tab for the user. 
  - The page also includes a form which enables users to submit their own tip suggestions for inclusion on the page again encouraging engagement and action from the user. 
  - For desktop layouts, 
  - For tablet and mobile layouts,

### Form Dumps

  - Two hidden form feedback pages exist to provide feedback to the user where they sign up to the newsletter or submit a tip suggestion. 
  - These are not functioning forms but are created using the method "Get" to call a feedback page. 
  - Following a sign-up to the Newsletter, the user is taken to a page with a "Welcome! Thanks for Signing Up!" message and a link to return to the homepage. All other aspects of the page including header and footer are consistent with the other pages of the site. 

  ![Newsletter Feedback](./docs/newsletter_signup.png)

  - Following a tip-submission, the user is taken to a page with a "Thank you for your Submission!" message and a link to return to the homepage. Again, all other aspects of the page including header and footer are consistent with the other pages of the site.

  ![Tip Submission](./docs/tip_submission.png)

## Potential Future Features

- Placeholder
***
## Testing 

### Responsiveness Testing
 - Responsiveness of the site was tested using Dev Tools for all screen size widths from 320px up to 1700px.
 - Responsiveness was also specifically checked for the following devices within Dev Tools:
      - iPhone SE
      - iPhone XR
      - iPhone 12 Pro
      - Pixel 5
      - Samsung Galaxy S8+
      - Samsung Galaxy S20 Ultra 
      - iPad Air
      - iPad Mini
      - Surface Pro 7 
      - Surface Duo
      - Samsung Galaxy A51/71
      - Nest Hub
      - Nest Hub Max
 - Specific breakpoints for each page were identified and managed through media queries. These were focused on adjusting the layout of boxes on the page, the size of margins and padding and also adjust the font-size for smaller screen sizes. 
 - I did not use Flexbox or CSS Grid in this project as I wanted to better familiarise myself and understand the float model but plan to use one or both of these newed methods in a future project. 

### Browser Testing
  - The site was developed and tested using Google's Chrome browser. 
  - The site has also been tested on Safari and functions as intended. 

### Accessibility Testing 

  - The accessibility of the site has been tested through the following tools: 

    - Dev Tools Lighthouse Report (screenshot included in Validation Testing section below)
    - [Wave (Web Accessibility Evaluation Tool)](https://wave.webaim.org/)
    - A11y project checklist 

  - The following aspects of the site development have been specifically included with accessibility in mind and as recommended by the above sources: 
    - For all images on the Events page, alt tags with appropriate descriptions have been applied.
    - Keyboard navigation for the site has been tested and is functioning as expected. 
    - Each page has its own title description (e.g. CARE - Home, CARE - Events, CARE - Tips). 
    - All color contrasts have been tested and validated. 
    - All forms have appropriate labels and the tips form specifically calls out in text the required fields. 
    - Icons including social media icons have appropriate aria-labels applied. 
    - Semantic HTML tags have been used including headers, nav, h1, h2, h3, section, footer etc. 
 
### Validation Testing 

- __HTML Validation__
  - No errors were returned for any of the pages in the site when passing through the official W3C Validator. 
  ![W3C validator Homepage](./docs/w3c_homepage_htmlvalidation.png)
  ![W3C validator Events](./docs/w3c_eventspage_htmlvalidation.png)
  ![W3C validator Tips](./docs/w3c_tipspage_htmlvalidation.png)

- __CSS Validation__
  - No errors were found when passing through the official 
  ![(Jigsaw) validator](./docs/w3c_css_validation.png)

- __Lighthouse Report__
  - In addition to the HTML and CSS Validation, I generated a lighthouse report for the site pages through Dev Tools.
  ![Lighthouse Report](./docs/lhreport_homepage_1280px.png)
  ![Lighthouse Report](./docs/lhreport_events_1280px.png)
  ![Lighthouse Report](./docs/lhreport_tips_1280px.png)


### Unfixed Bugs
 
***
## Deployment

- The site was deployed to GitHub pages following the below deployment steps: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here: [CARE - Community Action for Resources and the Environment](https://lw83.github.io/Project1-CARE/) 

On initial deployment of the site to GitHub pages, I found the images were not loading and upon some research found that I needed to remove the first forward slash in address location in order to pull in the image correctly for the deloyed site. This was resolved thanks to the GitHub community forum. 

***
## Credits  
 - The following tools are resources have been utilised in the creation of this project: 
     - https://imagecolorpicker.com/en - used to match colour in photo to text
     - https://fsymbols.com/copyright/ for copyright symbol
     - https://www.w3schools.com/html/html_favicon.asp for favicon 
     - https://www.codegrepper.com/code-examples/html/css+change+font+awesome+icon+color to change colour of font awesome icon in logo
     - https://stackoverflow.com/questions/19089018/how-to-align-form-at-the-center-of-the-page-in-html-css to centre form in middle of page 0 auto
     - https://www.w3.org/WAI/test-evaluate/preliminary/ - accessibility checks
     - https://wave.webaim.org/
     - https://www.a11yproject.com/checklist/
     - Slack
     - Stackoverflow
     - W3Schools
     - GitHub Community Forum

 - In addition a big thank you to the following people for their assistance in this project:

### Content 

- The text for the tips page was 
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Google Fonts
- Love Running 
- W3C Validators
- Color
- Accessability 

### Media

- The hero-image used in the header is from https://pxhere.com
- The images used for the gallery page were taken from 
- Images have been scales and resized using https://imageresizer.com/
- Images have been compressed using https://compressor.io

