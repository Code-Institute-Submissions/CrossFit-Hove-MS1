# CrossFit Hove - Static Website Project

This project was created for my Milestone 1 project for the Code Institute's Full Stack Dev course. 

I chose to make this site for the local CrossFit gym I use. The gym's existing site lacks content for existing members and potential new clients. The site I have designed is one page and encorporates the overview of the gym, it's ethos, motivational videos, a gallery of members, contact, location and social feeds

I've added nav functionality to link the booking site for existing members and purchasing memberships for new clients. This gives both sides of the target audience usability. 


## UX
 
The user experience was designed to predominantly attract new members to the gym but provide some functionality to existing members. It is a one page website so the user only has to scroll down to be lead through the content. The layout is logical and answers questions as you scroll down. This starts with what classes the gym provides, with a motivational video, followed by a gallery of members. The gallery showcases a broad range of photos of different sexes and ages to be all inclusive and show the membership is diverse. This project achieves it's goal by giving all the information and ability for new members to sign up. It also provides content (social and booking links) for existing members. 

The landing hero image starts the user on the UX journey and shows the site is professional. Next the site has 3 pieces and info on the gym, it's classes and their scope. These are kept to a single paragraph to keep the user engaged. 

A motivational vidoe is embedded to draw people in followed by a gallery of members working out. 

The pricing comes next with unique features set out for each class of membership. These clear pricing cards set out features that should define what propective new clients get for their money. 

The footer section added 3 pieces of functionality, the 'Contact Us' box for all general enquiries, google map for locating the gym and the social feeds taking users to external social networks. 

I feel the one page approach keeps the user engaged rather than a multiple pages where you could easily get lost and lose interest. 

Researching competitor websites showed that this one page UX was predominantly used for this business type.



### Typical User Stories

**Prospective Members**

- As a prospective new member you want to find out about the gym, it's classes and pricing. You can see all information as you scroll down the page or can use the nav links in the header to jump to the relevant section of interest.

- As a prospective new member you want to ask a general question not answered by the sites content. Jump to the Contact form and type your message without creating an email for you personal account. 

**Existing Members**

- As an existing member I want to book a class. I find the booking link easily from the Nav bar and book in to the class

- As an existing member I want to follow the gyms social feeds. I can link to them from the Nav bar


### Wireframe

The linked file to the wireframe mockup of the website.

[Wireframe PDF](https://github.com/StevePilcher/CrossFit-Hove-MS1/blob/master/assets/files/WireFrame%20MS1.pdf)


## Features

### Existing Features
1. Nav Bar - The nav bar loacted at the top of the page is well spaced and contrasts against the black background making it easy to read. Each link clicked by the user jumps them to the relevant section. 

2. Hero Image - The Hero image welcomes the user with a great visual of a woman lifting weights. This will landing will give the first impression.

3. About CrossFit - The about us section gives 3 paragraphs of information on the what the gym is and its class structure. I've kept the text to a minimum as not to put off any people browsing with and large blocks of content.

4. Embedded Video - The embedded video from YouTube of the Crossfit Games athletes with motivational music. I've used this video as a sales pitch to elite fitness. Something the CrossFit brand aims for. Video is embedded so the user stays on the site.

5. Gallery - The gallery section provides a good selection of photos with gym members working out. This showcases that the gym is popular and has a diverse membership.

6. Pricing - The pricing cards are set out clearly and are easy to read. The potential member get the info of each type without have search across the site. Linked 'Buy!' buttons would allow the user to be redirected to by a membership.

7. Contact Us - Simple contact form allows the user to send a general message the the gym owner by filling in the 3 required boxes and pressing submit.

8. Map - The embedded Google map allows the user to locate the gym by clicking on it or if they recognise the area can see where it is.

9. Social - The social media accounts the gym has are linked here, the user can easily identify the social platform by the logo and click to be redirected.

### Features Left to Implement

- Replacing the gallery with an Instagram feed allowing the content to be up to date. | This would require more understanding of Javascript.
- Embedded booking system would give more functionality to members. | This would require more understanding of Javascript.

## Technologies Used

The following technologies were used;

- HTML5 
- CSS3
- Bootstrap (with integrated Javascript)

## Testing

### Web Browser Testing

The following Web Browsers were tested and no errors found;

- Mozilla FireFox 75.0 (64-bit)
- Google Chrome Version 81.0.4044.122 (Official Build) (64-bit)

### Mobile Device 

The following devices were tested and no errors found;

- Samsung Galaxy S10 Plus
- iPhone 
- Google Pixel 2 & 2 XL
- iPhone 6/7/8 Plus

### Known Display Issues

- Internet Explorer not aligning pricing card-deck correctly. 
- iPhone 10x displaying a white line on the right side of all content.

## Validators 

### W3C Markup Validator 
- No errors or warnings were found on index.html

### W3C CSS Validator 
- No errors or warnings were found on style.css
- Bootstrap warnings were flagged but can be disregarded. 

## Issues

- Internet Explorer not aligning pricing card-deck correctly. 
- iPhone 10x displaying a white line on the right side of all content.

## Testing Scenarios

The following scenarios were manually tested;

1. NavBar:
    1. Click relevant link to required section.
    2. User is taken to that section.
    
2. Video:
    1. Navigate to the video. 
    2. Click play button.
    3. Video plays. 
    4. Use embedded controls pause, skip, volume. 
    5. All buttons work accordingly.

3. Contact Us:
    1. Attempt to submit without filling in content.
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

4. Map:
    1. Navigate to map section. 
    2. Manipulate map controls.
    3. Controls work as expected.
    4. Click link for larger map.
    5. New page opens with google maps.

5. Social Links:
    1.Navigate to social links.
    2.Click indvidual links to each platform.
    3.Sites open on new pages.

No automated testing was done.

## Deployment

This project was deployed using GitHub pages can found [here] (https://stevepilcher.github.io/CrossFit-Hove-MS1/). This version was off of the master branch, there are no differences between the deployed and deployment versions. 

## Credits
- Fonts taken from [Google Fonts](https://fonts.google.com) and [DaFont](https://www.dafont.com/gloss-and-bloom.font).
- Map from [Google](https://www.google.co.uk/maps/)
- Icons from [FontAwesome] (https://fontawesome.com/)

### Content
- Video taken from [Youtube](https://www.youtube.com)
- About us content taken from [Crossfit](https://www.crossfit.com/) & [Wikipedia] (https://en.wikipedia.org/wiki/CrossFit) webites.
### Media
- Hero Images for both full and mobile by Hipcravo on [Unsplash](https://unsplash.com) 
- Gallery photos used with permission from CrossFit Hove 

### Acknowledgements

- I received inspiration for this project from [pintrest](https://www.pinterest.co.uk/pilchy1983/developer-ideas/). 
- Code debugging help from my mentor Adegbenga Adeye
- Youtube tutorial on parallax image effect from [iEatWebsites](https://www.youtube.com/watch?v=d34GsFz-HkY)