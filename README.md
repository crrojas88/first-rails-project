## First Rails Project

### Overview
For this project you will be working in pairs to build your very first Rails project. No tests will be involved so you will be able to be creative with your ideas so long as you meet the requirements below. Get your ideas approved by an instructor before you start coding.

### Requirements

##### Database

Make sure that you are using Postgresql for this project. The easiest way to do this is to add it when you create your rails project by doing so:
```rails new app_name -d postgresql```

##### Models & Relationships
Your project must have at least three models that are all associated. You must have a ```has_many - belongs_to relationship```, and ```a has_many, through relationship```. For example: An **Artist** has many **Songs**, and a **Song** belongs to an **Artist**. An **Artist** has many **Genres**, through **Songs**.

##### CRUD/Routing

Your application should follow RESTful conventions, in that, your models should be able to be Created, Updated, Read, and Deleted. New objects should be _posted_ to the create actions, and updating objects should be _put_ to the update action, etc.

##### Login

Your application should have a login functionality that follows Rails Authentication practices.

##### BONUS: Forms

Your project can include a nested form for your has_many, belongs_to relationship. For example: If I am creating a Song in a form, I should be able to select from a list of Genres that exist already, or create a new one at the same time.

##### Recap
1 . Postgresql  
2 . Three models  
3 . Has Many - Belongs To relationship  
4 . Has Many, Through relationship  
5 . CRUD actions for your models  
6 . Login

BONUS: Nested form for your **Has_many, belongs to** relationship.  
