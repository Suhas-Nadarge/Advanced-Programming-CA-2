# Advanced-Programming-CA

*BULK EMAILER*

Stack Used:
-UI: Angular
-BE: Python(Flask)
-DB: SQLlite


In this project we have developed application which will offer users to send emails in bulk. 
(Currently we are sending all emails from Admin's account but we are planning to make it user specific. 
Due to some security issues we can not ask user to enter password for email,but we are working around and trying to find
if there any third party api which can provide login via GMAIL.)


User Guide:

-User need to register to our portal.

-Once user is registered, user can login with the same credentials.

-User can go to Send Email Page from nav bar, on that page user need to enter Email Subject, List of recipient(seperated by comma),
  and Email content which he can enter in text editor or copy paste the signiture of mail.
  
-After entering all the detail, user can hit the 'Send' button. Email will be sent to all valid email entered in recipent text area field.

-After sending email, User can go to 'View History' page where user can see the details of email sent including Username,Subject,Recipient,
  Status(Failed in case of invalid email else Success), Date-Time.
  
-User can also view the content of the mail from View History Table, by clicking on 'View button' on each row.

-Use can clear the history by clicking on Delete button from each row or can delete all using 'Delete All' button at the bottom of the table.

-For better understanding how to use the application, we have also embedded Youtube link of our demo on 'Home Page'



-We are facing difficulties while deploying application, so for time being we have up and running codebase on below virtual machine for Demo:
 -IP address:20.126.157.160
 -Username:Virender
 -Password:DBS@virtualpc
 
 
 
 
