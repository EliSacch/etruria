# Etruria Winery

Etruria is a family run winery, situated in Tuscany, the hearth of the lands once known as "Etruria".
The purpose of this website it to tell the story of the family, and to present their products, result of a great history. 

The website will be targeted toward wine lovers, and it will be useful to know more, not only about the products, but also about the tasting experiences offered by the family. 

![Responsice Mockup](https://github.com/EliSacch/etruria/blob/main/media/responsive-mockup.png)

[See deployed website](https://elisacch.github.io/etruria/)

## Table of content

- [Design and User Experience](#design-and-user-experience)
  - [Design](#design)
  - [User Experience](#user-experience)
  - [Wireframes](#wireframes)

- [Features](#features)
  - [Navbar and footer](#navbar-and-footer)
  - [Home Page](#home-page)
  - [Wines](#wines)
  - [Visit](#visit)

- [Testing](#testing)
  - [Tests](#tests)
  - [Validator Testing](#validator-testing)
  - [Fixed bugs](#fixed-bugs)
  - [Unfixed bugs](#unfixed-bugs)
  - [Performance](#performance)

- [Deployment](#deployment)
  - [Live Website](#live-website)
  - [Local Deployment](#local-deployment)

- [Credits](#credits)
  - [Content](#content)
  - [Media](#media)

- [Technologies used](#technologies-used)

## Design and User Experience

### Design

The design of the website is clean and simple, to allow the content to pop up.

Choice of fonts:

  - Poiret one - This is the brand font, so it's used for the Logo, the Wines names and the tasting expeciences names.
  - Montserrat (sans serif) - Used for the headings, the menu and the footer.
  - Cormorant Garamond (serif) - As serif font is used for the smaller text (paragraphh content), to male it more readable.


Choice of colours: 

  - Primary color:           
  ![Primary color](https://github.com/EliSacch/etruria/blob/main/media/primary.jpg)
  - Secondary color:         
  ![Secondary color](https://github.com/EliSacch/etruria/blob/main/media/secondary.jpg)
  - Darker secondary color:  
  ![Darker secondary color](https://github.com/EliSacch/etruria/blob/main/media/darker-secondary.jpg)

The map:

  - To accentuate the history of the lands where the wine is prduced, the map choosen for the footer is an old style map, showing the whole area once known as Etruria.
  - Users can still click on the address right next to it to open Google Maps.

 ![Map](https://github.com/EliSacch/etruria/blob/main/media/tuscany-map.jpg)


### User Stories

- As business owner I want:
    - To introduce my family and my products to the users.
    - A dedicated section to showcase my products.
    - A different section to showcase the different experiences that I offer.
    - That users know how to contact me.
    - That users can easily book their experience.

- As a user I want:
    - To easily understand the purpose of the website.
    - To clearly see what sections I can explore in the website.
    - To easily reach each section.
    - To know more about the company and the products.
    - To know if I can visit the winery, the opening time and prices of each visit.
    - To be able to book the experience through the website.
    - To have confirmation that the booking was successful.
    - To be able to contact the winery if there is any problem, or if I have any question.

### Wireframes

<details>
  <summary>Desktop</summary>

   ![Desktop Wireframes](https://github.com/EliSacch/etruria/blob/main/media/desktop-wireframes.jpg) 

</details>

<details>
  <summary>Mobile</summary>

   ![Mobile Wireframes](https://github.com/EliSacch/etruria/blob/main/media/mobile-wireframes.jpg) 

</details>

## Features 

There are three pages: Home page, Wines and Visit.
In each page we have a responsive navbar on top, for navigation, and a footer with contact information and social media links.

### Navbar and footer

Both navbar and footer change layout depending on the size of the screen.

- __Navigation bar__

  - All the navigation items are visible on larger screen, while they are hidden in a coppalsing navbar on smaller screens.

  - The collapsing navbar has an hamburger menu icon when it's closed, and an x symbol when it's open.

![Responsice Navbar](https://github.com/EliSacch/etruria/blob/main/media/navbar-large.png)

- __Footer__

  - The footer contains the contact information, including:
    - map of the area
    - address
    - email address
    - phone number
    - social media links

  - When clicking on the email address link it will open the user's default email client, and the recipient will be already filled out with the email address of the company.

![Footer](https://github.com/EliSacch/etruria/blob/main/media/footer.png)

### Home Page

- __landing page image__

  - This is the landing page for our users, so it has an eye-catching hero image to grab their attention.
  - The hero image is only on the homepage, to easily distinguish it from the other pages.

![Hero image](https://github.com/EliSacch/etruria/blob/main/media/hero-image.png)

- __About__

The homebage containg the information about the company. In particular it contains two distinc sections:

  - The family section, which includes a photograph of the family, and a brief introduction to their story, and how they built the Winery as we know it today.

  - The vineyard section, which contains an overview of the vineyard, the terroir and it explains the different varieties of grapes.

### Wines
  - This page introduces the users to the selection of wines produced by Etruria.

- __Secondary Navigation Bar__

  - This page includes a secondary navigation bar, which includes the names of the three wines offered.
  - The user can click on the name to reach the section dedicated to each label without having to scroll all the way down.
  - The navigation is sticky on larger screens, so it is always visible on top of the screen even when the user scrolls down, but it is not sticky on smaller screen, not to take unecessary space.
  - For this reason the main navigation bar includes a sub-menu, under the "Wines" item, so that users can still have the same functionality even in smaller screens, and reach the specific wine information in one click.

![Secondary menu view on small screens](https://github.com/EliSacch/etruria/blob/main/media/sub-menu.png)

- __Wine section__ 

  - There is one section for each product.
  - It contains one real image of the bottle, a brief description and the organoleptic test, alcohol content and serving temperature.

### Visit

  - This section offers an overview of the tasting experiences available, and what they include.

- __Experiences overview__ 

  - This section is valuable to the user as they will be able to easily identify the types of experiences available, the duration and what they include. 
  - There are three different experiences, and they are presented as three cards, each one with a dark image as backround, and light text.

  ![Experiences Cards](https://github.com/EliSacch/etruria/blob/main/media/experiences-cards.png)

- __Price table__ 

  - This table provides details of the prices, based on the experience type / number of people.
  - It changes layout on small screens.

 ![Two table views](https://github.com/EliSacch/etruria/blob/main/media/table.png)

- __The Booking form__

  - This section contains a form to book the experience.
  - The following fiels are required: Name, Email, Number of people, Experience type, Date and Time.
  - There is an additional field to add other information if needed, so this is the only non mandatory field.
  - The select element for "Number of People" allows a minimum of 1 and a mazimum of 10. For this reason the user is informed to contact the company directly to book an experience for more than 10 people.
  - Users can click on "contact us" from this message, to reach the contact information directly, so they will know how to contact.


- __Booking confirmation Page__

  - After filling out all the mandatory field, users are redirected to a new page with the following information:
    - Booking confirmation message
    - Company contact in case they have more questions or they need to cancel or modify the reservation.
    - A call to action to bring the user back to the homepage, with direct link, so that users are not redirected automatically, but they can review all the information and leave the page when they are ready.


## Testing 

To test my website I have opened it on different devices, to see if it was working as expected.

- Browser tested:
  - Chrome
  - Firefox
  - Edge
  - Brave
  - Safari

- Operating systems:
  - Windows
  - Android
  - iOS

### Tests

  <details>
  <summary>General</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Copy url of the browser and paste it in browser. Press enter | Browser should load index.html | Pass |
  |Scale up the window | The contentent should not stretch over a certain size | Pass |
  |Scale down the window | The contentent should be visible without having to scroll horizontally | Pass |
  |Scale down under 840px width | The layout should switch from 2 to 1 column | Pass |

  </details>

  <details>
  <summary>Navigation</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Scale down under 769px width | The top navigation bar should collapse into hamburger navbar | Pass |
  |Click or tap on hamburger menu icon | The navigation menu should open and the icon change into a close icon | Pass |
  |Click or tap on the close icon | The navigation menu should close and the icon change back into a hamburger menu icon | Pass |
  |Click or tap on the "Wines" item in navigation bar | The Wines page should open | Pass |
  |Click or tap on the "Tudemis" item in the secondary navigation bar | It should bring me to the Tudemis section of wines page | Pass |
  |Click or tap on the "Etesiaca" item in the secondary navigation bar | It should bring me to the Etesiaca section of wines page | Pass |
  |Click or tap on the "Apiana" item in the secondary navigation bar | It should bring me to the Apiana section of wines page | Pass |
  |Click or tap on the "Visit" item in navigation bar | The Visit page should open | Pass |
  |Click or tap on the "Contact us" link right above the form | It should bring me to the contact section in the footer | Pass |

  </details>

  <details>
  <summary>Footer</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Click or tap on the email address in the footer | It should open the device email client to send an email | Pass |
  |Click or tap on the address in the footer | It should open the address in Google Maps | Pass |
  |Click or tap on the LinkedIn icon in the footer | It should open LinkedIn in a new tab | Pass |
  |Click or tap on the Instagram icon in the footer | It should open Instagram in a new tab | Pass |
  |Click or tap on the Facebook icon in the footer | It should open Facebook in a new tab | Pass |

  </details>

  <details>
  <summary>Form</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Submit the form without any value | Browser should inform me that "Name" is a required field, and form should not be submitted | Pass |
  |Submit the form without email address | Browser should inform me that "Email" is a required field, and form should not be submitted | Pass |
  |Submit the form with invalid email address | Browser should inform me that "Email" field must be of email format, and form should not be submitted | Pass |
  |Submit the form without choosing one radio option | Browser should inform me that is a required field, and form should not be submitted | Pass |
  |Submit the form without choosing a date | Browser should inform me that is a required field, and form should not be submitted | Pass |
  |Submit the form with all the required information | Form should be submitted and user should be redirected to a confirmation page | Pass |

  </details>

  <details>
  <summary>Confirmation page only</summary>

  |Action | Expected behavious | Result|
  |-------|--------------------|-------|
  |Click or tap on the email address from the confirmation page | It should open the device email client to send an email | Pass |
  |Click or tap on the "Bring me home" link in the confirmation page | User should be redirected to index.html | Pass |  

  </details>  

### Validator Testing

- HTML
  - No errors were returned when passing the final version through the official [W3C validator](https://validator.w3.org/nu/#textarea)
- CSS
  - No errors were found when passing the final version through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator)

### Fixed Bugs

- When I first deployed the content on github pages, the form was giving an error.
  This was due to the POST method, which is not supported in GitHub pages, so I changed it into GET method, just for the scope of this project.
- When I first deployed the project it was not properly responsive on mobile, showing the content larger than the screen size and creating therefore an horizontal scroll bar. I found out it was a min-size set for the map image in the footer, that was causing the overflow.
- The booking form background image was not showing correctly on iOS. Especially on iPhone it was showing overstretched and pixelated. I tried out several fixes and the solution I found was to change the background image for mobile. In iPhone it shows only the black backfround which looks better than the pixelated grapes image.

### Unfixed Bugs

- In the booking form (visit page), the users are required to select the date for their experience. I could not restrict the dates dynamically using only HTML and CSS, so this results in users being able to select a date in the past.
This bug can be easilly fixed with the support of JavaScript, but that would be outside of the scope of this project.

### Performance

I have tested the performance in chrome, using lighthouse:

<details>
  <summary> Desktop </summary>
  
  - Home page:

   ![Desktop - home page](https://github.com/EliSacch/etruria/blob/main/media/performance-home.png)

  - Wines page:

   ![Desktop - home page](https://github.com/EliSacch/etruria/blob/main/media/performance-wines.png)

  - Visit page: 

   ![Desktop - home page](https://github.com/EliSacch/etruria/blob/main/media/performance-visit.png)

  - Booking confirmation page:

   ![Desktop - home page](https://github.com/EliSacch/etruria/blob/main/media/performance-booking-confirmation.png)

</details>

<details>
  <summary> Mobile </summary>
  
  - Home page:

   ![Desktop - home page](https://github.com/EliSacch/etruria/blob/main/media/performance-home-mobile.png)

  - Wines page:

   ![Desktop - home page](https://github.com/EliSacch/etruria/blob/main/media/performance-wines-mobile.png)

  - Visit page: 

   ![Desktop - home page](https://github.com/EliSacch/etruria/blob/main/media/performance-visit-mobile.png)

  - Booking confirmation page:

   ![Desktop - home page](https://github.com/EliSacch/etruria/blob/main/media/performance-booking-confirmation-mobile.png)

</details>


## Deployment

### Live Website

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - [Live Website](https://elisacch.github.io/etruria/)

### Local Deployment
  - For a local deployment follow these steps:
    - Create a new directory on your machine, where you want do deploy the files
    - Open the existing repository in GitHub
    - Go to the "Code" tab
    - Click on the "Code" button
    - Copy the HTTPS link
    - Open your terminal and run the command __git clone 'link'__
    - use the link just copied, without quotes, instead of 'link'

## Credits 

### Content

- Instructions on how to make the navbar sticky were taken from [Web Dev Simplified, The Forgotten CSS Position](https://www.youtube.com/watch?v=NzjU1GmKosQ)
- Instructions on how to apply glassmorphism to the form were taken from [Coding Artist tutorial](https://www.youtube.com/watch?v=FAfFlyaRAiI)
- Instructions on how to create responsive menu with CSS only were taken from [Angela Delise tutorial](https://www.youtube.com/watch?v=SIzi9z8mrTk&list=PLwgCAlizRKeXs2U_hrZOTCspYjqh2avjS&index=25)

- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The following fonts, used for the project, are from [Google Fonts](https://fonts.google.com/):
  - Montserrat
  - Poiret one
  - Cormorant Garamond

### Media

- The photos used for this website are from [Unsplash](https://unsplash.com/)
  - Family members portrait photo by [Omar Lopez](https://unsplash.com/@omarlopez1?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Vineyard photo by [Rudolf-Peter Bakker](https://unsplash.com/@rudolf_peter_bakker?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Black wine bottle with black label [No Revisions](https://unsplash.com/@norevisions?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Black wine bottle with white label [Ralph Darabos](https://unsplash.com/@darabosralph?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Clear whine bottle with rose wine [Cody Chan](https://unsplash.com/@cceee?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Barrel [Jonathan Borba](https://unsplash.com/@jonathanborba?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Tasting [Maksym Kaharlytskyi](https://unsplash.com/@qwitka?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  - Black grapes [Keegan Houser](https://unsplash.com/@khouser01?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)


## Technologies used

  - HTML
  - CSS