# Activity - JOINS

In this activity you are going to join Posts table with Comments table. Check out the schema of both tables. 

**posts** 
```
post_id 

title 

body

date_created
```

**comments:**
```
comment_id

title 

description

date_created 

post_id - FK to the postid column in posts table
```
 
- Add 3 posts in the post table using INSERT SQL command 

- Add 5 comments in comments table using INSERT command. Assign 3 commends to one post and 2 to some other post 

- Write SQL to join posts table and comments table and return the following information: 

(postid, commentid, comment title, post title) 

