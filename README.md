# Employee-CRUD-Application
Spring boot API for performing simple employee CRUD operation with user access and roles

# How to Run this Project
1. Navigate to https://start.spring.io/ and create a spring boot app with Group/Package name 'com.employee.crud.app' and Artifact/Name 'Employee-CRUD-App'
2. Open the pom.xml file to check the required dependencies to add. I used MySQL version <version>5.1.37</version>
3. Generate and download the file and open it in your favourite IDE. I used Intellij IDE
4. You may wish to copy the entire 'src' folder and replace it in yours or create the model, controller, service, security, payload, exceptions... packages and files seperately.
5. Check your database connection propertise in the application.properties file. Create the database 'employee_crud_db' in you MySQL terminal or query brower.
6. Run the app to generate the tables in your database.
7. Run the following query to insert three(3) user roles in the roles table:
    INSERT INTO roles(name) VALUES('ROLE_USER');
    INSERT INTO roles(name) VALUES('ROLE_ADMIN');
    INSERT INTO roles(name) VALUES('ROLE_SUPER_ADMIN');
8. Open Postman and test the app

# Screenshots
# User Sign Up
![Screenshot-Signup](https://user-images.githubusercontent.com/31050193/186705019-4d65a05b-55f5-45d4-b877-94505ea6c4ac.png)

# User Sign Up Response
![Screenshot-Signup Response](https://user-images.githubusercontent.com/31050193/186705091-bf5bbb84-0ce7-41d1-b293-997cc042398b.png)

# User Sign In
![Screenshot-User SignIn](https://user-images.githubusercontent.com/31050193/186705134-26f43516-20a5-42a9-a2b6-510f458de536.png)

# Saving Employee Record
![Screenshot-Save Employee](https://user-images.githubusercontent.com/31050193/186705160-2db08054-8d49-4a20-93c0-60210e178ce1.png)

# Enjoy!
