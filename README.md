java cEIE4432 Web Systems and Technologies Group Project: Functional Specification 
Project Milestone 1: UI Prototype  
Date of Submission: 2-Nov-2024 SAT (Week 10) (Submitted by ONE group representative) 
Project Milestone 2: Final Product 
Date of Submission: 28-Nov-2024 THU (Week 13) (Submitted by ONE group representative.) 
Application Description The Reservation/Payment/Sales System offers a user-friendly interface where sellers can create and manage events, set ticket types and prices, and monitor ticket sales. It provides real-time updates on ticket availability to both buyers and sellers. Buyers can easily browse corresponding information, select desired tickets through an interactive map, make online payments, and receive electronic tickets.Grouping 
Each group consists of 2 students. No group may contain more than two students. A single group is allowed but not recommended, as teamwork is also a necessary learning process. The requirement is the same for a one-member group or a two-member group. There are four topics for the group project. Each group will be assigned a topic by adding the last digit of each member's student ID and dividing the result by 4. The remainder will determine the assigned topic for the group.
Remainder 
Topic 
0 
Buffet Table Booking and Payment System 
1 
Football Ticket Sales System 
2 
Parking Space Booking and Payment System (e.g., Day/Half-Day parking at Disneyland) 
3 
Cinema Ticket Sales System 
Example 
The final digit of group member 1’s student ID: 4
The final digit of group member 2’s student ID: 7
Calculation: (4+7) mod 4 = 3
(For single-member group: the final digit of the student ID mod 4) 
Assigned Topic: Cinema Ticket Sales System
Warning: Working on an incorrect topic may lead to a 0 mark or mark deduction.
Technical Specifications 
Server Environment
Operating System: Windows, Linux or MacOS
Web Application Architecture: Node.js + Express.js + Database
Database Requirement
As this is not a database subject, students can choose any database, such as MySQL or any NoSQL database like MongoDB.
Hosting Requirement
Students can deploy and host the web application using NodeJS, enabling public access for other clients.
Alternatively, students can use public hosting services like Vercel or other cloud platforms.
Programming SpecificationThe first line of each source code file should include a comment to show all group members’ names and student IDs. All code should be refactored appropriately. That means the code should be reusable and readable to the best of your abilities. For instance, any reusable code should be encapsulated into functions and/or separate files for inclusion. There are no limitations on the framework used for front-end development; students can use any JavaScript-based framework.List of Features The project will be assessed based on features. There are three levels of features to accomplish: Basic, Credit, and Advanced. If your deliverables successfully achieve and demonstrate the listed features, marks will be awarded according to the number of completed features.1. Basic Features 
Category 
Deliverables 
Complete or not? 
User Account Registration · User registration page: support standard information including user ID, password, nickname, email, gender, birthdate, etc. · Validation checks for input value, i.e., password policy and duplicate user ID · Notification on validation failure and the success or failure of registration · An administrator is not required to create an account. 

User Authentication · Two roles: admin and user · Use user ID and password to log in. The admin uses the default ID “admin” and password “adminpass” to log in. · User logout  

Event Dashboard 
· Show the list of events with relative event details (date, time/timeslot, title, description, venue) · Minimum one event · Ticket sales for each event (current ticket availability) 

Ticket Booking Page 
· Select one seat / parking space from the SVG map  · Display available and occupied seats / parking bays in the SVG-based map using different colors · Immediate pricing calculation 

Payment Page 
· Display booking details, selected seat / parking bay and total cost · Enter payment details (Information could be fake) · Feedback on payment status (successful or not) · Display electronic tickets to buyers following a successful transaction · Update the order status upon successful payment 

Seat or Parking Space Management Page (Admin Access only) 
· Create SVG-based seat / parking bay maps for all locations, comprising a minimum of 30 seats or parking bays · View current available and occupied seats /parking bay in the SVG-based map (use different colors) · All seats / parking bays are priced uniformly 

Event Management Page (Admin Access only) 
· Create new events (date/time, title, venue, description)
e.g., lunch/dinner Buffet/monthly promotion/Christmas promotion/regular monthly sales 

2. Credit Features 
Category 
Deliverables 
Complete or not? 
User Account Registration · User registration page: in代 写EIE4432 Web Systems and TechnologiesJava
代做程序编程语言clude a profile image above the regular information fields · Password stored in a database via password hashing 

User Login · Choice to remember login user-id 

User Account Management · Access user profile · Update user profile, including name, password, email and profile image 

Event Dashboard 
· Display the list of events with event details (date/time, title, venue, description and cover image) · At least two events · Search options to filter events by date/time, title, venue and description · Real-time event name recommendations during searches (similar to Google auto-complete predictions) 

Ticket Booking Page 
· Select more than one seat / parking space from the SVG map at the same time · Display available and occupied seats / parking bays in the SVG-based map using different colors · Immediate pricing calculation 

Transaction History · Display the complete transaction history, including ticket details and pricing 



Seat / Parking Bay Management Page (Admin Access only) 
· Modify SVG-based seat / parking bay maps for all venues · There should be a minimum of two pricing tiers for all seats or parking spaces, such as economy and first-class rates for airplane tickets 

Event Management Page (Admin Access only) 
· Create new events (include cover image above date/time, title, venue, and description) · Search option to filter events by date/time, title, venue and description · Modify current events (date/time, title, venue, description, cover image) · List the transaction history of all users, including ticket details and pricing for each event 

3. Advanced Features 
Category 
Deliverables 
Complete or not? 
User Account Management
(Admin Access only) · Access all user account information (Admin only) 

Seat / Parking Bay Management Page (Admin Access only) 
· Interactive SVG-based seat or parking bay map displaying the associated user who bought the seat / parking bay upon clicking or hovering over the respective seat or parking bay 


Others · One major feature or two smaller advanced features designed by you, with a workload or time commitment comparable to the above. The feature can be an enhancement within a webpage or a new feature. Please mention them in your report and video demonstration. 

Delivery Time and Method 
Project Milestone 1: UI Prototype 
Date of Submission: 2-Nov-2024 SAT (Week 10) (Submitted by ONE group representative)
Deliverables:
● Interim Report
○ Cover page includes the names and student IDs of the group members and the assigned topic
○ Website Structure (e.g., Pages to be included in Tree Diagram Format)
○ UI Prototype Screen Captures (Utilize technologies such as HTML, MS Paint, or Figma to design the layout of web page)
○ Application Workflow Diagram
○ Work distribution
● Source Code of UI Prototype in ZIP or 7-ZIP file if you have
Project Milestone 2: Final Product 
Date of Submission: 28-Nov-2024 THU (Week 13) (Submitted by ONE group representative)
Deliverables:
● Final Report
○ Here are the parts required to be included, but not limited to:■ Cover page includes the names and student IDs of the group members and the assigned topic■ Table of Contents
■ Introduction
■ Tech Stack: Present a summary of the front-end technologies, back-end technologies, databases, development tools, and hosting platforms utilized.
■ Website Structure
■ Application Features
● A tabulated checklist table to indicate which features have been completed.
Features 
Complete or Partial Complete or Not Complete 
Feature 1  
Complete 
Feature 2 
Not Complete 
Feature 3 
Partial Complete 
… 
… 

■ Database Design
● Description of tables and data fields of each table

● If MySQL is used, please provide an Entity-Relationship Diagram (ERD)
● If NoSQL is used, please provide a Data Model Diagram
■ Describe any third-party APIs or npm packages utilized.
■ User test cases, including both valid and invalid scenarios, with screenshots
■ Conclusion■ Work distribution
● Bonus Section: (Optional; Capped at 100% the total)
○ To obtain this bonus mark, please incorporate the following elements in both the report and the video demonstration.
■ Utilization of GitHub for storage, publishing, and/or version control (evidence of more than two updates in different dates)
■ More than two GitHub pull requests in different dates.
■ Capable to hosting the website in the cloud. Please provide web address, username, and password for admin or user access.
● Source Code of Whole Project in ZIP or 7-Zip format
● Public URL for accessing the web application if you have

● Video Demonstration 
○ All members should participate and show their faces in the video demonstration, which should be in MP4 format. If the video is too large to submit, please share it using OneDrive or YouTube.
○ Demonstrate your system verbally (show all functions; do not show slides)
○ Time limit for the video (Maximum: 15 minutes)
○ Presentation fluency



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
