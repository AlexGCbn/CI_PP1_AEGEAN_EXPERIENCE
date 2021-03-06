# Aegean Experience - HTML & CSS Project
In order to view the live site, click [here](https://alexgcbn.github.io/CI_PP1_AEGEAN_EXPERIENCE/).

![Website mockup](docs/responsive-website.PNG)

The Aegean Experience is a website that intends to provide users with the appropriate information about the restaurant with the same name, both in text and images. As it is a restaurant's webpage, there was further scope than just the basic intent. The webpage strives to provide visitors with easy to find information, along with visual content that looks appetizing. It is also important to keep the page's style as close to the "sea" or "greek" style as possible, to provide the appropriate feeling to the visitor.
* The restaurant was imagined during the website creation and thus most of the information provided is a mock-up, that could be replaced in case it would be used for commercial purposes.

## Table of contents:

1. [User Stories](#user-stories)
2. [Goals](#goals)
3. [Features](#features)
4. [Design](#design)
    1. [Colours](#colours)
    2. [Fonts](#fonts)
    3. [Structure](#structure)
    4. [Wireframes](#wireframes)
5. [Technologies used](#technologies-used)
6. [Testing](#testing)
    1. [Validation](#validation)
    2. [Device and browser testing](#device-and-browser-testing)
    3. [User stories testing](#user-stories-testing)
7. [Bugs](#bugs)
8. [Deployment](#deployment)
9. [Credits](#credits)

## User Stories:

### As a first time user, I want to:
1. See photos of some meals.
2. Know where the restaurant is located.
3. See how I can contact the restaurant.
4. Learn more about the restaurant's origin and creator.
5. See the restaurant operating hours.
6. See the menu.

### As a recurring user, I want to:
7. Be able to easily provide feedback.
8. Have an easy way to contact the restaurant for reservations or information.
9. Have links to the restaurant's social media pages.
10. See what critics thought about the place.

### As the website owner, I want to:
11. Provide visitors with information about the restaurant's origins and leadership.
12. Have a way to easily navigate the website.
13. Showcase the restaurant's dedication to fresh ingredients.
14. Showcase the location.

## Goals:
### Development goals:
* Have a fully functional and accessible website.
* Provide a consistent experience throughout the pages.
* Have a consistent style throughout the pages.
* Provide easily accessible information.
* Have a simple yet intuitive design.

### Target audience goals:
* Provide an appropriately themed style for a Greek restaurant, for people that are interested in the experience.
* Have easy to find information so visitors can contact the restaurant.
* Have an easy to find location section.
* Showcase appetizing dishes to provide appropriate stimuli.

## Features:

### Pages:
We have a total of 4 pages on the website, which include the below features.

### Navbar:
![Navbar image](docs/images/navbar.PNG)
* The website navbar features the restaurant name and logo and links to the 4 pages.
* It is fully responsive, as it turns to a "hamburger" menu on medium to small screens.
* It is featured on all 4 pages, along with the 404 error page.
* The current page is underlined with a thick line.
* The hovered over page is underlined in a thinner line.  

#### User stories covered: 12

### Carousel:
![Carousel image](docs/images/carousel.png)
* The carousel provides the option to showcase images on the main page.
* 3 images have been added with the support for more.
* It is fully responsive and the image gets resized accordingly. For large screens the image is resized up to a point to maintain quality.  

#### User stories covered: 1

### Review section:
![Review section image](docs/images/review-section.png)
* The review section provides users with some mock-up reviews and images.
* It is a point of referrence to have a general idea of what other people think about the restaurant.  

#### User stories covered: 10

### Menu:
![Menu image](docs/images/menu.png)
* The menu was designed with simplicity in mind, providing easy to find information with an appropriate theme.
* It has a consistent style.
* It is responsive, as its elements become smaller for medium to small screens.  

#### User stories covered: 6

### About us page:
#### Our Story
![Restaurant entrance image](docs/images/our-story.png)
* Short story on how the restaurant was created.
* Features an image of the restaurant entrance.  

#### User stories covered: 4, 11

#### Our chef
![Restaurant chef image](docs/images/our-chef.png)
* Short bio on the restaurant's chef.
* Features a portrait of the chef.  

#### User stories covered: 4, 11

#### The island
![Oia, Santorini photo](docs/images/the-island.png)
* Short introduction to the location of the restaurant, Oia, on Santorini island.
* Features a photo of Oia.  

#### User stories covered: 14

#### The ingredients
![Ingredients (crab) photo](docs/images/the-ingredients.png)
* The restaurant's dedication to the ingredients, explained for all customers.
* Features a photo of some ingredients (crabs)  

#### User stories covered: 13

### Contact us page:
#### Feedback form
![Feedback form image](docs/images/feedback.png)
* Provides visitors with the option of sending in their feedback or questions.
* Has a dedication and a privacy statement.  

#### User stories covered: 7

#### Google maps iFrame
![Google maps iFrame image](docs/images/map-iframe.png)
* Provides visitors with the location of the restaurants. (Current version provides the location of Oia, the town where the restaurant would be, as the restaurant is not real)
* Is embedded correctly to clearly show that it is a Google maps iFrame.  

#### User stories covered: 2, 14

#### Contact details
![Contact details image](docs/images/contact-details.png)
* Provides visitors with all necessary information to contact the restaurant.
* Has operating hours.  

#### User stories covered: 2, 3, 5, 8

### Footer:
![Footer image](docs/images/footer.png)
* Is positioned at the bottom of all pages.
* Provides easy to use links to social media that open in separate tabs.  

#### User stories covered: 9

## Design:

The website was designed with simplicity in mind, while also trying to keep the style of Greece and the sea.  
The style is consistent across pages, as most images have softened corners so they seem more refined.  

### Colours:

The colour palette was taken from [Color Hunt](https://colorhunt.co/)  
The one that was used can be found [here](https://colorhunt.co/palette/e8ded2a3d2ca5eaaa8056676).   
The specific palette was picked because it is light, simple and can easily resemble the colour of the beach.  
![Colour palette image](docs/images/colour-palette.png)

### Fonts:
The fonts used were the following:  
[Dancing script](https://fonts.google.com/specimen/Dancing+Script?query=dancing) was used only for the website's logo. It is calligraphic and stands out from the rest of the text.  
  
[Poppins](https://fonts.google.com/specimen/Poppins?query=poppins) was used for titles on the page, as it is easy to understand and looks great in uppercase.

[Lora](https://fonts.google.com/specimen/Lora?query=lora) was used for the rest of the text on all pages, to make a contrast with the titles while also keeping a simple style.

### Structure: 
The website's structure follows the core idea of simplicity.  
The navbar is located on the top of the page, as it is the layout we are used to on the internet.  
On it, we have the logo on the left that takes users to the home page and the links to all the pages on the right.  
We also have a visual cue that shows on which page we are. (Thick bottom border)
There are a total of 4 pages:
  * Home: A carousel with some images welcomes the user, with some review snippets under it to showcase both some dishes and what critics' experience was.
  * Menu: Simple layout for a menu with header images.
  * About us: All the information needed to provide users with a story. Broken down in 4 parts: The restaurant, the chef, the island and the ingredients.
  * Contact: Grouped information needed to contact the restaurant.

### Wireframes:

<details>
<summary>Home page</summary>

![Home page wireframe image](docs/wireframes/1-home-wireframe.png)
</details>
<details>
<summary>Menu page</summary>

![Menu page wireframe image](docs/wireframes/2-menu-wireframe.png)
</details>
<details>
<summary>About us page</summary>

![About us page wireframe image](docs/wireframes/3-about-us-wireframe.png)
</details>
<details>
<summary>Contact us page</summary>

![Contact us page wireframe image](docs/wireframes/4-contact-us-wireframe.png)
</details>


## Technologies used:

### Languages
  * HTML
  * CSS

### Frameworks and tools
  * Github
  * VSCode
  * Bootstrap V5
  * Balsamiq
  * Adobe Illustrator
  * Google fonts
  * Favicon.io
  * TinyPNG
  * Font Awesome
  * Color Hunt

## Testing:
### Validation
<details>
<summary> HTML </summary>
The W3C Markup Validation Service was used to validate HTML code. All pages passed with no errors or warnings to show.

### Home:
![Home page html validation](docs/images/home-html-valid.png)

### Menu:
![Menu page html validation](docs/images/menu-html-valid.png)

### About us:
![About us page html validation](docs/images/about-html-valid.png)

### Contact us:
![Contact us page html validation](docs/images/contact-html-valid.png)
</details>
<details>
<summary> CSS </summary>
The W3C CSS Validation Service (Jigsaw) was used to validate CSS code.   
When performing the URI validation, we get 12 errors and many warnings. Those errors and warnings are related to Bootstrap.  
If we perform the code validation, we can see that there are no errors or warnings, as seen in the images below.  

### URI validation:
![CSS URI validation result image](docs/images/page-css-valid.png)

### Code validation:
![CSS code validation result image](docs/images/code-css-valid.png)
</details>
<details>
<summary> Performance </summary>
Website performance was tested with Google Developer Tools Lighthouse.   
All pages passed the tests with near perfect results.

### Home:
![Home page performance validation](docs/images/home-lh-valid.png)

### Menu:
![Menu page performance validation](docs/images/menu-lh-valid.png)

### About us:
![About us page performance validation](docs/images/about-lh-valid.png)

### Contact us:
![Contact us page performance validation](docs/images/contact-lh-valid.png)
</details>

<details>
<summary> Accessibility </summary>
Website accessibility was tested with the WAVE Web Accessibility Evaluation Tool.  
All pages passed with no errors. 

### Home:
![Home page accessibility validation](docs/images/home-wave-valid.png)

### Menu:
![Menu page accessibility validation](docs/images/menu-wave-valid.png)

### About us:
![About us page accessibility validation](docs/images/about-wave-valid.png)

### Contact us:
![Contact us page accessibility validation](docs/images/contact-wave-valid.png)
</details>

### Device and browser testing

The website was tested on the following devices:
* Windows desktop PC (various components) running Windows 10
  * Chrome Version 92.0.4515.159
  * Edge Version 92.0.902.78
* iPhone 12 Pro
  * Safari 
* Various devices from users who tested for feedback

The webpage works great on all devices and browsers that it was tested on.  
Functionality between desktop and mobile remains the same, with the look of the page changing slightly.  
As the website was designed mobile-first, it fits mobile browsers perfectly while also changing to fit a larger screen and occupy more space.

### User stories testing:

1. See photos of some meals.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Carousel | Navigate to the home page | Scroll through images of meals | Works as expected |

<details><summary>Screenshots</summary>

![Carousel location image](docs/images/us-testing-carousel.png)

</details>

2. Know where the restaurant is located.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Google maps iframe | Navigate to the contact page | See Google maps iframe (map) | Works as expected |
| Contact details | Navigate to the contact page | See the contact details section | Works as expected |

<details><summary>Screenshots</summary>

![Map location image](docs/images/us-testing-map.png)
![Contact details location image](docs/images/us-testing-contactdetails.png)

</details>

3. See how I can contact the restaurant.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact details | Navigate to the contact page | See the contact details section | Works as expected |

<details><summary>Screenshots</summary>

![Contact details location image](docs/images/us-testing-contactdetails.png)

</details>

4. Learn more about the restaurant's origin and creator.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Our story | Navigate to about us page | See "Our story" section | Works as expected |
| Our chef | Navigate to about us page | See "Our chef" section | Works as expected |

<details><summary>Screenshots</summary>

![Out story location image](docs/images/us-testing-ourstory.png)
![Our chef location image](docs/images/us-testing-ourchef.png)

</details>

5. See the restaurant operating hours.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact details | Navigate to the contact page | See the contact details section | Works as expected |

<details><summary>Screenshots</summary>

![Contact details location image](docs/images/us-testing-contactdetails.png)

</details>

6. See the menu.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Menu | Navigate to menu page | See menu | Works as expected |

<details><summary>Screenshots</summary>

![Menu location image](docs/images/us-testing-menu.png)

</details>

7. Be able to easily provide feedback.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Feedback form | Navigate to contact page | See and use form | Works as expected |

<details><summary>Screenshots</summary>

![Feedback form location image](docs/images/us-testing-feedback.png)
![Feedback form completed image](docs/images/us-testing-feedback-sent.png)

</details>

8. Have an easy way to contact the restaurant for reservations or information.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact details | Navigate to the contact page | See the contact details section | Works as expected |

<details><summary>Screenshots</summary>

![Contact details location image](docs/images/us-testing-contactdetails.png)

</details>

9. Have links to the restaurant's social media pages.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer | Navigate to the bottom of any page | Open social media links in a new tab | Works as expected |

<details><summary>Screenshots</summary>

![Social media footer location image on home page](docs/images/us-testing-social-1.png)

</details>

10. See what critics thought about the place.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Review section | Navigate to home page | Read critics' review shorts | Works as expected |

<details><summary>Screenshots</summary>

![Review section location image](docs/images/us-testing-reviews.png)

</details>

11. Provide visitors with information about the restaurant's origins and leadership.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Our story | Navigate to about us page | See "Our story" section | Works as expected |
| Our chef | Navigate to about us page | See "Our chef" section | Works as expected |

<details><summary>Screenshots</summary>

![Out story location image](docs/images/us-testing-ourstory.png)
![Our chef location image](docs/images/us-testing-ourchef.png)

</details>

12. Have a way to easily navigate the website.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navbar | Navigate to the top of any page | Have links for all pages | Works as expected |

<details><summary>Screenshots</summary>

![Navbar image](docs/images/us-testing-navbar.png)

</details>

13. Showcase the restaurant's dedication to fresh ingredients.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Ingredients | Navigate to about us page | Read short story about dedication to ingredients | Works as expected |

<details><summary>Screenshots</summary>

![Ingredients story location image](docs/images/us-testing-ingredients.png)

</details>

14. Showcase the location.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| The island | Navigate to about us page | Read short story about the island | Works as expected |

<details><summary>Screenshots</summary>

![Location/island story image](docs/images/us-testing-island.png)

</details>


## Bugs

1. Footer did not stay on the bottom of screen.
   * Fixed by adding a container for all content which has the full viewport height (100vh), minus the footer height.
2. Carousel would clip images when transitioning.
   * Fixed by changing the transition to a fade-out.
3. When navbar links had a bottom border added for hover effect, they would move slightly up when hovered.
   * Fixed by adding an invisible bottom border.

## Deployment:
* The site was deployed to GitHub pages. The steps to deploy are as follows: 
  * In the GitHub repository, navigate to the Settings tab 
  * From the source section drop-down menu, select the Master Branch
  * Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://alexgcbn.github.io/CI_PP1_AEGEAN_EXPERIENCE/

## Credits:

* All images were downloaded from [Pexels](https://www.pexels.com/), from various artists.
* Icons used in the logo and footer were linked from [FontAwesome](https://fontawesome.com/).
* Footer idea was derived from the [Love Running](https://github.com/AlexGCbn/love-running) project, from [Code Institute](https://codeinstitute.net/)
* The website [Navbar](https://getbootstrap.com/docs/5.0/components/navbar/) and [Carousel](https://getbootstrap.com/docs/5.0/components/carousel/) features and code were taken from their respective Bootstrap websites.
* Steps on how to link the 404 page were found in [this GitHub post](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-custom-404-page-for-your-github-pages-site)