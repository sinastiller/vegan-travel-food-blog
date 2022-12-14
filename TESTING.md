# TESTING FOR ONE BACKPACK FOR TWO

![Screenshot for responsiveness](images-readme/AmIResponsive.png)

## Contents
 * [Automated Testing](#automatedtesting)
    * [W3C Validator](#w3cvalidator)
    * [Responsiveness](#responsivness)
    * [Lighthouse](#lighthouse)
* [Manual Testing](#manualtesting)
* [Bugs](#bugs)

## [Automated Testing](#automatedtesting)

### [W3C Validator](#w3cvalidator)

To verify that the HTML code is written in the correct structure, I tested each .html individually. There are currently no errors, as I have fixed these.

![HTML Validator shows no errors](images-readme/hmtlvalidator.jpg)

To verify that the CSS code is written to the correct standards, I tested style.css using the W3C Jigsaw. There are currently no errors.

![CSS Validator shows no errors](images-readme/cssvalidator.jpg)

### [Responsiveness](#responsivness)

* The website was tested on different screen sizes and devices to ensure outstanding responsiveness. It has been tested on a large screen, laptop, iPad Mini, iPhone X, iPhone8, Xiaomi 9, and iPhone SE. It has also been tested in landscape mode.
* The website was tested on Mozilla Firefox, Chrome, Safari, and Microsoft Edge.

### [Lighthouse](#lighthouse)

Lighthouse was used to test the performance, accessibility, best practices, and SEO. My website achieved a high rating for all the .html pages.

* **HOME**

![Lighthouse Testing for index.html](images-readme/lighthouse_index.jpg)

* **TRAVEL**

![Lighthouse Testing for travel.html](images-readme/lighthouse_travel.jpg)

* **FOOD**

![Lighthouse Testing for food.html](images-readme/lighthouse_food.jpg)

* **ABOUT US**

![Lighthouse Testing for aboutus.html](images-readme/lighthouse_aboutus.jpg)

## [Manual Testing](#manualtesting)

| FEATURE | EXPECTED OUTCOME| ACTION | RESULT |
| -------------              | -------------                                | ------------- | ------------- |
| Navigation food.html Links | When clicked, go to the individual food.html page | Click on the link | food.html opens |
| Our Story Button | When clicked, go to aboutus.html | Click on the button |  aboutus.html opens  |
| Logo in Navigation Bar | When clicked, return to the Homepage | Click on the logo | index.html opens |
| Blog post image on the Homepage | When the user hovers over the image, they should see opacity during the transition | Hover over the image | opacity transition |
| Title of Blog Post on the Homepage | Go to desired food.html or travel.html | Click on title | food.html or travel.html opens |
| Newsletter submit form | User is brought to a new page | Click on submit button | New page opens and the form is submitted successfully |
| Form validation | First name and email address field required to be filled out to submit the form successfully | User types in the first name and email address | Form submitted successfully |
| Social media icons | New tab opens with the social media website | Click on the icon | New tab opens with social media website |

## [Bugs](#bugs)

The following bugs were identified during testing and fixed accordingly :

* ID attributes for labels were removed to have the correct HTML syntax.
* I removed the heights for the Latest Blog Post section, Newsletter Section, and About Us Section and added margins for better responsiveness.
* I fixed the structure on travel.html as an ordered list is not allowed to contain an img element or a paragraph. 
* Furthermore, I removed the a element for the "Our Story" Button and replaced it with a form element to achieve the desired result.
* When trying to make the navigation bar responsive, I was left with a lot of problems. I decided therefore to change the whole header into a flexbox.
* Giving the footer a max-height helped make it better responsive.
* The input field for email address in the form had an incorrect value, so I had to fix it to achieve the desired result.
* When hitting the submit button for the newsletter form an error 404 page opened. I inserted the action to have it open to Code Institutes' form dump.
* Resizing all the images on travel.html and food.html to be identical in size to achieve better responsiveness. 
* Converting some images from .jpeg to .webp for faster performance on page.
* Fixing the file path of #dublin as it wasn't working on moblie screen by making the file path ./food.html#dublin.