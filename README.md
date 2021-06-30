# Visit Penshaw Monument

Portfolio 1 HTML/CSS Essentials - Code Institute

Penshaw Monument is a historical landmark based in the north east of England. This site is for people interested in visiting the greek-like landmark - perhaps they have seen it up on the hill as they drive on the A1. The aim of this site is to be a reliable source of information to allow people to visit and make enquiries as necessary.


![Responsive Mockup] 

# User Experience

## Strategy

Reasons a user may visit a site

- A user is interested in site details such as
    - Location of the site
    - How to get to the site
    - Accessibility and facilities at the site
    - Opening times 
    - Guided tour options for the site
    - Prices for visiting the site

- A user may also wish to make an enquiry and find out more about
    - Bookings
    - History of the site
    - Ask for accessibility aids
    - General question

- A user may be interested in the history of the site

Reasons for the site

- Increase visitor numbers to Penshaw Monument by providing easy access to information in a minimalistic fashion

## Scope

Not all of the user reasons will be implemented into the site at this time. 

A user can expect: 
    
    - An easy to navigate, linear site
    - Consistent header and footer
    - Responsive design for screen sizes maintaining legibility of features
    - Information on site details as described in user stories
    - Ability to contact the National Trust (owners of Penshaw Monumet) via. a submittable form or 
    - Information to contact beyond the National Trust (owners of Penshaw Monument) beyond the site.
    - Easy to find social media links for Penshaw Monument/ The National Trust

## Structure

The website will consist of three separate pages:

1. Home page complete with hero image and call to action button linking to "Plan your visit" page.
2. Plan Your Visit page complete with hero image and sections including "Opening times", "Prices", "Facilities", "How to get here".
3. Contact Us page complete with submittable form for enquiries.

## Surface

### Colours

![Color Pallette](/assets/images/site-colors.png) 

- Charcoal has been used rather than black for most of the test
- White has been used for text overlayed on images or strong background colors for better contrast
- White has also been used as a background for the main bady of the site
- Cultured has been used to section the header and footer from the main body of the text
- Palatinate Purple has been selected from the hero-image-home.jpg using the colour picker tool. This has been used as an accent colour on the home page as well as gradienting into sky magenta for the Contact Us page form.

The colour picker used was in chrome dev tools.

The colour palette image and names were produced using coolors.co.

### Typography

I have used https://fonts.google.com/ for my fonts. Using Roboto for headings, Lato for main body text and sans-serif as back up. These are classic, easily legible fonts.
To achieve this I imported the following to the top of my style.css file.

    @import url('https://fonts.googleapis.com/css2?family=Lato&family=Roboto:wght@500&display=swap');

### Call to action

All hyperlinks have a dotted line when hovered over.

The navigation bar has an underline to show the active page.

### Imagery

The logo for this site was produced using freelogodesign.org. It has a transparent background allowing it to take the colour of the navigation bar, blending seamlessly into the site. 

![Penshaw Monument Logo](/assets/images/site-logo.png)

Fontawesome.com has been used for icons throughout the site. 

The three images of Penshaw Monument were found online.

1. Home page image: Title - Penshaw Monument, Artist - Tim Withnall, Copyright - Tim Withnall www.timwithnall.com, https://www.flickr.com/photos/timwithnall/43553627971
2. Plan Your Visit page image:  Artist - Dean Robson, Pixabay, https://pixabay.com/photos/monument-penshaw-pillars-columns-86034/
3. Contact Us page image: Artist - Mark Bryan, freeimages, https://www.freeimages.com/photo/penshaw-monument-by-night-1521077

## Skeleton

Wireframes were made using Balsamiq. They are for the desktop version however the design has been made responsive for smaller devices. 

Differences for smaller screen sizes:

- Navigation bar is vertically listed (in a column)
- Footer social media icons are vertically listed (in a column)
- The form on the contact us page is the whole width and in a single column
- Font-sizes and max-widths altered for different screen-sizes to maintain legibility of the text

![Wireframe Home](/assets/images/wireframe-home.png)

![Wireframe Plan Your Visit](/assets/images/wireframe-plan-your-visit.png)

![Wireframe Contact Us ](/assets/images/wireframe-contact-us.png)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

__Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Home page, Plan Your Visit and Contact Us page. It is identical across all pages to allow for easy, consistent navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](assets/images/navbar.png)



__Home Hero Image and Call To Action__

  - The first image seen when accessing the page is of the historical landmark itself so should be instantly recognisable to site visitors. Overlayed at the bottom is  large title stating the name of the landmark, Penshaw Monument to avoid confusion. The image has a darkened gradient over it to contrast with the white text.
  - There is a call to action button directing people to the Plan Your Visit page as this is likely to be the place users want to access as it contains all the practical information for visiting. The button is in the accent colour taken from the image to maintain a common colour scheme across the site.

__Home Blurb__

  - This section contains a fact about the landmark and highlights a reason to visit: for the stunning views.  

__The Footer__ 

  - The footer section includes links to the relevant social media sites for The National Trust/ Penshaw Monument.. The links will open to a new tab to allow easy navigation for the user. 
  - The footer section also contains contact information including address, email and telephone number.

![Footer](assets/images/footer.png)

__Plan Your Visit__

  - This page also has a different hero image of Penshaw Monument with the title of the page overlayed in large white text for consistency. 
  - The Plan Your Visit page is full of all the practical information a user may need for planning a visit to Penshaw Monument. It contains all the information as suggested in the user stories: Opening Times, Prices, Facilities, How to get here. 
  - As this page is long, there is a small page navigation bar at the top of the page that links to the relevant section.
  - How to get here contains a google map iframe for ease of planning a visit: a goal of the site. 
  
__Contact Us__

  - This page also has a different hero image of Penshaw Monument with the title of the page overlayed in large white text for consistency. 
  - This page contains a form to allow the user to make an enquiry. The form is has email and message as a requirement. It also captures enquirer data should they choose to input it. There is also a drop down list allowing the user to select the nature of their enquiry. 

## Features Left to Implement

- A page containing a historical time line of the site including images and facts.
- Add "top" links on the Plan Your Visit page to take the user back to the navigation bar

# Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


## Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

## Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

# Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


# Credits 

- Logo created using freelogodesign.org

- Fontawesome.com has been used for icons throughout the site. 
- Home page image: Title - Penshaw Monument, Artist - Tim Withnall, Copyright - Tim Withnall www.timwithnall.com, https://www.flickr.com/photos/timwithnall/43553627971
- Plan Your Visit page image:  Artist - Dean Robson, Pixabay, https://pixabay.com/photos/monument-penshaw-pillars-columns-86034/
- Contact Us page image: Artist - Mark Bryan, freeimages, https://www.freeimages.com/photo/penshaw-monument-by-night-1521077
- Information on Plan Your Visit page and the blurb from the Home page can be found from https://www.nationaltrust.org.uk/penshaw-monument
- Brian Machari - Mentor advice, guidance and tips for things to look out for throughout the project. 
- Matt Rudge for the Code Institute Master Template
- Balsamiq Wireframes for wireframes in the design phase
- W3C HTML Validator for testing validity of HTML
- Jigsaw CSS Validator for testing validity of CSS

