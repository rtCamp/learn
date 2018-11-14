# Sample Challenges for Systems Engineers

Server monkeys. Automation enthusiasts. Command line inhabitants. Welcome! Below are a couple of challenges that you can start hacking away at over the coming weekend. Have fun!

Rules of the Game
-----------------

1.  Use only the latest Ubuntu Server to test your code.
2.  Include proper error-handling because we will be running your creation on a real server.
3.  Create a new [Github](https://github.com/) repo and commit all your code to this repo.
4.  Create a `readme.md` file in your project's root folder that will include the following info:
    1.  any assumptions you have made
    2.  the libraries you have used
    3.  instructions that explain how we can run/use your code.
5.  You need to complete either one of the challenges.

### Challenge A: Web Server Setup for WordPress

Create a command-line script, preferably in bash, to perform following tasks in order.

1.  Check if PHP, Mysql & Nginx are installed. If not present, install the missing packages
2.  Ask the user for a domain name _We will assume that the user enters "example.com"_
3.  Create a `/etc/hosts` entry for _example.com_ pointing to localhost
4.  Create an nginx config file for _example.com_
5.  Download the latest WordPress version and unzip it locally in _example.com_ document root _(Hint: Use [http://wordpress.org/latest.zip](http://wordpress.org/latest.zip))_
6.  Create a new Mysql database for WordPress with name “example.com\_db”
7.  Create a `wp-config.php` with proper DB configuration _(Hint: You can use_ `wp-config-sample.php` _as your template)_
8.  Fix any file permissions, clean up temporary files and restart/reload Nginx config
9.  Prompt the user to open _example.com_ in a browser if all goes well

### Challenge B: Blogging Command-Line App

Create a command-line blogging application which implements following commands in bash. You will need to use a database; consider using sqlite.

1.  `blog.sh` will return the name of your application
2.  `blog.sh --help` will list help text and commands available
3.  `blog.sh post add "title" "content"` will add a new blog a new blog post with the specified title and content
4.  `blog.sh post list` will list all blog posts
5.  `blog.sh post search "keyword"` will list all blog posts where “keyword” is found in the title and/or content
6.  `blog.sh category add "category-name"` will create a new category
7.  `blog.sh category list` will list all current categories
8.  `blog.sh category assign <post-id> <cat-id>` will assign the specified category to a post
9.  `blog.sh post add "title" "content" --category "cat-name"` will add a new blog post with the specified title, content and assign a category to it. If the category doesn’t exist, it will first be created.

Use your imagination to either improve the functionality of the above commands or add more of your own commands.

Completed a Challenge?
----------------------

![](https://media.githubusercontent.com/media/rtCamp/hiring-assignments/master/img/hello-there.jpg)

Paste your GitHub repo link under ["Work Sample Link(s)" in this form](https://careers.rtcamp.com/systems-engineer/#application-form-systems-engineer).

Complete and submit the form. We'll get in touch with you within one working day! Questions? Doubts? Just wanna say hi🖖? Email us at [hr@rtcamp.com](mailto:hr@rtcamp.com)