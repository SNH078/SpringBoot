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
