Prototype Login Application

Prototype Central Backend Application with Spring Boot integrated with Identity Provider Auth0

OpenID Protocol with Authorization code flow is used

<img width="566" alt="Screenshot 2024-09-24 at 9 35 58 PM" src="https://github.com/user-attachments/assets/3ebe214f-3663-4ba8-a15d-2c2eeec5290f">

To run the application use the below command (Pre-requisites Docker)

docker run -p 8080:8080 anurajkumar/login-app 

Type http://localhost:8080/ in the browser

You will get redirected to the login page as below

<img width="531" alt="Screenshot 2024-09-24 at 9 47 17 PM" src="https://github.com/user-attachments/assets/b9a4264a-535e-4af6-92c4-2f11116d5aee">


You have multiple login options. Login with Google account

You will redirected to the Consent page to Authorize the login request as below

<img width="531" alt="Screenshot 2024-09-24 at 9 48 33 PM" src="https://github.com/user-attachments/assets/7107cc20-9f74-40a9-b9bc-dff5989a100b">


You have given permission to access the profile information and email.

On Accepting the request, you will get logged in.


<img width="563" alt="Screenshot 2024-09-24 at 9 50 06 PM" src="https://github.com/user-attachments/assets/6de38e68-6803-4b08-9867-af7014d90272">



On logout, you will get the option to log in again with Auth0

<img width="563" alt="Screenshot 2024-09-24 at 9 50 40 PM" src="https://github.com/user-attachments/assets/6e69d008-ff55-440f-99e5-44353a15b051">

All the subsequent login happen without entering the login details with SSO.






