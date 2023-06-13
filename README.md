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

<img width="960" alt="HomePage" src="https://github.com/samschodron/BulkyBook/assets/71097855/513f5745-c3ca-44a3-a2c4-5411b07f7ba8">


- Kept the default [ASP.NET](http://ASP.NET) Core homepage since I was more focused on creating the functionality
    - Used design template from Bootswatch for the shared HTML and CSS

2) Category List

<img width="960" alt="CategoryList" src="https://github.com/samschodron/BulkyBook/assets/71097855/7e534e31-ab69-4249-8ec4-972877a1673e">


- Created a table using Razor pages
    - Used Bootstrap icons for the delete, edit, and create buttons

3) Create Category

<img width="960" alt="AddScreen" src="https://github.com/samschodron/BulkyBook/assets/71097855/02330264-cd3c-46c1-9e37-73ded40e362f">


- Created user input boxes for the create a new category page
    - Includes warning messages when user attempts to create a category that doesn’t fulfill the required conditions

4) Edit Category

<img width="960" alt="EditScreen" src="https://github.com/samschodron/BulkyBook/assets/71097855/7d0b9f41-84f4-4bed-8bdb-601d4998144c">


- Created user input boxes for the edit category page
    - Includes warning messages when user attempts to create a category that doesn’t fulfill the required conditions

5) Delete Category

<img width="960" alt="DeleteScreen" src="https://github.com/samschodron/BulkyBook/assets/71097855/72ee7bea-6449-4747-b712-de563b7e5a12">


- Created user input boxes for the delete category page
    - Includes warning messages when user attempts to create a category that doesn’t fulfill the required conditions
    - Input boxes cannot be edited

6) Create Alert

<img width="960" alt="Pop-Up" src="https://github.com/samschodron/BulkyBook/assets/71097855/709fc602-7a17-427f-8b22-f12cf690ab70">


- Added Toastr alerts for all CRUD functionality, as seen above and below

7) Delete Alert

<img width="960" alt="Pop-Up2" src="https://github.com/samschodron/BulkyBook/assets/71097855/2d668eb0-fadc-49d8-8a34-7a19c2391671">


# Specifications

### System Design

![Blank diagram - Page 1 (3)](https://github.com/samschodron/BulkyBook/assets/71097855/86ffa2eb-b3a5-4c8e-bd40-f3bc489a0527)


### Database ERD

![Blank diagram - Page 1 (1)](https://github.com/samschodron/BulkyBook/assets/71097855/78bfc495-afa2-49d1-ba7a-7bc334a81b04)

