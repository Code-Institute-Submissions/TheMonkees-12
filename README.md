# The Mokees

A static (front-end only) website for about the 1960's band The Monkees. A live demo can be found [here](https://ngeorgi3v.github.io/TheMonkees/).

![alt text](https://i.imgur.com/5eHO2sL.jpg "Mockup")

## UX
- **Please also see 'User Design Experience' folder where you will find my breakdown of Strategy, Scope, Skeleton and Structure plane**
- This website is for the fans of the music band, and for all potential fans. The objective is the music of the band reaching to more people. The way I try to get more fans is by making a flashy and eye-catching design and adding extra attention to the videos and music files attached to the website.

### User scenario
- A user wants to view the Monkees video content
    - Ability to see them directly in the website
- A user wants to listen the Monkees music
    - Ability to listen them directly
- A user wants to know more about the band members
    - Ability to see information about each band member in website.
- A user wants to contact the Monkees
    - Ability to send them a message through the contact form in the website.

### Wireframes
- Mobile version: [link to image](https://github.com/NGeorgi3v/TheMonkees/tree/master/user%20design%20experience/Skeleton%20plane) or [link to the Photoshop project](https://drive.google.com/open?id=1ZiJ5VQ-kojZYSDfhKsOPWh8otCkFg8uR)
- Dekstop version: [link to image](https://github.com/NGeorgi3v/TheMonkees/tree/master/user%20design%20experience/Skeleton%20plane) or [link to the Photoshop project](https://drive.google.com/open?id=1l3L3kZUe4Ust7Y3ZHdLR27EPGQREfD4f)
- **Please note that the designs shown are just for demonstration and might not match exactly the actual look of the website!**

### Fonts
- [Roboto](https://fonts.google.com/specimen/Roboto) - for most of the text on the site
- [Raleway](https://fonts.google.com/specimen/Raleway) - for headings and captions on the site

### Colours
![Titles and button color](https://i.imgur.com/TZ2CAgy.png "Titles and button color")


- For titles and button hover effects


![Image overlay effect color](https://imgur.com/hgrxhkc.png "Image overlay effect color")


- For image overlay effects


![BG color](https://imgur.com/3P9zkUw.png "BG Color")


- For background color and text color at some places


![Footer BG color](https://imgur.com/MsnLzT1.png "Footer BG Color")


- For footer background color


![Caption color](https://imgur.com/Lasau3G.png "Caption color")


- For captions

## Features
 
### Existing Features
- Mobile first
- Navigation bar 
    - Fixed navigation bar at the top: users can easily reach the navigation menu to return to home or other sections without a need to click on the return button of the browser.
    - Hamburger menu: the navigation bar menu will convert to a hamburger menu when users visit the website on mobile phones or smaller devices. It enhances users' visual experience and users are able to view the information on the website clearly.
    - Hamburger menu collapse: When users click on any items in the menu, it will navigate to the selected section and the menu will be collapsed. It provides a great user experience as users can read the information on the website without an extra tap/click to close the menu.
    - Smooth scrolling feature: When users click on any items in the navigation menu, it will smoothly take users to the selected section with a great visual experience instead of the default anchor "jump".
- Newsletter subscription form
    - Users can simply subscribe and get the lastest news about they're favourite band.
- Social media buttons
    - By clicking on the social media buttons at the footer, users will be redirected to the relevant social media page of the brand so they can follow the and read the latest feed.
- Video and Audio player
    - By clicking on any of the music or video links, a modal shows up allowing the user to listen to the bands songs.
- Contact Form
    - Users can easily contact the band by sending them an email.

### Features Left to Implement
- Carousel
    - A slideshow at the home section to display professional photographs of the band to users. Users will be able to view the previous/following photos by clicking on the left/right arrows. The photos will also automatically change to the next one every five seconds.

## Technologies Used
- HTML 5
- CSS 3
- Javascript ( ES6 )
    - Sticky navigation in desktop version of the site
- BOOTSTRAP 3
    - Site layout, navigation and photos
- jQuery
    - Bootstrap's dropdown responsive menu
- Font Awesome
    - Used for all the icons on the site
- Google Fonts
- Git
- Github
- Google Chrome developer tools
- Visual Studio Code
- Photoshop CS6
    - Designing both the mobile and the desktop version of the website.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

### UX

Fulfil what users need:
    - Able to navigate to each section of the site smoothly without demand of clicking the return button
    - Able to view information about each band member
    - Able to subscribe for the latest band performances
    - Able to see the contact infromation for the Monkees
    - Able to follow the Monkees on social media pages
    - Able to listen to the music of the Monkees and view their videos
    - Able to see latest news 

### Code
This site was checked with W3C HTML and CSS validators, and issues were found in both files. In the HTML document all the issues were related to the font-awesome icon usage in `<h1>` tags, no changes were made since it will affect the appearence of the icons. In the CSS document all the issues were related to the variables used, no changes were made since it would affect the functionality.


### Features
1. Navigation bar
- Click on the band icon: it scrolls back to the home sectoin
- Click on each icon: the website scrolls up/down to take users to the specified section
- The navigation bar converts into a "hamburger menu" when the website is being viewed on mobile or smaller devices
- "Hamburger menu": click on each item to ensure that it brings users to the specified section of the site and the menu automatically collapses

2. Newsletter subscription form and contact form
- Try to submit the empty form and make sure that an eror message about the required fields appears
- Try to submit the form with an invalid input/email address ( such as 1960 and george'gmail.com ) and ensure that a relevat error message appears
- Try to submit the form with all the valid inputs and confirm that a success message appears.

3. Social media icons in the footer
- Hover over each social media icon and ensure the hover feature is active and the colour of each icon changes to match the official logos
- Click on each social media icon and verify that each icon opens the link of the relevant social media page in a new tab using `target="_blank"`

4. Video and audio player
- Click on the video tumbnail and try to play the video that shows up in the modal
- Click on each of the song tumbnails and try to play the song in the modal

### Browsers and devices
This site was tested across diffrent browsers and on different devices to ensure that its responsive and compatible. During testing I noticed that the font-sizes of the text and the size of some of the images has to changed to be seen better from the users, also a few of the elements were repositioned in the layout in order for them to look better. During testing I noticed that the site has a problem with larger screens ( over 1600px ) and made changes such as making the containers bigger/ giving them a certain size and eddinting the font sizes of the text and the sizes of some of the elements.

Devices:
- Chrome / Android 7 / Huawei P8 Lite
- Chrome / Android 7 / Sony Xperia XA
- Safari / iOS 12 / iPhone SE
- Safari / iOS 12 / iPhone 6s Plus
- Safari / iOS 12 / iPhone XS
- Safari / iOS 12 / iPad Air 2
- Opera / iOS 12 / MacBook Pro
- Firefox / Windows 10 / MSI Notebook
- Edge / Windows 10 / Dell Notebook
- Safari / macOS Mojave / iMac

## Deployment
This site is coded in Visual Studio Code, a local Git directory was used for version control. It is hosted by using GitHub, deployed via file upload because of issues with the git bash. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

## Credits

### Content
The content is taken either from google or from the official website of The Monkees.

### Media
- The photos used in this site were obtained from google or the once's provided from Code Institute.

### Acknowledgements
The sticky navigation effect on the desktop version was found [here](https://css-tricks.com/styling-based-on-scroll-position/).

The wireframes were created through Photoshop CS6
