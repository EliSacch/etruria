# Etruria Winery

Etruria is a family run winery, situated in Tuscany, the hearth of the lands once known as "Etruria".
The purpose of this website it to tell the story of the family, and to present their products, result of a great history. 

The website will be targeted toward wine lovers, and it will be useful to know more, not only about the products, but also about the tasting experiences offered by the family. 

![Responsice Mockup](https://github.com/EliSacch/etruria/blob/main/media/responsive-mockup.png)

[See deployed website](https://elisacch.github.io/etruria/)

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

- __Price table__ 

  - This table provides details of the prices, based on the experience type / number of people.
  - It changes layout on small screens.


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


## Testing - to be completed later

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing - to be completed later

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs - to be completed later

- In the booking form (visit page), the users are required to select the date for their experience. I could not restrict the dates dinamically using only HTML and CSS, so this results in users being able to select a date in the past.
This bug can be easilly fixed with the support of JavaScript, but that would be outside of the scope of this project.

## Deployment - to be completed later

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - 


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


## Other General Project Advice - to be completed later

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 
