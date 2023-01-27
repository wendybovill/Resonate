# Milestone 1 Project: Presentation of Static Data


## Target Audience:

- Members of the public that battle with anxiety and are looking for resources to assist them with "Mindfulness" calming techniques.

- Businesses where their employees battle with anxiety and having a bespoke app created will assist their employees to manage their anxiety and overall increase productivity and wellbeing in their business


## Purpose: 

- To demonstrate to the user that anxiety in the population has increased since the pandemic. 
- To promote awareness of Anxiety and its effects. 
- To promote our mindfulness app Resonate (lite version and enterprise bespoke version).

***This site will have:***

1. Introduction

2. Bar-chart showing statistics

3. Tips on how to manage anxiety, and tools including the Resonate App being promoted and with a QR code to download

4. Sign-posting to help sites and phone lines to help manage anxiety

5. Enquiry Form for users to find out more about the Resonate Mindfulness Apps (both free and bespoke versions)


## User Stories:

| User ID | Type     | User Story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Case Use                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1       | Personal | **Mary**<br>A teenage girl inn high school, battling anxiety<br>since returning to school after lockdowns. Was<br>very popular in school but didn't have internet <br>access at home during lockdowns. As a result<br>she was not included in her friends online<br>social lives, who continued socialising without<br>her. She now dreads going to school, as she<br>feels anxiety and panic. She feels behind her<br>peers and feels excluded and overwhelmed.                                                                                           | I would visit the site to get signposted<br>to other services and an organisation<br>where I can get counselling free as I'm<br>a student and can't afford counselling.<br><br>I would use the free version of the<br>Resonate App to help calm my thoughts<br>and get daily tips and positive<br>reinforcement content.                                                                                                                                                                                                                                                                                        |
| 2       | Personal | **John**<br>A single father lost his employment<br>during Covid lockdowns. His boss couldn't<br>afford to keep running the business. He battles<br>trying to pay his rent and get food for his<br>children. He's been visiting Foodbanks and<br>trying to get employment.                                                                                                                                                                                                                                                                                  | I would use the Resonate website to look<br>at the tools available to help me get<br>to sleep at night when I wake up with<br>panic attacks over not having enough<br>income to meet our needs.<br><br>I would use the Resonate App lite version<br>before going for job interviews, to calm<br>my mind and nerves and to boost my <br>confidence . The CBT part of the app is<br>very helpful.                                                                                                                                                                                                                 |
| 3       | Business | **Sound Bytes Record Productions**<br>The music industry has suffered greatly during<br>the Covid19 Lockdowns. Musicians were unable to<br>perform their usual gigs and lost out financially<br>as well as their inspiration and creativity was<br>reduced.                                                                                                                                                                                                                                                                                                | This website is exactly what we have been<br>looking for.<br>I would use it to be inspired and to<br>inspire other fellow musicians and help<br>those who developed anxiety to get back<br>into production as well as create music<br>to help "Soothe our Souls".<br><br>The App is customised for our musicians<br>to get inspirational content for song<br>writing and production, as well as <br>allowing uploads of soothing relaxing<br>musics that is a sample of what the <br>musician can do, and at the same time<br>help inspire each other and relieve<br>anxiety.                                   |
| 4       | Business | **Direct Demand Logistics**<br>During lockdowns our business became increasingly<br>busy. We had to hire more people, which is great!<br>But our employees suffered family losses due to <br>Covid19, and sadly some of them passed away.<br>This left families without income and struggling<br>anxiety which developed due to a combination of<br>factors: increased demand delivering=more hours<br>away from family, some not seeing family members<br>again due to them passing away while the employee<br>was away on a long-haul distribution job.  | We are grateful for the Resonate website<br>to be able to signpost us to free services<br>as well as give us tools and tips we can<br>use. <br><br>We have been able to provide our employees<br>with a bespoke App Resonate enterprise <br>version. This is geared towards helping<br>manage anxiety, alongside coping with<br>grief and we have also included a section<br>on budgeting and where they can apply for<br>loans or support grants, all within the<br>App.<br><br>We would use the Resonate App bespoke<br>version to assist with maintaining the <br>wellbeing of our staff and their families. |

*Test Cases: https://github.com/wendybovill/milestone-project-one/blob/8ba93d46f3bb4695df7b07fcc292d98d0c2f78b5/test_cases.md


## Technology Requirements:

Html
Css
Scss & @mixins
Bootstrap 5 (included in script and style links)
Gitpod
VS Code
NPM and Node to compile SCSS to CSS
Git Repository
CDN link to Gill Sans font (included in style links)
JS link for FontAwesome (included in scripts)
Favicons (as pngs and linked in styles in html head section)

XD Design Prototype and Creation
Balsamiq for Wireframes
Photoshop for image resizing to optimised images for responsive design

Chrome, Firefox, Safari
Ipad, Iphone, Macbook for testing
Windows, Android phone for testing


## Development: Html, SCSS, npm SASS Compiler, CSS, bootstrap. Gitpod. VS code. Git repository. 

*Development Method:*

After receiving technical specification and design requirements, html template in page 1 was setup
and SCSS template was setup. This was tested and edited until it was perfect. The initial testing
included running the code through html W3 Validator and Jigsaw CSS Validator. When this was
successfully passed, the styles and html index was used as a template for the rest of the site.

SCSS was used along with variables and mixins, this was then compiled out to CSS by using a SASS
Watcher extenstin in VS Code, which automated the compiling of the CSS each time SCSS was saved
with a change having been made to the code.

Duplicate pages were set up from the html index page, and the hero image was changed in each section
in styles, along with the relevant content for each page being changed in the html pages themselves.
New images were added from the exported images from Adobe XD mockups. These were then resized later
and optimised by Adobe Photoshop, and used as replacement images for device responsive styles. The
stylesheet and html was tweaked to allow responsive replacement images optimised using Photoshop
and exported to Web standard optimised format, keeping clear images and low filesizes. This is to
speed up page loading for various screensizes while still maintaining good image resolution.

Further content was added that was not in the mockups, such as the app.html page which is a hidden
page, but can be reached by clicking on the download app link or QR code, or scanning the QR code
using a mobile phone. This takes the user to a small form to fill in with a GET post that would
download an app. (This is yet to be developed at a later stage and not part of the project). The
download button points to Code Institutes form dump, as does the Contact Form on the contact.html
page. The results of the POST methods and GET methods can be seen in the form dump.

In the footer of the site is a link that will launch the users email application to send an email
with predefined subject. In the first page of the website, under the help numbers, each number has
a link to either call that number or text a number, if the user is using a smart phone or has
calling and texting applications on their computer.

After each change the page was viewed using Live Server in Gitpod VS Code, and testing was carried
out throughout the development process, using DevTools in the browser. Errors were identified and
corrected throughout the proces, screenshots were taken to document these. 

At the end of the Development, before final testing the code for CSS and html was again put through
the respective validators at W3 Validator and Jigsaw. Errors were identifed and fixed. Notes were
created of the errors and added to the debugging md file.

End Testing took place where the final site and css was run through the validators again, as well as
debugging techniques used in DevTools to ensure all errors were fixed. These were screenshot as
part of the debugging process and added to the debugging md file.

Throughout the development process, handwritten notes were made, serving as a 'To Do List' of what
needs to be done and then ticked off when completed. These are available as photographs in notes.md

Handwritten notes forming part of development and testing:
https://github.com/wendybovill/milestone-project-one/blob/f3642747c1d664d42cfb915bf2aceeca4bc39549/documentation/notes.md
	

*Site Information*

1. Content:

*Data from government website:*

https://www.gov.uk/government/publications/covid-19-mental-health-and-wellbeing-surveillance-report/3-triangulation-comparison-across-surveys


*Tips on managing Anxiety:* 

https://www.healthline.com/health/mental-health/how-to-cope-with-anxiety


*Document for signposting:*

Embed Mindfulness video: moving clouds https://www.youtube.com/watch?v=PBB4lnsH2b0
Or watching the ocean https://www.healthline.com/health/mental-health/how-to-cope-with-anxiety-or  fireplace video 
https://www.youtube.com/watch?v=kQocpm-Jh-o


2. Design: 

*Site Specification and Website Flow:* Documentation for Website Planning. 

https://github.com/wendybovill/milestone-project-one/blob/8c72aaecf6cd3bee71325d35dcd9570e086a9f3f/documentation/Wendy%20Bovill%20509620%20-%20Project%201%20-%20Anxiety%20Support%20Website%20Documentation.pdf

*Wireframe:* Adobe XD and Balsamiq. View Adobe XD pdf Design.

Wireframe with Balsamiq:

![Balsamiq Wireframe](https://github.com/wendybovill/milestone-project-one/blob/6c465eed1a2d48ac5ae74aa18e3a99e23818860e/documentation/wireframe-wendybovill-509620.png)
	
	
	Site Mockup with Adobe XD:
	
| Desktop Mockup | Ipad Mockup | Iphone Mockup |
|----------------|-------------|---------------|
| ![Desktop Mockup Page 1](https://github.com/wendybovill/milestone-project-one/blob/404aaf37ed6db2fb644e96c986394d316dab8849/documentation/Upload_20230116-1530431024_1.jpg)      | ![Ipad Mockup Page 1](https://github.com/wendybovill/milestone-project-one/blob/404aaf37ed6db2fb644e96c986394d316dab8849/documentation/Upload_20230116-1530431024_6.jpg)   | ![Iphone Mockup Page 1](https://github.com/wendybovill/milestone-project-one/blob/404aaf37ed6db2fb644e96c986394d316dab8849/documentation/Upload_20230116-1530431024_11.jpg)     |


	*Images:* Pexels: free images.

	*Colours:* pale yellow/gold and light blue/teal. 
	(Colour symbolism: Yellow: happiness, prosperity, hope. Blue: Calmness, logical, tranquility).


3. 	Documentation including readme file, spec sheet, timeline for project stages. Estimated time 1 week.

4. 	Development strategy: Develop the first page and styles, that then will be used as a template for the
	rest of the site pages. Use mixins and variables with SCSS to compile to CSS, to avoid repetative coding.


*Changes from Mockup Design*:

1. 	Removed 'More' menu item and moved the more content into the about content.
	The More menu item became the 'Contact' menu item.
	
2.	Colours changed on hover icons, swapped teal and blue colours.

3.	Added Qr code and hidden app.html page for download of Resonate App.


## Future Development:

1. 	Implement Voice Assistance / Voice Over for Assisted Technology

2. 	Feedback poll as an Enquiry Form with a radio button as a poll which allows the user to select if they
	have been battling with anxiety. And if yes, if it was worse before, during or after the lockdowns.

3. 	Further deployment to hosted subdomain name


**Feedback Form Plan:**

	Age, Ethnicity, Interested in Resonate App Radio button y/n
	Which version? Lite/Enterprise Checkbox y/n, 
	Name, Email, Message, Send Button.
	

# Acknowledgements

- CSS Animations from Stackflow:
https://stackoverflow.com/questions/42632767/css-animation-grow-from-center-zoom-from-center-dot-to-full-container  
  - I used the code and edited by removing the staged % keyframes and also made it shrink instead of grow. 
    For the flyIn one, I removed the inbetween keyframes and only had 2 to make the animation smoother.

- WAV files converted to MP3 using: https://www.freeconvert.com/wav-to-mp3

- Videos are from Youtube

- Markdown table generator used: https://www.tablesgenerator.com/markdown_tables

- QR Code added to go to page to download Resonate app lite version used https://me-qr.com/qr-code-generator/

- Fullscreen Youtube video fixed searching in google. Found Fix at https://stackoverflow.com/questions/63318113/youtube-iframe-fullscreen-is-unavailable. Now resizes youtube videos to fullscreen in browsers.



# Debugging & Test Results:

**TEST CASES:**

https://github.com/wendybovill/milestone-project-one/blob/8ba93d46f3bb4695df7b07fcc292d98d0c2f78b5/test_cases.md



**SCREENSHOTS using DevTools for error fixing and troubleshooting:**

https://github.com/wendybovill/milestone-project-one/blob/5f8720fa9fab58b3fe3f47c998bce31c660808d5/devtools_debugging.md



*Debugging:* 

Using devtools in chrome and safari. Corrected misaligned boxes with bootstrap. Resized font for smaller
devices. Had to hide the large content boxes on the front page from showing in very small devices, and
instead added sections with an image background. This is hidden from the users view on larger devices and
they see the larger content boxes on the front page.

The logo was overlapping the navigation on smaller devices. I had to resize it for smaller devices, and
change the position of the navigation, as well as make the padding for the hover view smaller so the
highlight behind did not overlap the logo.

There were issues when first deployed to github pages, where the stylesheet and images did not show.
This was corrected after consultation with my mentor Gaff, and the links were then corrected.

There were multiple issues trying to get the font awesome to show. No matter what css link I used. In the
end the only one it accepted is a kit link for js.

Early testing using W3 html validator found 2 attributes that needed to be separated by a space, and 
complained about the aria-labels I'd used as a violation so I changed them to titles to describe what the
following section was about.

End Testing has been included in the Test Cases document:
https://github.com/wendybovill/milestone-project-one/blob/8ba93d46f3bb4695df7b07fcc292d98d0c2f78b5/test_cases.md

Early testing in Jigsaw validator found some errors in the css and anmiations that were corrected. 
This was to setup the SCSS and CSS template which was then used throughout.

End Testing has been included in the Test Cases document:
https://github.com/wendybovill/milestone-project-one/blob/8ba93d46f3bb4695df7b07fcc292d98d0c2f78b5/test_cases.md

Document of validation and errors can be viewed by clicking on the link below:
https://github.com/wendybovill/milestone-project-one/blob/8ba93d46f3bb4695df7b07fcc292d98d0c2f78b5/test_cases.md	

Handwritten notes forming part of development and testing:
https://github.com/wendybovill/milestone-project-one/blob/f3642747c1d664d42cfb915bf2aceeca4bc39549/documentation/notes.md


*Refereces used to assist debugging:*

- SCSS https://sass-lang.com/guide

- CSS/Html fix floating footer: Bootstrap5: used col-12 in footer class

- CSS/Html not showing stylesheet or images:
	- removed begining / from file path for stylesheet fix, and added ../images/imagehere.jpg
	  instead of /assets/images/imagehere.jpg

- CSS animations changes: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations

- W3 schools html validator: http://validator.w3.org

- W3 schools jigsaw css validator: http://jigsaw.w3.org

- DevTools in Browser

- Gitpod was used in conjuction with VSCode and SASS compiler

- Regular commits were made throughout the process to github as deployed at onset using gitpod

- Stackflow used youtube video fullscreen fix from: https://stackoverflow.com/questions/63318113/youtube-iframe-fullscreen-is-unavailable



**A NOTE ON COMMITS AND COMMENTS:**

The site was deployed early to github to use as a testing environment, along with the Live Server in Gitpod.
As a result there were many commits made. Some were repeatitive commits with nothing but undoing or redoing
a previous change, and in some places correcting spacing or typos. These commits were not fully commented on,
instead using a simple fullstop "." as a comment for that commit. In some instances I used the words same to
indicate the commit was doing the same thing I had done before. This was due to an error with the previous
commit actually being sent correctly to Github, so needed to be redone or resent when there was a connection error.


## Screenshots of Index page from finished site - Desktop View

| Screenshot showing first part of Index Page Finished Site Desktop View  |
|-----------------------------------------------------------------------|
| ![Finished Site Page Part 1](https://github.com/wendybovill/milestone-project-one/blob/cf589814f144ad82fd843557ceed19e68b7346e7/documentation/site1.png)|
| ![Finished Site Index Page Part 2](https://github.com/wendybovill/milestone-project-one/blob/cf589814f144ad82fd843557ceed19e68b7346e7/documentation/site2.png)|
| ![Finished Site Index Page Part 3](https://github.com/wendybovill/milestone-project-one/blob/cf589814f144ad82fd843557ceed19e68b7346e7/documentation/site3.png)|
| ![Finished Site Index Page Part 4](https://github.com/wendybovill/milestone-project-one/blob/cf589814f144ad82fd843557ceed19e68b7346e7/documentation/site4.png)|


