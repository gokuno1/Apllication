{\rtf1\ansi\ansicpg1252\deff0\nouicompat{\fonttbl{\f0\fswiss\fcharset0 Calibri;}{\f1\fnil\fcharset0 Calibri;}}
{\*\generator Riched20 10.0.17134}\viewkind4\uc1 
\pard\widctlpar\f0\fs20\lang1033\par
Bank Application with Spring Boot and microservices This application performs Banking operations like opening account, transfering funds from one account to another. As it is basic project, there is no security used. But in future commits try to add more features. There are two services:\par
\par
1.Accout Service: This service has methods to create account, update account and delete account along with get account by Id and Name.\par
\par
 i. Create Account:\par
    - Uses Post Mapping\par
 \par
 ii. Delete Account:\par
     - Uses Delete Mapping\par
 \par
 iii. Update Account:\par
     - Uses Put Mapping\par
 \par
 iv. Get Account by account number:\par
     - Uses Get Mapping\par
     - account number is passed as PathVariable and details are retreived using account number.\par
Transaction Service: This service has only one method currently.\par
\par
 i.\tab Transfer Funds from one account to another\par
     1.\tab Uses Get Mapping\par
     2.\tab Account number of source and destination are passed as PathVariable through URL.\par
     3.\tab then update method is called to update details of account.\par
     4.\tab Feign is used for interservice communication and transfer of data.\par
Added Swagger configuration in last commit\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par
\par

\pard\sa200\sl276\slmult1\f1\fs22\lang9\par
}
 