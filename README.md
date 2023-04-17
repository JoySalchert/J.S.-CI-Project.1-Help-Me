# Help Me!
A website for the fictitious HelpMe!-Project.
It is meant to serve as a digital point of first contact with potential patients as well as people who are interested in volunteering their time and provide the basic information, like: the addresses of the two clinics

View the live site <a href="https://joysalchert.github.io/J.S.-CI-Project.1-Help-Me/" target="_blank">here</a>

<img src="assets/images/readme_multi_device_mockup_screenshot.jpg">

<hr>

## Features
### Navigation menu on home page and services page:
unordert list containing anchors to id's and html-forms linking them together and enabeling the user to move araund the website intuitively.

<img src="assets/images/readme_nav_menu_screenshot.jpg">

### Logo and Form menu exeption (Logo + Back to hompage promt):
The side wide Loge (HelpMe!) also contains an anchor linking it back to the top of the hompage.<br>
I made the decision to not include the navigation menu on the Form page because it looked cluttered and unnessesary.<br>
Instead I basicaly expanded the Logo to include a reminder that it brings the user back to the Home page.

<img src="assets/images/readme_logo_screenshot.jpg">
<img src="assets/images/readme_form_logo_screenshot.jpg">

### Footer:
The side wide Footer section holds an unordert list witch contains social media links (to home pages, if the Organization was real thier social links would go here).

<img src="assets/images/readme_footer_screenshot.jpg">

### Existing Features:
- Responsive design (for screens under 800px wide).
- Hompage with Hero image, about us article with internal link to services page. The Home page also showcases info on Clinic Locations and Help Hotline as well as navigation to the other two pages vie the menu.
<img src="assets/images/readme_hotline_screenshot.jpg">
<img src="assets/images/readme_home_page_locations_screenshot.jpg">
<img src="assets/images/readme_about_us_screenshot.jpg">

- Volunteer signup Form page with Form.
<img src="assets/images/readme_form_page_screenshot.jpg">

- Services Page with information articels and navigation menu.
<img src="assets/images/readme_services_page_screenshot.jpg">

<hr>

## Design
> Pretty much free-hand!

<hr>

## Technologies
- HTML:<br>
Was used to give the website its structure and semantic meaning.
- CSS:<br>
The website was styled with CSS on the style.css external file.
- GitHub:<br>
The Source code is hosted on GitHub and deployed via GitPages.
- Git:<br>
Used to commit and push code during the development of the website.
- Font Awesome:<br>
I got my icons from https://kit.fontawesome.com/7986ee263b.js Version5.
- Google Fonts:<br>
The Font Hind Siliguri is from https://fonts.googleapis.com/css2?family=Hind+Siliguri&display=swap ,sans-serif was used as backup.

<hr>

## Testing
- Responsivnes:<br>
The Website was tested on 3 devices (MacBookAir, iPadAir, iPhone13) and in developer tools.<br>
It passed my expectations the simple design is also very forgiving witch is why I made the decision to only make CSS media queries for small screens (under 800px).
- Accessibility:<br>
Wave Accessibility tool was used for the final testing of the edployed website.<br>
The result:

<img src="assets/images/readme_wave_test_screenshot.jpg">

The Location sections came back with a low contrast error,<br>
but I did not act on this since I wanted to achive the font outline effect<br>
(I susspect that the Wave tool can not recognise the -webkit-text-stroke).<br>
In my opinion the Azure has a high enough contrast to the Purple background (please dont fail me for this!).

<img src="assets/images/readme_lighthouse_test_screenshot.jpg">

Testing focused on:
- Color contrasts meet minimum ratio set in WCAG 2.1 Contrast Guidlines.
- Semantic elements like h1, p, article... are used properly.
- HTML page lang atribute is set.
- alt, title, aria-label atributes where used on all not text content.
- Adherence to the WCAG 2.1 Coding best practices.

## Light House Testing


## Functional Testing

- Navigation Links:<br>
Testing was done by clicking on all of the navigation links the ones in the Navigation Menue as well as the embedded links in the logo and the<br>("> learn more" link conecting the "About Us" section to the services page).
Result = all the navigation links worked on all 3 html files(index.html, services_page.html and form.html) the hover background-color change also works for all the links in the navigation menu.

- Form Testing:<br>
The hover background-color change works for both the Submit and the Reset input element.<br>
Forms are sent to https://formdump.codeinstitute.net .<br>
The requiered fields: Name, Email and Volunteer-Hours all throw up errors when not filled out correctly, as ecpected.

- Social Media Links Testing:<br>
All the social media icons link to the correct social media platform and are opened in a new tab.

<hr>

## Deployment

- The site was created using the GidPod code editor and pushed to github to the repository (J.S.-CI-Project.1-Help-Me-).
- I used the folowing comands to push the code from the GitPod Workspace to the repository:
> git add .<br>
> git commit -m "Message"<br>
> git push

- Deployment to Github Pages:<br>
I deployed the finished website to Gidhub Pages and got the folowing live link:<br>
https://joysalchert.github.io/J.S.-CI-Project.1-Help-Me-/

## Credits
- I took the HTML and CSS code for the footer from the CI-Love-Runnig-Project.
- I took my mentors (Gareth McGirr) README.md file as the outline for my README.md file.
- I used generel google queries when I got stuck (mostly W3Schools material).

## Content and Media
I wrote all the HTML/CSS code and Content-Text (exept for the footer section,<br>
wich I took and altered from the CI-Love-Runnig-Project).<br>
The images where free to use from https://www.pexels.com/ .
