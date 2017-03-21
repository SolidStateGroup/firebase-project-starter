# Firebase auth starter
This project is a template and step by step guide to customise confirm emails and reset password emails in firebase projects.


# Getting Started

## Step 1 - Create a fresh copy of this repo
``git clone https://github.com/SolidStateGroup/firebase-project-starter.git && cd ./firebase-project-starter/ && rm -rf .git``

** Add this folder to your project's source control **

## Step 2 - Create a new firebase project
https://console.firebase.google.com/

## Step 3 - Add a profiles object to your database
<img src="instructions_1.gif"/>

## Step 4 - Deploy this project to firebase
Go to Hosting > Get started > Follow the instructions for hosting

**Select all defaults, make sure you select no when asked if you wish to overwrite index.html**

# Step 5 - Set the email template action url (auth > email templates > customize action url in the bottom right of any of the templates) to your project url, enable signin providers you wish to use
<img src="instructions_2.png"/>

## Step 6 - Use fireauth with project config
For an example see https://git.solidstategroup.com/solidstategroup/ssg-frontend-boilerplate

# Getting Help
If you encounter a bug or feature request we would like to hear about it. Before you submit an issue please search existing issues in order to prevent duplicates. 

# Contributing
For more information about contributing PRs, please see our <a href="CONTRIBUTING.md">Contribution Guidelines</a>.

# Get in touch
If you have any questions about our projects you can email <a href="mailto:projects@solidstategroup.com">projects@solidstategroup.com</a>.
