# How to setup a static website on GitHub
This readme will explain how to host a markdown resume as a static website using GitHub pages.  
Additionally, it will connect the steps to the corresponding principle outlined in Andrew Etter's book Modern Technical Writing. 

## Prerequisites
* A markdown formatted resume.  
If you do not know how to create a resume formatted using Markdown then you can find a tutorial in the [More Resources](#more-resources) section below.

* A GitHub account.  
You can create a GitHub account [here](https://github.com/signup?source=login). 

## Instructions

![This is a visual version of the manual steps written out below.](https://github.com/chayward3113/chayward3113.github.io/blob/main/walkthrough.gif)

1. Confirm that the [Prerequisites](#prerequisites) listed above have been completed.  
   <br>When we create our resume we should follow the model that Andrew Etter set out in his book Modern Technical Writing.
   1. The first step is don't write this encourages us to learn everything we can about our topic, goal and how to achieve our goal.
   2. Then we should define our audience this encourages us to meet with and learn about our audience so that we don't do unnecessary work and so that we achieve our ultimate goal.
   3. Next we write the basic functional documentation in this step we write about the things that we learned in don't write and we write to the audience we defined. According to Etter in this step at a minimum we need to answer the following questions: what is the product, why do we want it, how does it fit into the bigger picture, where can we get it, how can we get it and how can we use it.

3. ### Create Github repository
    1. Sign-in to [GitHub](https://github.com/login).  
    2. Click the plus icon in the top right corner of the screen.
    3. Click New repository. 
    4. Name your reposirory username.github.io where username is your username.
    5. Check the Add a README option.
    6. Click the Create repository button at the bottom of the screen.  
<br>In this step we are following the  

4. ### Build Website
    1. Click Add file > Upload files.
    2. Select your markdown formatted resume for upload. 
    3. Click Commit changes.
    4. Click your resumes name.
    5. Click the pencil icon to edit.
    6. Change your resumes file name to be index.md.
    7. Commit changes. Now if you go to https://username.github.io you should see your markdown formatted resume in it's default format.  
<br>The principle for Etter's book outlined by this step is that....

5. ### Setup Markdown styling
    1. Click the Code tab in your GitHub repository.
    2. Click Add file > Create new file.
    3. Name the file _config.yml.
    4. Find a jekyll theme that you like. I have added links in the [More Resources](#more-resources) section below to a variety of Jekyll themes.
    5. Follow your jekyll themes installation guide.   If it is available I recommend using the remote-theme option. It requires a single line in your _config.yml file which is remote-theme: name. You should be able to find a particular themes name in either the README.md or in their _config.yml file.
    6. Click commit changes.  
<br>The principle for Etter's book outlined by this step is that....

6. ### Rebuild website with style choice
    1. Click code.  
Now you should see a yellow dot above the list of files. This indicates that your website is being rebuilt using the theme you selected in your _config.yml file. It will be done building when the dot turns into a green check mark you may need to refresh occasionally for this to happen. For more details on the build including what it is doing and it's progress simply click on the yellow dot followed by details.
    2. Go to https://username.github.io where username is your username. You should now see your resume formatted using the style that you chose.  
<br>The principle for Etter's book outlined by this step is that....

## More Resources
* If you need a refresher in Markdown or if you are still learning, then here is a [Markdown Tutorial](https://www.markdowntutorial.com/) you may find useful.
* Here are some useful Jekyll themes available on GitHub:
    * This is a list of [GitHub themes](https://pages.github.com/themes/)
    * This is a list of [GitHub remote-themes](https://github.com/topics/remote-theme)
    * This is [the theme I used](https://github.com/coogie/oscailte).
* If you are looking for a more indepth overview of GitHub pages and how it works then checkout [Quickstart for GitHub Pages](https://docs.github.com/en/pages/quickstart).
* If you are new to GitHub you can learn more about it's power and capabilities through it's [documentation](https://docs.github.com/en). I recommend starting with the [About GitHub and Git](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git) page so that you get at least a base understanding of how it works and why it is so useful.

## Authors and Acknowledgements
### Authors: 
* Casandra Hayward

### Acknowledgements: 
* First and foremost I must acknowledge Andrew Etter and his book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?crid=3OKPDZ4W0S9Z1&dib=eyJ2IjoiMSJ9.7x6_md7AJLm7s3fbCCniuA.Nmvdv518HN-JlKjwwGQs9AlUaOCB3fi5z3wPXDmeYik&dib_tag=se&keywords=modern+technical+writing+by+andrew+etter&qid=1709825104&sprefix=modern+tech%2Caps%2C267&sr=8-1) as it greatly inspired my README's contents.
* Next I must acknowledge coogie also known as Stephan Coogan and the other 6 contributors to the remote-theme [oscailte](https://github.com/coogie/oscailte) which I used to style and host my resume.
* Lastly, I need to acknowledge my two classmates Logan Doran and Harry Pu who helped me by peer editing my repository.

## FAQs
Why is Markdown better than a word processor?  
Markdown is better than a word processor for several reasons: 
* The first is that Markdown editors are free so anybody can use them and thus it makes it easier for others to contribute to markdown files.
* Secondly, it has fewer formatting options which makes it simpler to use. Therefore, you can write content faster without needing to worry about styling.
* Lastly, we can insure a consistent style accross multiple files by using a single Jekyll style for all the static sites we generate. Thus, removing the need to manually select the same template each time in word.

 
Why is my resume not showing up?  
If your resume is not showing up then you should try the following:
1. Confirm that the build has completed by verifying that the yellow circle is gone and that the green checkmark is present.
2. Confirm that the name of your resume is index.md.
3. Confirm that your respository has the name username.github.io where username is your GitHub username.
4. Confirm that you are using the correct url which is https://username.github.io where username is your GitHub username.
