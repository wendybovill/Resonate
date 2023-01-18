# Milestone 1 Project: Presentation of Static Data

## Target Audience:

- Members of the public that battle with anxiety and are looking for resources to assist them with "Mindfulness" calming techniques.

- Businesses where their employees battle with anxiety and having a bespoke app created will assist their employees to manage their anxiety and overall increase productivity and wellbeing in their business

## Purpose: 

To demonstrate to the user that anxiety in the population has increased since the pandemic.

***This site will have:***

1. Introduction

2. Bar-chart showing statistics, with a hover animation effect for each section that changes the opacity of the after pandemic statistic to show from 0 opacity to 50% opacity.

3. Tips on how to manage anxiety

4. Sign-posting to help sites and phone lines to help manage anxiety

5. Enquiry Form for users to find out more about the Resonate Mindfulness Apps (both free and bespoke versions).



## Technology Requirements:

Html
Css
Scss & @mixins
Bootstrap 5
Gitpod
VS Code
NPM and Node to convert SCSS to CSS
Git Repository

XD Design Prototype and Creation
Balsamiq for Wireframes


## Development: Html, css, bootstrap. Gitpod. VS code. Git repository.

1. Content:

*Data from government website:*

https://www.gov.uk/government/publications/covid-19-mental-health-and-wellbeing-surveillance-report/3-triangulation-comparison-across-surveys


*Tips on managing Anxiety:* 

https://www.healthline.com/health/mental-health/how-to-cope-with-anxiety


*Document for signposting:*

Embed Mindfulness video: moving clouds https://www.youtube.com/watch?v=PBB4lnsH2b0 Or watching the ocean https://www.healthline.com/health/mental-health/how-to-cope-with-anxiety-or  fireplace video https://www.youtube.com/watch?v=kQocpm-Jh-o


2. Design: 

	*Site Specification and Website Flow:* Documentation for Website Planning. 
	
	https://github.com/wendybovill/milestone-project-one/blob/8c72aaecf6cd3bee71325d35dcd9570e086a9f3f/documentation/Wendy%20Bovill%20509620%20-%20Project%201%20-%20Anxiety%20Support%20Website%20Documentation.pdf

	*Wireframe:* Adobe XD and Balsamiq. View Adobe XD pdf Design.
	
	Wireframe with Balsamiq:
		
	![Balsamiq Wireframe](https://github.com/wendybovill/milestone-project-one/blob/6c465eed1a2d48ac5ae74aa18e3a99e23818860e/documentation/wireframe-wendybovill-509620.png)
	
	
	Site Mockup with Adobe XD:

Desktop Mockup Page 1

![Desktop Mockup Page 1](https://github.com/wendybovill/milestone-project-one/blob/404aaf37ed6db2fb644e96c986394d316dab8849/documentation/Upload_20230116-1530431024_1.jpg)

Ipad Mockup Page 1

![Ipad Mockup Page 1](https://github.com/wendybovill/milestone-project-one/blob/404aaf37ed6db2fb644e96c986394d316dab8849/documentation/Upload_20230116-1530431024_6.jpg)

Iphone Mockup Page 1

![Iphone Mockup Page 1](https://github.com/wendybovill/milestone-project-one/blob/404aaf37ed6db2fb644e96c986394d316dab8849/documentation/Upload_20230116-1530431024_11.jpg)	

 
	*Images:* Pexels: free images.

	*Colours:* pale yellow/gold and light blue/teal. (Yellow: happiness, prosperity, hope. Blue: Calmness, logical, tranquility).


3. Documentation including readme file, spec sheet, timeline for project stages. Estimated time 1 week.

4. Development strategy: Develop the first page and styles, that then will be used as a template for the rest of the site pages. Use mixins and variables with SCSS to compile to CSS, to avoid repetative coding.


## Future Development:

1. Implement Voice Assistance / Voice Over for Assisted Technology

2. Feedback poll as an Enquiry Form with a radio button as a poll which allows the user to select if they have been battling with anxiety. And if yes, if it was worse before, during or after the lockdowns.

3. Further deployment to hosted subdomain name

**Feedback Form Plan:**

Name, Age, State/County, Country, Ethnicity, Have anxiety? Checkbox y/n, Getting support? Checkbox y/n, Anxiety Meter (radio buttons): Before pandemic 1 to 10, During pandemic 1 to 10, After pandemic 1 to 10, Now: 1 to 10.

# Acknowledgements

CSS Animations: Stackflow https://stackoverflow.com/questions/42632767/css-animation-grow-from-center-zoom-from-center-dot-to-full-container  - I used the code and edited by removing the staged % keyframes and also made it shrink instead of grow. For the flyIn one, I removed the inbetween keyframes and only had 2 to make the animation smoother.

# Debugging & Test Results

*Debugging:* Using devtools in chrome and safari. Corrected misaligned boxes with bootstrap. Resized font for smaller devices. Had to hide the large content boxes on the front page from showing in very small devices, and instead added sections with an image background. This is hidden from the users view on larger devices and they see the larger content boxes on the front page.

The logo was overlapping the navigation on smaller devices. I had to resize it for smaller devices, and change the position of the navigation, as well as make the padding for the hover view smaller so the highlight behind did not overlap the logo.

There were issues when first deployed to github pages, where the stylesheet and images did not show. This was corrected after consultation with my mentor Gaff, and the links were then corrected.

There were multiple issues trying to get the font awesome to show. No matter what css link I used. In the end the only one it accepted is a kit link for js.

W3 html validator found 2 attributes that needed to be separated by a space, and complained about the aria-labels I'd used as a violation so I changed them to titles to describe what the following section was about.

Jigsaw validator found some errors in the css and anmiations that were corrected.

Document of validation and errors can be viewed by clicking on the link below:



*Refereces used to assist debugging:*

SCSS https://sass-lang.com/guide

CSS/Html fix floating footer: Bootstrap5: used col-12 in footer class

CSS/Html not showing stylesheet or images: removed begining / from file path for stylesheet fix, and added ../images/imagehere.jpg instead of /assets/images/imagehere.jpg

W3 schools html validator

W3 schools jigsaw css validator


