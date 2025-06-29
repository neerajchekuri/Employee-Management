# Employee-Management
backend tech : 

spring-3.5
spring data JPA
java-17
mysql
embedded tomcat - 10 or 11

frontend tech:

angular - 15
node - 23
npm - 10
bootstrap - 5

steps 

1. create spring boot project from spring initialiser and add dependencies

dependencies:

spring web
spring data JPA
mySQL driver
spring boot dev tools

2. create database 

configure datasource url, username, password in the application properties

3.create JPA entity and JPA repository

>inside the model package create Employee entity
>create EmployeeRepository interface and extend JpaRepository interface inside repository package

4. create listemployee rest api

>first create a resourceNotfoundException that extends runtimeexception
>now create EmployeeController inside the controller package

5. create angular listemployee component

>create employee class that holds the response of the rest api
>create the listemployee component

6. connect angular with list employee rest api
 
>first create EmployeeService to make http client calls
>now use the method that we created in the service in the employee list component and display the data in the template file

7.Routing and navigation in angular app

8. create createEmployee rest api and add CreateEmployee component in the angular

>inside the CreateEmployee component add form to add employees

9. connect angular with add employee rest API

10. create getEmployeeById rest api, create employee details component in angular

11. create updateEmployee rest api, create update-employee component in angular

12. create deleteEmployee rest api, no need to create separate component we can use list-employee component for delete method



