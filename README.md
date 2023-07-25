# Compiling reproducibility resources
There are many resources that can help scientists to improve reproducibility, collaboration, and project management. A short list is available on the [NetNeuro website](https://uo-data-science.github.io/NetNeuro2023/Resources.html). Of course, GitHub itself is an important tool in this category!  

For this programming powerup, we will practice some GitHub skills while also expanding the list of reproducibility resources. We will use GitHub only for the following workflow:  
- Fork a repo
- Create a new branch
- Edit and/or create files
- Commit changes
- Create a pull request to submit changes to the source repository

These proceses can be the basis of a collaborative workflow, all done through the GitHub browser interface. However, for a code-based project, you'll likely want to have a local copy of your work for editing and running code.  

## Getting started
First, identify a reproducibility resource that you want to share with the cohort. It could be a scientific paper, a website, a programming cheat sheet, or any other resource.  You can add a link or a file. If you need inspiration, check out some of these [lists](https://ohi-science.org/news/importance-of-open-data-science-tools) of [resources](https://www.sesync.org/resources/data-learning-resources-0).   

Next, make sure you have a GitHub account and are logged in to start. If you haven't picked a username yet, check out [some advice on usernames](https://happygitwithr.com/github-acct.html).  

Start from the landing page for this repository, `netneuro-resources` - it should be the page where you are reading this file!  

## Fork the repo
Find the button labeled **Fork** in the upper right of the page. Click on this button to create a copy of the repo on your GitHub account. The fork may take a minute to load - then the top of the page should show `YOUR-USERNAME / netneuro-resources`.  

Note - if we were using a "fork and clone" workflow, you could now clone the repo to your local machine (make a copy to work on locally). However, we will not take that step for this exercise.   

## Create a new branch
From your fork of the repo, click on the branch button that should say `main`. Clicking on the button opens a dropdown menu, with the option to *Find or create a branch...*. Create a new branch by typing a name. Remember, it's good to make names informative, so for example `exercise-your-intials` gives you some information about what is in this branch. After you type in the name, click `Create branch`. You should get a message that the branch is created, and now the branch button should say `exercise-your-initials`.  

Remember, creating a new branch is a way of keeping your edits contained. This way, you and/or your collaborators can control the process of merging your changes with many other collaborators who are also updating the same documents.  

## Add your resource to the list
Open the markdown file named **Resource_List**. Click the pencil icon on the right to edit the file.  

Follow the template at the top of the file - add your name, the name of the resource, and a 1-2 sentence description of the resource.  

**Bonus** Use Markdown formatting to make the name of your resource **bold** or to create a hyperlink to your resource. Use the [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/) to look up formatting synatx.  

When you've finished editng the **Resource_List** document, click the green `Commit changes` button in the upper right. In the dialogue box, add a short commit message. Traditionally, a commit message completes the sentence *"If applied, this commit will..."*. You can write a short sentence in the `Commit message` box and if you had a detailed update, you could write a longer message in thet `Extended description` box.  

Select the option to `Commit directly to the exercise-your-initials branch` and click the green button to commit the changes. You should see your changes in the file, and you should now see a commit identifier in the upper-right-hand corner of the file.  

## Upload your file 
If your resource is a digital file, not a link, you will also need to upload your file to the repo. To do this, return to the landing page of the repo (click on the repo name, should be in the page header). NOTE - make sure your are still in your branch! You might need to switch back into it using the branch button navigator on the left.  

Click the button `Add file` and select `Upload files`.  

Drag or select your file, then again fill out the commit message, add to your branch.  

Great! Nowe we have an updated list of resources, and maybe some new files, that we want to add to the repository.  

## Create a pull request  
On the main page of your branch, there should be a message telling you how your branch relates to the source repository. It should state that your branch is 1 or 2 commits ahead of the source reop (`UO-Data-Science:main`), depending on how many commits you have made. There is an option in the message to contribute. Click on this button and select the green button to create a pull request.  

Now you should see an interface to allow you to give the pull request a title and explanation. Notice that at the top of the interface, you can identify the branch with the updated commits (the head) and the source repo that will incorporate the updates (the base). Make sure the appropriate branches are selected!  

Add an informative message to the pull request and click the green button to create the pull request.  

GitHub will automatically check to see if there are conflicts in completing the pull request. If there are, your collaborator might respond with a message suggesting a fix. Then, the source maintainer or anyone with administrative access to the repo will be able to merge the pull request into the source repo.  

## Interact with your collaborators' updates
Once a few people have made their pull requests and the branches have been merged, the resource list will start growing! Navigate back to the landing page of the main repo branch. Check out the resources your collaborators have contributed, and check out any that seem interesting!  

Lastly, spend a few minutes exploring the GitHub interface. How can you see pending pull requests? Can you leave a comment on someone else's pull request? How about finding pull requests that have been closed? 

**Bonus question**: Find the commit history for the main repo, and identify the first resource that was added to the list. Put the name of the resource in Slack. 
