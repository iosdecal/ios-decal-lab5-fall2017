#  hw4 part 2- Firebase #
Snapachat Clone Project 3

## Due Date #
November 6, 2017 at 11:59pm

## Overview

Congrats on making it this far on the Snapchat Clone project! By now, we've learned how to build a feed of images as well as to implement our own camera. The next step is to store the images that users take and allow them to share with others. For this part of the project, we'll be using Firebase's Authentication, Database, and Storage modules, which you can reference at any time here: https://firebase.google.com/docs/ios/setup

This part of the project is particularly interesting because you will all be working off of the same database, which means that you will get to share the pictures you take with your classmates!

## Getting started

Before adding Firebase to your Xcode project, you'll need to create a new application online at https://firebase.google.com/
. For grading purposes, we'll need you to configure the permissions so that we are able to access your database as well, which we'll go over below:

### Creating a new Firebase project and configuring access settings

Sign in using your berkeley.edu email, and click the "Go to Console" Button.

![Firebase console launch screen](/README-images/1.png)

Once here, create a new project with the name "Snapchat Clone"

![Firebase console add new project screen](/README-images/2.png)

This will open up a console for your new project. You'll be coming back here to access your Realtime Database (which you'll be using later in this project.

Open the settings tab (cog gear icon) and click "Users and Permissions"

![Firebase console add new project screen](/README-images/3.png)

Then grant "Owner" permissions to the email iosdecalstaff@gmail.com. Once added, the email should show up in "Members" list.

![Users and Permissions Tab button](/README-images/3.png)


### Firebase xcodeproject integration

https://firebase.google.com/docs/ios/setup
