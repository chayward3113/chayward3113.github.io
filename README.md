# How to Create a Website using GitHub Pages
## Purpose
This readme will explain how to host a markdown resume as a website using GitHub pages.  
Additionally, it will connect the setup steps to their corresponding principle outlined in Andrew Etter's book "Modern Technical Writing". 

## Prerequisites
* A markdown formatted resume.  
If you do not know how to create a resume formatted using Markdown then you can find a tutorial in the [More Resources](#more-resources) section below.

* A GitHub account.  
You can create a GitHub account [here](https://github.com/signup?source=login). 

## Instructions

1. Confirm that the [Prerequisites](#prerequisites) listed above have been completed.  
   ### Benefits of Lightweight Markup Language  
   According to Andrew Etter's book "Modern Technical Writing":  
   * One benefit of Lightweight Markup lanugages like Markdown is that editors are free so anybody can use them making it easier for others to contribute to markdown files.
   * Another benefit is that it has fewer formatting options which makes it simpler to use. Therefore, you can write content faster without needing to worry about styling.
   * One final benefit is that it is easy to maintain a consistent format across multiple documents. Since we keep the contents and style seperate through the use of a static site generator such as Jekyll. We can easily create a consistent style across multiple Markdown documents and remove the need to add styling to each individual document risking inconsistencies.   

3. ### Create GitHub Repository  
    1. Sign-in to [GitHub](https://github.com/login).  
    2. Click the plus icon in the top right corner of the screen.
    3. Click New repository. 
    4. Name your repository username.github.io where username is your username.
    5. Check the Add a README option.
    6. Click the Create repository button at the bottom of the screen.  
    #### Benefits of a Distributed Version Control System
    According to Andrew Etter's book "Modern Technical Writing":  
    * Firstly, by using a distributed version control system such as GitHub we can make it easy for anyone to contribute by making a public repository. Which allows anyone with a GitHub account to add, edit or delete files within the repository. This way viewers can help us maintain a useful and up to date resume.
    * Secondly, by using a distributed version control system it becomes very easy to publish new versions of our resume and keep track of changes. Because whenever a change to the repository is saved you are given the option to provide a commit message where you can state what changed and why. Additionally, whenever a change to the repository is saved the new version will be available to everyone in a matter of minutes.
    * Finally, when we use a distributed version control system like GitHub it makes it very easy to not duplicate work. Because we can keep all our documents in one location on the internet making it easy to add links from one document to another. 

5. ### Build Website
    1. Click Add file > Upload files.
    2. Select your markdown formatted resume for upload. 
    3. Click Commit changes.
    4. Click your resume name.
    5. Click the pencil icon to edit.
    6. Change your resume’s file name to be index.md.
    7. Commit changes. Now if you navigate to username.github.io in your web-browser you should see your markdown formatted resume.  

6. ### Setup Markdown Styling  
    1. Click the Code tab in your GitHub repository.
    2. Click Add file > Create new file.
    3. Name the file _config.yml.
    4. Find a Jekyll theme that you like. I have added links in the [More Resources](#more-resources) section below to a variety of Jekyll themes.
    5. Follow your Jekyll themes installation guide.
    6. Click commit changes.  
    7. Click code.  
Now you should see a yellow dot above the list of files. This indicates that your website is being rebuilt. It will be done building when the dot turns into a green check mark this should take a couple minutes. For more details on the build including what it is doing, and its progress simply click on the yellow dot followed by details.
    8. Navigate to username.github.io where username is your username. You should now see your resume formatted using the style that you chose.  
    #### Benefits of Generating Static Sites
    According to Andrew Etter's book "Modern Technical Writing":  
    * Creating a website ensures that everyone always has access to the most up to date version of our resumes.
    * Static site generators make it easy to style Markdown files and styling makes them easier to read. They accomplish this by simplifying the styling process by seperating content from styles so that we can apply the same style to multiple files.
    * Additionally, it makes updating and distributing our resume faster and simpler. Especially in GitHub because whenever, we make a change to our repository it will automatically rebuild the site using Jekyll within a matter of minutes.

### Demo
![This is a visual version of the manual steps written out below.](https://github.com/chayward3113/chayward3113.github.io/blob/main/walkthrough.gif)

## More Resources
* If you need a refresher in Markdown or if you are still learning, then here is a [Markdown Tutorial](https://www.markdowntutorial.com/) you may find useful.
* Here are some useful Jekyll themes available on GitHub:
    * This is a list of [GitHub themes](https://pages.github.com/themes/)
    * This is a list of [GitHub remote-themes](https://github.com/topics/remote-theme)
    * This is [the theme I used](https://github.com/coogie/oscailte).
* If you are looking for an in-depth overview of GitHub pages and how it works then checkout [Quickstart for GitHub Pages](https://docs.github.com/en/pages/quickstart).
* If you are new to GitHub, you can learn more about its power and capabilities through it's [documentation](https://docs.github.com/en), I recommend starting with the [About GitHub and Git](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git) page.

## Authors and Acknowledgements
### Authors: 
* Casandra Hayward

### Acknowledgements: 
* First and foremost I must acknowledge Andrew Etter and his book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?crid=3OKPDZ4W0S9Z1&dib=eyJ2IjoiMSJ9.7x6_md7AJLm7s3fbCCniuA.Nmvdv518HN-JlKjwwGQs9AlUaOCB3fi5z3wPXDmeYik&dib_tag=se&keywords=modern+technical+writing+by+andrew+etter&qid=1709825104&sprefix=modern+tech%2Caps%2C267&sr=8-1) as it greatly inspired my README's contents.
* Next, I must acknowledge coogie also known as Stephan Coogan and the other 6 contributors to the remote-theme [oscailte](https://github.com/coogie/oscailte) which I used to style my resume.
* Lastly, I need to acknowledge my two classmates Logan Doran and Harry Pu who helped me by peer editing my repository.

## FAQs
**Why is Markdown better than a word processor?**  
Markdown is better than a word processor for several reasons: 
* The first is that Markdown editors are free so anybody can use them. Thus, it makes it easier for others to contribute to markdown files.
* Secondly, it has fewer formatting options which makes it simpler to use. Therefore, you can write content faster without needing to worry about styling.
* Lastly, we can ensure a consistent style across multiple files by using a single Jekyll style. Thus, removing the need to manually select the same template each time in word.

 
**Why is my resume not showing up?**  
If your resume is not showing up, then you should try the following:
1. Confirm that the build has completed by verifying that the yellow circle is gone, and the green checkmark is present.
2. Confirm that the name of your resume is index.md.
3. Confirm that your repository has the name username.github.io where username is your GitHub username.
4. Confirm that you are using the correct URL which is https://username.github.io.
