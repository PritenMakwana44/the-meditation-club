# The Meditation Club

The meditation club is a place where anyone can become free from stress and become happier in their life. The club not only holds meditation lessons, but also holds two talks a week about ancient indian wisdom. With a combination of knowledge and meditation one can become happy. 

This website allows one to get a basic understanding of what the meditation club is, along with the timetable for the clubs events. The website allows one to sign up. Lastly the website shows social media links in the contact section to get in touch.

![Responsive](../the-meditation-club/readme-resources/images/Responsive.png)


## Features
<hr>

**Header**
- Header holds a heading for the whole page which reads 'The Meditation Club'.
- Dark coloured and has a specific modern font to make it stand out.

![Header-navbar](../the-meditation-club/readme-resources/images/Header-and-nav-bar.png)

**Navigation Bar**
- Navigation bar is in middle of page.
- When hovering over links on nav bar the specific item is underlined.
- Links to about section, timetable section and signup section. 
- Font contrasts with background which is off-white. It's in a simple but modern text.
- Fully responsive with diffrent devices. Easily done as it's in the center of page.

![Header-navbar](../the-meditation-club/readme-resources/images/Header-and-nav-bar.png)

**Landing Page**
- Landing page shows a picture of a women meditating which covers most of the page.
- Text is also over the image. The text is a means of claryfing what the website is about.
- Opacity set on image to make text stand out and easier to read.
- Text and image responsive to diffrent devices.

![main-image](../the-meditation-club/readme-resources/images/main-image.png)

**About Section**
- The about section covers what the club is about and what is included.
- This section breaks down the club into 4 parts. 
- Each section of the 4 has a header which breaks down the topic then a sentance to describe and a image for aesthetic.
- This section gives the viewer the essence of the meditation club.
- Again this section is responsive to tablets and mobiles too.

![about](../the-meditation-club/readme-resources/images/about.png)

**Timetable Section**
- The timetable section has a diffrent colour which stands out amongst the rest of the site to attract the viewers attention. 
- The writing is dark and the table is beige with offwhite lines breaking it up. 
- The timetable displays all days of the week with their respective events, who they are instructed by and what time. 
- The table is responsive to all devices. 

![timetable](../the-meditation-club/readme-resources/images/timetable.png)


**Sign Up Section**

- The signup section has a header with beige writing and a black background to contrast the offwhite background of the website. This makes it easy of users to identify the signup section.
- This section has a form for visitors to sign up with a submit button. 
- The signup form includes first name, last name, email and number. 
- The styling of the form is to have a dark box and beige border at bottom to keep the website consistent. 
- When the submit button is clicked or hovered over the button turns black.
- Responsive to mobile and tablet.

![signup](../the-meditation-club/readme-resources/images/signup.png)

**Footer**
- The footer has 4 social media icons. 
- Each social media icon is clickable and should go to the respective social media site. 
- All icons are stick with the same colour scheme of offwhite background and dark in color.
- Responsive to mobile and tablet.

![footer](../the-meditation-club/readme-resources/images/footer.png)

## Testing
<hr>

- Tested in diffrent browsers i.e chrome, firefox and safari. All working.
- Used dev tools to check everything works with diffrent screen sizes. all seemed to be fine. 
- All areas have great contrast and seem to be easy to see.
- Form works fine and submit button works. Did find a bug with the hover function of the button being out of place. Fixed below in bugs section.

### Bugs

Hover bug:
- When hovering over the submit button it is the correct colour, just the button is out of place. 

Before hover:

![signup](../the-meditation-club/readme-resources/images/signup.png)

After Hover: 

![submit-hover-bug](../the-meditation-club/readme-resources/images/submit-hover-bug.png)

**Solved Bugs**

Hover Bug:

Removed from #submit-button:hover:
margin-top: 5%;
padding: 1% 1%;


added to #submit-button:hover:
display: block;
margin: 1% auto;

- I must have missed this when adjusting the submit button code in css. 

![hover-bug-fix](../the-meditation-club/readme-resources/images/hover-bug-fix.png)



**Validator Testing**

HTML: No errors or warnings via W3C validator.

CSS: No errors or warnings via Jigsaw validator.



## Deployment

Hosting on github pages:
You can do it easily in Gitub:
1. Open the repository on GitHub
2. Go to "Settings" (the tab on the right)
3. On the left hand side select pages, select the main branch as the source.  Then it shows you a green confirmation "Your site is published at......" with the URL.

## Credits
**Content**
* The social media code was taken from the Code Institute Love running project, but was styled slightly diffrently.
* Sizing inspirtation was taken from the below link
https://gist.github.com/gokulkrishh/242e68d1ee94ad05f488
* Styling code inspirtation was taken from:
https://www.w3schools.com/howto/default.asp
* Much help was also taken from Stackoverflow when problems occured.
https://stackoverflow.com/


**Media**
* All images were taken from Pexels


## General
