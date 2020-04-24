
Bank Application with Spring Boot and microservices This application performs Banking operations like opening account, transfering funds from one account to another. As it is basic project, there is no security used. But in future commits try to add more features. There are two services:

1.Accout Service: This service has methods to create account, update account and delete account along with get account by Id and Name.

 i. Create Account:\par
    - Uses Post Mapping\par

 ii. Delete Account:\par
     - Uses Delete Mapping\par

 iii. Update Account:\par
     - Uses Put Mapping\par

 iv. Get Account by account number:\par
     - Uses Get Mapping\par
     - account number is passed as PathVariable and details are retreived using account number.\par
Transaction Service: This service has only one method currently.\par

 i. Transfer Funds from one account to another\par
     1. Uses Get Mapping\par
     2. Account number of source and destination are passed as PathVariable through URL.\par
     3. then update method is called to update details of account.\par
     4. Feign is used for interservice communication and transfer of data.\par
Added Swagger configuration in last commit\par

