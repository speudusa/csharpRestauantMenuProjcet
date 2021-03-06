# csharpRestauantMenuProjcet
creating a menu using classes


# 4.8. Studio: Restaurant Menu
Let’s practice designing classes using the following scenario. You’ve been hired to create a web application for a local restaurant. They want to both display their current menu and edit it through an admin panel.

You’re not going to build an actual application in this studio. Instead, you will focus on the design of a portion of this application. Object-oriented programming in C# requires intentional, up-front planning. While this may seem tedious, outlining your ideas before you code helps reduce the errors you need to fix later.

## 4.8.1. Design
You know you’ll need to create classes within the web application to facilitate this behavior and represent the various components of the menu. After talking to the owner, you have these details:

The menu consists of several menu items
Each menu item has a price, description, and category (appetizer, main course, or dessert)
It should be possible to display whether a menu item is new or not
The app should know when the menu was last updated, so visitors can see that the restaurant is constantly changing and adding exciting new items
Starting with pen and paper (or your favorite notes application on your laptop), sketch out the design for two classes, Menu and MenuItem. List the fields that each should have, along with the data type and access level for each. Also consider what constructors the classes might need.

##### Note
For this studio, we are focusing on class design for these two classes. You do not need to be concerned with how the classes would be used in an application. At this stage, don’t think about how the application will work or behave; you should focus on the way that data will be represented within these classes, and how they should relate to each other.

You may find it useful to use one or more of the classes provided by C#, such as DateTime.

## 4.8.2. Presenting Your Design
Once you have sketched out your fields and properties, pair with a classmate and take turns presenting your designs. Class design can be subjective, so it’s important to properly think and talk through your choices before coding.

While your partner is presenting their design, ask questions about why they made the decisions they did. Consider other use cases that might come up, and see if their design fits with those.

## 4.8.3. Implementation
In Visual Studio, create a new project, RestaurantMenu. Add the Menu and MenuItem classes and code the design that you created above. Be sure to add getters and setters as appropriate.

## 4.8.4. Commit Your Work
Create a repository on your Github account and push up your project.

Project details from LaunchCode
