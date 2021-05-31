![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Little Minds

This project Little minds is a website designed to help and give information to parents and carers of children with mental health issues. It contains links to useful tips and therapy booking session, videos of meditation and tips to keep a child well.

## Showcase
![Showcase-screenshot](assets/images/home_page_desktop.JPG)

A deployed version of my website can be found [here.] (https://melwatts.github.io/LittleMinds/)

## navigation

* [UX](#ux)
  + [UX-stories](#ux-stories)
* [Strategy](#strategy)
  + [User-needs](#user-needs)
  + [Business-vision](#business-vision)
* [Scope](#scope)
* [Structure](#structure)
* [Wireframes](#wireframes)
  + [Changes](#changes-to-wireframes)
* [Features](#features)
* [Technologies](#technologies)
* [Testing](#testing)
  + [Testing-plan](#testing-plan)
  + [Implementation](#implementation)
  + [Results](#results)
* [Bugs](#bugs)
* [Deployment](#deployment)
* [Credits](#credits)
* [Content](#content)
* [Media](#media)
* [Acknowledgements](#acknowledgements)

## UX

User stories
## First time visitor goals

•	As a first time visitor, my aim is for parents  / carers of vulnerable children to feel there is help for them, they are not alone and my site will direct them to a solution
•	As a first time visitor, my aim is for people to be able to find what they are looking for very easily with an simple navigation through the site.

## Returning visitor goals:

•	As a returning visitor, my aim is for the site to be familiar and clear for the visitor to find what they were previously researching.
•	As a returning 


The end goal of the project is to help parents and carers if they are worried about their child's behaviour and wellbeing. Providing them with links to professionals and youtubes video's of meditations and techniques.

### UX stories

* As a user I want to find help as I'm worried about my child's behaviour.
* As a user I want to find help as I'm worried about my child's wellbeing.
* As a user I want to know what help or support is out there.
* As a user I want to find out what professional therapy could I get for my loved one.
* As a user I want to find out some tips to keep my child well and happy.
* As a user I would like to feel I am not alone and things can be improved for my child and loved one.
* As a user I would like to know the signs of mental health issues so I can look out for them.

## Strategy

### User Needs

As a user the site has to be accessible on mobile, tablet and all browsers. Information should be clear to read, informative and helpful.
The site navigation needs to be optimal to move to the preferred section of the user.

### Business vision

The purpose of this project is to give users peace of mind and help is out there. 
The site also gives the users easy access to external sites to talk to professionals, find other people to talk to in the same position, and watch meditation and mindful videos .

## Scope

I want my users to feel they are not alone, there are like minded parents / carers, professionals to talk to and generally help is out there for the ones they love. 

## Structure

This project is a 3 page website. With the home page being things that can help keep a young people mentally well. An information page where users can find links to various other website where they will find help, chat forums and professional consultations. The third page is a contact form this is so users can reach out to the team and they will guide them to the correct help and resources.

## Wireframes

The original wireframes can be found [here](assets/images/wireframe.JPG)

### Changes to wireframes

My site has changed considerably from the intitial wireframe, as I had my initial idea and as I started to build my page it took me in another direction, the more I descovered new methods.


## Features

This section contains some of the features this project contains:
* The homepage will be the landing page showing a large hero image to draw people in, and a short paragraph showcasing how the website is of use to the user and an additional more info button.
* Scrolling down to the paragraph about mental health and a couple of nice images, I've added a contact us button here in case the user want to make contact.
* I have added a static image of some sun shining through trees, my thoughts were calming and hopeful in worrying times.
* I have added 3 images of young 'happy' children and some bullet point of tips to keep children happy.
* Further down is more information on the signs of mental health issues to look for and how to support.
* Then a couple of meditation videos and wellbeing tips to watch so assist the user and their child.
* Some helpful links to other sites including an online chat room for like minded people, to book therapy sessions and general help.
* Ending the website with a simple contact form and links to our social media platforms to keep in contact or follow us.


## Technologies

This project was build using the following technologies:

### Languages
* HTML5
* CSS3

### Libraries and online resources:
* Google Chrome Dev Tools: for testing purposes.
* My chosen fonts [Google Fonts}](https://fonts.google.com/).
* W3C HTML-validator: Used to find mistakes in my html code. [HTML-validator](https://validator.w3.org/nu/#textarea)
* FontAwesome: used for icons in the logo. [FontAwesome](https://fontawesome.com/)
* Coolors: to chose a color scheme. [Coolors](https://coolors.co/palettes/trending)

## Testing

### Testing Plan

I started this project, based on a desktop, once I was happy with the look I worked on my media query starting with mobile and working up through the various break off points of various screen sizes. This proved to be a mistake, as I was writing so much css for each screen size, my css document started to get overwhelming. After talks with my mentor we decided to go down the columns route as it proved much easier and better for all screen sizes. 

### Implementation

As this is the first website that I created on my own I had no experience debugging on my own. Testing was mainly done using DevTools in google chrome. 
Starting mobile first then working my way up to bigger screen sizes. 
Whenever an element wasn't located where I wanted it to be I would use the `element.style` box in DevTools to find a solution. 

I used the WC3 code validators to check my code for mistakes as well. 

Testing is done in the following way: 

1. Scroll up and down the page checking for overflow and general positioning of items.
2. Use navigation bar to move to section of the page. 
3. In the form, try and click the button to check whether all fields are required to be filled in, check as well whether the e-mail part was set to e-mail.
4. Check all links in the footer whether they react as intended by opening in a new tab (for links section in footer). 
5. Run through all of these steps for each different screen size.
6. Use HTML and CSS validators from W3C schools to find mistakes in code.


### Results

Once I had a general idea on how to run testing I followed all steps for each of my pages which gave me the following results:

* 2 class to one div, this was rectified
* Tried having control="" on my iframe.
* Tried having muted on my iframe. 
* Tried having loop on my iframe.
* I have 3 warnings left to rectify, all are 'Section lacks heading'.


* HTML-validator results: [index.html](assets/images/html-results/index-results.png)

* CSS-validator results: [style.css](assets/images/css-validator.JPG)



### Bugs

#### Media query

After writing my media query for a mobile, I noticed that, that was overwriting my desktop version. After a lot of meetings with my mentor and lots of chat and help from my fellow students on Slack, it was decided that all of my website was not set in columns or grids, once this was done everything was much clearer.

#### Images

Early on I was having a hard time getting the images to display properly. They looked good on a desktop version but wasn't scaling properly for tablet or mobile. This was due to using px height and width instead of %.



## Deployment

This project is deployed using gitpod in combination with github pages.
I used gitpod to write all code and seeing it is linked with github it was easy to use the terminal to commit, unfortunately in my haste I have committed a few spelling errors of which I did a quick google search to see if I could rectify this, I couldn't see a way.

Deployment was done in the following way:

1. Click on settings tab on my repository.
2. Click the pages tab. 
3. Set source branch to master. This created a link to the deployed version of the website.


## Credits 

* Fontawesome for use from their icons. [Fontawesome](https://fontawesome.com/).
* Responsinator to check my website on all devices. [Responsinator](https://www.responsinator.com/).
* Responsive web design columns and grids to help with css columns media query [Responsive Web Design Grid](https://www.w3schools.com/css/css_rwd_intro.asp).
* README template from code institute fellow student [README.md template](https://github.com/ThijsTerporten/Climbing-Traveller/blob/master/README.md).

## Content

All content in this project are taken from researching the website for helpful links and tips for Children with mental health issues.

## Media 

* All images where taken  [Pexels](https://www.pexels.com/nl-nl/).
* All video are from [YouTube](https://www.youtube.com/). 

## Acknowledgements 

I would like to acknowledge my mentor Antonio Rodriguez. He reassured me when I was doubtful of myself and my skills, and send me useful information during our mentoring sessions about things he saw I was struggling with. Especially during the media query, I was writing hundreds of lines of css, he showed me a simpler solution  - columns and grids - .

**This project was created for educational purposes only, credit for all images goes to their owners**

**Created by Mel Watts**

