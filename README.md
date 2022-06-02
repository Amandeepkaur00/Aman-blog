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

<p align="justify">Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ERPNext, is pretty generic and can be used to build database driven apps.</p>
#### Why Frappe?
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
<h3 align='center'>Introduction to Docker, Virtual Machine and ERPNext</h3>

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

**What is ERPNext?**
<p align="justify">ERPNext is a full-featured business management solution that helps SMEs to record all their business transactions in a single system. With ERPNext, SMEs can make informed, fact-based, timely decisions to remain ahead in the competition. It serves as the backbone of a business adding strength, transparency, and control to your growing enterprise.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Feb-2022** 
<h3 align='center'>Installing ERPNext in Frappe-bench</h3>

- If Frappe-bench installed in system follow second method otherwise you will get error.
- Installion done with two manner 
- By Adduser in linux
- And create Erpnext app and site in frappe-bench Diretory.
- For installation steps [Click here](https://github.com/D-codE-Hub/ERPNext-installation-Guide/blob/main/README.md). 
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
<h3 align='center'>Introduction to Education module in Erpnext</h3>
<p align="justify">The Education domain in ERPNext is designed to meet requirements of any organization which imparts knowledge and believe in doing so in an organized fashion. It has already been used at schools, colleges and even in private firms.
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
- Trying to install Erpnext on server.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Feb-2022** 
<h3 align='center'>Mysql Administration, Converting pdf to md file</h3>
- Today I created a new doctype in erpnext with different options
- then learned about the administration concept of database
- Converting pdf file to md and applying changes using markdown.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Feb-2022** 
<h3 align='center'>Working on ERPNEXT</h3>
- Today i started working on new platform erpnext it is open source, and low code or no platform.Today i am reading the documentation of erpnext to  understand the education domain. Today i have created some programs and courses now i am trying to understand how to enroll students in programs and courses.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Feb-2022** 
<h3 align='center'>How to use ssh</h3>
- Login to Server, Try to help other member to install ldap on server.
- Apply different permission related queries on database for different user.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Feb-2022** 
<h3 align='center'>Learning about how to import data in erpnext from csv file</h3>
- Try to import data in erpnext app throught csv file.
- Apply pagination in erpnext webpage.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Feb-2022** 
<h3 align='center'>Learning different modules of education domain</h3>
- I am learning about the modules of education domain. It has so many different modules like attendance module, assessment module, course scheduling, HR, settings, admission etc.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Feb-2022** 
<h3 align='center'>Creating Web page in ErpNext</h3>
- Creating Static Webpage on Erpnext.
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
<h3 align='center'>Learning Different modules of Erpnext</h3>
- Understand the structure of erpnext app.
- Understand the javascript code and python code of erpnext app.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Mar-2022**
<h3 align='center'>Meeting app</h3>
- Today vishal and pawan gave us a presentation of meeting app. They showed us how to create custom apps in erp and how to install it onto the site. And they also showed us the code of the app and structure and files of the meeting app. Working on instructure section of education module of erpnext.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Mar-2022** 
<h3 align='center'>Notice Board app</h3>
- Today we all created a notice board app in erpneext within 30 minutes. It was a wonderful experience as we can created such apps withiin a short time period.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-Mar-2022**
<h3 align='center'>Basic setup for Nankana Sahib Public school</h3>
- Today I am done with the basic setup of Nankana Sahib Public School. I have created three programs Class 1, Class 2, Class 3 and three instructors for each class , four courses for each class, and 2-2 topics per courses, three room and other basic requirements. I have imported data of 8 students using the data import feature in erpnext and also tried to update the existing record which is working fine without any issue.

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
<h3 align='center'>Attendance module in Erpnext</h3>
- Today, I studied about how to mark attendance in erpnext. There are two methods to mark attendance:- using Student attendance and Student Attendance tool.
For marking attendance of single student we can use student attendance and for bulk entries, we can use student attendance tool.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Mar-2022** 
<h3 align='center'>Leave in erpnext</h3>
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
<h3 align='center'>Installing new Erpnext on server</h3>
First we install frappe framework then install erpnext with education domain.

    After this we are collecting students and teachers data from Nankana Sahib Public School. - Arranging data according to doctype in erpnext.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Mar-2022** 
<h3 align='center'>Helping others in their tasks</h3>
Today i Was helping others in their tasks. I helped Jaspreet in importing instructors as there were some issue we both were trying to resolve it and after investing some time in it it got resolved. After this I helped Sehjal in importing And adding the students in erpnext. And was trying to understand their tasks.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->




























