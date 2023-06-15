# Adopt-a-Dog Ireland
The Adopt-a-Dog Ireland website was designed to allows the user to Adopt-a-Dog from a dog shelter in Ireland.

![Preview of website on various devices](documentation/responsive-design-screenshot.png)

<div style="text-align: center; font-size: 34px; font-weight: bold; text-decoration: underline ">

[Adopt-a-Dog Ireland Website](https://garydolan.github.io/ci-p1-adopt-a-dog-ireland/)

</div>

# Table of Contents
1. [Introduction](#adopt-a-dog-ireland)
2. [User Experience](#user-experience)
    * [Initial Discussion](#initial-discussion)
    * [User stories](#user-stories)
3. [Design](#design)
    * [Colour scheme](#colour-scheme)
    * [Typography](#typography)
    * [Icon creation](#icon-creation)
    * [Imagery](#imagery)
    * [Wireframes](#wireframes)
4. [Features](#features)
    * [Future implementations](#future-implementations)
    * [Accessibility](#accessibility)
5. [Technologies used](#technologies-used)
    * [Languages](#languages)
    * [Version control](#version-control)
    * [Programs](#programs)
    * [Tools](#tools)
6. [Deployment & Local Deployment](#deployment--local-deployment)
    * [Deployment](#deployment)
    * [Local Deployment](#local-deployment)
        * [How to Fork](#how-to-fork)
        * [How to Clone](#how-to-clone)
7. [Testing](#testing)
    * [Automated testing](#automated-testing)
    * [Manual testiing](#manual-testiing)
    * [Bugs](#bugs)
8. [Design & Development issues](#design--development-issues)
    * [Index page](#index-page)
    * [Dog profile page](#dog-profile-page)
    * [About us page](#about-us-page)
9. [Credits](#credits)
    * [Copy](#copy)
    * [Acknowledgements](#acknowledgements)

# User Experience

## Initial Discussion
Adopt-a-Dog Ireland is a website that I (Gary Dolan) developed for my first project as part of Code Institutes Diploma in Full Stack Software Development. The websites target audience is people interested in adopting a dog in Ireland. It was designed to allow prospective dog adopters to browser a catalogue of adoptable dogs. The website will provide the user with all the adoptable dogs details and also guide the user through the adoption process. It will allow the user to apply to adopt a dog of their choice.

## User stories

### Owner / Client goals
* To ensure the user can easily and intuitively use and navigate the website.
* To create a website that encourages first time learning, keeping consistant navigation, coloring and imagery site wide.
* To create a website that promotes feelings of positivity and trust in the user, using coloring, imagery and light hearted and informal text.
* To allow users to browse a catalogue of dogs available for adoption at the shelter. 
* To ensure the processes & steps involved in dog adoption are conveyed clearly to the user.
* To make it easy and straightforward for the user to apply to adopt a dog.
* To create a website which is viewable on a large array of devices.
* To instill a sense of family values in the website to bolster a high level of trust and comfort in the user. 
* To make it easy for the user to find and contact the shelter. 
* To create a high level of user feedback on the website, ensuring the user knows where they can and when the have interacted with the website.
* To create a website with a high level of accessibility so that all users regardless of capacity can access and use our services. 
* To create brand awareness via the website and social networks to drive business to the shelter.
* To use our increased awareness to generate add revenue. 
* To eventually partner with companies that sell products targeted at dogs. Initially targeting companies like "Big Gain" dog food,  "Chuckit" dog toys, "Halti" dog harnesses, "Hunter" dog beds, "Kong" dog toys and "Soopa" dog treats. 

### First time visitor goals
* I want to view dogs that are available for adoption.
* I want to get a feel for the dogs personalities and know their details.
* I want to understand how to adopt a dog.
* I want to apply to adopt a chosen dog directly from the website.
* I want to be able to learn about the shelter and have access to their social networks.

### Returning visitor goals 
* I want to view dogs that are available for adoption.
* I want to get a feel for the dogs personalities and know their details.
* I want to apply to adopt a dog directly from the website.
* I want to be able to find the shelter contact details and location. 
* I want to access the shelters social networks.


# Design
## Colour scheme
The primary objective I wanted to achieve with my color scheme was to invoke happiness in the user. Although the process of dog adoption can have some negative aspects, I wanted to focus on making the user feel positive and optimistic when on the website.  

The secondary objective for my color scheme was to instill a sense of trust in our users regarding our service. Dog adoption is a big decision and I want the user to know they are in good hands, so they can focus on the positive elements and leave the rest to us.

Although I wanted to use bright colours, I was also aware of the fact that I wanted to place a large amount of my content on white background. Due to this I wanted to take into account the accessibility of the colour scheme and choose darker version of some colors to insure there would be good contrast between them and a white background or text. 

To select my color palette I used [Color HEX](https://www.color-hex.com/) and took inspiration from one of their happy color palettes, specifically [this one](https://www.color-hex.com/color-palette/13743). The colors from this pallet were adjusted to ensure compliance with WCAG AAA standards. I also used [Coolors](https://coolors.co/) to visualise my palette. 

![Colour Palette](documentation/color-palette.png)

* #E1C418: This is one of my primary colors chosen to invoke happiness.
* #1C345E: This is another one of my primary colours chosen to invoke Trust.
* #2E4A52: This is one of my secondary colours intended for elements which require user feedback.
* #595454: This is another of my secondary colors. I felt it was important to has a dark color as it may be needed for contrast. 
* #B85C00: This is a color I chose for all my calls to action. It is intentionally different to the rest of my color scheme to draw the attention of the user. I again like with other colors, Iintentionally selected a duller shade of orange to ensure good contrast and accessibility.

In the end I did not use #595454 or #B85C00 and opted to use #1C345E with different levels of opacity.

All intended color combination from my pallet were tested on [Webaim](https://webaim.org/resources/contrastchecker/) and [Accessible web](https://accessibleweb.com/color-contrast-checker/) to ensure compliance with WCAG AAA standards.

The test for #B85C00 did fail the AAA check for normal text but I decided to still use it because it's only use would be on the site buttons which all contain large bold text and thus are WCAG AAA compliant. 


## Typography
When considering fonts, I used a combination of [Google fonts](https://fonts.google.com/) to research fonts, [Font joy](https://fontjoy.com/) to compare various fonts and [Chat GPT](https://openai.com/blog/chatgpt) to make font suggestions. The step below show how I arrived at my final choice. 

I Initially considered a combination of Oswald (which I liked from the love running walkthrough) for headings and Roboto for body text but found Roboto too heavy for body text.

![Comparsion of Oswald and Robto fonts](/documentation/fonts/font-oswald-roboto.png)

I then examined Oswald for heading with Raleway as a body text. When I switched these making Raleway the heading I much preferred it, but now found Oswald’s aspect ratio too high for body text making the characters look elongated and harder to read. 

![Comparsion of Oswald and Robto fonts](/documentation/fonts/font-raleway-oswald.png)

Having settled on Raleway as a heading and knowing I wanted a lightweight font for the body, I used chat GPT prompts to suggest lighter font pairings, based on Raleway as a heading. Trying all suggested fonts on fontjoy, I narrowed it down to Lato or Lora. In the end I chose to use Lora as I felt it better paired with Raleway and would be more accessible for visually impaired readers due to its larger spacing. 

![Comparsion of Oswald and Robto fonts](/documentation/fonts/font-raleway-lora.png)

The fonts were selected with accessibility and ease of use in mind. All fonts were will be imported using [Google fonts](https://fonts.google.com/).

## Icon creation
I decided that I wanted to create a custom icon for the website. I used two silhouettes from [Pixabay](https://pixabay.com/) specifically [this one](https://pixabay.com/vectors/home-black-house-building-simple-155128/) and [this one](https://pixabay.com/illustrations/silhouette-dog-animal-pet-simple-313610/). I then modified these images to create my logo using Inkscape, a fee open-source vector graphics editor.

![Comparsion of Oswald and Robto fonts](/documentation/logo.png)


## Imagery
All imagery for the website was taken from [Pixabay](https://pixabay.com). They were cut, resized and formats changed as required. With the exception of the 404 page image (which was purposely selected to look sad) all the image for the website were picked to convey happiness, fun and excite the user about the prospect of adopting a dog.
*[Image 1](https://pixabay.com/photos/golden-retriever-dog-pet-canine-4292254/)
*[Image 2](https://pixabay.com/photos/dog-puppy-canine-pet-animal-cute-6527479/)
*[Image 3](https://pixabay.com/photos/dog-corgi-cute-animal-4988986/)
*[Image 4](https://pixabay.com/photos/australian-shepherd-dog-7176981/)
*[Image 5](https://pixabay.com/photos/puppy-dog-mammal-cute-small-5124947/)
*[Image 6](https://pixabay.com/photos/german-longhaired-pointer-dog-pet-782498/)
*[Image 7](https://pixabay.com/photos/dog-beach-sea-domestic-animal-7956828/)
*[Image 8](https://pixabay.com/photos/english-bulldog-dog-sweet-charming-5422018/)
*[Image 9](https://pixabay.com/photos/dog-pet-canine-animal-fur-snout-3385541/)
*[Image 10](https://pixabay.com/photos/dog-puppy-pet-doggy-cute-sweet-2563759/)
*[Image 11](https://pixabay.com/photos/child-dog-nature-children-5334516/)
*[Image 12](https://pixabay.com/photos/autumn-dog-nature-leaves-fall-pet-4470022/)
*[Image 13](https://pixabay.com/photos/dog-puppy-pet-animal-cute-canine-1411397/)
## Wireframes
All the wireframes for the website we created using the Balsamic desktop application. They were also created for specific breakpoint, which I took from [W3schools](https://www.w3schools.com/css/css_rwd_mediaqueries.asp). Althought I did design my wireframes for these breakpoints, some were changed and some were added, as I developed the website.

<details>

<summary style="font-size: 20px; font-weight: bold;">PC – Large devices (1200px up)</summary>

#### Index page
![Index wireframe](/documentation/Wireframes/1200px/index-1200px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/Wireframes/1200px/dog-profile-1200px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/Wireframes/1200px/adopt-a-dog-1200px.png)

#### Our Partners page
![Our partners wireframe](/documentation/Wireframes/1200px/our-partners-1200px.png)

#### About Us page
![About Us wireframe](/documentation/Wireframes/1200px/about-us-1200px.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">PC – Standard (992px to 1199px)</summary>

#### Index page
![Index wireframe](/documentation/Wireframes/992px/index-992px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/Wireframes/992px/dog-profile-992px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/Wireframes/992px/adopt-a-dog-992px.png)

#### Our Partners page
![Our partners wireframe](/documentation/Wireframes/992px/our-partners-992px.png)

#### About Us page
![About Us wireframe](/documentation/Wireframes/992px/about-us-992px.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Tablet – Landscape (768x to 991px)</summary>

#### Index page
![Index wireframe](/documentation/Wireframes/768px/index-768px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/Wireframes/768px/dog-profile-768px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/Wireframes/768px/adopt-a-dog-768px.png)

#### Our Partners page
![Our partners wireframe](/documentation/Wireframes/768px/our-partners-768px.png)

#### About Us page
![About Us wireframe](/documentation/Wireframes/768px/about-us-768px.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Tablet – Portrait & Large phones (600x to 767px)</summary>

#### Index page
![Index wireframe](/documentation/Wireframes/600px/index-600px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/Wireframes/600px/dog-profile-600px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/Wireframes/600px/adopt-a-dog-600px.png)

#### Our Partners page
![Our partners wireframe](/documentation/Wireframes/600px/our-partners-600px.png)

#### About Us page
![About Us wireframe](/documentation/Wireframes/600px/about-us-600px.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Mobile – Standard phones (320px to 599px)</summary>

#### Index page
![Index wireframe](/documentation/Wireframes/320px/index-320px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/Wireframes/320px/dog-profile-320px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/Wireframes/320px/adopt-a-dog-320px.png)

#### Our Partners page
![Our partners wireframe](/documentation/Wireframes/320px/our-partners-320px.png)

#### About Us page
![About Us wireframe](/documentation/Wireframes/320px/about-us-320px.png)

</details>

# Features
## Future implementations
## Accessibility


# Technologies used
## Languages
## Version control
## Programs
## Tools

# Deployment & Local Deployment
## Deployment
## Local Deployment
### How to Fork
### How to Clone


# Testing
## Automated testing
## Manual testiing
## Bugs


# Design & Development issues
## Index page
## Dog profile page
## About us page


# Credits
## Copy
## Acknowledgements

