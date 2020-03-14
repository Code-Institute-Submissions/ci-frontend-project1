# User Centric FrontEnd Development Milestone Project

# Yoga Studio Website
## Website Overview
The purpose of this project is to design a static website for a yoga studio located in the city. The website provides an online presence to the yoga studio and allow customers and potential customers to browse their services and purchase yoga package from this website.

## UX
This website serves to inform the general public and workers in the local business and financial district about yoga studio services located in the vicinity. Presumably workers are tired and stressed out after a long day at work or even during work and this website serve to inform them of the fitness services provided to them, utilizing the location convenience of the yoga studio.

The design should be user friendly, simple and easy on the eyes. Users of this website should be able to gain information about the yoga studio, the services and the pricing offered. The possible User stories are as follows:

* User Story 1: The user is new to yoga and is curious to find out what yoga studio he/she can join to experience yoga.
* User Story 2: The user is an office worker or general public and wants to find yoga studio in the vicinity that he/she can go to, and wants to know the class timing offered in the yoga studio to be able to fit it into his/her personal schedule.
* User Story 3: The user is a pregnant office worker and would like to work-out pre-partum. She wants to know which studio offers prenatal yoga.
* User Story 4: The user/s is/are high income customers who wants personalized yoga classes.
* User Story 6: An organization wants to organize a yoga workout for its staff members and wants a yoga studio in the vicinity.

Based on the user stories, the website was designed with the following sections:
* Home - Landing page with pictures of person/people doing yoga
* Articles - Links to online article to list the benefits or trends of yoga
* Service Types - Breakdown of class-types by needs and links to schedule
* Pricing - Pricing packages on offer

A light beige/ brown theme is used throughout the whole site to reflect on the earthiness of yoga. A touch of pink is used to get the attention of the users, to selectively highlight certain content, for example certain buttons or price cards.

Ubuntu (sans-serif) font is chosen for heading because of its modern, easy to read look. The letters are appropriately spaced for a clean look. In a similar context, Lora(serif) font is used for the content because it is modern and clean and pairs perfectly with the Ubuntu headings.

A special logo is created for the website to represent the yoga studio and a name (The Prana Hut) for the yoga studio was chosen. The logo was designed such that it has a lotus shape that is symbolic to yoga mediation and it looks like the letter 'W' for wellness. There is a small image of a city in the center to symbolize the location of the yoga studio, which is one of the main attraction of the yoga studio. The colors of the logo is dark brown and matched to the website theme. As for the name, Prana, it is a word that originated in Sanskrit and often found in yoga. It means "breath, life-force". The word 'Hut' hopes to give the yoga studio brand a homely feel.

## Features 
### Existing Features
In the main page, this project has 4 sections: 
1. The Home Page consists of a carousel of people doing yoga poses. The purpose is to motivate users to want to do yoga as well either for relaxation of the mind or for sculpting their physique. At the 3rd carousel image, there is a call to action button to lead users to view the class-type offered.
1a. The Home Page has a nav bar that has a menu to allow users to find which part of the site they would like to visit next. In the nav bar, the menu item contact has a drop-down link to phone call, e-mail, location and query. The phone call icon will allow users to open a phone dialer and input the number. The e-mail icon will allow users to open up an e-mail app to send e-mail and the location icon will open a pop-up window to show the studio location on an embedded google map.
2. The second section consists of linked articles to inform users of the benefits of yoga exercises. Users are able to read through the article by clicking on the cards. 
3. The third section consists of flip cards. The features on this page are flip cards. It serves to summarize in 1-2 words what the users are looking for in doing yoga. For example, if the user wish to improve his/her fitness, he/she will flip over the fitness card to find which yoga class type is suitable for improving his/her fitness level and at the back of the flip-card, users are able to click the button that will allow them to view the class schedules or the button to purchase a class package.
4. The final section consists of pricing cards or tables. The features on this page are cards which are similar to the second section. It serves to inform users of the different class packages and the list of items/services that comes with the purchase.
The user may purchase the package or services by clicking on the purchase buttons of the pricing tables.
4a. The footer section has the e-mail address, the phone number, the location and links to feedback form displayed. It also has links to social media sites. The user is able to click on the icons to contact or be contacted as well as to visit the social media sites.

Off the main page, the Contact drop down in the menu has a Queries item that will link to a form page. This page only has 1 secion. The main feature of this page is a form which allows user to fill in his/her name, phone number, e-mail address and their preference of day and time to be contacted. There is also a input text box to allow users to put down their queries or comments.

### Features To Be Implemented In Future
One item that I would like to implement in the future is an About page that talks about the yoga studio, the mission and the vision of the business.

### Features Left to be Implemented
This project lacks pop-up/modal sign-up form when users click the purchase button. Another feature to add is the billing page for users to add the packages to cart and input their credit-card information. 

## Technologies Used
The technologies used in this project are:
* HTML5 (https://html.spec.whatwg.org/multipage/). HTML5 is the markup language that stores the structure of the webpage document.
* CSS3 (https://www.w3.org/Style/CSS/). CSS3 is used to style the contents, images and layouts of HTML documents.
* Boostrap 4 (https://getbootstrap.com/). Boostrap 4 is used as an additional framework tool for making structuring of the project easier and a lot faster. It has build in classes to allow me to style my layouts fast as well as making mobile-responsive design easier.
* GoogleFonts (https://fonts.google.com/). I use google fonts to style the texts in this project.
* Font Awesome Icons(https://fontawesome.com/). I use font awesome icons to add icons to certain part of the contents in this project for simplicity and readability.

## Testing
### (1) Manual Testing
The testing for this website is purely using manual testing.
1. Home Page.
When users enters the landing page/ home page, they should see a carousel made up of 3 photos images showing people doing yoga poses. In the third carousel, there is a call to action button to view the class-types. When this button is clicked, the webpage redirects to [the service-types section](https://oraclebun.github.io/ci-frontend-project1/#service-types)
Users should be able to see a navigation bar at the top of the landing page. When the mouse button hovers over the menu items in the navigation bar, it should change to a hand icon.

'Home' item redirects the page to itself.

'About' item directs the user to an external webpage [About](http://www.theyogastudio.org.uk/about.htm)

'Articles' item directs users to the articles section of this webpage [Articles](https://oraclebun.github.io/ci-frontend-project1/#articles)

'Teachers' item directs users to an external webpage [Teachers](https://levelsixstudios.co.uk/teachers)

'Store' item directs users to an external webpage [Store](https://shop.lululemon.com/c/women/yoga/_/N-7vfZ1z141d0?mnid=mn;en-US-JSON;women;yoga)

'Contact' item is a dropdown link that consists of 4 items - Location, E-mail, Phone and Queries.

1. The results of testing 'Contact' dropdown link items are as follows:  
i. Location - when this is clicked, users will see a modal box of an embedded google map location.  
ii. E-mail - when this is clicked, users will see a modal window of an empty e-mail message, addressed To: yoga@domain.com with a subject: Hello.  
iii. Phone - when this is clicked, users will be linked to a phone-dialer to make the call.  
iv. Queries - when this is clicked, users will be directed to a forms page.

2. Second Section (Articles Page)
When users enter this page, they should see a main heading 'Why we should yoga' and 3 cards that links to external websites.
The first article card has a photo of a woman doing yoga poses on a surfboard and links to [A Yoga Journal Article](https://www.yogajournal.com/lifestyle/good).  
The second article card has a photo of a woman lying face down on the floor. It links to [Very Well Mind](https://www.verywellmind.com/how-yoga-can-help-reduce-stress-3567211).  
The third article card has a photo of a woman facing front sitting in a lotus position. It links to an article in [Times of India](https://timesofindia.indiatimes.com/life-style/health-fitness/5-reasons-why-millennials-love-yoga/articleshow/74203145.cms).

3. 