TTP Assignment 10: Database Practice


Figma --- ER Diagram of database
![image](https://user-images.githubusercontent.com/26383888/150371848-9be0e9ba-0810-491f-9531-19654e46e696.png)



Goal:
This is an exercise for you to practice how to implement databases, work with Postman, as well as Figma/LucidChart ER Diagrams.

Direction:
Try to commit often and commit frequently on GitHub. Please incorporate GitHub Projects as well, using the Automated Kanban template. Create a note for each user story and then convert that note to an issue. Remember, try to have your branches named as closely to the feature/ticket/issue it is intended to build out. Do not forget to type in “closes #” in the body of Pull Requests to close associated issues. 


Click on a ticket/issue and explore the different sections such as “Assignees, Labels, and Projects” and make sure that your ticket is associated to your project, otherwise your PRs and Tickets won’t be automated and tethered together (this should be done for you already, but double-check).

A few useful resources that are useful for this assignment:

https://www.microfocus.com/documentation/idol/IDOL_12_0/MediaServer/Guides/html/English/Content/Getting_Started/Configure/_TRN_Set_up_PostgreSQL.htm

https://www.tutorialspoint.com/postgresql/postgresql_create_database.htm

https://www.postgresql.org/docs/

https://learning.postman.com/docs/getting-started/introduction/

https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/routes

https://blog.logrocket.com/nodejs-expressjs-postgresql-crud-rest-api-example/#settingupanexpressjsserver

https://documenter.getpostman.com/view/5922408/RznJmGfn




Assignment:

Download and install PostgreSQL on your devices (for Mac users I recommend the app)

1.Using Figma/Lucidchart, create an ER Diagram of your database

2.Create a brand new database with a specific topic (eg pizza, students, employees, etc.) with 

  a.At least four different tables.
  
  b.Each table should have a primary key
  
  c.Each table should have at least four dummy tuples
  
  d.Each table should be able to be joined with one other table in the database (this will make sense once you understand schemas)
  
3.Write an inner join query that joins two tables, one that joins three tables and one that joins all four tables (you can stack inner joins)

4.Finally using Postman, try to post a brand new line of data and get two different lines of dummy data that you placed inside the database. Take a screenshot of your work on Postman and put it inside of your repo.

https://www.youtube.com/watch?v=_Mun4eOOf2Q&t=1128s
  
  You can do this by either setting up Express routes to hit (recommended) or straight through the database using xmysql package

**You don’t have to try running your code on the psql shell, but it is recommended so you can make sure that you understand sql properly. 

***Highly recommend that you remember where you installed your postgres server on your windows pc, you need to add the postgres bin to your environmental variables to connect to postgres with libraries like node-postgres.

Grading criteria:

Code is commented with documentation and showcases what student is solving/attempting to solve

All solutions should explicitly fulfill the requirements noted in each problem.

Complete = Meets all grading criteria above.

Incomplete = Does not meet all grading criteria above. Needs improvement or missing submission.
