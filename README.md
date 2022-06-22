<head>
<link rel="stylesheet" href="github.css">
 </head>
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Feb-2022** 
<h3 align='center'>Introduction to Linux & Installing Ubuntu</h3>

<p align="justify">Linux is an open-source operating system like other operating systems such as Microsoft Windows, Apple Mac OS, iOS, Google android, etc. An operating system is a software that enables the communication between computer hardware and software. It conveys input to get processed by the processor and brings output to the hardware to display it. This is the basic function of an operating system.</p>

- Download the linux distribution of your choice.
- Creating Boot pendrive using rufus.exe in windows.
- Restart the system and open boot menu using boot key. (Eg.- F8, F2 etc.)
- Select your boot device in boot menu.
- Select Install Ubuntu then Click Noraml Installation.
- Select where to install alongside window or Erase disk or something else.
- Then Click next and start ubuntu installation.
- For More detail about Installation Guide [Click here](https://phoenixnap.com/kb/install-ubuntu-20-04)
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Feb-2022** 
<h3 align='center'>Introduction to LAMP Stack</h3>

<p align="justify">The LAMP stack is a popular open-source solution stack used primarily in web development.LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the LAMP acronym:</p>

- Linux is an operating system used to run the rest of the components.
- Apache HTTP Server is a web server software used to serve static web pages.
- MySQL is a relational database management system used for creating and managing web databases, but also for data warehousing, application logging, e-commerce, etc.
- PHP, Perl, and Python are programming languages are used to create web applications.
- Installing lamp on Ubuntu System.
- Verifying by run LAMP on localhost.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Feb-2022**
<h3 align='center'>Run Cgi Script</h3>

<p align="justify">CGI stands for Common Gateway Interface. CGI defines a standard way in which information may be passed to and from the browser and server. Any program or script that can process information according to the CGI specification can, in theory, be used to code a CGI script.</p>

- Create a cgi scirpt.
- Run it on Localhost using Apache Server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Feb-2022**
<h3 align='center'>Image to video</h3>

- Create a python Script.
- install pip,Image-MagicK on your system.
- goto ---- /etc/ImageMagick-6/policy.xml file. 
- Comment out line "policy domain="path" rights="none" pattern="@*" 
- Run the script by using python3 filename.py.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Feb-2022**
<h3 align='center'>Introduction to frappe</h3>

<p align="justify">Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ErpGuru, is pretty generic and can be used to build database driven apps.</p>
## Why Frappe?
<p align="justify">The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.</p>

- Install Frappe-bench and its required tool. For more info [Click here](https://frappeframework.com/docs/v13/user/en/installation).
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Feb-2022**
<h3 align='center'>Creating App and Site & run on local server in Frappe</h3>

- Start Bench in one Terminal.
- In Second Terminal.
- Creating App by using **bench new-app library_management** inside Frappe-bench Directory.
- Creating site by using **bench new-site library.test** inside Frappe-bench Directory.
- Run Site on Localhost by using library.test custom port name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Feb-2022**
<h3 align='center'>Introduction to Github Pages</h3>

- Getting Information What is GitHub Pages.
- Create a New Repository on GitHub.
- Setting Repository as the main branch and setting a theme for GitHub pages.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Feb-2022** 
<h3 align='center'>Library Management System app in frappe</h3>

- Created LMS app in frappe.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-Feb-2022** 
<h3 align='center'>Introduction to Docker, Virtual Machine and ErpGuru</h3>

**What is Docker?**
<p align="justify">Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up
time.</p>
- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
<br>

**What is Virtual Machine?**
<p align="justify">A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine.  Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.</p>
- It can start only a single VM on a VMX.
- It can run only a limited number of VMs on a system.
<br>

**What is ErpGuru?**
<p align="justify">ErpGuru is a full-featured business management solution that helps SMEs to record all their business transactions in a single system. With ErpGuru, SMEs can make informed, fact-based, timely decisions to remain ahead in the competition. It serves as the backbone of a business adding strength, transparency, and control to your growing enterprise.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Feb-2022** 
<h3 align='center'>Installing ErpGuru in Frappe-bench</h3>

- If Frappe-bench installed in system follow second method otherwise you will get error.
- Installion done with two manner 
- By Adduser in linux
- And create ErpGuru app and site in frappe-bench Diretory.
- For installation steps [Click here](https://github.com/D-codE-Hub/ErpGuru-installation-Guide/blob/main/README.md). 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Feb-2022** 
<h3 align='center'>Introduction to Selenium, Budibase, Coding standard for program</h3>
- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- <p align="justify">With Budibase, developers no-longer experience repetition, long-dev cycles, and frustration. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.</p>
- <p align="justify">How to write code in Any script so that it can easily read by other programmer who contribute to your project, take variable name which should be relevant with its function.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Feb-2022** 
<h3 align='center'>Try to Solve error redis-server during Installation</h3>
**error while loading shared libraries: libatomic.so.1: cannot open shared object file: No such file or directory**
- sudo apt purge libatomic1.
- install houncho  if file is missing.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Feb-2022** 
<h3 align='center'>Introduction to Education module in ErpGuru</h3>
<p align="justify">The Education domain in ErpGuru is designed to meet requirements of any organization which imparts knowledge and believe in doing so in an organized fashion. It has already been used at schools, colleges and even in private firms.
It helps you to effectively manage administration and allows you to focus on what is most important for your institute, to educate!</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Feb-2022** 
<h3 align='center'>Introduction to Jinja Templating</h3>
<p align='justify'>Jinja is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax. Then the template is passed data to render the final document.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Feb-2022** 
<h3 align='center'>Trying to fetch data from database using Jinja Templating</h3>
- Write a Python Script for establish connection with Mariadb.
- Still it gives permission error try to solve it.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Feb-2022** 
<h3 align='center'>Working with server</h3>
- Resetting the password of server.
- Trying to install ErpGuru on server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Feb-2022** 
<h3 align='center'>Mysql Administration, Converting pdf to md file</h3>
- Today I created a new doctype in ErpGuru with different options
- then learned about the administration concept of database
- Converting pdf file to md and applying changes using markdown.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Feb-2022** 
<h3 align='center'>Working on ErpGuru</h3>
- Today i started working on new platform ErpGuru it is open source, and low code or no platform.Today i am reading the documentation of ErpGuru to  understand the education domain. Today i have created some programs and courses now i am trying to understand how to enroll students in programs and courses.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Feb-2022** 
<h3 align='center'>How to use ssh</h3>
- Login to Server, Try to help other member to install ldap on server.
- Apply different permission related queries on database for different user.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Feb-2022** 
<h3 align='center'>Learning about how to import data in ErpGuru from csv file</h3>
- Try to import data in ErpGuru app throught csv file.
- Apply pagination in ErpGuru webpage.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Feb-2022** 
<h3 align='center'>Learning different modules of education domain</h3>
- I am learning about the modules of education domain. It has so many different modules like attendance module, assessment module, course scheduling, HR, settings, admission etc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Feb-2022** 
<h3 align='center'>Creating Web page in ErpGuru</h3>
- Creating Static Webpage on ErpGuru.
- Learning Frappe School Module.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Mar-2022** 
<h3 align='center'>Learn Module from Frappe School</h3>
- Creating new site with new app.
- Creating Doctype and linking doctype with other.
- Learn Jinja Script for frappe doctypes. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Mar-2022** 
<h3 align='center'>Learning Different modules of ErpGuru</h3>
- Understand the structure of ErpGuru app.
- Understand the javascript code and python code of ErpGuru app.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Mar-2022**
<h3 align='center'>Meeting app</h3>
- Today vishal and pawan gave us a presentation of meeting app. They showed us how to create custom apps in erp and how to install it onto the site. And they also showed us the code of the app and structure and files of the meeting app. Working on instructure section of education module of ErpGuru.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Mar-2022** 
<h3 align='center'>Notice Board app</h3>
- Today we all created a notice board app in erpneext within 30 minutes. It was a wonderful experience as we can created such apps withiin a short time period.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-Mar-2022**
<h3 align='center'>Basic setup for Nankana Sahib Public school</h3>
- Today I am done with the basic setup of Nankana Sahib Public School. I have created three programs Class 1, Class 2, Class 3 and three instructors for each class , four courses for each class, and 2-2 topics per courses, three room and other basic requirements. I have imported data of 8 students using the data import feature in ErpGuru and also tried to update the existing record which is working fine without any issue.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Mar-2022** 
<h3 align='center'>Started working on Mentor-mentee app</h3>
- Today, I and Sehjal started working on mentor-mentee app. In this, we need to create a list of mentors, a list of their mentees and their relation.
  The requiremnet is to create metors and get their mentees just by clicking on the mentor name. And when we click on any mentee's name it will show all its details.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Mar-2022** 
<h3 align='center'>Creating doctypes in mentor-mentee app</h3>
- Today, we have created a doctype named Mentor for mentor's information.
- In this, we entered mentors and their details.
- Also add their mentees under each mentor.
 <br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Mar-2022** 
<h3 align='center'>Creating doctypes in mentor-mentee app</h3>
- We have created a doctype named Mentee for mentee's information.
- In this, we entered mentees and their details.
- Also add their mentors under each mentee.
 <br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Mar-2022** 
<h3 align='center'>Creating doctypes in mentor-mentee app</h3>
- Today, we have created a doctype named Relation for mentor and mentee relation.
- In this, we entered mentees and their mentor details.
  <br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Mar-2022** 
<h3 align='center'>Web-page for mentor-mentee app</h3>
- After creating doctypes for mentor-mentee app, now we have created a web-page.
- We need to show mentors and mentees list in web-page and get their information just by clicking on their name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Mar-2022** 
<h3 align='center'>Reading files for mentor-mentee app</h3>
- After creating web-page, we are reading the files as we want to fetch the mentees from the mentees table. It creates .py and .html file when we created doctype and it creates row.html and .html file when we give the web view to doctype.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Mar-2022** 
<h3 align='center'>SQL query for fetching data</h3>
- Today, we are finding a query to fetch data from tables. We need to fetch mentees name under their respective mentors. Also we need to give reference of web-page to access it.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Mar-2022** 
<h3 align='center'>Searching in Web-page</h3>
- After fetching data, we are done with the search bar in web-page. It is needed so that we can easily search the mentee or mentor just by entering their name in search bar because there will be a huge list. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Mar-2022** 
<h3 align='center'>Attendance module in ErpGuru</h3>
- Today, I studied about how to mark attendance in ErpGuru. There are two methods to mark attendance:- using Student attendance and Student Attendance tool.
For marking attendance of single student we can use student attendance and for bulk entries, we can use student attendance tool.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Mar-2022** 
<h3 align='center'>Leave in ErpGuru</h3>
- In attendance, only instructors are able to add leave of a student. They have the access to accept/reject it.
- So, I logged in using an instructor's ID and password, and they can easily add it and can mark the student present/absent based on leave. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Mar-2022** 
<h3 align='center'>Gunicorn, Socket.io, Scaffhold</h3>
- Today we got to know three new terms that are used in frappe first is Gunicorn:-Gunicorn is built so many different web servers can interact with it. It - also does not really care what you used to build your web application - as long as it can be interacted with using the WSGI interface.Gunicorn takes care - of everything which happens in-between the web server and your web application.

- Socket.io:-Socket.IO is a library that enables low-latency, bidirectional and event-based communication between a client and a server. It is built on top - of the WebSocket protocol and provides additional guarantees like fallback to HTTP long-polling or automatic reconnection.

- Scaffhold:-Scaffolding is a meta-programming method of building database-backed software applications. It is a technique supported by some model-view-- - - controller frameworks, in which the programmer may write a specification that describes how the application database may be used. The compiler uses this - specification to generate code that the application can use to create, read, update and delete database entries, effectively treating the template as a - - "scaffold" on which to build a more powerful application.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Mar-2022** 
<h3 align='center'>Reading the excellent reports by seniors</h3>
- Today i was reading the three report that was written by our seniors. 1.The above report is based on the language translator in which a group is trying - - to understand the role of lex and parser. It was really fun to read this report I really enjoyed reading it. The starting of the report, the examples - - - delivered during the presentation, and the question answers during the presentation is really excellent. My favourite part of the report was someone said - "You should say, I don't know java rather than I don't like java" and also the chinese part as this is the best way to start and to gather the attention - of the audience and to . 2.The above report is based on the regular expressions , in the report they have mentioned the struggles of programmers in the - - early times as they did not had the laptops and personal computers. 3.This report "An ancient art of secure communication" is based on the encryption and - decryption It was really interesting to know how encryption was used in the ancient times the example of "shaving the head of employee" for secure - - - - communication was very interesting and the example of kheer and the phrases "Adhi raat da hanera, vich taare hi taare, mere gharo'n oat hoyi." was very - - intersting.

- I really enjoyed reading the above reports.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Mar-2022** 
<h3 align='center'>Installing new ErpGuru on server</h3>
- First we install frappe framework then install ErpGuru with education domain.
-  After this we are collecting students and teachers data from Nankana Sahib Public School. - Arranging data according to doctype in ErpGuru.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Mar-2022** 
<h3 align='center'>Helping others in their tasks</h3>
Today i Was helping others in their tasks. I helped Jaspreet in importing instructors as there were some issue we both were trying to resolve it and after investing some time in it it got resolved. After this I helped Sehjal in importing And adding the students in ErpGuru. And was trying to understand their tasks.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Mar-2022** 
<h3 align='center'>Basic setup of education domain</h3>
Today I have done the basic setup of education. First I added students then created programs and courses.
After that i enrolled the students in their respective programs.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Mar-2022** 
<h3 align='center'>Student Group</h3>
Today, I studied how we can create student groups and add students in their respective groups.
It is easy to create student groups by going in student group.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Mar-2022** 
<h3 align='center'>Integration of ErpGuru with moodle</h3>
Today sir gave me a task to find a solution to integrate ErpGuru with moodle.After searching i got to know a new tool by which we can integrate ErpGuru with moodle.Myddleware for Moodle enables you to transfer your data easily and safely from your Moodle application to other applications such as your e-commerce, CRM or messaging tools. By doing so, it ensures a durable quality of your data, which is a prerequisite for productivity and efficiency. Your company can save time and money on data issues : no more endless IT expenses to ensure a smooth and secure data migration process, no more worrying about lost, out of date or incorrect data. With Myddleware, increase customer satisfaction thanks to a greater data quality.

Myddleware, easily connect Moodle to other applications for more productivity and efficiency :

CRM/ERP : Salesforce, SAP CRM, SugarCRM, SuiteCRM, ErpGuru, Hubspot, Cirrus Shield Manage your Moddle courses directly from your CRM and collect information on course completion.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-Mar-2022** 
<h3 align='center'>User Permissions</h3>
Today my task was to only show all the instructor and students only their concerned programs and courses on desk and on lms as well. I was searching for the solutions and also posted my query on discussion forum. And i got one reply for this they said to use user permission for each user and assign them particular programs and courses. After doing this instrcutors and students was able to view only their concerned programs and courses on desk. Also on Lms only the assigned programs and courses was visible to the students but to the instructors all the programs and courses was visible even after giving user permissions and role based permissions.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-Mar-2022** 
<h3 align='center'>Arranging the csv file for adding programs</h3>
Today, I have to add the programs for NSPS. For that, i have arranged a csv file for Classes 1 to 10. Also, we can do it from front end .
The csv file has 2 fields:- program name and department. Department will be teaching or non-teaching but here it will be teaching.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 31-Mar-2022** 
<h3 align='center'>Reading the files of LMS</h3>
As by using user permissions still instructor was able to see all the programs and courses. To find the solution for this we are trying to understand the structure of lms for this i was reading all the files of lms present in ErpGuru in the programs and course file it is metioned that by default instructor has access to all the programs and courses.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-April-2022** 
<h3 align='center'>User Permission</h3>
After applying the user permission to the instructor for programs and courses instructor is able to see there current programs only. When instructor is trying to access the courses they are able to access it. But when they are trying to access the programs they are getting error/ Notification:- "Not allowed for Course: Math-6 in Row 2. Restricted field: courseUser "abc@gmail.com" (instructor) does not have access to this document

Insufficient Permission for Program Class-6" Now I am trying to understand how to resolve it. Because this error means that to give access to the instructor first we need to to give access of all the courses to the instructor even if they are not teaching all the courses which is unacceptable in technical terms.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-April-2022** 
<h3 align='center'>Arranging csv file for adding Courses </h3>
Today, I have to arrange the csv file for adding courses for NSPS. Another method to do it is from front end which is very time consuming. It can also be added while adding programs just by adding another field (course) in the file. After preparing, I have imported it in erp.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-April-2022** 
<h3 align='center'>Enrolling courses in programs</h3>
Today, I have to enrolled the courses in their respective programs. Firstly we need to have list of programs and courses so that we can easily fetch them.
We can enroll the courses in two methods:- front-end and via csv file. FOr front end , we have to do it manually for each program else we can arrange csv file for the same.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-April-2022** 
<h3 align='center'>Mark Attendence of student by different methods</h3>
Today i have explored mark attendance based on Student Group, then further there are three options i.e. Group based on: Batch, Course and Activity.

Based on Batch: We can mark attendance of all students of a group based on batch that is section A or section B. Based on Course: Here, we can mark attendance of all students of the group i.e. based on course. Based on Activity: Here, we can mark attendance based on the Activity group. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-April-2022** 
<h3 align='center'>Exploring LMS</h3>
Today we all have explored learning management system in ErpGuru too "https://gne11.gndec.ac.in/lms" which is basically student interface. Here we checked that we can only show the programs to the student.In which quiz , article, video content is show. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-April-2022** 
<h3 align='center'>Fetching data from another doctype in doctype</h3>
Today I was trying to fetch the fields in the doctype from other doctypes and sehjal also helped me in this we were able to fetch branch name (username) etc. I am not able to do it on my local ErpGuru as i am getting an error related to supervisor. So, i was trying to solve it and finding a solution for it. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-April-2022** 
<h3 align='center'>Web-page for converting temperature</h3>
Today, I was given a task to convert the temperature from celsius to fahrenheit. For that, I have to create a web-page through which user can enter the input  in fahrenheit and it will give output in celsius.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-April-2022** 
<h3 align='center'>Web-page for converting temperature</h3>
Today, I have created a doctype which has fields- Celcius and Fahrenheit, and give it a web-view. Then i have to add the conversion formula in the files. For that I am exploring files.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-April-2022** 
<h3 align='center'>Web-page for converting temperature</h3>
In the given task, I have to set the conversion formula. There are 2 main files:- .py and .html. For doctype, the formula was working when i write it in .py file, it was converting successfully. For web-page, it wasn't working so i am finding solution for that.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date :11-April-2022** 
<h3 align='center'>Web-page for converting temperature</h3>
In the given task, I was exploring files and while reading documentation, I got a solution that for web-page we need to write the conversion formula in .js file. It started working in web-form as well. Next, I have to explored whether it will work it web-forms as well ?
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-April-2022** 
<h3 align='center'>Working as a Instructor role</h3>
Today, my task was to check the flow of instructor. I have to check whether a instructor is able to mark student attendance or not. Also, the INstructor is able to see only their programs in which they are teaching. Also, they can add contents like quix, articles and topics for students.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-April-2022** 
<h3 align='center'>Quiz format</h3>
Today I was searching that how can we hide the quiz result from the users and show them after some time. For that first I have checked all the quiz related doctypes and related parameters but in these there wasn't any control available for this. Then i checked all the doctypes files in ErpGuru folder and tried to understand the coding. In these files there isn't any condition available for the result they are showing the result based on a condition if checked question is right then show status pass, result, time taken etc else status fail and result, time taken etc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-April-2022** 
<h3 align='center'>LDAP users</h3>
Today, my task was to check how we can add the LDAP users and in the normal users list. Also are they able to login with their email ?
For that, i have created two users: a LDAP user and a normal user. Then login with their credentials and checked the difference between them.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-April-2022** 
<h3 align='center'>Presentation of Nankana Sahib Public School Project</h3>
Today we had a meeting with Satinder Sir and a teacher from Nankana Sahib Public School. In today's meetings we all presented what we have done till now. We showed them the whole workflow to add a student. For which first we need to add a student applicant and explained that there are two methods for this one is online by using web form and another is offline after the application is accepted we can enroll them in the programs by single-2 enrollment of every student and by using the program enrollment tool and we showed them the lms interface of student how student is going to access the programs and courses and quizzes.

After student section we showed them the whole working of instructor how instructor can add content like articles, videos and quizzes in lms, mark the attendance of students etc. After Instructor we presented the HR module how to generate payrolls, salary slips, attendance of employees etc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-April-2022** 
<h3 align='center'>Understanding the concept of workflow</h3>
Today I am understanding the concept of Workflow. With workflows we can rewrite how a particular process/workflow is approved in ErpGuru.Once a Workflow is created, you can take actions on it via Workflow Actions.

Workflow Actions is a single place to manage all the pending actions you can take on Workflows. Workflow Actions will send email notifications only if the 'Send Email Alert' checkbox is ticked in the Workflow that you've created.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-April-2022** 
<h3 align='center'>Presentation of all the topics</h3>
Today I gave presentation to all my mates in which i had covered all the topic that i have learnt during training like LMS, Mentor-Mentee, ErpGuru and all the basic topics of education domain like student applicant, programs, courses, instructor, workflow, notifications.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-April-2022** 
<h3 align='center'>Understanding the Workflow</h3>
Today I am understanding the concept of Workflow. With workflows we can rewrite how a particular process/workflow is approved in ErpGuru.Once a Workflow is created, you can take actions on it via Workflow Actions. Workflow Actions is a single place to manage all the pending actions you can take on Workflows. Workflow Actions will send email notifications only if the 'Send Email Alert' checkbox is ticked in the Workflow that you've created. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-April-2022** 
<h3 align='center'>Assignment Rule</h3>
Today I am exploring Assignment rule. I am exploring that how we can use assignment rule in helpdesk.For assign the issue automatically amongst the employees who work on support, an Assignment Rule can be used. We can define the Assignment rule Select the condition for the assignment. We can write simple Python expressions for automatic assignment in the Assign Rule, Close Rule and Unassign Rule. We will have access to all the properties of the document and can use operators like >, <, ==, etc and also multiple conditions like and and or. status == "Open" issue_type == "Technical" and priority=="High" and status == "Open".
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-April-2022** 
<h3 align='center'>Course Scheduling</h3>
Today's task was to schedule courses/ time-table for Instructors. It can be done in two methods:- Course schedule and course scheduling tool.
For creating course scheduling for 1 year then course scheduling is better. Also, we can prepare a csv file but for that we have to create entries manually for a year.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-April-2022** 
<h3 align='center'>Course Scheduling</h3>
Today, Sir provided us the Time-table of NSPS. So, I was doing course scheduling with Jaspreet. We used course scheduling tool for this task. A instructor will be able to see their scheduled courses in their profile and from course scheduling list.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-April-2022** 
<h3 align='center'>Exploring Buying in erp</h3>
Today, i was given with the task of exploring buying module. I am reading the documentation and watching youtube videos to understand its flow. Also working on HR module with kanchan. Understanding how HR will mark attendance of instructors and their salary.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-April-2022** 
<h3 align='center'>Buying Module</h3>
In buying, i got to understand some of its concepts that we need to have item list, suppliers list and warehouse list.
So, firstly we need to add the items, suppliers and warehouses. After that first step would be to create Material Request of the items that we need to buy.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-April-2022** 
<h3 align='center'>Buying Module</h3>
Today, I have created a order to buy items. The flow for buying module is: First, we need to create material request and a request for quotation will be created and will be sent to the suppliers. Then, suppliers will reply with supplier quotation. Then a purchase order will be created against that material request. After that a payment request and a purchase invoice will be created. In the end, a payment entry will be created.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-April-2022** 
<h3 align='center'>Presentation of souvenir</h3>
Today My mates gave presentation to all juniors. They showed us all the requirements, specification and overall workflow of the project and what is the required output. They explained all the problems they have faced till now and also explained it very well.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-April-2022** 
<h3 align='center'>Testing of Souvenir</h3>
Today, our task was to test the souvenir by filling the form. Also we have to check the validations they have applied.
So, i checked that by filling the form with 2 different ID's and it was working well.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-April-2022** 
<h3 align='center'>Hierarchy of Nankana Sahib Education Trust</h3>
Today we have discussed the hierarchy and structure of Nanakana sahib education trust, gndec, nsps. Basic Structure:- First we have a parent company Nankana sahib education trust and under these we have child companies Guru nanak dev engineering college, Nankana sahib public school (21 branches), Guru nanak dev polytechnic college, ITI. Accounts Structure:- First we have a parent company NSET and it has a bank account which will take care of all the accounts of child companies. Under the parent company we have a child company gndec which also has a fee account and a salary account all the tuition fee of students will directly go to the fee bank account , and all the amount of fee bank account will be transferred to the salary account and all the employees will get their salaries from the salary account. All the development fee will be directly transferred to the development account. For the development company will get the amount/fund from the development account. Roles in NSET:- In the nankana sahib education trust we have president , director, managerial staff and under the president we have sub roles for other users, secretary, and trustees. and under the managerial staff we have clerks and accountant. Only the received amounts and all benefits should be visible to the instructor. Only the accounts part should be visible to the director.Clerk is responsible for all the inventories stocks. Clerk2 will be responsible for the hostlers fee.And they should be able to see only their assigned company details. NSET:- In NSET company we have a director role which should have access to all the child companies. All the child companies GNDEC, NSPS have a principal.After that other staff is divided into two sections one is Non-teaching and other is teaching.Under the non-teaching staff we have clerks, accountants, assistants and other staff. Teaching section is further divided into Examination, student section(admissions etc), Establishment, Department. The examination staff will take care of examinations of companies, the student section will take care of the students admissions,fees etc.In the departments we have the role of HOD, section incharge, staff.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-May-2022** 
<h3 align='center'>Hackathon Day-1</h3>
Roles for Nankana Sahib Education trust :- Director:- Director will have all permissions like fees, salary, accounts , total gain etc but with read only access. Accountant:- will have permissions to see all the account information of trust, nsps, gndec. Accountant will have read, write access to create the fee and salaries of the employee and also can create the fee report and salary report. HR:- HR will have permission to create the users and make them employees, leave allocation, holiday list, salary of employee. Superintendent Roles and flow for Nankana Sahib Public School:- Principal:- Will have only read only access to all the education domain related information and HR related information. Accountants:- 1 For students fee and 1 for salaries of employees. Teaching Incharge:- Will do all the tasks of academic user like course scheduling etc. HR:- will create employees and instructors only for Nankana sahib Public School, leave allocation, salary of employees etc. We need to show all the reports like employees attendance report, salary report, leave report etc to the HR.. Instructors:- will have access to student attendance, quiz, videos, article, Diary, Student list etc. Students:- will have access of only LMS and on lms they will have access of programs, Courses, Quizzes, Videos, Articles, daily diary and attendance. Accountant:- will create the salaries of employees and fees of students, will generate the balance sheet. We need to generate all the reports and graphs for necessary information for each role. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-May-2022** 
<h3 align='center'>Hackathon Day 2</h3>
Today, We created Director user of NSET, Superintendent of NSET, Principal user of NSPS and HR user of NSPS on erp server and gave them all the required permissions. And same roles are created on gne11.GNE, whose credentials are shared in other mail. You can check that roles with given credentials. Also we learn about Salary Structure and Salary Component of employees. In meeting with Harpreet sir, we learn about PF, Taxes, Funds, Earnings and Deductions etc. We will explore it and implement on gne11.GNE. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-May-2022** 
<h3 align='center'>Notice Board App </h3>
First we created an app named Gndec_NoticeBoard and installed it on gne11.gndec.ac.in. Then we created a doctype named Gndec_NoticeBoard with field names title,content,attachment, signature etc. As we want that Clerk will create notice and HOD will approve, reject or reassign it. So we created two roles: HOD and Clerk and gave them required permissions for Notices. Then we created a workflow named Notice for Gndec_NoticeBoard. Here we define states like Draft, Approves, Pending etc. and Transition Rules like first Clerk will create a notice, after approved by clerk it will go to HOD then HOD will approve it or reassign it to Clerk. If HOD reassigns it then it will go to Clerk in Draft state, here clerk can edit it and resend it to HOD. If HOD wants to reject it, then first he needs to click on Pending then he can reject it, after rejecting by HOD it will go to the Clerk and the clerk can delete it. Then we test the workflow with different roles and it is working nicely. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-May-2022** 
<h3 align='center'>Creating Presentation in Revel.js</h3>
Created Presentation for the Whole Project To so that we can present our work to the trusties so with the team we created a presentation which contains all the infomation related to the erp Syatem which deals with the all kind of accounting, maintaing all students,staff and employees and pushed on github. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-May-2022** 
<h3 align='center'>Course Scheduling on gne11</h3>
In course scheduling, when we are scheduling courses to Instructors of full year using a course scheduling tool, it shows all the entries of the whole year in the course schedule list. These entries will be in thousands. Earlier when we were scheduling courses, we just scheduled two or three courses of whole year, and server was not responding.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-May-2022** 
<h3 align='center'>Scheduling Time-Table</h3>
Today I have tried scheduling Time-Table with some dummy Entries on https://gne11.gndec.ac.in/. If we want to see the Time-table of a particular instructor, then it is available in that instructor's profile and also we can see that from course scheduling list just by entering the instructor's name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-May-2022** 
<h3 align='center'>Scheduling Time-Table</h3>
We are creating it using course scheduling tool. In this, we need Room, Time, Day of lecture. And Time of lectures is not given in the TT of NSPS. You may set your own time in this case, set time of lectures between 8 am to 2 pm. And In NSPS, they mark attendance once in a day(In morning by incharge). And the use of doing course scheduling is to mark attendance in every lecture like in our college. So for school, there is no use of course scheduling. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-May-2022** 
<h3 align='center'>Arranging Time Table file</h3>
Today, After exploring, we thought there is no use of writing script. We think script is useful where we have to do the same things again and again. But in our case, we will have different time-table for different schools, so in script we will have to give input for each TT which is the same thing doing entries one by one. I think csv is more productive than script. So Today I have arranged Time Table csv file. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-May-2022** 
<h3 align='center'>Buying Module</h3>
Today I am done with the course scheduling. Now I am exploring the buying module as it was assigned to me the other day. Now, I am working on buying module for NSPS. Understanding how it will be helpful to keep records of the buying process of school. It will keep the records of the items that the school will bought and also it will have all the entries of payment.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-May-2022** 
<h3 align='center'>Buying Module</h3>
Today, we have to create a "Material Request" with the purpose "Purchase". Here we have to set the quantity of required items and warehouse for which they are required. We can create it manually or through re-order item in items i.e. If item quantity goes below the re-order level of item then material request will be created automatically.  
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-May-2022** 
<h3 align='center'>Buying Module</h3>
After creating Material Request, we can create "Request For Quotation" from Material Request. In this we can send the request to multiple suppliers for multiple items. An email will be sent to the supplier with the "Supplier Quotation" link. From this link, Suppliers can submit their quotations. Then these quotations will be visible to us in the "Supplier Quotation" list. It will be in draft state, we have to submit it. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-May-2022** 
<h3 align='center'>Buying Module</h3>
From "Supplier Quotation", we have to create "Purchase Order" (A Purchase Order is a binding contract with your Supplier that you promise to buy a set of items under given conditions). We can create "Purchase Receipt" after "Purchase Order". After creation of Purchase Receipt, Items will be added in our warehouses. We can check item's entry in Stock Ledger Report. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-May-2022** 
<h3 align='center'>Buying Module</h3>
We can create "Purchase Invoice" ( A Purchase Invoice is a bill you receive from your Suppliers against which you need to make the payment) after "Purchase Receipt". Also we can create it after "Purchase Order". In "Account Payable", we can check Invoice Amount, Outstanding Amount, Paid amount etc. After "Purchase Invoice" we can create "Payment". After paying, Invoice status will be changed to "Paid" and also now this invoice will not available in Account Payable Report.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-May-2022** 
<h3 align='center'>Stock and Asset module in ErpGuru</h3>
Stock, Buying and Accounting modules are inter linked with each other. It is so complex. We are trying to understand terms like General Ledger, Journal Entry, Purchase Receipt, Depreciation Ledger, Fixed Asset Register etc. Till now, we don't know which type of data is required.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-May-2022** 
<h3 align='center'>Stock module</h3>
Today, we have created Item Groups, Items, Warehouses, Suppliers etc. Item Group: Create parent and child item groups for different categories of items. Item: Create items from Stock > Item. If we want to maintain the stock for particular item then we have to enable "Maintain Stock" option while creating Item. After creating item with "Maintain Stock" field checked, the Stock Entry, Stock Ledger, Accounting Ledger will created automatically. Warehouse: If "Perpetual Inventory" option enabled in warehouse, then accounting entry is automatically done for every stock transaction. If "Perpetual Inventory" disabled, user will have to manage the account entries manually. Supplier: Create Supplier and add contact and email of supplier. We can make User of this Supplier also. With this, Supplier will not have access to desk, he can create Supplier Quotation etc from website only. We have checked this by creating entries on gne11.gndec.ac.in 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-May-2022** 
<h3 align='center'>Stock module</h3>
Today , We add item in the warehouse, we have to create stock. We have following two ways to create stock; If item is non serialized/non batched then we have to add entry in Stock Reconciliation. If item is serialized and Serial Number Series is defined for particular item, then also we can add entry here. If item is serialized/batched then add entry in Stock Entry with Entry Type "Material Receipt". Here we have to define serial number or batch number of items. After adding entry in Stock Reconciliation or Stock Entry, the item with specified quantity will be added in stock. We can check it in Stock Ledger Report. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-May-2022** 
<h3 align='center'>Asset module</h3>
Today I am done with the course scheduling. Now I am exploring the asset module as it was assigned to me the other day. Asset: In ErpGuru, We can maintain fixed asset records for Company assets like computers, furniture, cars, etc. and manage their depreciations, sale. It is any valuable item owned by a company. Asset category: Asset Category based on the type of assets. For example, all desktops and laptops can be part of an Asset Category named 'Electronic Equipments'. Types of assets: Assets can be an existing asset which has been bought earlier and it can be a newly purchased item. For new assets, we cannot create the asset record directly from the Asset form. We need to create a Purchase Receipt/Invoice for it. Before creating an asset we need to create an item with 'is fixed asset' and create a purchase receipt against that item. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-May-2022** 
<h3 align='center'>Asset module</h3>
Asset Reports: Asset Depreciation Ledger This report shows the Purchase Amount, Depreciated Amount and accumulated total depreciation for all the assets under the selected date range. It also shows the current value and current depreciation status of the Asset. Fixed Asset Register Fixed asset register provides a unified view of all the details regarding current status of an asset. A Fixed asset register tracks all the fixed assets that the you have created. This not only includes assets that are currently in your possession, but also tracks those assets that are disposed. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-May-2022** 
<h3 align='center'>HR module in ErpGuru</h3>
The Human Resources (HR) module covers the processes related to the HR department of a company. It maintains a complete employee database including contact information, salary details, attendance, performance evaluation, leaves, and appraisal records. The most important feature here is processing the payroll by using Payroll Entry to generate Salary Slips. Most countries have complex tax rules stating which expenses the company can make on behalf of its Employees. There are a set of rules for the company to deduct taxes and social security from employee payroll. ErpGuru accommodates all types of taxes and their calculation. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-May-2022** 
<h3 align='center'>HR module</h3>
In the HR domain we have Shift Management module.The Shift Management module in ErpGuru HR helps us efficiently manage shifts for our employees. Under the shift Management we have Shift type, Shift assignment, shift request .

Shift type:- In the shift type doctype we can create multiple shifts of our company like morning, evening etc. It contains Name of the shift, start time and end time of shift.

Shift Request :- Shift request is used by employees of a company to request for a particular shift.

Shift Assignment:- when the employee requests for a particular shift and when the shift request is approved and submitted then the system will automatically assign shifts to the employees. 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-May-2022** 
<h3 align='center'>View According to roles in the desk</h3>
Today Sir has assigned me and kanchan a new task. I am working on what should be visible to a particular role in the desk view. I will also compare the current system (Fee bank) of Nankana Sahib Public School with the ErpGuru.Today I am reading the files of ErpGuru and also exploring desk so that we can change the view / sidebar based on the roles.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-May-2022** 
<h3 align='center'>View According to roles in the desk</h3>
We were finding a way to generate/ update the view according to the role. We haven't found anything in the files of ErpGuru and on desk. Sowe have checked all the posts on the communutity related to this for the solution. In the community they are saying currently it is not possible to restrict the modules according to the roles. But we can do this for each user.Means if there is an instructor role and we want to restrict the other modules for instructor role except the education module.This is not possible to do this for role. If there are 10 instructor users then we can do this for each user.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 27-May-2022** 
<h3 align='center'>Arranging csv file for role-wise permission</h3>
Today we have created the csv file for every instructor so that we can block all the other modules in the instructor view except education module. We have also implemented it for a single instructor for testing purpose. Only the ducation domain is visible to the instructor.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-May-2022** 
<h3 align='center'>Supplier for Stock</h3>
Suppliers are companies or individuals who provide you with products or services.

    Go to the Supplier list and click on New.
    Enter a name for the supplier.
    Select the supplier group.
    Save.
    Create New Address and New Contact.
    In New Contact, if the supplier is already a user of erp then select the user id otherwise enter email id in contact details.
    Then click on “Invite as User” then email will be sent to this email to set up the password.
    Supplier will become a user now.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-May-2022**
<h3 align='center'>Stock Reports</h3>
Quick Stock Balance

    Quick Stock Balance is a tool that can be used to quickly retrieve the current stock balance (quantity) and value of an item, in the specified warehouse, on the specified date.
    To access, go to Stock > Tool > Quick Stock Balance.
    Now select warehouse and item. Now we can see the current item quantity in this warehouse.
    We can also view the Stock Balance report by clicking on 'Stock Balance Report' . It will redirect to the report with the Item and Warehouse filters populated.

Stock Ledger Report

A Stock Ledger Report is a detailed record that keeps track of stock movements for a company. It reflects the quantity and value of stock issued, received, or transferred along with the stock item and its warehouse details. Following are Stock Ledger Report Attributes:

    Incoming Rate: It reflects the actual value of the stock at which it was brought under your inventory. It reflects the same value as entered in the Rate field of the document.
    Balance Value: It represents the total value of the remainder stock in the inventory. It is the product of Valuation Rate and Balance Quantity of a stock item.
    Valuation Rate: It is calculated based upon the valuation method selected.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 31-May-2022** 
<h3 align='center'>Desk Theme</h3>
    Sir assigned us (Me and Jaspreet) the task to beautify the desk view with bootstrap. So we are exploring about it.
    We found theme of desk. We install a theme from this url: https://github.com/hashirluv/r
    After installing this theme, colour of heading, navigation bar etc got changed.
    Then we tried some other themes also. We tried White Theme, Blue Theme etc.
    Then we understand the code and css files to change the view of desk. We can change only background colours, text colours, hover text colour etc with some changes in the css files.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-June-2022** 
<h3 align='center'>Dashboard for ERPGURU</h3>
    Now we (I and Jaspreet) have to create a new dashboard page according to the rquirement specified by sir.
    There should be links of Student, Program, Fee, Attendance etc. After clicking, it would ask for login.
    So we explored about this and create a new webpage. (Go to Website > Webpage then create new webpage)
    Enter Title, Route etc. Select HTML in Content Type.
    <br>

















































































































































































