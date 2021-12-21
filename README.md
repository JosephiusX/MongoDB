# MongoDB

# Sec 1

5. MongoDB Ecosystem

   self-Managed/Enterprise Atlas (Cloud) Mobile CloudManager/OpsManager (not covered in this course) BI Connectors MongoDB Charts

   Stitch - new serverless option (gives more than data storage such as): - Serverless Query API - Serverless Functions (unrelated to database) allows me to execute javascript in the server - Database Triggers - Real-Time Sync

6. General Setup Instructions & Installing MongoDb MAC

7. Installing MongoDB on windows.

i did this in another course already so im going to skip it for now

8. Installing MongoDB Shell

              - look up mongoDB shell on google and download latest version

              - install it and place the 'mongosh.exe' and the 'mongocryptd-mongosh.exe' into the bin file

   now when we open our database we can also use the new mongo shell by opening 'mongosh.exe'

9. Installing mongoimport

10.   Time To Get Started!

            -  open mongoDB
            -  open mongosh
            -  press enter in mongosh
            -  see list of dbs:
                  >show dbs

create a database with an item that has a price:

               > db.products.insertOne({name: "A Book", price: 12.99})
               {
                     "acknowledged" : true,
                     "insertedId" : ObjectId("61c18268ab576446eb9ca3e5")
               }

to view the database we just created:

         > db.products.find()
         add '.pretty' to format the output

11. Shell vs Drivers

Drivers are a way to communicate with the database using code instead of the shell. Theres a different driver for each different programing language. The core features are the same.

12.   MongoDB + Clients: The Big Picture

                 APPLICATION:
                    - Frontend(UI)
                    - Backend(Server)
                       drivers: (communicates with mongodb server)
                          - node.jf
                          - java
                          - python
                          - ...

      MongoDB Shell can communicate with the mongodb server as well as the drivers.

                 DATA:
                    MongoDB Server

13.   Course Outline

Thinking I should jump to 'CRUD Deep Dive - Create' lesson, or maybe checkout 'Data Schema & Relations' first.

14. How To Get The Most Out Of The Course
