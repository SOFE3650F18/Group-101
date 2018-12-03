# Group-101  

### Use Cases:  

##### UC-1: Manage Backups  

##### UC-2: Update Course Offerings  

##### UC-3: Access  

##### UC-4: Manage System Downtime  

##### UC-5: Login & User Account Typing  

##### UC-6: Messaging System  

##### UC-7: Courses  

##### UC-8: Security & Privacy  

##### UC-9: Notifications & Teams  

##### UC-10: Boz File Import   

### Quality Attributes:

##### QA-1: Availability  
A System Maintainer requests the CMS system create a copy of itself to serve as a backup. The system copies all data and stores the backup in a designated location.  

##### QA-2: Modifiability  
An administrator requests that a specific course runs an hour later than originally implemented. The system receives this request, modifies the selected information and returns confirmation.  

##### QA-3: Usability  
A user requests access to view the course information. The system retrieves this information through the database and display the information to the user.  

##### QA-4: Performance  
The System Maintainer schedules the system to shut down in two days. The system displays a message to all users notifying them of the future downtime. The system shuts down when the requested time is reached.  

##### QA-5: Security  
A user enters their correct login credentials into the login page. The system sends this information securely to the database and searches for a match. After finding a match, the system connects the user to their account.  

##### QA-6: Usability  
A user sends a message to a list of users through the in-app messenger. The message is then sent to the mailbox of all the users who were included in the recipient field.  

##### QA-7: Modifiability  
A course modification setting, which is available only to the system maintainer, can be accessed to insert new courses, modify the information of current courses, and delete courses.  

##### QA-8: Security  
The system must be able to handle data abstraction based off user permission hierarchy as well as be protected against security attacks.  

##### QA-9: Usability  
The system must be able to display notifications set by lecturers and administration to a designated group of users.  

##### QA-10: Usability  
System will need to be able to handle BOZ file imports from users.  
