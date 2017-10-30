# SI 364 - Fall 2017 - Homework 4

### DEADLINE: Sunday, November 12, at 11:59 PM

## To Submit

* Fork and clone this repository
* Edit files per instructions and push your changes to your GitHub fork
* Submit the link to your GitHub repository to your

## Instructions

In this HW, you'll be writing an application that's *kind of like* Twitter for one person: you'll be saving data about tweets, but instead of getting tweets by different users on `twitter.com`, you'll be using a form to gather data from a user about tweets they would *like to see posted*, for example -- and saving that data in a database.

We've provided templates, and instructions in the `SI364_hw4.py` file. Your task(s) are to fill in code as directed in that file. Everywhere you'll need to write code, you'll find a comment `TODO SI364`. Filling in code correctly in each of those spaces will allow you to complete this application so that it works!

You'll see examples of applications and database relationships in class (section and lecture) that will be examples similar to what you're doing here.

### Note

It's important that you make your PostgreSQL database for this HW assignment your uniqname, with HW4. For example, Jackie's would be `jczettaHW4`. Mauli's would be `maupandeHW4`. So your database URI in the `app.config` should look something like this (except replace my uniqname with yours!): `postgresql://localhost/jczettaHW4`

This will allow us to grade each of your projects without incurring conflicts between different students' databases!

## Files Included

* `templates` directory:

    * `all_tweets.html`
    * `all_users.html`
    * `index.html`

* `README.md` (this file, with instructions)
* `SI364_hw4.py` (the main Python file for the application)

You may add additional files or additional features/routes if you wish, but that is not required. It is required, in order to get full credit, that the TODOs as listed be completed and function. *We will not grade code that does not run, so make sure your application does run! Check with an instructor if you are having troubles with this.*
