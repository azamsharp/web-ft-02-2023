# Assignment - Blog App Using PostgreSQL Database

In this assignment you are going to create a blog application. Here are the features you will implement: 

- Ability to create a new post (title, body, date_created, date_updated, is_published) 

**posts Schema**

```
post_id - SERIAL PRIMARY KEY

title - varchar(200) 

body - Text 

date_created - timestamp default current_timestamp 

date_updated - timestamp default current_timestamp 

is_published - boolean default False 
```
 

- Ability to view all posts 


**HARD MODE:** 

- Ability to delete a post 

- Ability to update a post 

**HARDER MODE:**

- Add the ability to allow the users to create an account 

- Add the ability to allow the users to login 

- Add the ability to associate User will blog post 

- User should be able to view all his/her blog posts 