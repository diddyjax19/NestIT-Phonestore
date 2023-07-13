# NestIt Store - An Online store App!

## [](https://github.com/diddyjax19/NestIT-Phonestore--pp4#)[![](screenshot/responsive.png)](screenshot/responsive.png)

The NestIt Phone Store is  regular store where people can go to browse and order from a variety of phone and accesories.The store is open 24 hrs with staffs processing order to meet the clients need, it also as a place where customers can register and be part of the community to receive deals and promotions. Through the The NestIt store, users can check thier orders and the status of the delivery,they are also aware of where the good are coming from.

A simple online market place built with the Django Framework using HTML, CSS and Javascript

This fictional site was created for Portfolio Project #4 (Full-Stack Toolkit) - Diploma in Full Stack Software Development Diploma at the [Code Institute](https://www.codeinstitute.net).

[View live website here](http://david158.pythonanywhere.com/)

![Responsive design](static/screenshot/responsive-nest.png)


## [](https://github.com/diddyjax19/NestIT-Phonestore#toc)Table of Contents



# Table of contents

  * [Project goals](https://github.com/diddyjax19/NestIT-Phonestore#project-goals)
  * [UX](https://github.com/diddyjax19/NestIT-Phonestore#ux)
     * [User stories](https://github.com/diddyjax19/NestIT-Phonestore#user-stories)
  
  * [Features ](https://github.com/diddyjax19/NestIT-Phonestore#features)
      * [Navigation](https://github.com/diddyjax19/NestIT-Phonestore#navigation-bar)
      * [Home page](https://github.com/diddyjax19/NestIT-Phonestore#home-page)
      * [Registration page](https://github.com/diddyjax19/NestIT-Phonestore#registration-page)
      * [Log In / Log Out page](https://github.com/diddyjax19/NestIT-Phonestore#registration-page)
      * [Categories](https://github.com/diddyjax19/NestIT-Phonestore#recipe-library)
      * [About](https://github.com/diddyjax19/NestIT-Phonestore#about) 
      * [Contact](https://github.com/diddyjax19/NestIT-Phonestore#contact)
      * [Cart](https://github.com/diddyjax19/NestIT-Phonestore#cart)
      * [Profile](https://github.com/diddyjax19/NestIT-Phonestore#Profile)
      * [Orders](https://github.com/diddyjax19/NestIT-Phonestore#orders)
      * [Change Password](https://github.com/diddyjax19/NestIT-Phonestore#change-password)
    

  * [Design](https://github.com/diddyjax19/NestIT-Phonestore#design)
      * [Colours](https://github.com/diddyjax19/NestIT-Phonestore#colours)
      * [Typography](https://github.com/diddyjax19/NestIT-Phonestore#typography)
      * [Images](https://github.com/diddyjax19/NestIT-Phonestore#images)
      * [Wireframes](https://github.com/diddyjax19/NestIT-Phonestore#wireframes)
  * [Libraries And Installed Packages](https://github.com/diddyjax19/NestIT-Phonestore#libraries-and-installed-packages)
  * [Testing](https://github.com/diddyjax19/NestIT-Phonestore#testing)

  * [Deployment](#deployment) 
  * [Technologies Used](#technologies-used)
  * [Credit](#credits)

 ![](./readmeDocumentation/screenshot/iAmResponsive.png)


# Project Goals
***
The NestIt Phone Store is  regular store where people can go to browse and order from a variety of phone and accesories.The store is open 24 hrs with staffs processing order to meet the clients need, it also as a place where customers can register and be part of the community to receive deals and promotions. Through the The NestIt store, users can check thier orders and the status of the delivery,they are also aware of where the good are coming from.

# UX
***
 ## User Stories 
 ***

My Project was developed with agile planning. I had three columns: To Do, In Progress, and Done. This helps me to manage my project and helps me to be more flexible and adaptable to changes.
Below are the User stories that were used in creating this project. I add 8 EPIC with labels MUST, SHOULD-HAVE.

[Link for User stories](https://github.com/Aliona83/project4--test/issues)

<details>
<summary>Click to see more</summary>

1 EPIC - Home Page and Navigation Bar

    * As a Site User I can easily navigate around the site so that I can view different pages. As a Site User, I want to see a home page with basic information about the app.
2 EPIC - Account registration 

    * As a Site User I want to be able to create an account and log in into my app with my username and password.

3 EPIC - Add CRUD functionality

    * As a Site User I want to browse the website. .
    * As a Site User I want to browse my categories.
    * As a Site User I want to update my cart.
    * As a Site User I want to delete cart from my cart page. 

4 EPIC - Create Recipe Form 

   * As a Site User I want to have a recipe form where I will be able to add all ingredients, and instructions, sort by meal type and be able to add an image of the recipe.

5 EPIC - Recipe page
    
   * As a Site User I want to have a separate page where I will be able to see all recipes that I save.

6 EPIC - Pagination 

   * As a Site User I want to see a number of pages in recipe page. 

7 EPIC - Search Bar 
   
   * As a Site User I want to be able search my recipes by ingredients and by type of meals(breakfast, lunch and dinner)
</details>

# Features  
  ***
<details>
<summary>Click to see more</summary>

 ## Navigation Bar

 ![](readmeDocumentation/screenshots/navigation-menu-web-not-login.png)

 * The navigation menu consists of Logo-text,Categories,About,contact, Log In and Create Account. By clicking on the Logo, the user can always return to the Home page. 
 If the User is new, he will have to register, and if the User already exists, he can easily Log In to his Nestit webpage. When the User login, some links on the navigation bar will change, and the user will be able to see the cart and My Account.

 ![](readmeDocumentation/screenshots/navigation-menu-web-loggedin.png)

 * Also on the small screen the navigation menu will be changed to the burger menu which shows all the navigation links.

 ![](./readmeDocumentation/screenshots/navigation-menu-mobile-loggedin.png)


 ## Home Page
 ![](readmeDocumentation/screenshots/homepage.png)

 * The home page has a welcome message and a short description of the application. At the bottom are three bright images of a recipe with the small guide on what users can do with this app.

 ## Registration page
  
 * Django allauth was installed and used to create the Sign-Up, Login, and Log Out functionality and pages

   * Sign UP

 * The user has to fill up the fields in the registration form: username, email, and password. If the User already exists they can click on the top page Sign In button, and will be transferred to the log-in form.
 ![](readmeDocumentation/screenshots/create-account.png)
   
   * Log In

 * Log in form is similar to Sign up, only has a few fields username and a password. If the User forgotten to register as a new user,on the top of the Sign Up page there is a Sign Up link were the user can Sign Up. 
 ![](readmeDocumentation/screenshots/signup.png)

   * Success/unsuccess messages 

 * Success messages inform the user if they already have an account, enter the wrong password or username or enter the short password by creating a new account user.
 ![](readmeDocumentation/screenshots/user-existalready.png)
 ![](readmeDocumentation/screenshots/incorrect-password.png)
 ![](readmeDocumentation/screenshots/password-2short.png)

 ## Categories 

 * This is the main page where all created categories are saved. Under each category is the title of the manufacturer of the phone.

 ![](readmeDocumentation/screenshots/catergories.png)


 * By clicking on the image of the category, the user will be see all the phones avaliable from that manufacturer.

 ![](readmeDocumentation/screenshots/catergories-2.png)

 * At selecting the phone he is then redirected to the product description.In this section the user can view all the specification and the price.In this section the user is able to get see a  complete detail of the product and also see similar products.

 ![](readmeDocumentation/screenshots/Product-detail.png)

 ![](readmeDocumentation/screenshots/Product-detail2.png)

 ![](readmeDocumentation/screenshots/Product-detail2.png)

   * About Us 

 * This section tell the user a brief description of the website and a hiistory of the website.

 ![](readmeDocumentation/screenshots/about-us.png)

   * Contact Page

 * In this section,the user has the opportunity to contact us directly or reach out to make enquiry.

 ![](readmeDocumentation/screenshots/contact.png)

   * Like/ unlike button

 * Under each recipe, there is a like button where the user can like the recipe that he likes or leave unlike. A Like button was created in the shape of a heart. If the user liked the recipe, the heart will turn red; if the recipe is not liked, the heart will be white un text will be unlike.
   
 ![](./readmeDocumentation/screenshot/likeButton.png)
 ![](./readmeDocumentation/screenshot/unlike%20button.png)
   
   * Success Messages

  * The user will be getting success message if the recipe were successfully delete, add or updated

  ![](./readmeDocumentation/screenshot/deleteRecipe.png)
  ![](./readmeDocumentation/screenshot/addRecipe.png)
  ![](./readmeDocumentation/screenshot/updateRecipe.png)
 
 ## Add Recipe page

 ![](./readmeDocumentation/screenshot/addRecipeForm.png)

 * Each registered user will be able to add a recipe to this application. The recipe form consists of the recipe's title, description, recipe ingredients, recipe instructions, add image and sort recipes by meal type(breakfast, lunch, dinner).

</details>

 # Design 
  ***
## Colours

 ![](./readmeDocumentation/screenshot/coloursUsed.png)

  * The colour scheme was chosen by the background image of the project. I want to choose golden-brown colours so that they will blend with the background image.

 For the navigation bar and footer, I used --earthyellow: #e6b56d;,--copper: #a67732; and  --Sunset: #f2c88b.
 For all buttons that exist in the project I used  --smokyblack: #131200; and --copper: #a67732;
 For the jumbotron background colour I used --Sunset: #f2c88b.
 For paragraph and heading I used --smokyblack: #131200;
 For pagination I used background colour --copper: #a67732; and for border-colour --Sunset: #f2c88b.

## Typography

* The font chosen for the website is a font called Merriweather. I used this font because Merriweather font is ideal for text-dense design: the letterforms have a tall x-height but remain relatively small, making for excellent readability across screen sizes while not occupying extra horizontal space. The font was found on [Google Font](https://fonts.google.com/) and imported to the website through a CSS import.

## Images

* All images were all taken from [Pexels](https://www.pexels.com/ru-ru/). 

## Wireframes

[Link to wireframes](https://github.com/Aliona83/project4--test/tree/main/readmeDocumentation/wireframes)

# Libraries And Installed Packages
***
  * Django -crispy-forms - Used to render forms throughout the project.
  * Django - allauth - Allows authentication, registration and account management in Django.
  * Gunicorn - a Python WSGI HTTP Server for UNIX
  * Dj3-Cloudinary-storage - Facilitates integration with Cloudinary by implementing Django Storage API.


# Testing 
***

Details of all testing done can be viewed in depth in the 

[Link to TESTING.md](https://github.com/diddyjax19/NestIT-Phonestore--pp4/blob/main/TESTING.md) document.

 ## [](https://github.com/diddyjax19/NestIT-Phonestore--pp4#deployment)Deployment

### [](https://github.com/diddyjax19/NestIT-Phonestore--pp4#forking-the-github-repository)Forking the GitHub Repository

1.  Go to [the project repository](https://github.com/diddyjax19/Taskit-FrontEnd)
2.  In the right most top menu, click the "Fork" button.
3.  There will now be a copy of the repository in your own GitHub account.

### [](https://github.com/diddyjax19/NestIT-Phonestore--pp4#running-the-project-locally)Running the project locally

1.  Go to [the project repository](https://github.com/diddyjax19/Taskit-FrontEnd)
2.  Click on the "Code" button.
3.  Choose one of the three options (HTTPS, SSH or GitHub CLI) and then click copy.
4.  Open the terminal in you IDE program.
5.  Type `git clone` and paste the URL that was copied in step 3.
6.  Press Enter and the local clone will be created.

### [](https://github.com/diddyjax19/NestIT-Phonestore--pp4#alternatively-by-using-gitpod)Alternatively by using Gitpod:

1.  Go to [the project repository](https://github.com/diddyjax19/Taskit-FrontEnd)
2.  Click the green button that says "Gitpod" and the project will now open up in Gitpod.

### [](https://github.com/diddyjax19/NestIT-Phonestore--pp4#deploying-with-Netlify)Deploying with Netlify

1.  Go to [https://www.netlify.com/](https://www.netlify.com/) and log in; if you do not already have an account then you will need to create one.

#### [](https://github.com/diddyjax19/NestIT-Phonestore--pp4#Netlify-deployment)Netlify Deployment

1.  On Netlify’s dashboard, select the Site tab. Next, click on Add new site and then select Deploy manually from the drop-down menu options.
[![Netlify](screenshot/Netlify1.PNG)](screenshot/Netlify1.PNG)

2.  In the drag-and-drop feature page, select the folder containing the React build files and drop it into this user interface. The project will instantly deploy on Netlify.
[![Netlify](screenshot/netlify2.PNG)](screenshot/netlify2.PNG)

*  Alternatively, you can click on Browse to upload to select your build folder from the file system. On Netlify’s dashboard, select the Site tab. Next, click on Add new site and then select Deploy manually from the drop-down menu options.

# Technologies Used

* [GitHub](https://github.com/Aliona83/project4--test) - is Used in conjunction with Gitpod as the code editor, to store the project and utilise git version control.
* [Heroku](https://dashboard.heroku.com/apps/project4-recipe/deploy/github) -  Used to deploy and host the finished product.
* [Cloudinary](https://cloudinary.com/ip/gr-sea-gg-brand-home-base?utm_source=google&utm_medium=search&utm_campaign=goog_selfserve_brand_wk22_replicate_core_branded_keyword&utm_term=1329&campaignid=17601148700&adgroupid=141182782954&keyword=cloudinary&device=c&matchtype=e&adposition=&gad=1&gclid=CjwKCAjwhdWkBhBZEiwA1ibLmOvYU6owOOD0_4WV0wjEeSKAO26vKCB4t7DVKWyjJLhud_3K3Y0DFRoCQBIQAvD_BwE) -  Used as cloud-based storage, storing any submitted media in the deployed application.
* [ElephantSQ](https://customer.elephantsql.com/login) - Used to host the PostgreSQL database for the application.
* [W3C](https://validator.w3.org/) - HTML Used to validate all HTML code.
* [W3C](https://jigsaw.w3.org/css-validator/) - CSS Used to validate all CSS code.
* [CI PEP8](https://pep8ci.herokuapp.com/) -  Testing Used to validate all Python code.
* [Google Fonts](https://fonts.google.com/) - Used to provide the fonts used in application styling.
* [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) - Used to aid the implementation of styling and responsiveness.
* [Fontawesome](https://fontawesome.com/) - is Used to implement effective icons.
* Google Chrome Dev Tools -  Used during the development to debug and test responsiveness.
* [Balsamiq](https://balsamiq.com/wireframes/?gad=1&gclid=CjwKCAjwhdWkBhBZEiwA1ibLmBf4umD1_GJ4rfxmLez1jQMyL3j_-olvsWrn5Rgxvvae-sQbboRbaRoC-eAQAvD_BwE) - Used to build both the database schema diagram and design wireframes.
* [Pexel](https://www.pexels.com/search/free/) - All mages were taken from this website.
* [Color palette](https://coolors.co/) - Select colors for website.
* [Ax Dev Tools](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd) - Find and fix more accessibility issues during website development with axe DevTools. 
     
# Credits    
* [Stack Overflow](https://try.stackoverflow.co/explore-teams/?utm_source=adwords&utm_medium=ppc&utm_campaign=kb_teams_search_brand_emea-dach&_bt=657236278309&_bk=stack+overflow&_bm=p&_bn=g&gclid=CjwKCAjwhdWkBhBZEiwA1ibLmF2ghGSQXiKfjiQcnpRL_87pacwew2yt-jYDV9_z56sxtUF-BMthsRoCB7oQAvD_BwE)
* [BBC good food](https://www.bbcgoodfood.com/)
* [Codemy.com](https://www.youtube.com/watch?v=B40bteAMM_M&list=PLCC34OHNcOtr025c1kHSPrnP18YPB-NFi) 
* [Django documentation](https://docs.djangoproject.com/en/4.2/)
* [LinkedIn Learning](https://www.linkedin.com/learning/paths/become-a-django-developer)
* [E-commerce website with django](https://www.youtube.com/watch?v=YZvRrldjf1Y)
* [Codecademy](https://www.codecademy.com/?g_network=g&g_productchannel=&g_adid=528849219280&g_locinterest=&g_keyword=codecademy&g_acctid=243-039-7011&g_adtype=&g_keywordid=kwd-41065460761&g_ifcreative=&g_campaign=account&g_locphysical=1007835&g_adgroupid=70492864474&g_productid=&g_source={sourceid}&g_merchantid=&g_placement=&g_partition=&g_campaignid=1726903838&g_ifproduct=&utm_id=t_kwd-41065460761:ag_70492864474:cp_1726903838:n_g:d_c&utm_source=google&utm_medium=paid-search&utm_term=codecademy&utm_campaign=INTL_Brand_Exact&utm_content=528849219280&g_adtype=search&g_acctid=243-039-7011&