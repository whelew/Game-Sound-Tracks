# **Video Game Sound Tracks**

Video Game Sound Tracks is a website designed to showcase the iconic music found in video games. It will help give informative information on the techniques and processes used when design and writing music for a video game. 

The website is aimed at lovers of both video games and music, whether you are just a fan of video games in general or you personally are learning to compose, it is designed to bring a community together to celebrate the beauty of video game music.

## **Features** 

1. Nav Bar
    - Permanently placed on each individual html page, this is used to allow the user to navigate around the website.
    - This introduces the feel and aesthetic of the website to the user. 
    - There is a burger menu icon in the form of a game controller that is removed when the screen size reaches over 767px. 

![Screenshot of current nav bar live on the website.](/assets/images/Nav%20Bar.jpg) 

2. Wallpaper
    - Each html page has the same wallpaper image covering the main body of the website. 
    - This is to help tie the asthetic of the website together and maintain the theme of the website the user will now be expecting. 

3. Home Page
    - The home page is there to help the user understand the purpose of the website.
    - It also includes a section of a brief overview of what we will be covering, chords, instrumentation and genre.

![Screenshot of homepage and the main three pillars of game music](/assets/images/homepage.jpg)      

4. Soundtracks
    - This section includes 5 iconic game sound tracks. Each individual soundtrack has a breakdown of what is going on in the track along with a youtube video player to allow the user to listen to the track alongside the information.

![Screenshot of youtube video with placeholder text to show context.](/assets/images/youtube.jpg)

5. Artwork - Newsletter
    - The artwork page includes 2 forms to allow the user to either sign up for a newsletter or submit artwork to be used in the newsletter. 
    - This will help create a community that the page will be able to grow with. 

![Screenshot of newsletter and artwork signup forms](/assets/images/signupform.jpg)

6. Footer 
    - The footer includes links to all the social media platforms, facebook, twitter, instagram and youtube.
    - I added a discord link as well with the purpose of having a forum that would allow a community to form where people can chat and share there own thoughts on the content.

![Screenshot of footer](/assets/images/Footer.jpg)

## Future Features

1. Adding a forum page where people are able to leave comments, this would be ideal for building a community. 
2. I would like to add a gallery for artwork to be featured, I would add this to the bottom of the artwork page. 
3. I would want to turn each soundtrack page into its own individual page so that I would be able to add more content whilst keeping the look of the website clean. 

## Testing

### HTML

- I tested all my individual HTML pages on [W3C Validator](https://validator.w3.org/)
- All HTML have now passed without error.

![Screenshot of no errors for HTML pages](/assets/images/noerrors.jpg)

- A few errors were found, it did not like having a p element as a child of a span. 

![Screenshot of span error in soundtrack.html](/assets/images/span-error.jpg)

- To fix this I changed all span elements to divs. 

![Screenshot of no errors after changing spans to divs](/assets/images/divfix.jpg)

### CSS

- I tested my css using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
- One syntax error was found, I used "," when defining a border style. 

![Screenshot of css error](/assets/images/css-error.jpg)

- This error was easily fixable, I ended up removing the border styles alltogether because they were no longer needed.

![Screenshot of css without errors](/assets/images/CSS-no-errors.jpg)

### Lighthouse

I used Google Chromes developer tool Lighthouse to check the performance of each individual webpage on my site.

#### Index.html

- The index had a good review overall, the performance varied from 87-91 on multiple checks.
![Screenshot of performance of index.html](/assets/images/index-html-check.jpg)

#### Soundtrack.html

- The soundtrack html had a good review except from its performance. I have 5 embedded youtube videos on this page and I believe this was the main issue in slowing down the performance of the site.
![Screenshot of soundtrack.html performance](/assets/images/soundtrack-html-check.jpg)

#### Artwork.html

- The artwork html page had a good review overall.
![Screenshot of artwork.html performance](/assets/images/artwork-html-check.jpg) 

#### Submit.html

- The submit html page functions well, it has the least amount of content therefore has the highest performance.
![Screenshot of submit.html performance](/assets/images/submit-html-check.jpg)