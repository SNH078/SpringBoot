## spring
java framework  
to build applications (especially backend systems).  

👉 Its main job:

Manage objects
Reduce boilerplate code
Make code loosely coupled  

---

## spring Boot  
Java framework  
built on top of Spring

👉 It makes Spring:  
Faster to start  
Easier to configure  
Ready for production quickly
 
Spring Boot = Spring + automation + less setup

---

## Auto-Configuration
 biggest feature of Spring Boot

👉 Spring Boot automatically:  
Configures database  
Sets up web server   
Loads required beans

<img width="385" height="297" alt="image" src="https://github.com/user-attachments/assets/2f013c75-4115-455f-8e3d-2643effcc177" />

---

## Starter Dependencies  
Starters are pre-packaged dependencies  

👉 Instead of adding many libraries manually, you add one starter

<img width="308" height="207" alt="image" src="https://github.com/user-attachments/assets/81d0cd71-5896-48d1-b6b8-52549095bd39" />

---

servlets (outdated) -> spring MVC (new)
apache tomcat (Servlets container)  

**build tool**  
maven *  , gradle 

**DB connectivity**  
JDBC  

Hibernate  

---

## IOC ( inversion of control )   - principle
 you don’t control object creation — Spring does    
 to achieve this we hv ```IOC container``` in spring - > 
 <img width="475" height="585" alt="image" src="https://github.com/user-attachments/assets/1786a5dc-3f58-4a27-8399-708e7ec2c0c4" />  
 Control of object creation is inverted (shifted) from you → to Spring

 ---

## DI (Dependency Injection)     - design pattern 
 Spring provides required objects (dependencies) to your class
<img width="381" height="407" alt="image" src="https://github.com/user-attachments/assets/f38db51d-1d15-4ee4-88dc-57919f983f08" />
👉 DI is a way to achieve IoC

<img width="314" height="576" alt="image" src="https://github.com/user-attachments/assets/025ad04e-77dd-4fee-adb9-3db4b00cd212" />
