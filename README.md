# User Guide for The Curious Case of Cosmetics

This is a web application designed for all users of beauty products as a one-stop solution to beauty aficionados' problems.  

* [1. Introduction](#1-introduction)
   * [1.1 Project Motivation](#11-project-motivation)
   * [1.2 Project Aim](#12-project-aim)
   * [1.3 Quick Start](#13-quick-start)
* [2. Features and Usage](#2-features-and-usage)
   * [2.1 Public Features](#21-public-features)
      * [2.1.1 Home](#211-home)
      * [2.1.2 About](#212-about)
      * [2.1.3 Login](#213-login)
      * [2.1.4 Register](#214-register)
   * [2.2 Private Features : Personal](#22-private-features--personal)
   		* [2.2.1 Dashboard](#221-dashboard)
      * [2.2.2 My Products : My Beauty Routine](#222-my-products--my-beauty-routine)
      * [2.2.3 My Products : Shelved](#223-my-products--shelved)
      * [2.2.4 My Products : Currently Using](#224-my-products--currently-using)
      * [2.2.5 My Products : Wish List](#225-my-products--wish-list)
      * [2.2.6 Search Products](#226-search-products)
      * [2.2.7 Create Product to Add to Database](#227-create-product-to-add-to-database)
      * [2.2.8 Add Product to My Products](#228-add-product-to-my-products)
      * [2.2.9 Edit Product](#229-edit-product)
      * [2.2.10 Profile](#2210-profile)
      * [2.2.11 Logout](#2211-logout)
   * [2.3 Private Features : Social](#23-private-features--social)
      * [2.3.1 Leave a Review](#231-leave-a-review)
      * [2.3.2 Leaderboard](#232-leaderboard)
      * [2.3.3 Forum Thread](#233-forum-thread)
      * [2.3.4 Add Thread](#234-add-thread)
      * [2.3.5 Forum Reply](#235-forum-reply)
      * [2.3.6 View Product](#236-view-product)
      * [2.3.7 View Brand](#237-view-brand)
   * [2.4 Admin Features](#24-admin-features)
      * [2.4.1 Delete Thread](#241-delete-thread)
      * [2.4.2 Delete Reply](#242-delete-reply)
      * [2.4.3 Delete Product](#243-delete-product)
    
* [3. Contributors](#3-contributors)

## 1. Introduction

  * [1.1 Project Motivation](#11-project-motivation)
  * [1.2 Project Aim](#12-project-aim)
  * [1.3 Quick Start](#13-quick-start)

### 1.1 Project Motivation 

With the deluge of beauty products in the market today, many are overwhelmed by the choices available. They often have no idea which product they should buy, and more often than not, they end up buying whatever insidious advertisements push them to. This leads to overconsumption of ill-suited beauty products, which will eventually be left to expire in a corner of their vanities. Also, many beauty products require consistent application for optimal results, but with their busy lives they forget steps in their beauty routines and may even end up skipping it entirely.

Furthermore, it is difficult to find people around them who use the same type of beauty products as them. This makes it challenging when they want to discuss specific beauty issues or discover the latest trending product. 

### 1.2 Project Aim 

We hope to solve beauty enthusiasts’ woes through an integrated web application. Leveraging on the experience and knowledge gathered through crowdsourcing, the community of beauty product users can optimise their purchase and use of beauty products. Our web application also serves as a tool to organise users’ many beauty products and visualise their beauty routines. Moreover, we hope to provide a platform for like-minded users to connect.

### 1.3 Quick Start

Our web application can be accessed at https://thecuriouscaseofcosmetics.herokuapp.com.

Clicking on the link above or entering that link into a browser will bring you to our home page. 

## 2. Features and Usage

Public features can be viewed by anyone and do not require users to be logged in. 

Private features can only be accessed by users who have logged in. Users who have not created an account and/or who have not logged in cannot access private features.

### **2.1 Public Features**

  * [2.1.1 Home](#211-home)
  * [2.1.2 About](#212-about)
  * [2.1.3 Login](#213-login)
  * [2.1.4 Register](#214-register)

#### **2.1.1 Home**

This is the first page users will see when they access the web application. 

![Screenshot 2021-07-20 at 1.04.15 AM](/assets/Screenshot%202021-07-20%20at%201.04.15%20AM.png)

*How to access this feature*: 

Upon accessing the web application, users are automatically brought to this home page. Users can also click on Home in the header of all public pages.

*Function*:

* **View the Video Demostration & Download the User Guide**

To view the video demostration and download the user guide, click on the *Watch Video Demo* button on the home page. Users will be brought to a page to view the video. (see below)

![Screenshot 2021-07-20 at 1.04.29 AM](/assets/Screenshot%202021-07-20%20at%201.04.29%20AM.png)

To navigate back to the home page, click on Back to Home below the video.

Navigate back to the feature list: [2.1 Public Features](#21-public-features)

#### **2.1.2 About**

This feature gives user information on this web application and its purpose.

![about](https://i.imgur.com/uxdx3YS.jpg)

*How to access this feature*: 

Users can click on About in the header of all public pages.

*Function*:

* **View information about the aim of the website**

Navigate back to the feature list: [2.1 Public Features](#21-public-features)

#### **2.1.3 Login**

This feature allows existing users to log into their accounts to access private features.

![Screenshot 2021-07-20 at 1.01.36 AM](/assets/Screenshot%202021-07-20%20at%201.01.36%20AM.png)

*How to access this feature*: 

Users can click on Login in the header of all public pages. Users can also click "Already a member? Log in now!" at the bottom of the Register page.

*Function*:

* **Log into account**

Users can key in their username and password, then click the Log In button or press Enter.

Navigate back to the feature list: [2.1 Public Features](#21-public-features)

#### **2.1.4 Register**

This feature allows new users to create an account to access private features.

![Screenshot 2021-07-20 at 1.01.28 AM](/assets/Screenshot%202021-07-20%20at%201.01.28%20AM.png)

*How to access this feature*: 

Users can click on Login in the header of all public pages. Users can also click "Not a member? Sign up now!" at the bottom of the Login page.

*Function*:

* **Register for a new account**

New users who are new to this website and do not have an existing account can register for one, by filling in their username, email, first name, last name, gender and password.

* **Admin Authentification**

All usernames beginning with *Admin* (e.g. Admin1) will be automatically registered as an admin user. To ensure only authorised personnels have access to admin functionalities, those who are attempting to register as admin users will be brought to a page where they would be required to enter a pin (i.e. 1234). (see below)

![Screenshot 2021-07-20 at 12.59.13 AM](/assets/Screenshot%202021-07-20%20at%2012.59.13%20AM.png)

Note:
* All fields must be filled in to register for an account.
* Each username can only be used by one user. If user is alerted that username already exists, please use a different username.
* "Admin" prefix is case-sensitive.

Navigate back to the feature list: [2.1 Public Features](#21-public-features)

### **2.2 Private Features : Personal**

  * [2.2.1 Dashboard](#221-dashboard)
  * [2.2.2 My Products : My Beauty Routine](#222-my-products--my-beauty-routine)
  * [2.2.3 My Products : Shelved](#223-my-products--shelved)
  * [2.2.4 My Products : Currently Using](#224-my-products--currently-using)
  * [2.2.5 My Products : Wish List](#225-my-products--wish-list)
  * [2.2.6 Search Products](#226-search-products)
  * [2.2.7 Create Product to Add to Database](#227-create-product-to-add-to-database)
  * [2.2.8 Add Product to My Products](#228-add-product-to-my-products)
  * [2.2.9 Edit Product](#229-edit-product)
  * [2.2.10 Profile](#2210-profile)
  * [2.2.11 Logout](#2211-logout)

#### **2.2.1 Dashboard**

This feature allows users to view all their important information at one glance. 

![dashboard](https://i.imgur.com/gKMPwKY.jpg)

*How to access this feature*: 

Upon login, users are automatically brought to their dashboard. Users can also click the icon in the top left corner of the page to access their dashboard.

*Functions*:

* **Reminders for upcoming expiry dates**

Users can view expiry date reminders for products that the user is currently using (i.e. in the user's Currently Using shelf), which will be expiring in the next 30 days. The products are listed with the product expiring the soonest on the leftmost. 

* **Checklist for day and night beauty routines**

Users can keep track of their beauty routines and check off the products they have already used by clicking on the product in the checklist. The checkbox beside the product will be pink if it has been used, and white if it has not. 

* **Notifications from forum**

Users will be notified of new replies made to forum threads they created. Clicking on the notification will bring the user to the specific forum thread in the notification. (see below)

![Screenshot 2021-07-10 at 4.30.23 PM](/assets/Screenshot%202021-07-10%20at%204.30.23%20PM.png)

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.2 My Products : My Beauty Routine**

This feature allows users to view the products they are currently using in table format, split into Day Routine and Night Routine. (see below)

![Screenshot 2021-06-25 at 2.29.18 PM](https://i.imgur.com/INPSY9T.png)

*How to access this feature*: 

Users can click on *My Products* in the header of all pages. Users can also click on *My Beauty Routine* in the sidebar if they are currently on one of the My Products pages.

Note:
* Only products under *Currently Using* will be reflected in *My Beauty Routine*.


Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.3 My Products : Shelved**

This feature allows users to view the products that they have shelved (products that they have tried before but do not wish to continue using)
.
![Screenshot 2021-06-25 at 2.35.40 PM](https://i.imgur.com/zfVB2p0.png)

*How to access this feature*: 

Users can click on *My Products* in the header of all pages, then on *Shelved* in the sidebar of *My Products*.

*Functions*:

* **Delete a product from Shelved**

Users can click on the *Delete* button besides the product they wish to delete from the table. (see below)

![Shelve Delete](https://i.imgur.com/9z6yk6E.png)

* **Edit a product in Shelved (refer to 2.2.9 Edit Product for more details)**

Users can click on the *Edit* button to access *Edit*, where they can make the intended amendments. (see below)

![Shelve Edit](https://i.imgur.com/Fcayh9e.png)

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.4 My Products : Currently Using**
This feature allows user to view the products that they are currently using.

![Currently Using](https://i.imgur.com/MfgwNin.png)

*How to access this feature*: 

Users can click on *My Products* in the header of all pages, then on *Currently Using* in the sidebar of *My Products*.

*Functions*:

* **Delete a product from Currently Using**

Users can click on the *Delete* button besides the product they wish to delete from the table. (see below)

![Currently Using Delete](https://i.imgur.com/WxHtwJz.png)

* **Edit a product in Currently Using (refer to 2.2.9 Edit Product for more details)**

Users can click on the *Edit* button to access *Edit*, where they can make the intended amendments. (see below)

![Currently Using Edit](https://i.imgur.com/pb4YHcb.png)

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.5 My Products : Wish List**

This feature allows users to view the products that are in their wish list (products that they wish to use but have yet to try).

![Wish](https://i.imgur.com/u5dj7YY.png)

*How to access this feature*: 

Users can click on *My Products* in the header of all pages, then on *Wish List* in the sidebar of *My Products*.

*Functions*:

* **Delete a product from Wish List**

Users can click on the Delete button besides the product they wish to delete from the table. (see below)

![Wish Delete](https://i.imgur.com/36FCllB.png)

* **Edit a product in Wish List (refer to 2.2.9 Edit Product for more details)**

Users can click on the Edit button to access *Edit*, where they can make the intended amendments. (see below)

![Wish Edit](https://i.imgur.com/Co00cVR.png)

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.6 Search Products**

This feature allows users to search for a specific product in the community-contributed database of beauty products.

![search](https://i.imgur.com/8TsrU07.png)

*How to access this feature*: 

Users can click on *Search Products* in the header of all pages.

*Functions*:

* **View all products in current database**

Users can view all the products in the database by pressing a single space in the search bar and pressing *Enter* or clicking on the *Search!* button. (see below)

![searchresults](https://i.imgur.com/mR4mbtK.png)

* **Search for a product or brand**

Users can search for a specific product using its product name, or for all products of a brand by using the brand name. The search results returned will be all products which contain the keyword that was searched in its product name or brand name.

If no product that matches the search keyword is found, the user will be prompted to create a product to be added to the database. (see below)

![searchnone](https://i.imgur.com/glEaE8W.png)

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.7 Create Product to Add to Database**

This feature allows users to create a product that does not exist in the current database, then add it to the database.

![createproduct](https://i.imgur.com/T86xHim.png)

*How to access this feature*: 

Users can click on the *Click here to add a product* hyperlink from the Search Products page that is shown when the user searches for the product and no products matching the search keyword were found.

*Function*:

* **Add a new product to the community database**

Users can input the details (product name, brand and type) of the beauty product they wish to add to the community database. 
After adding the product to the database, they will be redirected back to the search page with the product they just added automatically "searched" for them. This is for users' convenience, should they wish to leave a review on that product or add it to *My Products*. (see below)

![createsuccess](https://i.imgur.com/k5CgxKH.png)

Note:
* Products that are newly added will have a default average rating of 0. The average rating will be updated once users start leaving reviews of that product.

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.8 Add Product to My Products**

This feature allows users to add a product to one of the categories in *My Products* (Currently Using, Shelved or Wish List).

![add](https://i.imgur.com/ClXpY5i.png)

*How to access this feature*: 

Users can only add a product by searching for the product on the Search Products page. Users can click on the dropdown box in the second-rightmost column of the row for the product they wish to add, then select the category they wish to add this product to. (see below)

![addwhere](https://i.imgur.com/CnOyUbk.png)

*Function*:

* **Add a product to Shelved or Wish List**

Users can select the appropriate category (Shelved or Wish List) in the dropdown box, then click the *Add!* button at the side. Users will then be redirected to the corresponding My Products page (Shelved or Wish List) showing all the products the user has shelved or put into the user's wish list respectively.

* **Add a product to Currently Using**

Users can select Currently Using in the dropdown box, then click the *Add!* button at the side. Users will then be redirected to a page to fill up additional details for usage of the product, namely its expiry date, frequency of usage, and which beauty routine it should be in.

If the user indicates a weekly or monthly usage, the default number of times to use it would be once a week on Mondays / once a month on the 1st of each month respectively. 

If the user wishes to specify more detailed, personalised usage of the product, the user can fill up the optional fields. For instance, if one wishes to use the product twice a week on Tuesdays and Thursdays, one would fill up the optional fields as such (see example below).

If the user wishes to use the product a certain number of times a week / month but has no preference for which specific days to use it on, the user can leave the *Specific days to use product* portion empty and our app will automatically allocate days to use the product on. 

![addcurrentlyusing](https://i.imgur.com/HZZnO9S.png)

After clicking the *Add to Currently Using* button at the bottom of the page, users will be redirected to the Currently Using page showing all the products the user is currently using.

Note:
* If the product the user wishes to add to *My Products* does not exist, the user has to create the product first, then add it to *My Products*.
* If the user indicates *n* times to use a product per week/month and specifies fewer than *n* specific days to use the product on, the display of the product in the beauty routine checklists on the Dashboard will follow the specified days. 
For example, if a user indicates a product to be used 3 times a week with specific days indicated as '1,3', the beauty routine checklists will only show the product on Mondays and Wednesdays.

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.9 Edit Product**

This feature allows users to edit the product information in their *My Products* page.

![Edit](https://i.imgur.com/l69sRYa.png)

*How to access this feature*:

Click on the *Edit* button beside any product on any one of the *My Product* pages.

*Function*:

* **Edit a product to place it into *Shelved***

Users can indicate the My Products Category as *Shelved*  to move the product into *Shelved*. (see below)

If product is already in *Shelved*, the product will remain in this category, but the shelved date will be updated to the date of edit 

![Edit Shelved](https://i.imgur.com/L5KSIHL.png)

After clicking the *Edit* button at the bottom of the page, users will be redirected back to the *My Products* page they were previously on.


* **Edit a product to place it into *Wish List***

Users can indicate the My Products Category as *Wish List* to move the product into *Wish List*. (see below)

If product is already in *Wish List*, the product will remain in this category, but the wished date will be updated to the date of edit.

![Edit Wish](https://i.imgur.com/2zrolpm.png)


After clicking the *Edit* button at the bottom of the page, users will be redirected back to the *My Products* page they were previously on. (see below)


* **Edit a product to place it into *Currently Using***

Users will then be required to fill up additional details for usage of the product, namely its expiry date, frequency of usage, and which beauty routine it should be in.

If the user indicates a weekly or monthly usage, the default number of times to use it would be once a week on Mondays / once a month on the 1st of each month respectively. 

If the user wishes to specify more detailed, personalised usage of the product, the user can fill up the optional fields. For instance, if one wishes to use the product twice a week on Tuesdays and Thursdays, one would fill up the optional fields as such (see example below).

If the user wishes to use the product a certain number of times a week / month but has no preference for which specific days to use it on, the user can leave the *Specific days to use product* portion empty and our app will automatically allocate days to use the product on. 

![Edit copy](https://i.imgur.com/zZuo0wv.png)

If product is already in the *Currently Using*, the product will remain in this category, but the relevant information will be updated.

After clicking the *Edit* button at the bottom of the page, users will be redirected back to the *My Products* page they were previously on.

Note:
* To edit a previously added product to *Wish List* or *Shelved*, users only need to fill up the My Products Category option. All other inputs filled up by the user will be ignored.
* Expiry date of the product is assumed to be the date of edit unless otherwise indicated.
* If the user indicates *n* times to use a product per week/month and specifies fewer than *n* specific days to use the product on, the display of the product in the beauty routine checklists on the Dashboard will follow the specified days. 
For example, if a user indicates a product to be used 3 times a week with specific days indicated as '1,3', the beauty routine checklists will only show the product on Mondays and Wednesdays.

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.10 Profile**

This feature allows users to view a profile of a user.

![profile](https://i.imgur.com/aXadveQ.png)

*How to access this feature*: 

To access their own Profile page, users can click on *Profile* in the header of all pages. To access profile pages of other users through the Forum pages, users can click on the username of that user.

*Function*:

* **View personal information**

Users can view the user's first name, last name, gender and email address.

* **View all reviews made by the user**

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

#### **2.2.11 Logout**

This feature allows users to logout of their account.

![logout](https://i.imgur.com/B76yPhp.png)

*How to access this feature*: 

Users can click on the *Logout* button at the bottom of their own Profile page.

*Function*:

* **Log out of account**

Note:
* Once users have logged out, they will no longer be able to access the private features.

Navigate back to the feature list: [2.2 Private Features : Personal](#22-private-features--personal)

### **2.3 Private Features : Social**

  * [2.3.1 Leave a Review](#231-leave-a-review)
  * [2.3.2 Leaderboard](#232-leaderboard)
  * [2.3.3 Forum Thread](#233-forum-thread)
  * [2.3.4 Add Thread](#234-add-thread)
  * [2.3.5 Forum Reply](#235-forum-reply)
  * [2.3.6 View Product](#236-view-product)
  * [2.3.7 View Brand](#237-view-brand)

#### **2.3.1 Leave a Review**

This feature allows users to leave a review on a product, which is an integer rating of the product upon 5.

![Screenshot 2021-07-10 at 4.40.31 PM](/assets/Screenshot%202021-07-10%20at%204.40.31%20PM.png)

*How to access this feature*: 

Users can click on *Leave a Review* in the rightmost column of the row for the product they wish to leave a review of, in the Search Products page. (see example below)

![reviewwhere](https://i.imgur.com/uhDk5Da.png)

*Functions*:

* **Leave a review of a product**

Users can leave a review on a product, both in the form of a numerical ("stars") rating upon 5 and a text review. The text review, however, is optional. To give, for instance, 4 stars out of 5 stars and a text review "Cool!", users can click on the fourth star from the left, input "Cool!" in the text box, and click the *Submit!* button to submit the review. (see below)

![Screenshot 2021-07-10 at 4.40.31 PM](/assets/Screenshot%202021-07-10%20at%204.40.31%20PM.png)

Once the review is submitted, users will be redirected back to the search page with the product they just reviews automatically "searched" for them. The average rating of the product will also be updated accordingly. (see below)

![reviewsuccess](https://i.imgur.com/sYOQ6Fw.png)

Note: 
* Users can only leave a review once for each product, and it cannot be deleted nor edited.
* Users can leave a review of any product in the database, even if it is not in their *My Products*.

Navigate back to the feature list: [2.3 Private Features : Social](#23-private-features--social)

#### **2.3.2 Leaderboard**

This feature allows users to see the Top 10 skincare products and Top 10 makeup products, ranked based on the products' average rating given by our users.

![leaderboard](https://i.imgur.com/BtZVleJ.png)

*How to access this feature*: 

Users can click on *Leaderboard* in the header of all pages.

*Function*:

* **View Top 10 skincare products**

Users can view the Top 10 skincare products by clicking on the *Skincare* button in the Leaderboard page. (see below)

* **View Top 10 makeup products**

Users can view the Top 10 makeup products by clicking on the *Makeup* button in the Leaderboard page.

![leaderboardskincare](https://i.imgur.com/OA3Havh.png)

Navigate back to the feature list: [2.3 Private Features : Social](#23-private-features--social)

#### **2.3.3 Forum Thread**

This feature allows users to interact with other members of the community, facilitating the discussion of beauty issues.

*How to access this feature*: 

Users can click on *Forum* in the header of all pages.

*Function*:
* **Search Threads**

Users can choose ‘Titles’ or ‘Descriptions’ in the drop-down box before entering the keywords into the search bar. Then, users can click the button with the magnifying glass icon to run the search. (see below)

![Search Thread](https://i.imgur.com/k7GGStj.png)

If user chose ‘Titles’, all threads whose title contains the keyword(s) entered into the search bar will be displayed. 

If user chose ‘Descriptions’, all threads whose description contains the keyword(s) entered into the search bar will be displayed. 

* **Add Threads (refer to 2.3.4 Add Thread for more details)**
Users can click on the *+* button, which will direct them *Add Thread*, where they will be able to create their own forum posts. (see below)

![Add Thread](https://i.imgur.com/snHXvcG.png)

* **Access *Forum Reply***

User can click the title of any thread in *Forum Thread*, which will direct them to *Forum Reply* of the corresponding thread. (see below)

![Screenshot 2021-06-26 at 12.13.21 AM](https://i.imgur.com/lby00lm.png)

* **Delete Thread**

Users can click the *Delete* button at the bottom right-hand corner of any thread started by the users themselves. (see below)

![Screenshot 2021-06-26 at 2.09.49 AM](https://i.imgur.com/EIVmlWY.png)

The Thread and its replies will no longer be avilable on any page.

* **Visit profiles of other users** 

Users can click on the username or the word "Created" on the right-hand side of each thread to be directed to the profile with the corresponding username. (see below)

![Screenshot 2021-06-26 at 2.09.49 AM](https://i.imgur.com/qRwuqpr.png)
 

Navigate back to the feature list: [2.3 Private Features : Social](#23-private-features--social)

#### **2.3.4 Add Thread**
This feature allows users to add threads to *Forum Thread*.

*How to access this feature*: 


Users can click the *plus* button located in the search bar on *Forum Thread*. (see below)

![Add Thread](https://i.imgur.com/snHXvcG.png)

*Function*:

* **Add Thread to *Forum Thread***

Users can enter the title and description of the new thread and click the *Add* button. (see below)

![Screenshot 2021-06-25 at 11.10.46 PM](https://i.imgur.com/Bja8kak.png)

Users will be directed back to *Forum Thread*, where the thread they have added will appear on the page.

Navigate back to the feature list: [2.3 Private Features : Social](#23-private-features--social)

#### **2.3.5 Forum Reply**
This feature allows users to reply to threads and view replies made by other users.

*How to access this feature*: 

Click the title of any thread in *Forum Thread*. (see below)

![Screenshot 2021-06-26 at 12.13.21 AM](https://i.imgur.com/lby00lm.png)

*Function*:
* **Post reply to a thread**

Users can click on the ‘Comment’ button at the bottom of the thread description, making the Comment box appear at the bottom of *Forum Reply*. 

Users can then enter the reply in the Comment box and press the *Submit* button. (see below)

![reply](https://i.imgur.com/a8CoAG9.png)

* **Delete forum reply** 

Users can delete the thread replies they themselves posted by clicking the *Delete* button at the bottom right-hand corner of any reply posted by themselves. (see below)

![Screenshot 2021-06-26 at 12.29.41 AM](https://i.imgur.com/h1viDu8.png)

* **Return to *Forum Thread*** 

Users can click the *< BACK* button to return to *Forum Thread*.

![Screenshot 2021-06-26 at 12.16.35 AM](https://i.imgur.com/p2RO18L.png)

* **Visit profiles of other users** 

Users can click on the username either at the top of the thread or at the top of any reply to be directed to the profile with the corresponding username. (see below)

![Screenshot 2021-06-26 at 12.58.34 AM](https://i.imgur.com/0iBVTI1.png)
 

Navigate back to the feature list: [2.3 Private Features : Social](#23-private-features--social)

#### **2.3.6 View Product**
This feature allows users to view the information on and the reviews left by others for any product. (see below)

![Screenshot 2021-07-10 at 4.48.03 PM](/assets/Screenshot%202021-07-10%20at%204.48.03%20PM.png)

*How to access this feature*: 
Click the name of the product either in *Search*, any *My Products* pages, or the page for that product's brand. (see below)

![Screenshot 2021-07-10 at 4.51.52 PM](/assets/Screenshot%202021-07-10%20at%204.51.52%20PM.png)

*Function*:
* **Visit profiles of other users**
Users can click on the username under the Username column of the reviews table. (see below)

![Screenshot 2021-07-10 at 4.54.14 PM](/assets/Screenshot%202021-07-10%20at%204.54.14%20PM.png)

* **Direct to the *My Products* page where the product is added to**
If users have already added the product to any of their *My Products* pages, they can click on the name of that page to to be directed there. (see below)

![Screenshot 2021-07-10 at 4.57.50 PM](/assets/Screenshot%202021-07-10%20at%204.57.50%20PM.png)

#### **2.3.7 View Brand**
This feature allows users to view all the products in the database that belong to a specific brand. (see below)

![Screenshot 2021-07-20 at 12.29.36 AM](/assets/Screenshot%202021-07-20%20at%2012.29.36%20AM.png)

*How to access this feature*: 
Click the brand name either in *Search*, any *My Products* pages or any of that brand's product pages. (see below)

![Screenshot 2021-07-10 at 5.04.30 PM](/assets/Screenshot%202021-07-10%20at%205.04.30%20PM.png)


### **2.4 Admin Features**

  * [2.4.1 Delete Thread](#241-delete-thread)
  * [2.4.2 Delete Reply](#242-delete-reply)
  * [2.4.3 Delete Product](#243-delete-product)

#### **2.4.1 Delete Thread**
This feature allows admins to delete *any* thread they deem inappropriate.

*How to access this feature*: 

Admins can click the *Delete* button at the bottom right-hand corner of any thread. (see below)

![Screenshot 2021-07-20 at 12.38.15 AM](/assets/Screenshot%202021-07-20%20at%2012.38.15%20AM.png)

#### **2.4.2 Delete Reply**
This feature allows admins to delete *any* reply they deem inappropriate.

*How to access this feature*: 

Admins can delete the *any* thread reply by clicking the *Delete* button at the bottom right-hand corner of the reply. (see below)

![Screenshot 2021-07-20 at 12.41.04 AM](/assets/Screenshot%202021-07-20%20at%2012.41.04%20AM.png)

#### **2.4.3 Delete Product**
This feature allows admins to delete *any* product they deem unnecessary (e.g. duplicate products).

*How to access this feature*: 

Admin can first search for the products under *Search Products*, before clicking the *Delete* button of the corresponding product. (see below)

![Screenshot 2021-07-20 at 12.47.26 AM](/assets/Screenshot%202021-07-20%20at%2012.47.26%20AM.png)

## 3. Contributors

Xie Ke Xin ([@kekekexinnn](https://github.com/kekekexinnn)) and Lyn Tan ([@lyntanrambutan](https://github.com/lyntanrambutan))

This project is done as an Orbital Project for the AY2020/21 run, for the achievement level of Project Apollo 11.
