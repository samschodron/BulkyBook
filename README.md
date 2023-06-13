# Bulky Book Web App

**Requirements and Specification Document**

2023-06-07

# Project Abstract

This project was created with the intent of learning more about using Razor pages in the .NET environment and deploying a .NET project using Azure.

This project was built following a tutorial from [freeCodeCamp.org](http://freeCodeCamp.org) on YouTube. The link to this tutorial can be found below.

[https://www.youtube.com/watch?v=hZ1DASYd9rk&t=10480s&ab_channel=freeCodeCamp.org](https://www.youtube.com/watch?v=hZ1DASYd9rk&t=10480s&ab_channel=freeCodeCamp.org)

# User Stories

1. As a user, I want to be able to add a category
    1. After navigating to the category list, user can hit the create new category button to be navigated to the create category page
        1. User can then fill in the input boxes and hit the button to create a new category
2. As a user, I want to delete a category
    1. After navigating to the category list, user can hit the delete button to be navigated to the delete category page
        1. The user can then hit the delete button to delete a category
3. As a user, I want to edit a category
    1. After navigating to the category list, user can hit the edit button to be navigated to the edit category page
        1. User can then edit the input boxes and hit the update button to edit a category

# User Interface

1) Landing screen
![HomePage.png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/HomePage.png)


- Kept the default [ASP.NET](http://ASP.NET) Core homepage since I was more focused on creating the functionality
    - Used design template from Bootswatch for the shared HTML and CSS

2) Category List

![CategoryList.png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/CategoryList.png)

- Created a table using Razor pages
    - Used Bootstrap icons for the delete, edit, and create buttons

3) Create Category

![AddScreen.png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/AddScreen.png)

- Created user input boxes for the create a new category page
    - Includes warning messages when user attempts to create a category that doesn’t fulfill the required conditions

4) Edit Category

![EditScreen.png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/EditScreen.png)

- Created user input boxes for the edit category page
    - Includes warning messages when user attempts to create a category that doesn’t fulfill the required conditions

5) Delete Category

![DeleteScreen.png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/DeleteScreen.png)

- Created user input boxes for the delete category page
    - Includes warning messages when user attempts to create a category that doesn’t fulfill the required conditions
    - Input boxes cannot be edited

6) Create Alert

![Pop-Up.png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/Pop-Up.png)

- Added Toastr alerts for all CRUD functionality, as seen above and below

7) Delete Alert

![Pop-Up2.png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/Pop-Up2.png)

# Specifications

### System Design

![Blank diagram - Page 1 (3).png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/Blank_diagram_-_Page_1_(3).png)

### Database ERD

![Blank diagram - Page 1 (1).png](Bulky%20Book%20Web%20App%201f98d6a200754236a217ff0a92ecebac/Blank_diagram_-_Page_1_(1).png)
