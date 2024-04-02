# **Video Game Sound Tracks**

Video Game Sound Tracks is a website designed to showcase the iconic music found in video games. It will help give informative information on the techniques and processes used when design and writing music for a video game. 

The website is aimed at lovers of both video games and music, whether you are just a fan of video games in general or you personally are learning to compose, it is designed to bring a community together to celebrate the beauty of video game music.

![Screenshot of finished website design for all screens](/assets/images/Website%20Display.png)

## **Design**

I used Balsamiq to create some wireframes of how my design will initially look. 

### Home Page

- This design did change slightly, I added in 3 boxes of information, I wanted it to be a brief overview of what will be covered on the site.

![Screenshot of original Home Page Design](/assets/images/Home-Wireframe.jpg)

### Soundtracks Page

- Originally I wanted there to be 5 seperate soundtrack pages that would cover a particular soundtrack in detail, I decided against this as it looked a lot cleaner doing it all on one page.

![Screenshot of original Soundtracks Page](/assets/images/Soundtrack-wireframe.jpg)

### Artwork Page

- The artwork/form page was quite simple, its design did not change a lot, and was kept similar on both mobile screens and larger screens.

### Mobile Screen Designs

- Here are the mobile designs, the menu becomes a burger icon menu and the content is always aligned in a column.

![Screenshot of mobile screen design](/assets/images/mobile-wireframe.jpg) ![Screenshot of mobile screen design](/assets/images/mobile-form-wireframe.jpg)

## Color Scheme

- Here is the color scheme I used, I wanted to capture a retro feel of 80's gamecraft which I think works well with the font style and color of the font. 

![Screenshot of color scheme](/assets/images/color-scheme.jpg)

## Typography

- I decided to use google fonts, specifically, the font "Honk". It suited the aesthetic I was aiming for and tied in well with the overall color scheme.

![Screenshot of example honk font style on google fonts website](/assets/images/font-typo.jpg)

- Here is an example of the font color scheme, this was causing some contrast issues which I believe was due to the darker gradient of the colors in the font color scheme.

![Screenshot of honk color scheme](/assets/images/font-color-scheme.jpg)

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

![Screenshot of youtube video with placeholder text to show context.](/assets/images/Soundtrack-html.jpg)

5. Artwork - Newsletter
    - The artwork page includes 2 forms to allow the user to either sign up for a newsletter or submit artwork to be used in the newsletter. 
    - This will help create a community that the page will be able to grow with. 

![Screenshot of newsletter and artwork signup forms](/assets/images/signupform.jpg)

6. Footer 
    - The footer includes links to all the social media platforms, facebook, twitter, instagram and youtube.
    - I added a discord link as well with the purpose of having a forum that would allow a community to form where people can chat and share there own thoughts on the content.

![Screenshot of footer](/assets/images/Footer.jpg)

## **Future Features**

1. Adding a forum page where people are able to leave comments, this would be ideal for building a community. 
2. I would like to add a gallery for artwork to be featured, I would add this to the bottom of the artwork page. 
3. I would want to turn each soundtrack page into its own individual page so that I would be able to add more content whilst keeping the look of the website clean. 

## **Testing**

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

## Unfixed Bugs

- When testing on mobile phones, the font loads however the color will of the font does not, it is readable however it will need to be updated with a new font for smaller screen sizes in a media query.
- The Input type=file button was difficult to center, when text aligned center it, due to its own format would still not sit right in line with the other content. 
- Contrast error when using [wave evaluation tool](https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh), the font has a mixture of colors, I believe that the darker color gradient at the bottom of the font is what is causing the contrast error, to compensate for this I have tried to increase the font size where possible.  

## Technologies Used

- HTML5 - All code was written using HTML. 
- CSS - Cascading style sheet used to style my html code.
- VS Code - The main IDE is used. I decided to use VS Code after a discussion with my mentor, it is much more reliable than Codeanywhere and runs a lot faster.
- Codeanywhere - Online IDE 
- Font Awesome - A great website for logos and icons.
- Google Fonts - Open-source fonts and icons that are easy to integrate into html code reliably. 
- Youtube - I embedded 5 videos from youtube, using the share button followed by copying the embedded code.
- W3schools - For quick and useful information when trying to problem solve when writing with HTML and CSS.

## **Deployment** 

I deployed my site on Github. 

1. First go on to your github repository page. 
2. Then go to the settings tab.
3. In the settings tab go to the pages tab on the side menu.
4. Ensure that the source is "Deploy from a branch" 
5. Then make sure the Branch is set to "Main" and the folder selected is the "root" folder.
6. After this click save and this will deploy a live version of the website.

- The live site can be found from this link - https://whelew.github.io/Game-Sound-Tracks/ 

### Cloning the site.

Instructions to clone: 

1. Go to https://github.com/whelew/Game-Sound-Tracks.
2. Click on the green code button. 
3. Copy the HTTPS URL or Github CLI link. 
4. Open Git Bash. 
5. Change your current working directory to the location where you want the clone directory.
6. Type git clone, followed by the URL you copied. 
7. Press enter to create your local clone.

## **Credits**

- The code was all written by myself, [W3schools](https://www.w3schools.com/html/) was a helpful tool in providing useful information when I struggled with working out an issue. 
- My mentor also helped provide useful solutions and identified issues or errors.
- The content on the page was all written by myself also. 
- The Icon Images were taken from [Font Awesome](https://fontawesome.com/) 
- The Background Wallpaper Image was from [iStock](https://www.istockphoto.com/) I purchased it so I could use it publically.