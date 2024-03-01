Recipe Book App
Recipe Book is an application that will allow users to create a collection of recipe that users can view in detail. 
Users often forget the recipe they mastered overtime. This app identifies and solves this problem by helping user store all the recipe they mastered overtime.
This problem made us think about the Recipe-Book app.Through various user-friendly functions the app will implement registering and login functionalities, a record of database stored by each user. 
The main feature consists of adding personalized recipes & allowing the users to edit and delete the recipe according to their personal preferences.  
This app is targeted to general people who find it hard remembering all the recipes as they master the new one as this app makes it easier to remember entire user recipes in a single platform.

Contributors:
- Rajesh Yaksho
- Ribesh Joshi
- Zobia Tahir
- Khanh Ha
- Thanh Tran

Functions

Create the Recipe
Users can create their own virtual recipe list and store it in their personal inventory. 
Simply, users can name their own creations and there are no any limitations to what the user prefers their recipe to be. It’s entirely based on the user's preferences. 
User recipe data is stored in the server using firestore API  by firebase from google.

Login/Logout Feature
All the users have their separate personalized list of recipes stored in the authentication database. 
The login information is stored safely in google firebase authentication database enhancing the user information privacy. Along with that users can have the logout option from their space at any time.

Create Account Feature
All the users are required to create a personal account or login before accessing the recipe.This creates a personalized space for each user. To create the account user needs to authenticate their mail.

Edit / Delete Recipe Feature
Users have the ability to edit the recipe they have created previously. They can also delete the recipe if they don't want anymore allowing them to customize their recipe book.
The edit/delete feature will take effect in the real time database as well giving each user the maximum customization feature.

View Recipe Feature
Users have the ability to view the recipe they have created in an organized list.
This organized list is updated eventually in the firestore database and the timestamp is also presented to the user.

Resources

Our app will utilize an Application Programming Interface (API) to manage the user authentication process for the Database of the Virtual Recipe application. 
Firebase Authentication by Firebase will be integrated to ensure a secure and seamless user authentication experience. 
The Firestore database will serve as the backend, storing and managing all the recipes created by users.
In addition to leveraging Firebase services, the application optimizes its performance by efficiently using system resources.
Specifically, the application employs chunks of memory from the device's system as all applications do.T
his allows the application to load and run various components directly from the phone's memory in smaller, manageable chunks. Java does all the work for the integration of API and phone’s memory in the background. 
