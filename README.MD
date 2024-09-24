Prototype Login Application

Prototype Central Backend Application with Spring Boot integrated with Identity Provider Auth0

OpenID Protocol with Authorization code flow is used

<img width="566" alt="Screenshot 2024-09-24 at 9 35 58 PM" src="https://github.com/user-attachments/assets/3ebe214f-3663-4ba8-a15d-2c2eeec5290f">

To run the application use the below command (Pre-requisites Docker)

docker run -p 8080:8080 anurajkumar/login-app 

Type http://localhost:8080/ in the browser

You will get redirected to the login page as below

You have multiple login options. Login with Google account

You will redirected to the Consent page to Authorize the login request as below

You have given permission to access the profile information and email.

On Accepting the request, you will get logged in.

On logout, you will get the option to log in again with Auth0

All the subsequent login happen without entering the login details with SSO.






