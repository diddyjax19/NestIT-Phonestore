
# Table of Contents
 * [Validator Testing](https://github.com/diddyjax19/NestIT-Phonestore--pp4#validator-testing)
   * [HTML](https://github.com/diddyjax19/NestIT-Phonestore--pp4#html-validator)
   * [CSS](https://github.com/diddyjax19/NestIT-Phonestore--pp4#css-validator)
   * [PYTHON](https://github.com/diddyjax19/NestIT-Phonestore--pp4#python)
   * [LIGHTHOUSE](https://github.com/diddyjax19/NestIT-Phonestore--pp4#lighthouse)
   * [GTMETRIX](https://github.com/diddyjax19/NestIT-Phonestore--pp4#gtmetrix)
   

 * [Device Testing](https://github.com/diddyjax19/NestIT-Phonestore--pp4#device-testing)
 * [Manual Testing](https://github.com/diddyjax19/NestIT-Phonestore--pp4#manual-testing)
 * [Bugs](https://github.com/diddyjax19/NestIT-Phonestore--pp4#bugs)

# Validator Testing
<details>
<summary>Click to see more</summary>

  ## HTML Validator

  * Home Page
    ![](https://validator.w3.org/nu/?doc=http%3A%2F%2Fdiddy.pythonanywhere.com%2F)
    * Category Page
    ![](https://validator.w3.org/nu/?doc=http%3A%2F%2Fdiddy.pythonanywhere.com%2Fcategories%2F)
    * Cart Page
    ![](https://validator.w3.org/nu/?doc=http%3A%2F%2Fdiddy.pythonanywhere.com%2Fcart%2F)
    * Profile Page
    ![](https://validator.w3.org/nu/?doc=http%3A%2F%2Fdiddy.pythonanywhere.com%2Faccounts%2Fprofile%2F)
     * Order Page
    ![](https://validator.w3.org/nu/?doc=http%3A%2F%2Fdiddy.pythonanywhere.com%2Faccounts%2Fprofile%2F)
    * Log In
    ![](https://validator.w3.org/nu/?doc=http%3A%2F%2Fdiddy.pythonanywhere.com%2Faccounts%2Flogin%2F)
    * Sign-Up Page
    ![](https://validator.w3.org/nu/?doc=http%3A%2F%2Fdiddy.pythonanywhere.com%2Faccounts%2Fregister%2F)


 ## CSS Validator

  * Css 
  ![](https://jigsaw.w3.org/css-validator/validator?uri=http%3A%2F%2Fdiddy.pythonanywhere.com%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

## Note
  - Probably gets flagged because its outdated but you need it for older browsers. Vendor prefixes increase compatibility with older browsers.

  - W3's never validate because its browser specific. W3's validators validate based on the official standards. Things that other browsers add in will always be flagged

## Python

 Store folder 
 All available files have been checked
  * form.py
  ![](./readmeDocumentation/screenshot/formFile.png)
  * model.py
  ![](./readmeDocumentation/screenshot/modelfile.png)
  * url.py
  ![](./readmeDocumentation/screenshot/urlFile.png)
 
 Phones Store
    * url.py
    ![](./readmeDocumentation/screenshot/recipeUrl.png)
    * view.py
    ![](./readmeDocumentation/screenshot/recipeView.png)

## Note
 -  Most of the issues where about the number of line is 2 long,this should be > 79 characters.)

</details>


## Lighthouse

<details>
<summary>Click to see more</summary>

 * Home Page
     * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/web-lighthouse.png)
     * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/mobile-lighthouse.png)
 
 * Categories
    * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/category-lighthouse-web.png)
    * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/category-lighthouse-mobile.png)
   
  * About 
    * Desktop
 ![Desktop](readmeDocumentation/pythonanywhere/about-us-lighthouse-web.png)
     * Mobile
 ![Mobile](readmeDocumentation/pythonanywhere/about-us-lighthouse-mobile.png)

  * Contact Page 
     * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/conntact-lighthouse-web.png)
     * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/conntact-lighthouse-mobile.png)
  
  * Cart Page
 * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/cart-lighthouse-web.png)
    * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/cart-lighthouse-mobile.png)
  
  * Profile
  * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/profile-lighthouse-web.png)
    * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/profile-lighthouse-mobile.png)

   * Orders
 * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/order-lighthouse-web.png)
    * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/order-lighthouse-mobile.png)

   * Change Password Page
  * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/change-password-lighthouse-web.png)
    * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/change-password-lighthouse-mobile.png)

   * SignUp Page 
    * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/signup-lighthouse-web.png)
    * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/signup-lighthouse-mobile.png)

  * LogIn Page
 * Desktop
  ![Desktop](readmeDocumentation/pythonanywhere/login-lighthouse-web.png)
    * Mobile
  ![Mobile](readmeDocumentation/pythonanywhere/login-lighthouse-mobile.png)


  </details>

   ## GTMETRIX 
   ![](readmeDocumentation/pythonanywhere/gtmatrix.png)

  

    # Device Testing
     ***

     The project has been checked on these devices :
       
    * iMac 
    * iPad Apple
    * MacBook Pro
    * Samsung Galaxy Tablet
    * Iphone 6
    * Iphone 11
    * Chrome
    * Firefox
    
    On all these devices the project worked perfectly, and no errors were detected.

   # Manual Testing

<details>
<summary>Click to see more</summary>

(1)

| Feature       |           Test Performed    |             Result           |        
|:--------------|:--------------------------- |:---------------------------  |
|                        Navigation                                        |
| Logo          | Clicked on Logo to check or redirect to the home page| Pass |
| Home button   | Clicked on the Home button from different pages to check or redirect to the home page| Pass  | 
| Categories   | Clicked on the categories and was redirected to the categories section | Pass |
| Sign-Up     | When clicking on the Sign-Up link, brings the User to the registration page | Pass |
| Small screens |  Checked that on smaller devices changes to the burger menu | Pass |
| About US      | Clicked About US and was redirected to the page with brief info on the | Pass | 
| Log In        | Clicked on the log-in link that will bring the User to the login page  | Pass |
| Log Out       | Clicked on the log-out link that will bring the User to log out page | Pass |
|                                                         Footer                      |
| Small screens |       Checked that all media links are visible on small devices | Pass |                                |
| Media  Links  | Clicked on each media link opens a new page   | Pass |
| Footer is on all pages      | Check all pages how the footer looks   | Pass |


(2)

| Feature       |           Test Performed    |             Result           |        
|:--------------|:--------------------------- |:---------------------------  |
|                        Categories                                      |
| Categories Page      | For this test, I want to make sure that when you clicked the full menu of all categories.| Pass |
| All Categories Button   | For this test, I want to make sure that when you clicked the full menu of all categories.| Pass  | 
| Sub-Category Overview  | For this test, I want to make sure that when you click the product ,it open up an overview of all the different products in that sub-Category.  | Pass |
| Products    | For this test, I want to make sure that when you click on a product,you are redirected to a Products Overview. | Pass |
| Products Overview|  For this test, I have a clear overview of all details of the product with descriptions,ratings and add-cart button. | Pass |
| View form on different sizes of devices | Check how will look categories form on tablets and phones, make sure all form fields are easy to see and use | Pass | 
| Log In        | Clicked on the log-in link that will bring the User to the login page  | Pass |
| Log Out       | Clicked on the log-out link that will bring the User to log out page | Pass |
|                                                         Footer                      |
| Small screens |       Checked that all media links are visible on small devices | Pass |                                |
| Media  Links  | Clicked on each media link opens a new page   | Pass |
| Footer is on all pages      | Check all pages how the footer looks   | Pass |


(3)

| Feature       |           Test Performed    |             Result           |        
|:--------------|:--------------------------- |:---------------------------  |
|                    About US Page                                   |
| About US   | For this test, I want to make sure that when you clicked the About link.| Pass |
| View form on different sizes of devices | Check how will look about Us form on tablets and phones, make sure all form fields are easy to see and use | Pass | 
| Log In        | Clicked on the log-in link that will bring the User to the login page  | Pass |
| Log Out       | Clicked on the log-out link that will bring the User to log out page | Pass |
|                                                         Footer                      |
| Small screens |       Checked that all media links are visible on small devices | Pass |                                |
| Media  Links  | Clicked on each media link opens a new page   | Pass |
| Footer is on all pages      | Check all pages how the footer looks   | Pass |


(4)

| Feature       |           Test Performed    |             Result           |        
|:--------------|:--------------------------- |:---------------------------  |
|                         Contact  Page                     |
| Contact Page| For this test, I want to make sure that when you clicked the Contact link.|Pass |
| Save Contact | I filled out all the fields and Contact was successfully. | Pass|
| View form on different sizes of devices | Check how will look contact form on tablets and phones, make sure all form fields are easy to see and use| Pass. |
| Log In        | Clicked on the log-in link that will bring the User to the login page  | Pass |
| Log Out       | Clicked on the log-out link that will bring the User to log out page | Pass |
|                                                         Footer                      |
| Small screens |       Checked that all media links are visible on small devices | Pass |                                |
| Media  Links  | Clicked on each media link opens a new page   | Pass |
| Footer is on all pages      | Check all pages how the footer looks   | Pass |


(5)

| Feature       |           Test Performed    |             Result           |        
|:--------------|:--------------------------- |:---------------------------  |
|                        Cart Page                     |
| Cart Page| For this test, I want to make sure that when you clicked the Cart link.|Pass |
| Shopping Cart| For this test, I want to make sure that when User has added  to the cart from the categories folder they can be able to see,add,delete each order on the cart.|Pass |
| Continue Shipping| For this test, I want to make sure that when you clicked the Continue shipping button under the shopping card the user will be redirected to the Home page.|Pass |
| Cart Total| This section shows the user what selections they have chosen and also shows the shipping address available on file.Also it allow the user to select from variety of shipping address avialable. |Pass |
| Payment Option| For this test, I want to make sure that when you clicked any desired payment option the user can be redirected to a vendor of thier choice to fill out the necessary informations required.|Pass |
| Home button| For this test, I want to make sure that when you clicked the home button is clicked in this section the user is directed to the home page.|Pass |
| View form on different sizes of devices | Check how will look cart form on tablets and phones, make sure all form fields are easy to see and use| Pass. |

(6)

| Feature       |           Test Performed    |             Result           |        
|:--------------|:--------------------------- |:---------------------------  |
|                         Profile Page                     |
| Profile Page| For this test, I want to make sure that when you clicked the Profile link.|Pass |
| Add Address | For this test, I want to make sure that when you clicked on add address they are directed to another Page.|Pass |
| Delete Address| For this test, I want to make sure that when you an address it stays deleted.|Pass |
| Address form| For this test, I want to make sure that when the user has fill his address and all the neccessary area,the changes are able to save and update in the profile page.|Pass |
| View form on different sizes of devices | Check how will look Profile page on tablets and phones, make sure all form fields are easy to see and use| Pass. |

(7)

| Feature       |           Test Performed    |             Result           |        
|:--------------|:--------------------------- |:---------------------------  |
|                         Order Page                     |
| Orders Page| For this test, I want to make sure that when you clicked the Orders link.|Pass |
| Add Address | For this test, I want to make sure that when you clicked on add address they are directed to another Page.|Pass |
| Delete Address| For this test, I want to make sure that when you an address it stays deleted.|Pass |
| Address form| For this test, I want to make sure that when the user has fill his address and all the neccessary area,the changes are able to save and update in the profile page.|Pass |
| View form on different sizes of devices | Check how will look Order page on tablets and phones, make sure all form fields are easy to see and use| Pass. |


(8)

| Feature       |           Test Performed    |             Result           |        
|:--------------|:--------------------------- |:---------------------------  |
|                         Change Password                     |
| Change Password Page| For this test, I want to make sure that when you clicked the Change Password link.|Pass |
| Save Password | I filled out all the fields (Old Password and New Password) and password was successfully saved. | Pass|
| View form on different sizes of devices | Check how will look Change password form on tablets and phones, make sure all form fields are easy to see and use| Pass. |


</details>
