# Food Blog - Introduction

Portfolio project for Code Institute Full-stack development program.
This project is a Full Stack website built with the Django framework. Food Blog is a blog with recipes
where users can share their own favorite recipes with each other. When the user is logged in, they can too
like/unlike a post and comment on a post. They can also share their favorite recipes by adding a post
on the book page and upload or update their username.

[Live Project Here]()



README Table Content

- [Tasty Blog - Introduction](#tasty-blog---introduction)
  - [User Experience - UX](#user-experience---ux)
    - [User Stories](#user-stories)
    - [Agile Methodology](#agile-methodology)
    - [The Scope](#the-scope)
      - [Main Site Goals](#main-site-goals)
  - [Design](#design)
      - [Colours](#colours)
      - [Typography](#typography)
      - [Imagery](#imagery)
    - [Wireframes](#wireframes)
  - [Database Diagram](#database-diagram)
  - [Features](#features)
    - [Home Page](#home-page)
    - [Home Page - Highlight Posts](#home-page---highlight-posts)
    - [About Page](#about-page)
    - [Blog Page](#blog-page)
    - [Post Detail Page - Top](#post-detail-page---top)
    - [Post Detail Page - Steps](#post-detail-page---steps)
    - [Post Detail Page - Comments](#post-detail-page---comments)
    - [Edit Comments Page](#edit-comments-page)
    - [Contact Page](#contact-page)
    - [Categories Page](#categories-page)
    - [Categories Results](#categories-results)
    - [Books Page](#books-page)
    - [Add/Edit Books Page](#addedit-books-page)
    - [Search Box](#search-box)
    - [Search Results Page](#search-results-page)
    - [Search Results - Input Empty](#search-results---input-empty)
    - [Search Results - No Results Found](#search-results---no-results-found)
    - [Signup Page](#signup-page)
    - [Login Page](#login-page)
    - [Logout Page](#logout-page)
    - [User Profile Page](#user-profile-page)
    - [Navbar](#navbar)
    - [Footer](#footer)
  - [Messages and Interaction With Users](#messages-and-interaction-with-users)
    - [Sign up](#sign-up)
    - [Login](#login)
    - [Logout](#logout)
    - [Profile Update](#profile-update)
    - [Like Post](#like-post)
    - [Unlike Post](#unlike-post)
    - [Comment Post](#comment-post)
    - [Comment Post - 2](#comment-post---2)
    - [Delete/Edit Comment](#deleteedit-comment)
    - [Delete Comment - 1](#delete-comment---1)
    - [Delete Comment - 2](#delete-comment---2)
    - [Edit Comment](#edit-comment)
    - [Email Sent - Success](#email-sent---success)
    - [Email Sent - Failed](#email-sent---failed)
    - [Add Book](#add-book)
    - [Edit Book](#edit-book)
    - [Delete Book 1](#delete-book-1)
    - [Delete Book 2](#delete-book-2)
    - [Empty Search](#empty-search)
    - [No Search Found](#no-search-found)
  - [Admin Panel/Superuser](#admin-panelsuperuser)
  - [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
      - [Django Packages](#django-packages)
    - [Frameworks - Libraries - Programs Used](#frameworks---libraries---programs-used)
    - [Testing](#testing)
  - [Creating the Django app](#creating-the-django-app)
  - [Deployment of This Project](#deployment-of-this-project)
  - [Final Deployment](#final-deployment)
  - [Forking This Project](#forking-this-project)
  - [Cloning This Project](#cloning-this-project)
  - [Credits](#credits)
    - [Content](#content)
    - [Information Sources / Resources](#information-sources--resources)
  - [Special Thanks](#special-thanks)

## User Experience - UX

### User Stories

* As a website user, I can:

1. Navigate around the site and easily view the desired content.
2. View a list of recipes and choose accordingly.
3. Click on post to read the recipe details.
4. Register for an account to avail of the services offered to members.
5. View the number of likes on a recipe thereby showing which is most popular.
6. View comments on recipes so that I can read other users opinions.

* As logged in website user, I can:

1. Like/unlike recipes marking the recipes I enjoyed.
2. Comment on recipes and give my opinion about the posts.
3. Delete my previous comments.
4. Manage my profile by updating my details and user image.
5. Share my favourites recepies by posting them on the blogs Page.
6. Edit my favourite recepie posted previously.
7. Delete my favourite recepie posted previously.
8. Logout from the website.

* As a website superuser, I can:

1. Create and publish a new recipe.
2. Create draft recipe posts that can be reviewed and finalised later.
3. Create a new user, recipes, author and categories.
4. Delete user, recipes, author, categories and comments.
5. Approve user's comments.
6. Edit user's favourite recepie that was posted previously.
7. Delete user's favourite recepie that was posted previously.
8. Change the website permissions for a user.

### Agile Methodology


### The Scope

#### Main Site Goals

* To provide users with a good experience when using the food recipes website.
* To provide users with a visually pleasing website that is intuitive to use and easy to navigate.
* To provide a website with a clear purpose.
* To provide role-based permissions that allows user to interact with the website.

#### Design
I have been inspired by: https://tasty-blog-portfolio-project-4.herokuapp.com/cosmopolitan-cocktail/ and I Think Therefore I Blog - https://learn.codeinstitute.net/ci_program/diplomainfullstacksoftwarecommoncurriculum

#### Colours

![Colours Palete](./media/Colors-pp4.png)<br>

* I created the palette because I wanted to get an impression of a whole with a soft feel. The colors are a mixture of dark and light in the same tone, which makes it restful for the eyes. The purpose of this website is to create a good looking website with an appealing color scheme, my colors were chosen and made in colors: https://coolors.co/

#### Typography

* The fonts used for this project were from https://fonts.google.com/

#### Imagery

* All the imagery is related to the recipes and website design.
The remaining imagery will be uploaded by the author to the database.

### Wireframes

Wireframes for this project can be located [here](WIREFRAMES.md)


## Features

### Home Page

![Home Page]()


### About Page

![About Page]()



### Blog Page

![Blog Page]()


##



### Post Detail Page - Comments

![Post Detail Page - Comments]()

* At the bottom of this page, users can read the comments posted by other users. If the user is logged in or is a 
superuser they have access to the buttons for deleting or updating comments. But now its an error so that has to be fixt

### Edit Comments Page

![Edit Comments Page]()

* On this page, users are allowed to comment, delete and edit their own post comments. The website superuser can 
 delite ther comment. But now its an error so that has to be fixt



### Signup Page

![Signup Page]()

* On the Signup Page, a new user can sign up for the Tasty Blog website by filling out and then submitting the form. But now its an error so that has to be fixt.

### Login Page

![Login Page]()

* On the Login Page, users can log in to the website by inputting the username and password and have access 
  to website services for a user registered.

### Logout Page

![Logout Page]()

* On the Logout Page, users can confirm that they wish to exit the website.


### Navbar

![Navbar]()

* The navigation bar is present at the top of every page and houses all links to the various other pages.
* The options to Register or Log in will change to the option to log out once a user has logged in.
* Once a user has signed in, more options such as profile page and user image will be available in the navbar.
* A search icon is nested in the navbar and once clicked it will open the search box.
* The navbar is fully responsive, collapsing into a hamburger menu when the screen size becomes smaller.

![Navbar]()
* In the navbar users can access the categories list by clicking on the dropdown menu.

### Footer

![Footer]()
* On the website footer, users can see basic information about the blog such as contact, social media, 
  copyright.

## Messages and Interaction With Users


### Sign up

![Sign up]()

* When users sign up to the website they will see a message at the top of the page saying "Successfully signed in as
(username)".<br>

### Login

![Login]()

* When users sign in to the website they will see a message at the top of the page saying "Successfully signed in as
(username)".<br>

### Logout

![Logout]()

* When users log out of the website they will see a message at the top of the page saying "You have signed out".<br>
  

### Like Post

![Like Post]()
* *When users are logged in to the website they can like a post and they will see a message at the top of the page 
  saying "You have liked this post".<br>

### Unlike Post

![Unlike Post]()

* When users are logged in to the website they can unlike a post that has been liked by the user and they will see a message 
  at the top of the page saying "You have unliked this post".<br>

### Comment Post

![Comment Post]()

* When users are logged in to the website they can comment on a post and after they submit the comment they will see a 
  message at the top of the page saying "Your comment was sent successfully and is awaiting approval".But now its an error so that has to be fixt<br>

### Comment Post - 2

![Comment Post - 2]()

* After a user submits a comment, they will see a message over the input comment saying "Thanks (username). Your 
  comment is awaiting approval! <br>

### Delete/Edit Comment

![Delete Comment]()

* When users are logged in to the website and they have previously posted a comment or if the user is a superuser they will see the 
Delete and Edit buttons at the bottom of comments.But now its an error so that has to be fixt<br>

### Delete Comment - 1

![Delete Comment - 2]()

* If they wish to delete their comment, they can press the button Delete and a Bootstrap box model will pop up with the message 
  "Are you sure you want to delete your comment?".But now its an error so that has to be fixt<br>

### Delete Comment - 2

![Delete Comment - 3]()

* After pressing the Delete button again inside the Bootstrap box model they will see a message on the 
  top of the page, "Your comment was deleted successfully".But now its an error so that has to be fixt<br>

### Edit Comment

![Edit Comment]()

* After pressing the Update, users will see a message on the top of the page, "The comment was successfully updated".But now its an error so that has to be fixt<br>



## Admin Panel/Superuser
![No Search Found]()

* On the Admin Panel, as an admin/superuser I have full access to CRUD functionality so I can view, create, edit and
delete the following ones:
1. Posts
2. Comments
3. Author
4. Categories

   
*As admin/superuser I can also approve comments, approve posts and change the status and give other permissions to the users.<br>

## Technologies Used

### Languages Used

* [HTML 5](https://en.wikipedia.org/wiki/HTML/)
* [CSS 3](https://en.wikipedia.org/wiki/CSS)
* [JavaScript](https://www.javascript.com/)
* [Django](https://www.python.org/)
* [Python](https://www.djangoproject.com/)

#### Django Packages

* [Gunicorn](https://gunicorn.org/)<br>
   As the server for Heroku
* [Cloudinary](https://cloudinary.com/)<br>
   Was used to host the static files and media
* [Dj_database_url](https://pypi.org/project/dj-database-url/)<br>
   To parse the database URL from the environment variables in Heroku
* [Psycopg2](https://pypi.org/project/psycopg2/)<br>
   As an adaptor for Python and PostgreSQL databases
* [Summernote](https://summernote.org/)<br>
   As a text editor
* [Allauth](https://django-allauth.readthedocs.io/en/latest/installation.html)<br>
   For authentication, registration, account
   management
* [Crispy Forms](https://django-crispy-forms.readthedocs.io/en/latest/)<br>
   To style the forms

### Frameworks - Libraries - Programs Used

* [Bootstrap](https://getbootstrap.com/)<br>
   Was used to style the website, add responsiveness and interactivity
* [Jquery](https://jquery.com/)<br>
   All the scripts were written using jquery library
* [Git](https://git-scm.com/)<br>
   Git was used for version control by utilizing the Gitpod terminal to commit to Git and push to GitHub
* [GitHub](https://github.com/)<br>
   GitHub is used to store the project's code after being pushed from Git
* [Heroku](https://id.heroku.com)<br>
   Heroku was used to deploy the live project
* [PostgreSQL](https://www.postgresql.org/)<br>
   Database used through heroku.
* [VSCode](https://code.visualstudio.com/)<br>
   VSCode was used to create and edit the website
* [Lucidchart](https://lucid.app/)<br>
   Lucidchart was used to create the database diagram
* [PEP8](http://pep8online.com/)<br>
   PEP8 was used to validate all the Python code
* [W3C - HTML](https://validator.w3.org/)<br>
   W3C- HTML was used to validate all the HTML code
* [W3C - CSS](https://jigsaw.w3.org/css-validator/)<br>
   W3C - CSS was used to validate the CSS code
* [Fontawesome](https://fontawesome.com/)<br>
   To add icons to the website
* [Google Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)<br>
   To check App responsiveness and debugging
* [Google Fonts](https://fonts.google.com/)<br>
   To add the 2 fonts that were used throughout the project
* [Balsamiq](https://balsamiq.com/)<br>
   To build the wireframes for the project
* [PIXLR](https://pixlr.com)<br>
   To convert the images to webp format
* [CANVA](https://www.canva.com/)<br>
   To build the logos for the project
* [Coolors](https://coolors.co/)<br>
   To build the colour palette of the project
* [Emailjs](https://www.emailjs.com/)<br>
   To send emails from the contact form

### Testing

Testing results [here]()

## Creating the Django app

1. Go to the Code Institute Gitpod Full Template [Template](https://github.com/Code-Institute-Org/gitpod-full-template)
2. Click on Use This Template
3. Once the template is available in your repository click on Gitpod
4. When the image for the template and the Gitpod are ready open a new terminal to start a new Django App
5. Install Django and gunicorn: `pip3 install django gunicorn`
6. Install supporting database libraries dj_database_url and psycopg2 library: `pip3 install dj_database_url psycopg2`
7. Create file for requirements: in the terminal window type `pip freeze --local > requirements.txt`
8. Create project: in the terminal window type django-admin startproject your_project_name
9. Create app: in the terminal window type python3 manage.py startapp your_app_name
10. Add app to the list of installed apps in settings.py file: you_app_name
11. Migrate changes: in the terminal window type python3 manage.py migrate
12. Run the server to test if the app is installed, in the terminal window type python3 manage.py runserver
13. If the app has been installed correctly the window will display The install worked successfully! Congratulations!

## Deployment of This Project

* This site was deployed by completing the following steps:

1. Log in to [Heroku](https://id.heroku.com) or create an account
2. On the main page click the button labelled New in the top right corner and from the drop-down menu select Create New
App
3. You must enter a unique app name
4. Next select your region
5. Click on the Create App button
6. Click in resources and select Heroku Postgres database
7. Click Reveal Config Vars and add a new record with SECRET_KEY
8. Click Reveal Config Vars and add a new record with the `CLOUDINARY_URL`
9. Click Reveal Config Vars and add a new record with the `DISABLE_COLLECTSTATIC = 1`
10. The next page is the project’s Deploy Tab. Click on the Settings Tab and scroll down to Config Vars
11. Next, scroll down to the Buildpack section click Add Buildpack select python and click Save Changes
12. Scroll to the top of the page and choose the Deploy tab
13. Select Github as the deployment method
14. Confirm you want to connect to GitHub
15. Search for the repository name and click the connect button
16. Scroll to the bottom of the deploy page and select the preferred deployment type
17. Click either Enable Automatic Deploys for automatic deployment when you push updates to Github

## Final Deployment 

1. Create a runtime.txt `python-3.8.13`
2. Create a Procfile `web: gunicorn your_project_name.wsgi`
3. When development is complete change the debug setting to: `DEBUG = False` in settings.py
4. In this project the summernote editor was used so for this to work in Heroku add: `X_FRAME_OPTIONS = SAMEORIGIN `to
   settings.py.
5. In Heroku settings, delete the config vars for `DISABLE_COLLECTSTATIC = 1`

## Forking This Project

* Fork this project by following the steps:

1. Open [GitHub](https://github.com/PedroCristo/portfolio_project_4)
2. Find the 'Fork' button at the top right of the page
3. Once you click the button the fork will be in your repository

## Cloning This Project


## Credits

### Content

* All food recipes were taken from [mathem](https://www.mathem.se)
* The images were sourced from [istockphoto](https://www.istockphoto.com/)
* 

### Information Sources / Resources

* [W3Schools - Python](https://www.w3schools.com/python/)
* [Stack Overflow](https://stackoverflow.com/)


## Special Thanks

* Special thanks to my mentor Martina for their help.



