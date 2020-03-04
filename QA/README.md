# Quality Assurance Engineer

This assignment will assess both manual and automation testing skills. You must complete both parts.

# Automation Testing

### Script-Review

* For script-review, you must use [Github](https://github.com/)
* Create a free account on Github _(if you do not have an existing account there!)_
* Create a git repo for your code _(take help of Google to know how-to in case you have never used git before)_
* We will review your code only from Github, hence, please do NOT email your codes to our HR Team!

### Documentation Process

* Create scripts for test cases given below on [Codeception](https://codeception.com/)
* Keep all the automation code in Github root itself
* Create a Readme for your repo which will describe the following
  * A short description of the repo
  * How to set it up
  * How to run the code locally
* You can add screenshots to provide more details

### Test Cases


Test Objective | Expected Results
-------------- | ----------------
Login with valid username and password and should be able to successfully login | User should successfully log in
URL: https://qa.rtcamp.net/activity/ UN: demo PW: demo 
Login with invalid username and password and should not be able to login | User should get the error message, should not get logged in
Update the status of a post with any of the media type and privacy should be private | Media should be uploaded with private privacy
Create the album with any valid name with private privacy and upload 5 media inside that album URL: https://qa.rtcamp.net/members/demo/media/album/ | Album should be created with given name and privacy, 5 media should be uploaded successfully
Like/Unlike the media (Open any recently uploaded media, Click on like) | Media should show Unlike once liked and vice versa. If liked it should appear here https://qa.rtcamp.net/members/demo/media/likes/
Change cover image (Go to profile, Click on change cover image) | The cover image should be updated successfully

# Manual Testing
*   Please download the [Manual Testing Readme](https://github.com/rtCamp/hiring-assignments/blob/master/QA/QA%20Testing%20Readme.png).
*   Do the UI testing of qa.rtcamp.net web page w.r.t Readme file you have downloaded.
*   Also, check for responsiveness of the qa.rtcamp.net web page w.r.t below screen size[Portrait and Landscape mode both]
      * 360X640
      * 375X667
      * 414X736
      * 768X1024
*   Mark the issues using GitHub issues. Use the same repo as the one used for Automation Testing.
*   Attach the necessary screenshots to explain the bug description.

Challenge Completed?
--------------------

Share the GitHub repo link with us.
