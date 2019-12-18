<h1 align="center"><strong> FATTORIA DI COLLEMEZZANO </strong> </h1>
<p align="center">
  <img width="100" height="100" src="./assets/images/logo.png">
</p>
<h3 align="center">Live website on <a href="https://gbrachetta.github.io/Fattoria/"> GitHub Pages</a></h3>
<h3 align="center">Code on<a href="https://github.com/GBrachetta/Fattoria/"> GitHub Repository</a></h3>


# TESTING

## VALIDATION
This website has gone through validation using the following resources

- HTML <a href="https://validator.w3.org/">Validation</a>
- CSS Validation <a href="https://jigsaw.w3.org/css-validator/">Here</a> and <a href="http://csslint.net/">Here</a>
- <a href="https://autoprefixer.github.io/">AutoPrefixer</a>
    - For checking browser compatibility of the CSS code.
- <a href="https://www.google.com/chrome/">Google Chrome Developer Tools</a>
    - For permanently checking, testing on the fly, identifying issues and controlling device compatibility.

## KNOWN ISSUES

- The two fields `type="date"` in the form in contact.html display a validation warning:
    - Safari and IE don't include a native datepicker. As a workaround I included a `placeholder:"dd-mm-yyyy"` as a fallback for the above browsers. I applied this solution found in <a href="https://stackoverflow.com/questions/35682138/html5-date-picker-doesnt-show-on-safari">this thread</a>, answer number 3.

## USER STORIES
### For people looking for a holiday resort
- The images, video and descriptions of the place and places nearby provide enough and engaging information.
- The design relies a lot on visual impact with stress in the authenticity of the place.
- The website makes emphasis on the fact that it is or offers:
    - Family/children/pets friendly
    - Excellent location
    - Personal tratment
- Easy Navigation
- The navigation highlights indicate visually where the user is in the website and where they can go.
- The logo always takes the user back to the homepage
- Besides the Navigation Bar, different call to action buttons invite the user to perform an action (book, go back, open).
- Images
    - Well organised and distributed.
    - When several images need to be displayed, they are organised in carousels or accordion to prevent clutter.
- After eventually making a choice, the user has the chance to make a booking or request extra information.
- The form doesn't oblige the user to make a reservation, as only name, surname, phone number and email address are required fields. In this way the user can send the form asking for more information or sending a comment or message.

### FOR OWNERS
- The owners have the possibility to show their product.
- The owners have an easy way to be contacted.

# FUNCTIONALITIES
The following functionalities have been tested and behave correctly in mobile devices and desktop using Google Chrome, Safari, Mozilla Firefox, Opera and IE.

### Home Page
- The user browsing the website finds on landing a strong image immersing them in a place they would like to visit.
- The navigation reacts with a visual transition where it's clickable. The same transition is applied to the social media icons in the footer of all pages. Navigation and footer are present on all pages of the website.
- An interactive map can be zoomed in/out by the user to find the location and refer to points of interest.
- Tabs in the accordion on the homepage invite to be clicked with a transition and display more images and text which would otherwise clutter the page.

### About Page

- This page displays photos and text, no interactive content besides navigation bar and social icons.

### Apartments Page

- This page displays the same as the previous one, with added call to action buttons which open each a new page with more detailed information.

### Individual Apartments Page

- This is the page opened by clicking the call to action button from the previous page.
- They include a carousel to accomodate more images without cluttering.
- They also have a call to action button opening contact.html in order to interact with the form to make a reservation or request information.
- They also have an extra (smaller) call to action button to go back to the Apartments Page from where this came from.

### Contact Page

- This page includes a form with 4 required fields (requirement also underlined by their red border)
    - Name
    - Surname
    - Phone Number
    - Email Address

- The form also includes a variety of non required fields.

