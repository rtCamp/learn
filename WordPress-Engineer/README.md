# WordPress Engineer Assignment

**Already Developed on WordPress?** If you have already developed a plugin or theme on WordPress, you can use it as a work sample. Just make sure your code is complaint with the rules of the game.

As rtCamp is mainly into WordPress themes, plugins, customization, migrations & more, we have plenty of interesting work in every aspect of WordPress. Keeping that in mind, we have created a challenge for WordPress themes & plugins. Choose one which you like more!

Rules of the Game
-----------------

*   Some challenges have multiple parts. You must complete all parts.
*   Use of Google is allowed & encouraged. 😉
*   You are also free to use 3rd party libraries. But please mention if you use them.

### Web Hosting for Demo purpose

For all coding challenges below, you will need a web host to showcase your working demo. You can use a free web hosting for your demo. Microsoft Azure, Google Cloud, Amazon AWS – all offers free trial plan. You can use any of these cloud providers or simply any free web hosting.

### Coding Guidelines

Before you choose a challenge, please note down our common minimum requirements applicable to all challenges.

1.  **UI Framework** - Use Foundation/Bootstrap for CSS/JS. Make sure what you create looks nice!
2.  **Responsive** - Your code must work on mobile devices like iPhone/Android.
3.  **Code Organisation** - All 3rd party codes, library must be inside `lib` folder. No unwanted files e.g. IDE files, temporary files should be committed on git-repo. _(Hint: Write a nice `.gitignore`)_
4.  **Coding Standard** - Your code must pass WordPress coding standard. You can use PHP Code Sniffer and JSHint on localhost. Additionally, you can should configure [scrutinizer-ci](https://scrutinizer-ci.com/) so your code quality can be seen easily.
5.  **Unit Testing** - Submissions without unit tests will not be accepted. You may use [wp-cli to setup unit testing easily](http://wp-cli.org/blog/plugin-unit-tests.html).
6.  **Github Readme** - Write a nice Github Readme using markdown syntax. Make sure you include demo link and links to libraries used in readme.

Failure to meet any of above guidelines will result in disqualification.

List of Challenges
------------------

We have two kinds of challenges for WordPress:

1.  [WordPress Theme Challenges](#challenge-1-wordpress-theme-challenge)
2.  [WordPress Plugin Challenges](#challenge-2-wordpress-plugin-challenge)

You need to complete any one. If you wish to complete two, we won't mind. ;-)

### Challenge-1: WordPress Theme Challenge

Please create a WordPress theme based on details provided in the attachment. Attachment contains:

*   Original PSD file.
*   Sliced Images from PSD _(this will help if you do not have photoshop)_
*   Readme files with instructions.

Below are download links for two WordPress theme challenges, with different complexity levels. You can take any one based on your skills, expertise and interests.

*   [Simple PSD to WordPress Theme Assignment](https://github.com/rtCamp/hiring-assignments/releases/latest/download/PSD-to-WordPress-Simple-HomePage-Only.zip "Download Assignment")
*   [Complex PSD to WordPress Theme Assignment](https://github.com/rtCamp/hiring-assignments/releases/latest/download/PSD-to-WordPress-Complex-Home-Page-Only.zip "Download Assignment")

**Important Notes:**

*   You need to create a homepage only. Don't bother about inner-pages styling.
*   You must use WordPress "Theme Options Page" for different settings. Do not hard code a lot of stuff.
*   Please use [https://underscores.me/](http://underscores.me/) starter theme for this challenge



### Challenge-2: WordPress Plugin Challenge

There are already more than 10000 WordPress plugins out there. So it’s really hard to setup a challenge for you! Still, we need to create a playground for you. So we came up with a few ideas for plugin. Go ahead with any one below:

#### Challenge-2a: WordPress-Slideshow Plugin

This plugin will test if you are familiar with WordPress shortcodes. 

**Admin-Side:**

1.  Create an admin-side settings page.
2.  Provide an interface to add/remove images from plugin settings page.
3.  User must be able to change order of uploaded image. (Hint: Use [http://jqueryui.com/demos/sortable/#connect-lists](http://jqueryui.com/demos/sortable/#connect-lists) )

**Front-end:**

1.  Create provision for a shortcode like \[myslideshow\]
2.  When you add shortcode \[myslideshow\] to any page, it will be replaced by a slideshow of images uploaded from admin-side.
3.  You can use any jQuery slideshow library/plugin.

#### Challenge-2b: WordPress-Contributors Plugin

This plugin will test if you are familiar with [WordPress metabox](http://codex.wordpress.org/Function_Reference/add_meta_box) functionality. Goal is to create a plugin so that we can display more than one author-name on a post. 

**Admin-Side:**

1.  Add a new metabox, labeled "contributors" to WordPress post-editor page.
2.  This metabox will display list of authors (wordpress users) with a checkbox for each author.
3.  User (author/editor/admin) may tick one or more authors name from the list.
4.  When post saves, states of checkboxes for author-list in "contributors" box must be saved as well.

**Front-end:**

1.  Use a post-content filter.
2.  At the end of post, display a box called "Contributors".
3.  It will have list of authors checked for that post.
4.  Show contributor names with their Gravatars.
5.  Contributor-names must be clickable and will link to their respective "author" page.

Challenge Completed?
--------------------

Share the Demo working link and the GitHub repository link with us.
