##### ePortfolio
#### Andres Cruz Portfolio


```
#####Professional Self-Assessment:
Over the course of SNHU computer science program, I was introduced to different coding languages. The coding languages formed the base of my software development skills and allowed me to try out the languages first hand. In doing this I was able to get a taste for each languages syntax, ease of use, and in ability to be implemented into other projects. I was also exposed to software development best practices and the lifecycle models. Overall it was a great deal of information in a seemingly short amount of time. For my ePortfolio I chose an artifact from my MongoDb course. I felt that the incorporation of the jupyter notebook, the python language, and the mongo database was a well round demonstration of a few of the things I learned.  I worked on fine tuning the programs code making it more concise and implementing more comments to help the next person with implementation or improvements. The project had me create an html dashboard that could be accessed remotely with a username and password. With the creation of users I also was able to assign user privileges based on the users role. This is helpful for separation of duties with a focus on the least privilege security principle. The dashboard would have the company’s loaded database, in my situation it was a pet rescue service. The user could then search the database to find the perfect animal match for its specific rescue need with traits and characteristics that I built.  All of this was coded in the python language and modeled together with the jupyter notebook. The project and the course overall introduced us to the software development process which often times required us to collaborate on projects as a team. We would perform peer reviews that would provide helpful insight and feedback. One course had us work together to build a jukebox that we loaded with our favorite artists and songs. Team collaborations model the real world where often times multiple teams will work on different pieces of the program and utilize a tool like GitHub to keep everything updated and easily viewable from any location. 

The artifact I chose combined a few different computer science skills. The first skill was mongo dB knowledge on building a database. We started off with basic database traversing and learned how to add/delete and modify entries from an existing template. For the final we had to build our database from the guidelines given by the customer. The database I built included information on the customers service which featured rescue dogs based on the type of rescue. Once the database was created I wrote a CRUD python script that assisted in initializing the mongo client, provide secure access with the username and password and access the data to create remove update or delete. The jupyter notebook was the glue that allowed me to combine all these pieces together and create the webpage that would be accessible to the customer and its employees. 


```


```
#####Code Review:


 ```
 
 ```
#####Software Design and Engineering:
  The interactive database and data table was not working this update to the old code should allow the data table to be used. Originally, before the inclusion of the CRUD document, the HTML dashboard laded and presented the user with a username and password box to login. Once I incoprtated the crud file in jupyter and updated the html format code something  broke. The format I will use is simple and almost a basic default setting for the client. I wont try and get to fancy with style, height and size adjustments or even color. The Jupyter ipynb also needs to be revised as the preivrous code was formatted with incorrect input data. This caused my html dashboard to load but not display any of the database.  . The goal is to get the dashboard to load the correct UI features and connect to the database to display the search filters and pie graph.
  
```


```
######Data Structure:

The artifact I chose was a project that incorporated python, mongodb, and jupyter. I was tasked with creating a website dashboard that could retrieve data from a mongodb. The artifact incorporated data that the company gave me on their rescue animals. I needed to create the dashboard with a username and login and its ui, make the ui easy and appealing. I also had to create the data entries and have them be retrievable online. Ultimately, while the process progressed I wasn’t able to get my dashboard up and running. Early tests with the dashboard saw the creation of a dashboard UI with a working login and password. When I utilized jupyter to connect the Mongodb the dashboard stopped loading and the data did not populate. I reviewed the  dashboards UI and the code that creates the interaction between the dashboard and the database. I created this application about 16 weeks ago. I felt it deserved to be in here because it utilized a lot of different skills, python, mongodb and jupyter notebook. I selected this piece because I put a lot of time into it and while the code looks great the dashboard never loaded after the inclusion of the database interaction. Even though the data was created in mongodb and I am able to retrieve it locally and even though without the database interaction the dashboard loaded and utilized a username and password, together I had an error that I corrected by cleaning up the logic in the code. I am going to rewrote the data structure and the dashboard code and can login and dosplay the data from the database.  I have condensed and  cleaned up  the interactive features to make it more user friendly. 

```

```

#####Databases:

. My next update improved the interaction between the components and the controller by rewriting the code to filter interactive data table with MongoDB queries. The mongoDb database was already created and the information was entered into the rescue table. The challenge was determining why the addition of my interactive data filters in jupyter caused my dashboard not to load. The update involved reviewing the code for the database and controller. I made a few changes to the query method. The method uses the and/or callback for the data retrieval. I specified a few searchable traits, breed, gender, and age to filter out the results. The and/or function allows for combinations of specific details to narrow down the dog search. I also realized that my app callback was missing a line for my viewport graph which I corrected. I had somehow omitted the viewport selected rows so, on the def update_graphs nothing was happening since it didn’t have the line instructing it to show the required rows.  The new changes allow for querying of my database and the ability to generate a user px.pie chart that will break down the query into percentages.



```
Github link:

https://github.com/cruzinbyu/Portfolio


