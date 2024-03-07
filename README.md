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

1. Sign-in to [GitHub](https://github.com/login).

2. ### Create Github repository  
    1. Click the plus icon in the top right corner of the screen.
    2. Click New repository. 
    3. Name your reposirory username.github.io where username is your username.
    4. Check the Add a README option.
    5. Click the Create repository button at the bottom of the screen.  
<br>By creating a GitHub repository we are creating a centralized location for documentation, code or in our case resumes. GitHub repositories allow us to publish changes as frequently as we want, track changes and if we make our repository public it allows anyone with a GitHub account to make changes. On top of this GitHub can build and host a website for us. Thus it can handle Etter's principles of style, cataloging differences, building a website, helping others write and publishing frequently. 

3. ### Build Website
    1. Click Add file > Upload files.
    2. Select your markdown formatted resume for upload. 
    3. Click Commit changes.
    4. Click your resumes name.
    5. Click the pencil icon to edit.
    6. Change your resumes file name to be index.md.
    7. Commit changes. Now if you go to https://username.github.io you should see your markdown formatted resume in it's default format.  
<br>The principle for Etter's book outlined by this step is that....

4. ### Setup Markdown styling
    1. Click the Code tab in your GitHub repository.
    2. Click Add file > Create new file.
    3. Name the file _config.yml.
    4. Find a jekyll theme that you like; I found my theme [here](https://github.com/topics/remote-theme).
    5. Follow your jekyll themes installation guide.   If it is available I recommend using the remote-theme option. It requires a single line in your _config.yml file which is remote-theme: name. You should be able to find a particular themes name in either the README.md or in their _config.yml file.
    6. Click commit changes.  
<br>The principle for Etter's book outlined by this step is that....

5. ### Rebuild website with style choice
    1. Click code.  
Now you should see a yellow dot above the list of files. This indicates that your website is being rebuilt using the theme you selected in your _config.yml file. It will be done building when the dot turns into a green check mark you may need to refresh occasionally for this to happen. For more details on the build including what it is doing and it's progress simply click on the yellow dot followed by details.
    2. Go to https://username.github.io where username is your username. You should now see your resume formatted using the style that you chose.  
<br>The principle for Etter's book outlined by this step is that....

## More Resources

## Authors and Acknowledgements

## FAQs
