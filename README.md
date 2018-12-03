# Group-101  

### Use Cases:  

##### UC-1: Manage Backups  
Backups for the system should be created on a regular basis, where after the creation of a new backup, the previous revision is overwritten.  
##### UC-2: Update Course Offerings  
Administrator can change and implement new course offerings, as well as modification of previously existing courses.  
##### UC-3: Access  
User requests information pertaining to courses and the system sends responses corresponding to their queries.  
##### UC-4: Manage System Downtime  
System Maintainer sends notifications to all users prior to shutdown of the system for purposes of system management. These updates and modifications are only done at non-peak hours.  
##### UC-5: Login & User Account Typing  
Login credentials are supplied by users and their corresponding account, including their account type is retrieved showing the user only information available as per their clearance level.  
##### UC-6: Messaging System  
A messaging system to allow for users to communicate with one another.  
##### UC-7: Courses  
Allows for access of course information, modification of the course offerings, availability of courses and storage of courses.  
##### UC-8: Security & Privacy  
System shall maintain security through login system and privacy through protection of user information.  
##### UC-9: Notifications & Teams  
System shall send users notifications based on changes that affect them. Furthermore, system shall allow for creation of teams.  
##### UC-10: Boz File Import   
System shall allow the import of BOZ roster information into the course roster.  

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

### Constraints  

##### CON-1:  
The system must be accessed through a web browser (Chrome V3.0+, Firefox V4+, IE8+) on either Windows, MacOS, or Linux.  

##### CON-2:  
The system will require a database capable of storing at minimum 5 TB of data.  

##### CON-3:  
The System must be accessible on low bandwidth connections.  

##### CON-4:  
All actions performed by the database within the last month should be stored.  

##### CON-5:  
Backups must be created each day at 11 59 PM and should take no longer than 5 minutes to generate.  

##### CON-6:  
System must be able to process large amounts of requests without crashing.  

##### CON-7:  
System must be protected from Denial of Service attacks as well as SQL injection attacks.  
