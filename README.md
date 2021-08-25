# Aegean Experience - HTML & CSS Project

![Website mockup](docs/responsive-website.PNG)

The Aegean Experience is a website that intends to provide users with the appropriate information about the restaurant with the same name, both in text and images. As it is a restaurant's webpage, there was further scope than just the basic intent. The webpage strives to provide visitors with easy to find information, along with visual content that looks appetizing. It is also important to keep the page's style as close to the "sea" or "greek" style as possible, to provide the appropriate feeling to the visitor.
* The restaurant was imagined during the website creation and thus most of the information provided is a mock-up, that could be replaced in case it would be used for commercial purposes.

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
11. Provide visitors with information about the restaurant's origins and staff.
12. Have a way to easily navigate the website.
13. Be able to receive feedback from visitors.
14. Showcase some of the dishes.

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

### Carousel:
![Carousel image](docs/images/carousel.png)
* The carousel provides the option to showcase images on the main page.
* 3 images have been added with the support for more.
* It is fully responsive and the image gets resized accordingly. For large screens the image is resized up to a point to maintain quality.

### Review section:
![Review section image](docs/images/review-section.png)
* The review section provides users with some mock-up reviews and images.
* It is a point of referrence to have a general idea of what other people think about the restaurant.

### Menu:
![Menu image](docs/images/menu.png)
* The menu was designed with simplicity in mind, providing easy to find information with an appropriate theme.
* It has a consistent style.
* It is responsive, as its elements become smaller for medium to small screens.

### About us page:
#### Our Story
![Restaurant entrance image](docs/images/our-story.png)
* Short story on how the restaurant was created.
* Features an image of the restaurant entrance.

#### Our chef
![Restaurant chef image](docs/images/our-chef.png)
* Short bio on the restaurant's chef.
* Features a portrait of the chef.

#### The island
![Oia, Santorini photo](docs/images/the-island.png)
* Short introduction to the location of the restaurant, Oia, on Santorini island.
* Features a photo of Oia.

#### The ingredients
![Ingredients (crab) photo](docs/images/the-ingredients.png)
* The restaurant's dedication to the ingredients, explained for all customers.
* Features a photo of some ingredients (crabs)

### Contact us page:
#### Feedback form
![Feedback form image](docs/images/feedback.png)
* Provides visitors with the option of sending in their feedback or questions.
* Has a dedication and a privacy statement.

#### Google maps iFrame
![Google maps iFrame image](docs/images/map-iframe.png)
* Provides visitors with the location of the restaurants. (Current version provides the location of Oia, the town where the restaurant would be, as the restaurant is not real)
* Is embedded correctly to clearly show that it is a Google maps iFrame.

#### Contact details
![Contact details image](docs/images/contact-details.png)
* Provides visitors with all necessary information to contact the restaurant.
* Has operating hours.

### Footer:
![Footer image](docs/images/footer.png)
* Is positioned at the bottom of all pages.
* Provides easy to use links to social media that open in separate tabs.

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

### User stories testing
<details>
<summary> 1. See photos of some meals.</summary>

### Feature: Carousel & Menu
With the Home page Carousel, we can showcase the finest dishes in the restaurant.
Some dish photos can also be seen in the menu.
![Carousel feature image](docs/images/carousel-feature.png)
![Menu feature image](docs/images/menu.png)
</details>
<details>
<summary> 2. Know where the restaurant is located.</summary>

### Feature: Google Maps iFrame & Contact details
With the Google Maps iFrame we can directly show where the restaurant is located.
Right beneath it we can also find the contact details, which have the restaurant location details.
![Google Maps iFrame image](docs/images/map-iframe.png)
![Contact details image](docs/images/contact-details.png)
</details>
<details>
<summary> 3. See how I can contact the restaurant.</summary>

### Feature: Contact details
In the contact details section we can find all information related on how to contact the restaurant.
![Contact details image](docs/images/contact-details.png)
</details>
<details>
<summary> 4. Learn more about the restaurant's origin and creator.</summary>

### Feature: Our story & Our chef
In the About Us section, we can find stories about the restaurant and the chef.
![Restaurant entrance image](docs/images/our-story.png)
![Restaurant chef image](docs/images/our-chef.png)
</details>
<details>
<summary> 5. See the restaurant operating hours.</summary>

### Feature: Contact details
In the contact details section we can find the operating hours of the restaurant.
![Contact details image](docs/images/contact-details.png)
</details>
<details>
<summary> 6. See the menu.</summary>

### Feature: Menu page
The Menu page is dedicated to providing visitors with a list of the menu items.
![Menu image](docs/images/menu.png)
</details>
<details>
<summary> 7. Be able to easily provide feedback.</summary>

### Feature: 
</details>
<details>
<summary> 8. Have an easy way to contact the restaurant for reservations or information.</summary>

</details>
<details>
<summary> 9. Have links to the restaurant's social media pages.</summary>

</details>
<details>
<summary> 10. See what critics thought about the place.</summary>

</details>
<details>
<summary> 11. Provide visitors with information about the restaurant's origins and staff.</summary>

</details>
<details>
<summary> 12. Have a way to easily navigate the website.</summary>

</details>
<details>
<summary> 13. Be able to receive feedback from visitors.</summary>

</details>
<details>
<summary> 14. Showcase some of the dishes.</summary>

</details>

## Deployment:


## Credits: