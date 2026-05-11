<img width="456" height="253" alt="image" src="https://github.com/user-attachments/assets/6b943fd8-40aa-4ecb-8ab1-d4010a7dd73b" />
<img width="4080" height="2108" alt="image" src="https://github.com/user-attachments/assets/8cec383e-4957-4794-a810-54b4f2d0542b" />

<img width="360" height="314" alt="image" src="https://github.com/user-attachments/assets/e681784f-bcf7-4bbe-b62e-66aaa1c16b61" />
<img width="438" height="362" alt="image" src="https://github.com/user-attachments/assets/1461b0e9-8fab-4ac8-ab55-694d1ca9980f" />


# creating a springBoot web app 

## 1 
<img width="1162" height="874" alt="image" src="https://github.com/user-attachments/assets/88757163-3292-4921-8a57-12ba487cdf9c" />  

## 2 
run the app (localhost 8080)  
<img width="616" height="217" alt="image" src="https://github.com/user-attachments/assets/e2ffd373-6d79-442d-8503-3a0102748193" />

## 3   
create a folder "webapp" under "mian" folder     
under that "index.jsp"  
<img width="621" height="575" alt="image" src="https://github.com/user-attachments/assets/3c3daa5e-2ef2-45a4-9937-68fdba486ec7" />

## 4   write controller    
<img width="742" height="568" alt="image" src="https://github.com/user-attachments/assets/f4948ad8-6da1-42ef-acda-7b127c6939a4" />

 springboot by default doesn't support JSP  
 need to convert JSP into servlet   
 need to add tomcat jasper dependency (from maven repo)  


# code for sum of 2 numbers     
just do this change  
<img width="188" height="29" alt="image" src="https://github.com/user-attachments/assets/fa07d25f-47c5-4311-9298-23ba2ea0781e" />

  notice  when you hit submit button 
  <img width="760" height="398" alt="image" src="https://github.com/user-attachments/assets/bda94603-d0b1-4320-a5f1-d4c37502b9a0" />  
  <img width="442" height="772" alt="image" src="https://github.com/user-attachments/assets/8eb6c87f-06e3-4c2f-88f9-83eff9512249" />

need to add controller to handle the request   
- spring allows you to have multple controller method in a single controller file i.e. multiple mapping

- also need to accept the values ->  `http://localhost:8080/add?num1=3&num2=4`
- 2 ways to do so using : 1)servlet  2) spring
- **servlet :**  HttpservletRequest   <img width="580" height="331" alt="image" src="https://github.com/user-attachments/assets/bf0a7cd3-4890-4363-8246-cc0aa3c3b057" />

- now to print the result on result page is : need to send data
- <img width="836" height="739" alt="image" src="https://github.com/user-attachments/assets/30e4f08b-4d55-4a49-9a65-737a20e899a3" />

 <img width="758" height="398" alt="image" src="https://github.com/user-attachments/assets/8d163dd2-0173-44b2-8fde-f1204195c5d6" />

- <img width="724" height="235" alt="image" src="https://github.com/user-attachments/assets/3a31951b-4969-468f-a22b-e30278c4447c" />

- <img width="775" height="235" alt="image" src="https://github.com/user-attachments/assets/556e0802-f2f2-4832-9b43-7bfe51b3c8e4" />
