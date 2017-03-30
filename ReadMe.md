LOCEAT

March 30, 2016 | Version 1.1

DOCUMENT OBJECTIVES
The purpose of this document is to provide detailed documentation that clearly defines the work that Kati will perform and the scope of this project.

SCOPE OF WORK FEATURE DETAILS
Loceat will be a mobile app for both iOS and Android platforms and have browser compatibility. The purpose of this application is provide location and product information about independent local food distributors and farmers markets. Currently, there are no efficient methods to collect and distribute accurate information regarding road-side market stands. Loceat will provide the tool to connect users with fresh, local produce and the farmers who grow it.
 
FEATURES 
 
 Login
 Users will be required to login for use of the Favorites and Add New features. For application simplicity and 
 efficiency Google Authentication with Passport will be used. An Admin will be assigned to oversee application data. 
 The search function will be accessible to a general audience without logging in. 
 
 Search Field
 Users will be able to use the search function on the homepage to find vendors by zip code, vendor name, or product. 
 Search criteria will be entered into the form field on the Homepage, the user will select the type of search from a 
 dropdown menu containing zip code, vendor name, or product. Upon selection the form will be submitted. The National Farmers Market Directory API and user-submitted data in a MongoDB database will be queried via the search
  function. Results will be displayed on a map displaying vendor name. When the name of a search result item is clicked an information page will expand display detailed information available about the vendor. 
 
 Add New
 Registered users may add new vendors to the database. The Add New page contains a form with fields 
 including vendor name, farm name, location, products, about, last-seen, phone, payment, association and url. When 
 the submit button is clicked an alert box will notify the user that the form has been successfully submitted.Upon verification and approval the form information will entered into the database. 

STRETCH GOALS

Favorites
Users will be able to save favorites and view in a ‘favorites’ page. A ‘favorite’ button will be associated with
 each vendor. Upon clicking, the vendor will be added to the ‘favorites’ page.
 
Page animations 
Improve overall site styling to include page animations on page and/or element transitions. 

Related API
Include a related api with information about local vendors and/or food systems. Examples include CSAs, U-Pick 
farms, home-based small food businesses, ranches etc.

Comments 
A comment button and field will be added to allow registered users to add a short (less than 140 characters) comment 
to a search result that will appear when user clicks the ‘details’ button of the entry.

Ratings
A 5 carrot rating system will be available for registered users to rate each entry in the database.

Social Media
Instagram, twitter and pinterest links will be displayed on the app connected to related accounts.

PROJECT MILESTONES

Development will begin immediately. 
Mockups: 4.1
Project skeleton setup, database setup: 4.5
Templates setup: 4.7
Working Database and API connections: 4.11
Maps API working: 3.14
Styling Review: 3.15
Testing: 3.19
Final Review: 3.20
Launch: 5.1

BROWSERS

Application will fully support only the below listed browsers and QA will test only in the following browsers and 
versions. All browsers or versions not listed below are considered out of scope.
Current as of 3.30.17 Chrome, iOS, Android


ASSUMPTIONS

While completing this estimate the following assumptions were made.
AngularJS
ReactJS
JavaScript
MongoDB
Mongoose
Express
Passport
Node.js
GitHub
Heroku
USDA National Farmers Market Directory
Google Maps API
 