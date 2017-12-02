# Markdown Resume #
******************************
Markdown Resume is a simple resume template build in markdown, parsed into HTML, and hosted on Github. 

### Prerequisites ###
To use this template, you will need the following:  
* [Github Account](https:github.com/)
* [git](https://git-scm.com/)
* [pandoc](https://pandoc.org/)


### Instructions ###

##### Clone the Repository #####
1. Make a new folder on your computer. You can call it something like ``` resume ```
2. Open a terminal and change the current working directory to the folder you created
3. Type in the terminal ``` git clone https://github.com/sdrtownsend/markdown-resume.git ``` and press *enter/return*

##### Edit the Template #####
1. Open the template titled ``` resume.md ``` with any editor of your choice
2. Edit the template with your own information
3. Save your changes

##### Parse into HTML #####
1. In the terminal, type ``` pandoc resume.md -o resume.html --css=style.css -s ``` and press *enter/return*
2. Open the ``` resume.html ``` file in the browser to make sure it worked
3. In the terminal, type ``` git add resume.md -o resume.html ``` and press *enter/return*
4. In the terminal, type ``` git commit -m 'Updated resume.md and resume.html' ``` and press *enter/return*

##### Create Your Repository #####
1. In your web browser, sign into https://github.com
2. Click the *plus icon* in the top right corner and click *create repository*
3. In the ``` repository name ``` box, type *my* and click *create repository*

##### Upload Your Resume #####
1. In the terminal, type ``` git push https://github.com/<YOUR-USERNAME>/markdown-resume/ master ```
2. Change ``` <YOUR-USERNAME> ``` to your github username and press *enter/return*
3. Enter your github password and press *enter/return*
4. In your web browser, return to your repository at ``` https://github.com/*<YOUR-USERNAME>*/my/ ```
5. Verify that your resume.md, resume.html, and style.css files exist, then click on the *settings button*
6. Scroll down to the section called ``` Github Pages ```
