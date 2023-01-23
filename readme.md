# **My Portfolio website**
This is a website that I created to showcase my skills and work history. The website will be used by potential employers to find out more about me.
## **UX and Features**
I have chosen a simple and responsive layout for my portfolio. 
### **Existing Features**
1. Navigation Links - Allows users to navigate around my website by clicking each navigation link, which redirects them to the relevant section of the page.(Single page Navigation)
2. Each Menu item on the Nav Bar when clciked remains highlighted. The code for this is from [Stack Overflow.com](https://stackoverflow.com/questions/50791413/link-must-be-active-when-clicked)
3. Hamburger button - Clicking the hamburger button triggers an overlay menu containing the navigation links to all pages on my website. The user can click the links to navigate to the relevant webpage.
4. Footer "Get Connected" links - Each link opens a new page with the relevant page (LinkedIn, GitHub, Email). They are displayed to the right in the footer on medium to extra large screens. They are displayed in the centre of the footer on extra small and small screens.I used W3Schools to add this footer.
#### **Home Section**
1. Brief introduction to my page with a simple typewriter animation effect that runs only once on screens less than 1200px. I have amended the code from [CodeOpen](https://codepen.io/alvarotrigo/pen/ZEJgqLN) to create this animation.
2. Links to email me and to download my resume
3. Canvas with image on the right - This is hidden on extra small and small screens and displayed on medium to extra large screens. I used [Stack Overflow.com](https://stackoverflow.com/questions/14757659/loading-an-image-onto-a-canvas-with-javascript) as an example to create this canvas.
#### **About Section**
1. Image on the left with a description about myself on the right. This is displayed one below the other on small and extra small screens.
2. Skills section shows my proficiency in each of the coding languages. This has some animation to show the level of proficiency. It is dispalyed one below the other on small and extra small screens. I have used the code from [FreeFrontEnd.com](https://bbbootstrap.com/snippets/circle-progress-bar-percent-loading-81242857) to create this animation.
#### **Work History Section**
1. Timeline built to show work history using FreeFronEnd(https://freefrontend.com/bootstrap-timelines/) as an example.
2. Each timeline item has a little arrow to the left that can be opened and closed to view the summary. 
3. Links to each company's website
4. Timeframe at each work place is dispalyed below the title.
#### **Contact Section**
1. This section uses a simple form to get user's Name, Email and Message
2. There is a checkbox to receive a copy of the email for the user
3. A Submit button to submit the form.
### **Features Left to Implement**
Once I've learnt more of JavaScript and server side programing,  I will add further functionality to the existing features on my website.
1. Change image on while hovering over the canvas.
2. The submit button functionality on the form to send the email.

## **Technologies Used**
* HTML 5
   * The project uses HTML5 to create the basic elements and content of my website.
* CSS3
    * The project uses CSS3 to add custom styles to the elements and content of my website
* Bootstrap v4.3
    * The project uses Bootstrap v4.3 to add a responsive grid system, prebuilt components, plugins built on jQuery, and Bootstrap styles to my website, before adding my custom styles.
* Javascript
    * The project uses JavaScript from Bootstrap which is required to add functionality to some of Bootstrap's components.
    * It also has other minor javascript code for inserting an image on a canvas and for Text animation.
* jQuery
    * The project uses jQuery to simplify DOM manipulation. This is the standard jQuery that is built with Bootstrap components.
* Font Awesome
    * The project uses Font Awesome for the social media links and the hamburger button on my website.
* Visual Studio Code
    * I've used Visual Studio Code as the development environment to write the code for my website.
* Git
    * I've used Git as a version control system to regularly add and commit changes made to project in Cloud9, before pushing them to GitHub.
* GitHub
    * I've used GitHub as a remote repository to push and store the committed changes to my project from Git. I've also used GitHub pages to deploy my website in a live environment.

## **Testing**
I used Google Chrome's Development tools to constantly test each change that I made to my website and to ensure that it appeared in the desired way on different screen sizes. I also tested my website on different screen sizes (mobile, tablet and desktop) to ensure it appeared in the desired way on different devices.

To test my whole website, I went through each page, feature by feature, and documented the results on a spreadsheet. The spreadsheet also documents any responsive features and confirms that they work and appear as intended on different screen sizes. The link to the spreadsheet it below:
* [Testing Checklist](https://github.com/Aarthee22/Portfolio/blob/master/Testing%20Checklist.xlsx)

I used the [W3C HTML Validator tool](https://validator.w3.org/) to validate my HTML code.

I used the [W3C CSS Validator tool](https://codebeautify.org/cssvalidate#) to validate my CSS code.

### **Bugs**

1. During Testing, I fond out that Details tag in the Timeline section did not work in IE.
I did some research and have added a plugin from [Github.com](https://github.com/mathiasbynens/jquery-details) to make this work.
2. Nav bar did not extend to the full device width. Upon investigation, I found that it was due to a div container. After removing it, it works as intended.
3. When clicking the "Resume" button on the home page, it brought up a File not Found error. This was due to the file being on a local machine. I have now moved the document into the Git Repository and since then, it is working as intended.
## **Deployment**
The hosting platform that I've used for my project is GitHub Pages. To deploy my website to GitHub pages, I used the following steps:

1. Loaded the terminal window in my Vistual Studio workspace.

2. Initialised Git using the git init command.

3. Added all files to the Staging area (Git) using the git add . command.

4. Committed the files to Git using the git commit -m "My first commit" command.

5. Created a new repository in GitHub called 'Portfolio'.

6. Copied the below code from GitHub into the terminal window in my Visual Studio workspace:

        git remote add origin https://github.com/Aarthee22/Portfolio.git

        git push -u origin master

7. Entered my GitHub username and password to push the files from Git to GitHub.

8. Went into 'Settings' on my repository page in GitHub.

9. Selected the 'master branch' option under the 'GitHub Pages' section.

10. Ran several regular commits throughout my project.

## Repository Link
https://github.com/Aarthee22/Portfolio/

## Running Code Locally
To run my code locally, users can download a local copy of my code to their desktop by completing the following steps:

1. Go to my [GitHub](https://github.com/Aarthee22/Portfolio/) repository.
2. Click on 'Clone or download'.
3. Click on 'Download ZIP'.
4. Once downloaded, extract the zip file's contents and run my website locally.