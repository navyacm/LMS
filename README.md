# LMS
Library Management system

A demo CRUD app and JWT authentication and autohrization for library management system built with asp .net core web api and sql database.

How to Run Project
1. Download the  zip file and set up files in visual studio 2019.
2. Run the LMNSDBScript in the sql
3. Seup the Connection string in appjsonsettings.app with your database configuration.
4. Build and run the applcation.
5.Install Postman(if not installed).
6. for authentication use http://localhost:port/api/Authentication/Login (note use your system port number). and select post method.
7. pass the parameters usernameand password in the body tab in json format
8. if it authenticated user, will get a JWT token, copy it.
9. select Get method - http://localhost:port/api/book (note use your system port number) and o to authorization tab select bearer token and right side in token option paste the copied JWT token and clik and send button.


