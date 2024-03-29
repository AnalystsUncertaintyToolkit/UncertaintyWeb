# Uncertainty Toolkit Website
The Uncertainty Toolkit is a guide for analysts working in government 
to use when confronted by a problem that includes elements of uncertainty. 
The Toolkit forms part of the Aqua Book resources and is updated with the 
latest evidence and advice from government experts, the academic community 
and other external bodies.  

The Toolkit is built using R Markdown and hosted on GitHub. [You can view it here](https://analystsuncertaintytoolkit.github.io/UncertaintyWeb/index.html).
The lastest version of the code is contained in this repository.

## How to update the website

You will need a GitHub account and access to RStudio.

**After making changes, before you “build” the output**
- Delete the folder called “_site” and the folder called “docs” from your local repo (this is to prevent you from ending with folders within folders as RStudio can be a bit weird sometimes) 
- Click ‘build’ tab in the environment pane and click on “Build website” (NB it can take a few minutes for it to be done as there’s a lot of stuff for it to do. Be patient. Once it’s done, your output will pop up in a new window.) 
- Create a new folder called “docs” then copy everything from the new “site” folder into the “docs” folder (this is because GitHub Pages is set up to read everything from a folder called “docs”, so it needs to be there for it to recognise it) 
- Using Git, GitHub or the built in Git within R, add then commit the changes and push them up to the remote. 
- Changes will appear here, but note that it might take a few minutes to be fully reflected. 
- Repeat as required 

## Feedback

Please get in touch if you identify any areas for improvement for the site or its contents by raising a GitHub issue.
