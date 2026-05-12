# Servlet Container
<img width="306" height="311" alt="image" src="https://github.com/user-attachments/assets/26cf7317-bfb0-48c2-afe9-2ab850c33b8a" />

In a Spring Boot web application, the Servlet Container is the component that actually runs your web app and handles HTTP requests/responses.  

Browser → Tomcat → Spring Boot Application → Controller → Response  

Example:  

User hits:  
http://localhost:8080/users  
Apache Tomcat receives the HTTP request.  
Tomcat passes it to Spring’s DispatcherServlet.  
DispatcherServlet finds the correct controller method.  
Controller returns data/view.  
Response goes back through Tomcat to the browser.  

# WAR file   
Web Application Archive   

packaged Java web application used for deployment on a servlet container/server like Apache Tomcat. 
<img width="191" height="357" alt="image" src="https://github.com/user-attachments/assets/7e89fe6a-4333-405e-b81c-1f37a61a472a" />  
<img width="443" height="304" alt="image" src="https://github.com/user-attachments/assets/c5d4f60c-88ef-43de-8403-65dc67bfd253" />

----

# steps to run tomcat    --- embedded tomcat 
1 . <img width="292" height="444" alt="image" src="https://github.com/user-attachments/assets/c18d1191-ae74-4397-8925-e5c4ea9148d4" />  

2. open IDE -> create 'maven archetype' project   
3. browser -> add "java servlet api"& "jakarta servlet" dependency in pom.xml   
4. **run tomcat server** <img width="1041" height="690" alt="image" src="https://github.com/user-attachments/assets/03657dd3-024d-41d6-a40e-e8d13093a7a1" />
5. <img width="1029" height="820" alt="image" src="https://github.com/user-attachments/assets/dcd2f66b-2778-4649-82e1-83d222d8f2fe" />
6. earlier days, we used web.xml for mapping of servelet & url : It tells Tomcat: “Which URL should call which servlet?”
Now modern Java uses annotations.
use this for external tomcat : 
<img width="421" height="102" alt="image" src="https://github.com/user-attachments/assets/d1790af3-bd82-4819-b08f-b3808417b577" />
<img width="524" height="192" alt="image" src="https://github.com/user-attachments/assets/66ad1f06-1a46-4e4c-8614-a5b6c0efc451" />
<img width="376" height="178" alt="image" src="https://github.com/user-attachments/assets/dbafc03d-da72-41cd-9f28-14a4ff858fff" />
addContext() : adds/registers a web application into embedded Apache Tomcat.
 <img width="261" height="530" alt="image" src="https://github.com/user-attachments/assets/cf77c3df-2f45-4e03-9720-6d3e2e9adbd2" />
<img width="270" height="407" alt="image" src="https://github.com/user-attachments/assets/2e78379a-16e2-4fed-ab02-933bfd15f2be" />


8.  <img width="1398" height="959" alt="image" src="https://github.com/user-attachments/assets/73337921-ab52-4b57-9af1-8edb19b77873" />
9.  <img width="1495" height="965" alt="image" src="https://github.com/user-attachments/assets/558cb702-a361-4ddf-8937-4847b314a3b2" />
10. everytime you hit `http://localhost:9090/hello` "hello world1" gets printed on tomacat terminal




## note    
 <img width="267" height="283" alt="image" src="https://github.com/user-attachments/assets/31d41628-6244-4d62-872d-669bead969e4" />

<img width="356" height="607" alt="image" src="https://github.com/user-attachments/assets/062b6d88-1f65-44e5-b87c-83e96ebbbfe1" />

<img width="446" height="264" alt="image" src="https://github.com/user-attachments/assets/d5696d10-9fdf-4480-b3c6-04fe699c94f2" />

