# Uncertainty Toolkit Website
The Uncertainty Toolkit is a guide for analysts working in government 
to use when confronted by a problem that includes elements of uncertainty. 
The Toolkit forms part of the Aqua Book resources and is updated with the 
latest evidence and advice from government experts, the academic community 
and other external bodies.  

The Toolkit is hosted on github here https://analystsuncertaintytoolkit.github.io/UncertaintyWeb/index.html and is built in R Markdown.
The lastest version of the code is contained in this repo.

## How to update the website
**First time only**
- If you haven’t already, install git and RStudio.  
- Open up the GitHub page 
- Clone the repo to a local folder on your computer

**Before making changes** 
- Open the folder location of the cloned files in your local repo 
- Open git bash, then do a “git fetch” to update your local repo to make sure it matches the latest master version 
- Check “git status” – you may then be instructed to do “git pull” in order to fast forward your way through the latest commits.  
- Open up the UncertaintyWeb.Rproj RProject file from this folder location. This will open up RStudio where you can make changes directly in relevant RMarkdown files. 

**After making changes, before you “build” the output**
- Delete the folder called “_site” and the folder called “docs” from your local repo (this is to prevent you from ending with folders within folders as RStudio can be a bit weird sometimes) 
- Click ‘build’ tab in the environment pane and click on “Build website” (NB it can take a few minutes for it to be done as there’s a lot of stuff for it to do. Be patient. Once it’s done, your output will pop up in a new window.) 
- Create a new folder called “docs” then copy everything from the new “site” folder into the “docs” folder (this is because GitHub Pages is set up to read everything from a folder called “docs”, so it needs to be there for it to recognise it) 
- Using Git, GitHub or the built in Git within R, add then commit the changes and push them up to the remote. 
- Changes will appear here, but note that it might take a few minutes to be fully reflected. 
- Repeat as required 

## Feedback

Please get in touch if you identify any areas for improvement for the site or its contents by raising a GitHub issue.
