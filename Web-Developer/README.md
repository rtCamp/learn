# Sample Challenges for Web Developers

If you can develop on WordPress, you can directly apply for [WordPress developer opening here](https://careers.rtcamp.com/wordpress-engineer/assignment/ "WordPress Developer Assignment"). At rtCamp, we believe coding should be fun. For the same reason, we have set up multiple challenges for you! Choose a challenge based on your interest/expertise. Rather than merely completing tasks/steps mentioned below, go ahead and use your own imagination to make your code as good as possible!

Rules of the Game
-----------------

*   Use git and Github from the start of your challenge.
*   Some challenges have multiple parts. It is must to complete all the parts.
*   Feel free to add any extra functionality you want to make your submission better.
*   Use of Google is allowed & encouraged. ;-)
*   You are also free to use 3rd party **php libraries**. But please mention if you use them.

### Web Hosting for Demo purpose

For all coding challenges below, you will need a web host to showcase your working demo. You can use free web hosting for your demo. Microsoft Azure, Google Cloud, Amazon AWS - all offer free trial plan. You can use any of these cloud providers or simply any free web hosting.

### Coding Guidelines

Before you choose a challenge, please note down our common minimum requirements applicable to all challenges.

1.  **UI Framework** - Use Twitter Bootstrap for frontend user interface. If you're good at CSS then don't use boostrap or any other CSS framework and mention that in assignment(this will be consider as plus point). Make sure what you create looks nice!
2.  **Responsive -** Your code must work on mobile devices like iPhone/Android.
3.  **Code Organisation** - All 3rd party codes, library must be inside `lib` folder. No unwanted files e.g. IDE files, temporary files should be committed on git-repo. _(Hint: Write a nice `.gitignore`)_
4.  **Coding Standard** - You can use PHP Code Sniffer and JSHint on localhost. Additionally, you can configure [scrutinizer-ci](https://scrutinizer-ci.com/) so your code quality can be seen easily.
5.  **Unit Testing** - You should use [phpunit testing library](https://phpunit.de). You should integrate travis or any other CI to run point 4 and 5. This will be considered as plus point and would be given priority in sorting.
6.  **GitHub Readme - **Write a nice GitHub Readme using markdown syntax. Make sure you include demo link, links to libraries and CI badge used in readme.

Failure to meet any of above guidelines will result in disqualification.

List of Challenges
------------------

Complete any one challenge from the following list. There is no time limit. Quality is more important.

1.  [Twitter-Timeline Challenge](#challenge-1-twitter-timeline-challenge)
2.  [Facebook-Album Challenge](#challenge-2-facebook-photos-challenge)

### Challenge-1: Twitter-Timeline Challenge

Create a small PHP-script to accomplish following parts: **Part-1: User Timeline**

1.  Start => User visits your script page.
2.  User will be asked to connect using his Twitter account using Twitter Auth.
3.  After authentication, your script will pull latest 10 tweets from his "home" timeline.
4.  10 tweets will be displayed using a pure CSS and Plain JS slideshow.

**Part-2: Followers Timeline**

1.  Below slideshow _(in step#4 from part-1)_, display list 10 followers (you can take any 10 random followers).
2.  Also, display a search followers box. Add auto-suggest support. That means as soon as the user starts typing, his followers will start showing up.
3.  When user will click on a follower name, 10 tweets from that follower's user-timeline will be displayed in the same slider, without page refresh (use AJAX).

**Part-3: Download Followers**

1.  There will be a download button to download all followers of any user(we will input user @handler).
2.  Download can be performed in one of the following formats i.e. You choose the format you want. It would act as an advantage if you give the option to download the followers in all the following formats: google-spreadsheet, pdf and xml formats.
3.  For Google-spreadsheet export feature, your app-user must have Google account. Your app should ask for permission to create a spreadsheet on user's Google-Drive.
4.  Once the user clicks download button (after choosing option) all followers of the specified user should be downloaded.

**Note –** We are aware of Twitter API limits for retrieving tweets/follower’s data although you have to overcome these by thinking outside the box, like we do at rtCamp. If you're not able to obtain developer account within the stipulated time then please attempt the [Facebook-Photos Challenge](#challenge-2-facebook-photos-challenge).

### Challenge-2: Facebook-Photos Challenge

Create a small PHP-script to accomplish following parts: **Part-1: Album Slideshow**

1.  User visits your script page
2.  User will be asked to connect using his FB account
3.  Once authenticated, your script will pull his album list from FB
4.  User will click on an album name/thumbnail
5.  A pure CSS and Plain JS slideshow will start showing photos in that album (in full-screen mode)

**Part-2: Download Album**

1.  Beside every album icon (step #4 in part-1), add a new icon/button saying "Download This Album"
2.  When the user clicks on that button, your script will fetch all photos in that album behind the scene and zip them inside a folder on server.
3.  You may start a "progress bar" as soon as user-click download button as download process may take time.
4.  Once zip building on server completes, show user link to zip file.
5.  When user clicks zip-file link, it will download zip folder without opening any new page.
6.  Beside album names, add a checkbox. Then add a common "Download Selected Album" button. This button will download selected albums into a common zip that will contain one folder for each album. Folder-name will be album-name.
7.  Also, add a big "**Download All**" button. This button will download all albums in a zip, similar to above.

**Part-3: Backup albums to Google Drive**

1.  Provide the user with an option to move albums to a Google Drive.
    *   The Google Drive will contain a master folder whose name will be of the format `facebook_<username>_albums` where `username` will be the Facebook username of the user.
    *   The user's Facebook albums will be backed up in this master folder. Photos from each album will go inside their respective folders. Folder names will be the same as the Facebook album names.
2.  To improve the user experience, include the three following buttons:
    *   "Move" button- This button will appear under each album on your website. When clicked, _the corresponding album only_ will be moved to Google Drive
    *   "Move Selected"- This button will work along with a checkbox system. The user can select a few albums via checkboxes and click on this button. _Only the selected albums_ will be moved to Google Drive
    *   "Move All"- This button will immediately move _all user albums_ to Google Drive within their respective folders.
3.  Make sure that the user is asked to connect to their Google account only once, no matter how many times they choose to move data.

**Note -** Before submitting your challenge for review, please add Facebook profile with username '[rtc.test](https://www.facebook.com/rtc.test)' as tester while your app is in development mode. This will expedite the review process.

Completed a Challenge?
----------------------

![](https://media.githubusercontent.com/media/rtCamp/hiring-assignments/master/img/hello-there.jpg)

Paste your GitHub repo link under ["Work Sample Link(s)" in this form](https://careers.rtcamp.com/web-engineer/#application-form---web-engineer-php). Complete and submit the form. We'll get in touch with you within one working day!

Questions? Doubts? Just wanna say hi🖖? Email us at [hr@rtcamp.com](mailto:hr@rtcamp.com)