# fullstack_application
It contains sample serverless and react application


I uploaded whole project as zip because of secuirity mesaures my company not allowing us to use own credentials in our system.

----------------------Backend----------------------------------------------------
And I created node application using aws lambda function and serverless framework.

To run the project install configure aws credentials to your system and aws cli

then install serverless framework using npm i serverless then run the command serverless deploy

-----------------------------------------------------------------------------------

------------------------Front end----------------------------------------------

To run the project run the componet npm i and npm start

--------------------------------------------------------------------------

Functionality:

   1,In password text box we should enter the value when the all checks passed then only the store button will be enabled 
   and we can store the password to db using that api.
   
   2,To check the password stored or not check the following end points
   
   https://rdmh97sni5.execute-api.us-east-1.amazonaws.com/dev/getPasswords 
   
   https://rdmh97sni5.execute-api.us-east-1.amazonaws.com/dev/getPassword/2b763028-b0e3-4cd9-8464-9b276ab45470
   
