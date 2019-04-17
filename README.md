# Han.YJ | Space
First milestone project: Han.YJ | Space.<br><br>
This is a concise blog website with a related landing page to fit for both private and public usage, based on the "less is more" designing mentality.<br>
And differentiate itself from lots of blogs with too much information and function in the same page, which in the end lead to an underemphasized blog page viewing effect.<br><br>
The project is mainly consist of two parts: 
1. landing page with a brief self-introduction and contact form 
2. blog navigation page and the blog pages

## UX
#### Audience & User
The blog user is me, who is the writer and operator.<br>
The main targeted audiences are people who also programming from zero or who intend to start to learn it.<br>
#### Purpose
This website is build under the purpose of 
- setting up my own space to record my growing path to Full Stack Developer
- summarize learning results regularly and share out
- learn and help other to learn
- get feedback from audience, as well as possibilities for connections <br>

#### Fullfill the purpose
The top three purpose are realized by blog pages while the last purpose can be realized by the landing page.<br><br>
For writer, as the blog navigation page and blog pages are already built, it is easy to use them as template, create new blogs and update the navigation page.<br>
For audience, the blog page and landing page are clearly separated. They can either browse the blog navigation page and find content they need, or being quickly informed by writer intend, or get connected in multiple ways.
#### Mockup
Please check mockups [here](https://github.com/Y-username/milestone-project-1/blob/master/assets/images/mockups) or check this repository at assets/image/mockups

## Feautres
#### Existing Features
- separate blog pages and landing pages for audience-friendly and emphatic viewing experience
- Logo in each blog page lead back to Blog Navigation page instead of Home page, as a more intuitive function for audience
- a simplified landing page for brief writer introduction and contact methods
- multiple button elements in landing page to emphysize and lead audience to blogs
- attached extra audio for blog contents, to add more detailed information and release audiences' eyes when they do not want to read.<br>
Audios are showcase in each page to demonstrate its functionality, so I have make mutiple different audios. Their content will be article related when put to real use.
- social medias display in both header and footer to increase connection posibilities

#### Features Left to Implement
- make search bar in blog navigation page functional
- make contact form functional 
- add comment section at bottom of each blog page

## Technology Used
- HTML5
- CSS3
- Bootstrap 4.3

## Testing
#### Responsive testing
The website is tested in mobile(iphone5, iphone8, Samsung S9 and Andriod phone), iPad(iPad Air2), laptop(Mac Pro) and monitor(Sharp LCD) size browser. It is well displayed in all device.
#### Different browser testing
The website is opened in Safari, Google Chrome, FireFox and Internet Explorer, the content is all well displayed.
#### Function testing
##### Navbar
- Navbar logo in landing page lead to Home page, navbar logo in blog pages lead to Blog Navigation page
- About, Blog and Contact in navbar lead to relative pages as well
- Social media icon opens corresponding social media in a new tab

##### Footer
- Footer button in each page opens the corresponding page in a new tab
- Social media icon opens corresponding social media in a new tab

##### Content
- Buttons in each page are all functional. "Read more in blog" button opens blog page in a new tab; "Get in contact" button lead to contact page, "Send Me" button checks if content and email filled in form valid, and work as submit
- Video and Audio are all functional. Video also support fullscreen
- Search bar in blog navigation page is not functional at present, but displayed on the page for future upgrading
- Media list in blog navigation page are all clickable, and link to corresponding blog page
- Content in each page displays responsively
 

## Deployments
The website project is hosted by GitHub pages, deployed directly in master branch. <br>
It is mainly consiste of 
- html files for landing page (index.html) and blog pages (blog.html, blogpage1.html, blogpage2.html, blogpage3.html, blogpage4.html)
- assets folder including main.css, images and audio files
- archiv is the folder for previous built page which are abandoned to use for now, but save for reference

To run locally, please go to <kbd>Github Pages</kbd> in <kbd>Settings</kbd> of this repository and copy the address https://y-username.github.io/milestone-project-1/ into your browser.<br>

## Credits
#### Content 
The website is designed and wrote by myself.<br>
Content of blog pages is processed by myself, the orginal information comes from [MDN web docs](https://developer.mozilla.org/en-US/) and [wikipedia](https://en.wikipedia.org/wiki/Main_Page)
#### Media
Logo made by myself using [freelogodesign](https://www.freelogodesign.org) <br>
Background image is downloaded in [Pexels](https://www.pexels.com/photo/beach-dawn-dusk-ocean-189349/)<br>
Image in [What is Javascript](https://milestone-project-1-yolanda1999.c9users.io/blogpage3.html) is made by myself in [visual-paradigm](https://online.visual-paradigm.com/)<br>
Image in audio cards are from [google image](https://www.google.de/imghp?hl=en&tab=ri)
#### Acknowledgements
Thank for developing advice from my mentor Maranatha Ilesanmi<br>
Fullscreen design was inspired by [this](https://www.youtube.com/watch?v=ZDcMe-uMAXI) tutorial<br>
Responsive navbar is originally from [Bootstrap example](https://getbootstrap.com/docs/4.3/components/navbar/#supported-content)<br>
Fullscreen background image setting was fund in this [snippet](https://css-tricks.com/perfect-full-page-background-image/)<br>
Previous blog navigation page design was inspired by [Scott Young's blog](https://www.scotthyoung.com/blog/articles/)<br>
Current blog navigation page design was inspired by [this post](https://medium.com/refactoring-ui/redesigning-laravel-io-c47ac495dff0)