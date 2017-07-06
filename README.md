Assignment 5 (Due: Wednesday July, 5th @ 11:59 PM)
 

** This assignment will combine a few things that you have learned in this class and will require a little learning on your own. Do your best and be creative.  If you need help ask sooner rather than later in slack. Myself and your classmates are here to help and do not wait to the last minute to do this assignment.
** You may work in two person teams, if you plan to do so please email me to let me know who you are working with. You may NOT work in multiple teams.
** You may use python, JAVA or node.js (javascript) for this assignment.
** I have listed some tutorials below, but you may need to google some on your own.
 

What You Will Do:
You will create a RESTful web service that runs in a docker container.
Your web service will contain two GET routes:
One that displays a collection of records
One that displays a single record that the corresponds to an ID
Example: If I created two routes, /customers and /customers/35 (note, that 35 is the ID of a given customer in my database)
The data returned from your web service routes must be in JSON or XML form.
Note, if you would like to load your results in a web page you are welcome to do so, you just need a way to display the data your routes return in a web browser.
You will create a hardcoded JSON file based database as the backing datastore for your web service routes.
Note, if you are comfortable using a SQL or NO-SQL database as your datastore you may do so but it is not required.
Also note, your data model is something you make up. Meaning you can store a collection of cars, customers, food items, restaurants, video games, sports teams etc. Be creative :)
This is similar to what the presenter did in the GraphQL video we watched in our last class. He used a JSON file as a database for his demo.
IMPORTANT: You must create a screencast video you recorded running your web service from own computer. The screencast must also contain a presentation of your slides for the assignments. Make sure you discuss issues you encountered creating the project and how you resolved them.  This is not optional!
 

Tutorials:
Docker
What is docker:  https://www.youtube.com/watch?v=dz5_lsWlfTU
Installing Docker:  Windows - https://www.youtube.com/watch?v=wCTTHhehJbU
Docker Tutorial (Step by Step) - https://www.youtube.com/watch?v=Vyp5_F42NGs
https://blog.talpor.com/2015/01/docker-beginners-tutorial/
https://docs.docker.com/engine/getstarted/
https://hackr.io/tutorials/learn-docker
Python RESTful services using Flask:
https://code.tutsplus.com/tutorials/building-restful-apis-with-flask-diy--cms-26625
https://impythonist.wordpress.com/2015/07/12/build-an-api-under-30-lines-of-code-with-python-and-flask/
Node + Express REST API Example
https://closebrace.com/tutorials/2017-03-02/creating-a-simple-restful-web-app-with-nodejs-express-and-mongodb
Node Simple RESTful API (shows using json file as DB)
https://www.tutorialspoint.com/nodejs/nodejs_restful_api.htm
Dockerize your Flask App
https://www.smartfile.com/blog/dockerizing-a-python-flask-application/
http://containertutorials.com/docker-compose/flask-simple-app.html
Docker + Spring Boot (JAVA)
https://spring.io/guides/gs/spring-boot-docker/
 

To Submit The Assignment (Read Carefully):
** Please follow all instructions as not following them will lead to loss of points.
Create a github account.
Create public github repository and all all of your source code for this assignment to the repository. (See the “getting started with github” document in the “Course Documents  > Tutorials & Cheat Sheets” folder for help)
Make sure to add a README file to the root of your repository that describes what your web service does.
Create a presentation powerpoint slide deck that contains 2 slides:
A title slides that contains your name(s) and the name of your web service project
A slide that talks a little about your data model
Submit the following to the “Submit Assignment” thread in RESTful Web Service Implementation + Docker discussion board.
The powerpoint slide file.
Link to your public github repository that contains all of the source code including your JSON database file.
Note, if you worked with classmate for this assignment...if you did please state the person you worked with.
