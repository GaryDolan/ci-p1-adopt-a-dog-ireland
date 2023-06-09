# Adopt-a-Dog Ireland
The Adopt-a-Dog Ireland website was designed to allow the user to Adopt-a-Dog from a dog shelter in Ireland.

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
    * [Common to all](#common-to-all-pages)
    * [Home Page](#home-page)
    * [Dog profile page](#dog-profile-page)
    * [Adopt a dog page](#adopt-a-dog-page)
    * [About us page](#about-us-page)
    * [From complete page](#form-complete-page)
    * [404 page](#404-page)
    * [Future Implementations](#future-implementations)
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
    * [Lighthouse testiing](#lighthouse-testing)
    * [User story testing](#user-story-testing)
    * [Bugs](#bugs)
8. [Design & Development issues](#design--development-issues)
    * [Index page issue](#index-page-issue)
    * [Dog profile page issue](#dog-profile-page-issue)
    * [About us page issue](#about-us-page-issue)
9. [Credits](#credits)
    * [Copy](#copy)
    * [Imagery](#imagery)
    * [Acknowledgements](#acknowledgements)

# User Experience

## Initial Discussion
Adopt-a-Dog Ireland is a website that I (Gary Dolan) developed for my first project as part of Code Institutes Diploma in Full Stack Software Development. The websites target audience is people interested in adopting a dog in Ireland. It was designed to allow prospective dog adopters to browse a catalogue of adoptable dogs. The website will provide the user with all the adoptable dogs details and also guide the user through the adoption process. It will allow the user to apply to adopt a dog of their choice.

## User stories

### Owner / Client goals
* To ensure the user can easily and intuitively use and navigate the website.
* To create a website that encourages first time learning, keeping consistent navigation, colouring and imagery site wide.
* To create a website that promotes feelings of positivity and trust in the user, using colouring, imagery and light hearted and informal text.
* To allow users to browse a catalogue of dogs available for adoption at the shelter. 
* To ensure the processes & steps involved in dog adoption are conveyed clearly to the user.
* To make it easy and straightforward for the user to apply to adopt a dog.
* To create a website which is viewable on a large array of devices.
* To instil a sense of family values in the website to bolster a high level of trust and comfort in the user. 
* To make it easy for the user to find and contact the shelter. 
* To create a high level of user feedback on the website, ensuring the user knows where they can and when the have interacted with the website.
* To create a website with a high level of accessibility so that all users regardless of capacity can access and use our services. 
* To create brand awareness via the website and social networks to drive business to the shelter.
* To use our increased awareness to generate add revenue. 
* To eventually partner with companies that sell products targeted at dogs. Initially targeting companies like "Big Gain" dog food, "Chuckit" dog toys, "Halti" dog harnesses, "Hunter" dog beds, "Kong" dog toys and "Soopa" dog treats. 

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

[Return to Table of Contents](#table-of-contents)

# Design
## Colour scheme
The primary objective I wanted to achieve with my colour scheme was to invoke happiness in the user. Although the process of dog adoption can have some negative aspects, I wanted to focus on making the user feel positive and optimistic when on the website.  

The secondary objective for my colour scheme was to instil a sense of trust in our users regarding our service. Dog adoption is a big decision and I want the user to know they are in good hands, so they can focus on the positive elements and leave the rest to us.

Although I wanted to use bright colours, I was also aware of the fact that I wanted to place a large amount of my content on white background. Due to this I wanted to take into account the accessibility of the colour scheme and choose darker versions of some colours to ensure there would be good contrast between them and a white background or text. 

To select my colour palette I used [Color HEX](https://www.color-hex.com/) and took inspiration from one of their happy color palettes, specifically [this one](https://www.color-hex.com/color-palette/13743). The colors from this pallet were adjusted to ensure compliance with WCAG AAA standards. I also used [Coolors](https://coolors.co/) to visualise my palette. 

![Colour Palette](documentation/color-palette.png)

* #E1C418: This is one of my primary colours chosen to invoke happiness.
* #1C345E: This is another one of my primary colours chosen to invoke Trust.
* #2E4A52: This is one of my secondary colours intended for elements which require user feedback.
* #595454: This is another of my secondary colours. I felt it was important to has a dark color as it may be needed for contrast. 
* #B85C00: This is a colour I chose for all my calls to action. It is intentionally different to the rest of my colour scheme to draw the attention of the user. I again, like with other colours, Intentionally selected a duller shade of orange to ensure good contrast and accessibility.

In the end I did not use #595454 or #B85C00 and opted to use #1C345E with different levels of opacity.

All intended colour combination from my pallet were tested on [Webaim](https://webaim.org/resources/contrastchecker/) and [Accessible web](https://accessibleweb.com/color-contrast-checker/) to ensure compliance with WCAG AAA standards.

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

![Custom Icon](/documentation/Logo.png)

## Imagery
All imagery for the website was taken from [Pixabay](https://pixabay.com). They were cut, resized and formats changed as required. With the exception of the 404 page image (which was purposely selected to look sad) all the image for the website were picked to convey happiness, fun and excite the user about the prospect of adopting a dog.
* [Image 1](https://pixabay.com/photos/golden-retriever-dog-pet-canine-4292254/)
* [Image 2](https://pixabay.com/photos/dog-puppy-canine-pet-animal-cute-6527479/)
* [Image 3](https://pixabay.com/photos/dog-corgi-cute-animal-4988986/)
* [Image 4](https://pixabay.com/photos/australian-shepherd-dog-7176981/)
* [Image 5](https://pixabay.com/photos/puppy-dog-mammal-cute-small-5124947/)
* [Image 6](https://pixabay.com/photos/german-longhaired-pointer-dog-pet-782498/)
* [Image 7](https://pixabay.com/photos/dog-beach-sea-domestic-animal-7956828/)
* [Image 8](https://pixabay.com/photos/english-bulldog-dog-sweet-charming-5422018/)
* [Image 9](https://pixabay.com/photos/dog-pet-canine-animal-fur-snout-3385541/)
* [Image 10](https://pixabay.com/photos/dog-puppy-pet-doggy-cute-sweet-2563759/)
* [Image 11](https://pixabay.com/photos/child-dog-nature-children-5334516/)
* [Image 12](https://pixabay.com/photos/autumn-dog-nature-leaves-fall-pet-4470022/)
* [Image 13](https://pixabay.com/photos/dog-puppy-pet-animal-cute-canine-1411397/)


## Wireframes
All the wireframes for the website we created using the Balsamic desktop application. They were also created for specific breakpoint, which I took from [W3schools](https://www.w3schools.com/css/css_rwd_mediaqueries.asp). Although I did design my wireframes for these breakpoints, some were changed and some were added, as I developed the website.

<details>

<summary style="font-size: 20px; font-weight: bold;">PC – Large devices (1200px up)</summary>

#### Index page
![Index wireframe](/documentation/wireframe/1200px/index-1200px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/wireframe/1200px/dog-profile-1200px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/wireframe/1200px/adopt-a-dog-1200px.png)

#### Our Partners page
![Our partners wireframe](/documentation/wireframe/1200px/our-partners-1200px.png)

#### About Us page
![About Us wireframe](/documentation/wireframe/1200px/about-us-1200px.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">PC – Standard (992px to 1199px)</summary>

#### Index page
![Index wireframe](/documentation/wireframe/992px/index-992px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/wireframe/992px/dog-profile-992px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/wireframe/992px/adopt-a-dog-992px.png)

#### Our Partners page
![Our partners wireframe](/documentation/wireframe/992px/our-partners-992px.png)

#### About Us page
![About Us wireframe](/documentation/wireframe/992px/about-us-992px.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Tablet – Landscape (768x to 991px)</summary>

#### Index page
![Index wireframe](/documentation/wireframe/768px/index-768px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/wireframe/768px/dog-profile-768px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/wireframe/768px/adopt-a-dog-768px.png)

#### Our Partners page
![Our partners wireframe](/documentation/wireframe/768px/our-partners-768px.png)

#### About Us page
![About Us wireframe](/documentation/wireframe/768px/about-us-768px.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Tablet – Portrait & Large phones (600x to 767px)</summary>

#### Index page
![Index wireframe](/documentation/wireframe/600px/index-600px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/wireframe/600px/dog-profile-600px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/wireframe/600px/adopt-a-dog-600px.png)

#### Our Partners page
![Our partners wireframe](/documentation/wireframe/600px/our-partners-600px.png)

#### About Us page
![About Us wireframe](/documentation/wireframe/600px/about-us-600px.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Mobile – Standard phones (320px to 599px)</summary>

#### Index page
![Index wireframe](/documentation/wireframe/320px/index-320px.png)

#### Dog Profile page
![Dog profile wireframe](/documentation/wireframe/320px/dog-profile-320px.png)

#### Adopt-a-Dog page
![Adopt a dog wireframe](/documentation/wireframe/320px/adopt-a-dog-320px.png)

#### Our Partners page
![Our partners wireframe](/documentation/wireframe/320px/our-partners-320px.png)

#### About Us page
![About Us wireframe](/documentation/wireframe/320px/about-us-320px.png)

</details>


[Return to Table of Contents](#table-of-contents)

# Features
The website contains 15 pages in total. There is one home page, an adopt a dog page, an about us page, a form complete page, a 404 page and 10 dog profile pages. The website is fully responsive and will work on a range of devices. 

## Common to all pages
### Header
The header is a common feature across every page on the website. It consists of a custom logo containing an image and text and the navigation section. The custom logo is clickable and will return the user to the home page regardless of where on the site they are. The navigation section has four main links, Home, Dog profiles, Adopt a dog and about us. Each link will drive the user to the corresponding section of the website. The nav bar also contains some user feedback, as the user hovers over any item it will change colour and become underlined. 

![Image of the header](/documentation/features/header.png)

![Image of the header mobile](/documentation/features/header-mobile.png)

### Footer
The footer is also a feature that is common across all pages of the website. The footer holds icon links to all of the different social networking platforms as well as a copyright. The icons are a deep yellow colour to draw the users attention. All icons in the footer also provide feedback to the user and change colour to indicate they are clickable. When clicked the links will open in new tabs to ensure the user still has access to our website.

![Image of the footer](/documentation/features/footer.png)

![Image of the footer mobile](/documentation/features/footer-mobile.png)

## Home page
The home page consists of a hero image and two sections, they are the how it works section and the browse our dogs section.

### Hero image
The hero image is a large image that acts as a banner for the page. The image is of a young girl, lovingly looking at and petting her dog. The dog in the picture also looks very happy. The image is suppose to bolster a sense of positivity about the website and dog adoption process. The hero image also has an animation attached to it and the image will zoom in 10% when the page loads. On mobile the hero image will be switch to a smaller image. 

![Image of the hero image](/documentation/features/home-hero-image.png)

![Image of the hero image mobile](/documentation/features/home-hero-image-mobile.png)

### How it works
The how it works sections purpose is to explain to the user how the process of dog adoption is carried out and the steps that are involved. The section uses bright eye catching icons to draw the users attention. There are six icons which indicate, without having to read what the steps will be. Each icon is accompanied by a small piece of text explaining that step. 

![how it works section](/documentation/features/home-how-it-works.png)

![how it works section mobile](/documentation/features/home-how-it-works-mobile.png)
### Browse our dogs
The second section of the home page is the browse our dogs section. To create a good user experience we want the user to get to the dogs as fast as possible, as it is the reason they are here. The section consists of ten dog images arranged neatly in rows and columns. The pictures are circular, which is common across the website. Under each dogs picture is a button which allows the user to visit the dogs profile when clicked. The button design is a burned orange colour which stands out from all the other site colours as a call to action. It will also provide feedback to the user on hover, changing background, text and border colours. This button is again consistent across the website.

![browse our dogs section](/documentation/features/home-browse-our-dogs.png)

![browse our dogs section mobile](/documentation/features/home-browse-our-dogs-mobile.png)

## Dog profile pages
The purpose of the dog profile page is to allow the user to learn a little more about the dogs before they make their decisions. It consists of a larger banner with the dogs name, an image of the dog, the dog details and a button saying adopt me. When pressed it will drive the user to the adopt a dog page. The page also has prev and next buttons to allow the user to browse through the dogs without leaving the page. 

![Dog profile](/documentation/features/dog-profile.png)

![Dog profile mobile](/documentation/features/dog-profile-mobile.png)

## Adopt a dog page
The adopt a dog page is a page with a form on it, which allows the users to apply to adopt a dog. It is responsive and will scale down to mobile, at which point the image will be moved to the background. The form consists of various user inputs which are required to proceed. The user will be given directions regarding the correct formats for each input and will be informed if incorrect or missing. The form submit button will drive the user to the form complete page.

![Adopt a dog page](/documentation/features/adopt-a-dog-page.png)

![Adopt a dog page mobile](/documentation/features/adopt-a-dog-page-mobile.png)


## About us page
The about us page has three main sections, about us, meet the team and our details. The about us section is a small paragraph about the shelter. The meet the team section introduces the user to the team. It is purposefully light hearted, fun and promotes a sense of family. This is done in the effort to make the user trust us and feel comfortable. The final section, our details, is a google map link to the location of the shelter, the address, phone number and email. The google map is fully functional.

![Adbout us ](/documentation/features/about-use-meet-team.png)

![about us 2](/documentation/features/about-use-meet-team2.png)

## Form complete page
The form complete page is where the user is driven after they complete an application to adopt a dog. It is used as feedback to let the user know the application has gone through. It is simply a page with an image, some text and a button to return home.

![Form complete](/documentation/features/form-complete.png)

![Form complete](/documentation/features/form-complete-mobile.png)

## 404 page
The 404 page is the page the user will be directed to if they try to visit a page that doesn't exist. Again it is used as feedback to let the user know that something has gone wrong and provide them with a home button back to safety

![404 page](/documentation/features/404-img.png)

![404 page](/documentation/features/404-img-mobile.png)


## Future implementations
In the future I would like to add the following features to the website,
* Update the purpose of the website to include the possibility for people to surrender their dog for adoption, adding all the relevant pages forms etc. 
* Add the ability for users to help Adopt-a-Dog Ireland by volunteering, donating, holding events etc.
* Add a detailed help and advice section that the user could visit at all stages of the adoption process. This section would have subsections that would provide the user with relevant information and advice based on their stage in the adoption process (before, during, after).
* Add a success stories / Gallery section to the website that showcases stories and images of adopted dogs and their happy owners. The purpose of this section would be to encourage potential dog adopters to undertake the adoption process by showing them how well it has worked for others.  
* Add a Partners page promoting brands we trust, special offers etc.. I had planned to add this section during my initial design and wireframe stage but decided to remove it. I did this due to concerns over copyright infringement. The images I would need to use for this page would be copywritten. I spoke to my cohort facilitator who seemed to think it would be fine but my mentor advised against using copywritten material so I scrapped the page. 

## Accessibility
I was conscious of accessibility throughout the entire website development process and took the following steps to ensure that the website would be as accessible as possible

* Used as much semantic HTML as possible, where relevant.
* Choose the website colours carefully ensuring I used colours that were compliant to the highest standards and provided excellent contrast.
* Used alt attributes and aria labels where applicable. 
* Where I could not use alts or labels I added descriptive text for screen readers. I used CSS to hide this text from site.

[Return to Table of Contents](#table-of-contents)

# Technologies used
## Languages
* HTML - Used to add website content and structure.
* CSS - Used to style the website content.

## Version control
* Git commands - Used via windows powershell (using Posh-Git module) 
* Github.com. - Repository created using code institute student template 
* Github desktop - Used as a local visual aid between pushing to master. It offers a clean view of all code changes since last commit, commit history etc.

## Programs
* Microsoft Visual Studio Code 
* Inkscape for logo creation and image editing
* Notepad ++
* Balsamiq desktop for creation of wireframes

## Tools
* [Color hex](https://www.color-hex.com/) was used to select the colour palette I used.
* [Coolors](https://coolors.co/) was used to visualise colour palettes.
* [Webaim](https://webaim.org/resources/contrastchecker/) was used to ensure colour palette is compliant. 
* [Google fonts](https://fonts.google.com/) was used to research and import fonts.
* [Font joy](https://fontjoy.com/) was used to compare various fonts.
* [Font awesome](https://fontawesome.com/) was used to import font icons.
* [Chat GPT](https://openai.com/blog/chatgpt) was used to make font pairing suggestions and copy suggestions (copy was usually re-written by me).
* [Pixabay](https://pixabay.com) was used as a source for images used on the website and images to create the website logo.
* [Tiny png](https://tinypng.com/) was used to compress images.
* [Birme](https://www.birme.net) was used to change image formats and resize images.
* [Flex box froggy](https://flexboxfroggy.com/) was used to figure out flexbox. Excellent resource, highly recommended.
* [Google](https://www.google.ie/), [Youtube](https://www.youtube.com/) and [wW3schools](https://www.w3schools.com) were used throughout the website development to help solve issues when stuck etc. 
* [Google Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) used to test the websites performance, accessibility etc.
* [W3C CSS validator](https://jigsaw.w3.org/css-validator/) used to validate the CSS
* [W3C HTML validator](https://validator.w3.org/nu/) used to validate the HTML
* Google and firefox build in dev tools user to test and examine code

[Return to Table of Contents](#table-of-contents)


# Deployment & Local Deployment
## Deployment
Github pages was used to deploy this website. To deploy a website using github pages, do the following,

1. Log into or signup at [Github](https://github.com).
2. Find the correct repository and select it.
3. Select the settings icon from the menubar.
4. Select the pages option from the left hand menu.
5. In the source dropdown box select main.
6. Click the save button.
7. The website is now deployed using github pages and when ready (can take a minute) a link will appear at the top of the page for your website. 

## Local Deployment
### How to Fork
To fork this repository,
1. Log into or signup at [Github](https://github.com).
2. Select the repository for this website
3. Click the fork button (upper right).
### How to Clone
To clone this repository,
1. Log into or signup at [Github](https://github.com).
2. Select the repository for this website
3. Click the green code button (upper right).
4. Copy the URL using the copy button. 
5. Open the terminal in your editor (or of your choosing) and move to the directory which you want to clone to.
6. Type git clone and paste the repository link, then press enter.

# Testing
Testing of the website was ongoing throughout the development process. I used the developer tools in chrome and firefox to test all aspect of the site including its responsiveness.  
## Automated testing
The automated testing of the website HTML code was carried out using [Validator w3](https://validator.w3.org/nu/), all html pages passed without any errors or warnings, the results are shown below 

* [404.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2F404.html)  
* [about-us.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fabout-us.html)
* [adopt-a-dog.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fadopt-a-dog.html)
* [bruno-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fbruno-profile.html)
* [charlie-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fcharlie-profile.html)
* [cooper-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fcooper-profile.html)
* [daisy-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fdaisy-profile.html)
* [form-complete.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fform-complete.html)
* [hercules-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fhercules-profile.html)
* [hugo-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fhugo-profile.html)
* [index.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Findex.html)
* [lily-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Flily-profile.html)
* [lucy-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Flucy-profile.html)
* [max-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Fmax-profile.html)
* [toby-profile.html results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2Ftoby-profile)

The website CSS was validated using [W3C CSS validator](https://jigsaw.w3.org/css-validator/). The website passed with no errors or warnings and the test results can be seen below.
[CSS Test Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fgarydolan.github.io%2Fci-p1-adopt-a-dog-ireland%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

## Manual testiing
The tests for this website listed below were conducted on a number of browsers (google chrome, mozilla firefox, microsoft edge, samsung internet) across various devices (msi laptop with large screen attached, surface pro, Huawei P30 Pro). I also tested the websites responsive design using the developer tools on chrome and firefox to ensure it responded as intended.

### Home page tests
| Test                             | Expected Result                  | Pass |
|----------------------------------|----------------------------------|------|
|Logo function                     |Sends user to home page           |   Y  |
|Nav bar link feedback             |Nav changes colour and underline  |   Y  |
|Footer icon feedback              |Colour change                     |   Y  |
|Footer icon function              |Open correct site in new window   |   Y  |
|Responsive design @ 1600px        |All media query rules are applied |   Y  |
|Responsive design @ 1300px        |All media query rules are applied |   Y  |
|Responsive design @ 1100px        |All media query rules are applied |   Y  |
|Responsive design @ 992px         |All media query rules are applied |   Y  |
|Responsive design @ 850px         |All media query rules are applied |   Y  |
|Responsive design @ 700px         |All media query rules are applied |   Y  |
|Responsive design @ 600px         |All media query rules are applied |   Y  |
|Responsive design @ 500px         |All media query rules are applied |   Y  |
|Hero image zoom                   |Zooms by 10% on page load         |   Y  |
|Dog buttons feedback              |Colours reverse                   |   Y  |
|Dog buttons function              |Send user to correct profile      |   Y  |


### Dog profiles tests x 10
| Test                             | Expected Result                  | Pass |
|----------------------------------|----------------------------------|------|
|Logo function                     |Sends user to home page           |   Y  |
|Nav bar link feedback             |Nav changes color and underline   |   Y  |
|Footer icon feedback              |Colour change                     |   Y  |
|Footer icon function              |Open correct site in new window   |   Y  |
|Responsive design @ 1600px        |All media query rules are applied |   Y  |
|Responsive design @ 1300px        |All media query rules are applied |   Y  |
|Responsive design @ 1100px        |All media query rules are applied |   Y  |
|Responsive design @ 992px         |All media query rules are applied |   Y  |
|Responsive design @ 850px         |All media query rules are applied |   Y  |
|Responsive design @ 700px         |All media query rules are applied |   Y  |
|Responsive design @ 600px         |All media query rules are applied |   Y  |
|Responsive design @ 500px         |All media query rules are applied |   Y  |
|Prev & next button feedback       |Colour change                     |   Y  |
|Prev & next button function       |Sends user to correct profile     |   Y  |
|Adopt me button feedback          |Colour change                     |   Y  |
|Adopt me button function          |Sends user to adopt a dog page    |   Y  |


### Adopt a dog page tests
| Test                             | Expected Result                  | Pass |
|----------------------------------|----------------------------------|------|
|Logo function                     |Sends user to home page           |   Y  |
|Nav bar link feedback             |Nav changes colour and underline  |   Y  |
|Footer icon feedback              |Colour change                     |   Y  |
|Footer icon function              |Open correct site in new window   |   Y  |
|Responsive design @ 1600px        |All media query rules are applied |   Y  |
|Responsive design @ 1300px        |All media query rules are applied |   Y  |
|Responsive design @ 1100px        |All media query rules are applied |   Y  |
|Responsive design @ 992px         |All media query rules are applied |   Y  |
|Responsive design @ 850px         |All media query rules are applied |   Y  |
|Responsive design @ 700px         |All media query rules are applied |   Y  |
|Responsive design @ 600px         |All media query rules are applied |   Y  |
|Responsive design @ 500px         |All media query rules are applied |   Y  |
|User input cell feedback          |Colour change                     |   Y  |
|User input cell validation        |Each cell must have correct format|   Y  |
|User input cell message           |Message shown on hover            |   Y  |
|Drop down list function           |All dogs listed & selectable      |   Y  |
|Radio button function             |All can be selected, one at a time|   Y  |
|Apply button restriction          |If any cell empty, no go          |   Y  |
|Apply button feedback             |colour change                     |   Y  |
|Apply button function             |Sends user to form complete page  |   Y  |



### About us page tests
| Test                             | Expected Result                  | Pass |
|----------------------------------|----------------------------------|------|
|Logo function                     |Sends user to home page           |   Y  |
|Nav bar link feedback             |Nav changes colour and underline  |   Y  |
|Footer icon feedback              |Colour change                     |   Y  |
|Footer icon function              |Open correct site in new window   |   Y  |
|Responsive design @ 1600px        |All media query rules are applied |   Y  |
|Responsive design @ 1300px        |All media query rules are applied |   Y  |
|Responsive design @ 1100px        |All media query rules are applied |   Y  |
|Responsive design @ 992px         |All media query rules are applied |   Y  |
|Responsive design @ 850px         |All media query rules are applied |   Y  |
|Responsive design @ 700px         |All media query rules are applied |   Y  |
|Responsive design @ 600px         |All media query rules are applied |   Y  |
|Responsive design @ 500px         |All media query rules are applied |   Y  |
|Video feedback                    |border and colour change          |   Y  |
|Video functionality               |Video plays, all controls function|   Y  |
|Video playback                    |Video does not auto play          |   Y  |
|Google maps functionality         |All controls function correctly   |   Y  |


### Form complete page tests
| Test                             | Expected Result                  | Pass |
|----------------------------------|----------------------------------|------|
|Logo works correctly              |Sends user to home page           |   Y  |
|Nav bar link feedback             |Nav changes colour and underline  |   Y  |
|Footer icon feedback              |Open correct site in new window   |   Y  |
|Responsive design @ 1600px        |All media query rules are applied |   Y  |
|Responsive design @ 1300px        |All media query rules are applied |   Y  |
|Responsive design @ 1100px        |All media query rules are applied |   Y  |
|Responsive design @ 992px         |All media query rules are applied |   Y  |
|Responsive design @ 850px         |All media query rules are applied |   Y  |
|Responsive design @ 700px         |All media query rules are applied |   Y  |
|Responsive design @ 600px         |All media query rules are applied |   Y  |
|Responsive design @ 500px         |All media query rules are applied |   Y  |
|Home button feedback              |colour change                     |   Y  | 
|Home button functionality         |User sent to home page            |   Y  |

### 404 page tests
| Test                             | Expected Result                  | Pass |
|----------------------------------|----------------------------------|------|
|Logo works correctly              |Sends user to home page           |   Y  |
|Nav bar link feedback             |Nav changes colour and underline  |   Y  |
|Footer icon feedback              |Open correct site in new window   |   Y  |
|Responsive design @ 1600px        |All media query rules are applied |   Y  |
|Responsive design @ 1300px        |All media query rules are applied |   Y  |
|Responsive design @ 1100px        |All media query rules are applied |   Y  |
|Responsive design @ 992px         |All media query rules are applied |   Y  |
|Responsive design @ 850px         |All media query rules are applied |   Y  |
|Responsive design @ 700px         |All media query rules are applied |   Y  |
|Responsive design @ 600px         |All media query rules are applied |   Y  |
|Responsive design @ 500px         |All media query rules are applied |   Y  |
|Home button feedback              |colour change                     |   Y  | 
|Home button functionality         |User sent to home page            |   Y  |


## Lighthouse testing
The google lighthouse chrome developer tool was used to test the website performance, accessibility, best practices and Search engine optimisation. For all tests on all pages (both desktop and mobile) the website scored very well. all results can be seen below 

<details>

<summary style="font-size: 20px; font-weight: bold;">404 </summary>

Desktop
![404 lighthouse results](/documentation/lighthouse/404-desktop-lighthouse.png)

Mobile
![404 lighthouse results](/documentation/lighthouse/404-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">About Us</summary>

Desktop
![About Us lighthouse results](/documentation/lighthouse/about-us-desktop-lighthouse.png)

Mobile
![About Us lighthouse results](/documentation/lighthouse/about-us-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Adopt a Dog</summary>

Desktop
![Adopt a Dog lighthouse results](/documentation/lighthouse/adopt-a-dog-desktop-lighthouse.png)

Mobile
![Adopt a Dog lighthouse results](/documentation/lighthouse/adopt-a-dog-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Bruno Profile</summary>

Desktop
![Bruno Profile lighthouse results](/documentation/lighthouse/bruno-profile-desktop-lighthouse.png)

Mobile
![Bruno Profile lighthouse results](/documentation/lighthouse/bruno-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Charlie Profile</summary>

Desktop
![Charlie Profile lighthouse results](/documentation/lighthouse/charlie-profile-desktop-lighthouse.png)

Mobile
![Charlie Profile lighthouse results](/documentation/lighthouse/charlie-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Cooper Profile</summary>

Desktop
![Cooper Profile lighthouse results](/documentation/lighthouse/cooper-profile-desktop-lighthouse.png)

Mobile
![Cooper Profile lighthouse results](/documentation/lighthouse/cooper-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Daisy Profile</summary>

Desktop
![Daisy Profile lighthouse results](/documentation/lighthouse/daisy-profile-desktop-lighthouse.png)

Mobile
![Daisy Profile lighthouse results](/documentation/lighthouse/daisy-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Form Complete</summary>

Desktop
![Form Complete lighthouse results](/documentation/lighthouse/form-complete-desktop-lighthouse.png)

Mobile
![Form Complete lighthouse results](/documentation/lighthouse/form-complete-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Hercules Profile</summary>

Desktop
![Hercules Profile lighthouse results](/documentation/lighthouse/hercules-profile-desktop-lighthouse.png)

Mobile
![Hercules Profile lighthouse results](/documentation/lighthouse/hercules-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Hugo  Profile</summary>

Desktop
![Hugo  Profile< lighthouse results](/documentation/lighthouse/hugo-profile-desktop-lighthouse.png)

Mobile
![Hugo  Profile< lighthouse results](/documentation/lighthouse/hugo-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Index</summary>

Desktop
![Index lighthouse results](/documentation/lighthouse/index-desktop-lighthouse.png)

Mobile
![Index lighthouse results](/documentation/lighthouse/index-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Lily Profile</summary>

Desktop
![Lily Profile lighthouse results](/documentation/lighthouse/lily-profile-desktop-lighthouse.png)

Mobile
![Lily Profile lighthouse results](/documentation/lighthouse/lily-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Lucy Profile</summary>

Desktop
![Lucy Profile lighthouse results](/documentation/lighthouse/lucy-profile-desktop-lighthouse.png)

Mobile
![Lucy Profile lighthouse results](/documentation/lighthouse/lucy-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Max Profile</summary>

Desktop
![Max Profile lighthouse results](/documentation/lighthouse/max-profile-desktop-lighthouse.png)

Mobile
![Max Profile lighthouse results](/documentation/lighthouse/max-profile-mobile-lighthouse.png)

</details>

<details>

<summary style="font-size: 20px; font-weight: bold;">Toby Profile</summary>

Desktop
![Toby Profile lighthouse results](/documentation/lighthouse/toby-profile-desktop-lighthouse.png)

Mobile
![Toby Profile lighthouse results](/documentation/lighthouse/toby-profile-mobile-lighthouse.png)

</details>

## User story testing
### Owner / 
* I want to test if the user can easily and intuitively use and navigate the website.
    * Navigation bar is the header is clear, easy to use, provides feedback and is in the same location site wide.
* I want to test that the site performance is good, with regards to responsiveness and load times.
    * Website performance testing has been excellent. 
* I want to test that the Website accessibility is good.
    * Website accessibility was 100% in all tests on all pages.  
* I want to test that the website is viewable on a wide array of devices.
    * Website was tested on various devices and at all sized using google dev tools. 
* I want to test the websites feedback to the user regarding items that can be interacted with.
    * All items site wide supply the user with feedback in terms of colour changes, prompts, page changes etc.
* I want to test that the user is given all necessary information regarding the adoption process.
    * This information is provided to the user on the first section of the first page
* I want to test if the user can browse a catalogue of dogs available for adoption at the shelter.
    * This is an option in the navigation menu and is displayed on the home page. Functionality of the prev and next buttons also means user can quickly move from profile to profile.
* I want to test that the user can apply to adopt a dog.
    * Application form is accessible directly from the navigation bar or from any dogs profile
* I want to test that the user has access to our contact details and social network links.
    * This is available to the user in the footer section, which is on every page on the site
* I want to ensure if anything goes wrong the user can navigate back to the home page.
    * There is a 404 page with clear instruction and home button should this occur.
* 
### New user
* I want to view dogs that are available for adoption.
    * Available on the first page of website and from navigation bar.
* I want to get a feel for the dogs personalities and know their details.
    * Profile gives full dog details and a paragraph about them.
* I want to understand how to adopt a dog.
    * This is the first information presented to the user on the home page.
* I want to apply to adopt a chosen dog directly from the website.
    *This can be done from every dogs profile or from any page via the navigation menu.
* I want to be able to learn about the shelter and have access to their social networks.
    * All social networks are on every page in the footer, the about us section give details about the shelter, it's owners and even their dogs.

### Returning user
* I want to view dogs that are available for adoption.
    * Available on first page and from navigation menu
* I want to get a feel for the dogs personalities and know their details.
    * This is provided in the dogs profile section
* I want to apply to adopt a dog directly from the website.
    * This can be done from every dogs profile or from any page via the navigation menu.
* I want to be able to find the shelter contact details and location.
    * This information is provided on the about us page and we even provide an interactive google map.
* I want to access the shelters social networks.
    * All social networks are on every page in the footer


## Bugs

During the automated testing various errors were found on the website, all errors were fixed.

Index page
* Errors were shown as I had placed buttons inside of anchor elements on the main page. This mistake was made as I wanted to use the styling of the button. This issue was fixed by removing the button and adding style rules to the anchor elements directly. Fixed in commit #86 “Fix error where buttons were placed in a elements”
* Warning were shown as I had misused h2 element, section element and h1 elements. These were all fixed in commit 87, “Fix index html warnings from html validator”

404 & form complete page
* These pages showed the same errors as they were based on the same code. The error highlighted that a p element cannot be a child of a strong element and that button cannot be a descendant of a element. Warnings regarding the use of h1 element. All fixed in commit #89, Fixed wc3 errors and warnings for 404 and form page

About-us page
* Errors highlighted that frameborder attribute was obsolete, so it was removed. Fixed warnings regarding headings and section. Fixed in commit 90. Fix wc3 error and warnings for about us html page. Error also flagged about bad value on google map iframe. The error was because it expected a fixed size and I used a %. Error was fixed

Adopt-a-dog
* Error flagged around the use of legend in a fieldset, issue with it being inside a div. Error also flagged for using the required attribute on a submit type input. Warnings about headings. All fixed in commit #91 . Fix wc3 error and warnings for adopt a dog html page

Dog profile html files (x10)
* Errors flagged using button as a descendant of anchor element. Warning regarding headings. Fixed all in commit #92. Fix wc3 errors and warning for all dog profile pages

CSS
* One error found, forgot to include unit after number in a font size declaration. Fixed issue on form complete and 404 page.

[Return to Table of Contents](#table-of-contents)



# Design & Development issues
## Index page issue
During my initial design of the index page, I designed the how it works section to contain a heading and 3 divs. Each of these divs would hold 2 icons and 2 paragraphs and would be distributed evenly across the page. Although this did work perfectly, I realised when starting to design my next section of the index page(browser our dogs) that the design of the how it works section would be extremely hard to scale correctly. The main issue would be that the 6 icons and 6 accompanying paragraphs needed to be in a specific order. To do this I completely redesigned the section using 6 individual divs containing only 1 icon and 1 paragraph. This was done in commit #13.

## Dog profile page issue
During my design of the dog profile page I originally followed the design I set out in my wireframes, with the image on the right and content on the left. When making the page responsive I found I needed to reverse the order as when changing to a column style the picture of the dog was placed beneath the content.   

While designing my first dog profile page I had a lot of issues with its layout, especially with regards to the table. Although I knew it was not best practice I decided to work on the page from start to finish without making any commits as it allowed me to constantly try new things until I figured out what worked. I found that a lot of the time what I done in one side of the webpage was dependant on what I would do with the other and thus needed to do it all at once to ensure I was happy with the result. I also done all of my media queries for this page during this time as it again effected how my design would be built. I spent a full day on this page (well as much of the day as I could with a newborn and a 4 year old in the house) and was delighted with my result. It was a real challenge to get right. At the end of the night I decided to copy my code to notepad ++ and then put it back into my code in smaller commits. I did this so that it could be easily understood and followed by the reader. I just wanted to highlight this here as I had a lot of commits close together with a lot of content and although I’m sure some people can do that much work in a very short time, I did not.  
## About us page issue
When creating my About us page I had initially created wireframes to use as a guide. When I created the page based on these wireframes they worked perfectly but were very hard to make responsive. Due to this I modified the layout of the page completely and was then able to make the page responsive. This is why the layout does not match the wireframe. I swapped the location of the form pages image and content for the same reason.

[Return to Table of Contents](#table-of-contents)


# Credits
https://petmatch.ie/ Which inspired my design of my how it works section and dog profile page.
## Copy
Partial copy on this website was written by chat GPT. Copy was usually heavily modified by myself or written by me first and pass to chat GPT which was prompted to add to my copy.
## Images

* [Dog 1 Image](https://pixabay.com/photos/golden-retriever-dog-pet-canine-4292254/) by [dnlrmrzsnz](https://pixabay.com/users/dnlrmrzsnz-1896203/)
* [Dog 2 Image](https://pixabay.com/photos/dog-puppy-canine-pet-animal-cute-6527479/) by [RebaSpike](https://pixabay.com/users/rebaspike-21022195/)
* [Dog 3 Image](https://pixabay.com/photos/dog-corgi-cute-animal-4988986/) by [lucioliu](https://pixabay.com/users/lucioliu-4032922/)
* [Dog 4 Image](https://pixabay.com/photos/australian-shepherd-dog-7176981/) by [liggraphy](https://pixabay.com/users/liggraphy-7165278/)
* [Dog 5 Image](https://pixabay.com/photos/puppy-dog-mammal-cute-small-5124947/) by [Cparks](https://pixabay.com/users/cparks-1593059/)
* [Dog 6 Image](https://pixabay.com/photos/german-longhaired-pointer-dog-pet-782498/) by [ ID 422737](https://pixabay.com/users/422737-422737/)
* [Dog 7 Image](https://pixabay.com/photos/dog-beach-sea-domestic-animal-7956828/) by [Katrinbechtel](https://pixabay.com/users/katrinbechtel-4450173/)
* [Dog 8 Image](https://pixabay.com/photos/english-bulldog-dog-sweet-charming-5422018/) by [BLACK17BG](https://pixabay.com/users/black17bg-10107562/)
* [Dog 9 Image](https://pixabay.com/photos/dog-pet-canine-animal-fur-snout-3385541/) by [RebeccasPictures](https://pixabay.com/users/rebeccaspictures-18516/)
* [Dog 10 Image](https://pixabay.com/photos/dog-puppy-pet-doggy-cute-sweet-2563759/) by [Printeboek](https://pixabay.com/users/printeboek-6033538/)
* [Home page hero image](https://pixabay.com/photos/child-dog-nature-children-5334516/) by [Muscat_Coach](https://pixabay.com/users/muscat_coach-8040223/)
* [Hero image small, form image](https://pixabay.com/photos/autumn-dog-nature-leaves-fall-pet-4470022/) by [Big_Heart](https://pixabay.com/users/big_heart-5883177/)
* [Form complete image](https://pixabay.com/photos/dog-puppy-pet-animal-cute-canine-1411397/) by [dfaen](https://pixabay.com/users/dfaen-951654/)
## Acknowledgements
I would like to acknowledge the following people for support and guidance during this project,
* My Mentor Spencer Barriball for his excellent advice before and during this project.
* Our Cohort Facilitator Alan Bushell, for offering excellent advice, guidance, and support in the lead to and during this project. 
* Fellow students, For participation on slack (comments and questions) and discussions during our weekly meetings, all of which gave further understanding and insight into the course content.
* Fellow student Shane_Donlon and cohort facilitator Alan Bushell for answering my question on slack regarding media queries for varying device sizes.
* Kera Cudmore, for her excellent presentation “Creating your first ReadMe” from which I used the main bullet points for the starting structure of my README file.
* Code institutes love running walkthrough, which gave excellent ideas, particularly the zoom animation on the main image

[Return to Table of Contents](#table-of-contents)

