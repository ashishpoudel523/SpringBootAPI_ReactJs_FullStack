Created a Full stack web application using Spring Boot and ReactJS. In this project, Spring Boot ( MVC, JPA, Hibernate) is used and Mysql Database to create the Backend application (Restful web service API) with and use React.js to create the frontend application with React Hooks( useState, useEffect) with functional components. Its simple full stack project with RESTful Web services API and also use fetch can use axios) for consuming REST API.

CURL = Client URL 
command line tool and library
for transferring data with URLs


For get,
curl -v url


For post,
curl -i -X POST http://localhost:8080/save \ -H "Content-Type:application/json" -d "{\"id\":1, \"fname\":\"Ashish\", \"lname\":\"Poudel\"}"


For put,
curl -i -X PUT http://localhost:8080/edit/2 \ -H "Content-Type:application/json" -d "{\"fname\":\"Ashmi\"}"


For delete,
curl  -X DELETE http://localhost/delete/id