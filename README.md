
# Aquarium Specialists

A website for aquarium and fish tank lovers and hobbiests based in Limerick, Ireland. Website features a short summary about what the business does, a vibrant gallery portraying the businesses work and a contact page where customers can fill in their queries or visit the shop by looking at the map.

[View deployed site here](https://pradnya144.github.io/Portfolio-Project-1/)

![Website mockup](README-docs/mockup.JPG)


## Table of Contents

* [User Experience (UX)](#User-Experience-(UX))
* [Design](#Design)
* [Features](#Features)
* [Technologies](#technologies)
* [Testing](#Testing)
* [Deployment](#Deployment)
* [Acknowledgements & Credit](#Acknowledgements-&-Credit)


## User Experience (UX)

### User Story

User stories were created to help guide the design and implementation phases of the project and to ensure the needs of each stake holder are undestood.

* Visitor Goals

    * As a visitor:
        * I want to know about the business.
        * I want to undertsand the services they offer.
        * I want to be able to see the kind of projects they have done before.
        * I want to be able to contact them.

* Business Owner Goals

    * As a business owner:
        * I want to more customers to find the business.
        * I want customers to check our projects.
        * I want customers to contact us.
        
### Structure

The website consists of 3 pages.

* A landing page/home page with a section having brief description of the business and links to the Photo Gallery and Contact form.
* A Gallery page displaying the highlights of the projects done by the business.
* A Contact page having a fill out form for enquiries and a map showing the location to the store along with store timings.


## Design

### Colour

Keeping in mind the purpose of this website, I have chosen colors close to the ocean and the beach. The background on most pages is Caribbean blue. I have used a font color similar to Ivory to give a good contrast. The fonts over white background is again a different sharde of blue, in orer to manintain contrast and the theme.
I knew I wanted to go with the whole water and ocean theme, so I used googles search engine to help me find some suitable color palettes.  
I have used https://coolors.co/ to generate the palette. 

![color palette](README-docs/color-scheme.JPG)  

### Font

I have used https://fonts.google.com/ for my fonts. I have chosen to use Playfair Display as my main font throughout the website. This is a fairly modern style that is easy to read at various sizes. To increase the readability, I have increased the font sizes at various occasions.

I have used the font Lobster in the header for the website name as it has an underwater kind of feel to it.

I imported the following code into the top of my style.css file

````
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap&family=Playfair+Display&display=swap');
````

### Images

All the images for the website are from https://unsplash.com/. I wanted to keep the hero image very basic, yet very vibrant and inviting, with a large area of base color and not very cluttered. 

The I chose a variety of images for the gallery section, some with just planted fish tanks, some with fresh water fishes and some with marine fishes in order to try and display all the things this business offers.

### Wireframe

I have used balsamiq to create layout mockup of how the website would look. Being the developer and designer of the website, wireframes helped arrange different elements on the webpage to see what appeals the most visually.

![First page wireframe](README-docs/first-page.png)

![Second page wireframe](README-docs/second-page.png)

![Third page wireframe](README-docs/third-page.png)


## Features  

1. The header is visible on all the pages and has a maintained style throughout.  
    * The title of the website is quite clear as to what the business offers.
    * The navigation menu is at the bottom right of the header and clarly indicated the relevant section.
    * The navigation is kept simple on purpose.  

![website header](README-docs/header.JPG)  

2. The main body of the website on the landing page has a hero image and a section for about us.  
    * The hero imaage is chosen appropriate to the aquarium theme and covers all of the page.
    * I have added a parallax effect on scrolling the page on which the about us section becomes visible.  
    * About us section contains few lines on what the business offers and a link to the "Gallery" and the "Contact form" so the visitor does not need to scroll back on top of the page to visit either of the two.  

![hero page body](README-docs/hero-body.JPG)  

3. The footer is visible on all the pages and has a consistent style throughout.  
    * The footer contains icons which are links to social media accounts of the business.
    * When an icon is clicked the social media account opens in a new tab so that the visitors website viewing is not disrupted.  
    * The color of the icons is selected to keep it consistent with the theme of the website.  

![footer](README-docs/footer.JPG)  

4. The Gallery page is a very vibrant page with images of different kinds of fishes and fish tanks on display.  
    * On larger screens the images are arranged in 3 columns, where as on smaller screens it changes to 2 columns for better visibility.
    * The images have a slight pop up effect on hover.  

![gallery](README-docs/gallery.JPG)  

5. The contact us page is designed keeping in mind two things that a customer would want to do. 
    * Send in a query  
    A form allows the website visitors to type in their name, email and query to submit it to the business.  
    The business can then get in touch with the customer by replying back to the email.  

![query form](README-docs/query-form.JPG)  
    * Visit the store  
    A google map with the location of the store pinned on it is availabe for customers who would want to visit the store.  
    The store timings are also mentioned below the map for the customers to check for suitable timings.  

![google map location](README-docs/map-location.JPG)  

## Technologies

### Languages used

* HTML5
* CSS3

### Frameworks, Libraries and Programs used

1. Google Fonts:
    * Google fonts import statements were used as part of this project to make use of the fonts which are used on all pages of the website.
2. Font Awesome:
    * Font Awesome was used on all pages of the website to add social media icons.
3. Gitpod:
    * Gitpod IDE was used for writing and editing code and version control.
4. GitHub:
    * GitHub is used to store the projects code after being pushed from Git.
5. Balsamiq:
    * Balsamiq was used to create the wireframes during the design phase.
6. Compressor.io:
    * Used free version of https://compressor.io/ to compress jpg images.


## Testing  

Since the website is purely built with HTML and CSS , I have made use of the [W3C Markup Validation Service](https://validator.w3.org/) and [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/validator.html.en) to validate HTML and CSS syntax in this project.  

Both the tests **Pass**  
![html validator result](README-docs/html-validator.JPG)  

![css validator result](README-docs/css-validator.JPG)  

I have run the entire website through Chrome's lighthouse audit service and the results are shown below.  

**index.html**  

![lighthouse result index page](README-docs/lighthouse_test_before.JPG)  

In order to increase the Performance , I then compressed the hero image.  
Below is the screenshot taken after the fix was applied.

![lighthouse result after index page](README-docs/lighthouse-desktop-index.JPG)  

**gallery.html**  
**contact.html**  

![lighthouse result contact page](README-docs/lighthouse-desktop-contact-before.JPG)




## Deployment

### Github Pages

This project was developed using the Gitpod IDE and pushed to a Github repository with the use of Git version control.
The project was deployed to GitHub Pages using the following steps.  
1. Login to Github and open the Github Repository.  
2. Within the Repository click on "Settings" from the top menu.  
3. Go to the "Pages" section.  
4. Under the Sources click the dropdown displaying None and select the branch to be deployed ("Main").  
5. Click on the "Save" button.  
6. Deployed link is now generated at the top.  

The website can directly be viewed using this link now.

### Forking Github Repository

To make a copy of the original repository to make changes to it without affecting the original repository follow the below steps.  
1. Login to Github and open the Github Repository.    
2. Within the Repository click on the "Fork" at the right top corner.   

This would have created the same repository in your account.  

 ### Cloning Github Repository

 For creating a clone of this repository follow the below steps.  
1. Login to Github and open the Github Repository.  
2. Click on the Code dropdown above the file list.  
3. Copy the https link shown in the https section.  
4. Open your local terminal/command prompt where git is installed.  
5. Navigate to the location where you want to clone the repository.  
6. Type the command   
     ````
    git clone https://github.com/Pradnya144/Portfolio-Project-1.git
    ````   
The repository is cloned and ready to use.  


## Acknowledgements & Credits

I have looked at a lot of html and css on [W3School](https://www.w3schools.com/) especially the for the parallax scrolling effect on the main page.  
I have looked at a lot of questions and suggestions on [stackoverflow](https://stackoverflow.com/) especially for linking my thank you page after submitting the form.  
For the iframe I have taken the google map location from https://www.maps.ie/create-google-map/ .  
All the images have been taken from [Unsplash](https://unsplash.com/).  
My mentor Brian Macharia, has given me valuable feedback and input during every stage of development of this project.

