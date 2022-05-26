# Batch--19-VIRTUAL--NETBANKING--SYSTEM--USING--ADMINISTRATIVE--MODULE

# Project Title

VIRTUAL NETBANKING SYSTEM USING ADMINISTRATIVE MODULE


# About the Project

A computer-based Banking system is designed to handle all the primary information required to calculate monthly statements of customer account which include monthly
statement of any month. Separate database is maintained to handle all the detailsrequired for the correct statement calculation and generation. This project intends to
introduce more user friendliness in the various activities such as updating records,maintenance, and searching. The searching of record has been made quite simple as
all the details of the customer can be obtained by simply keying in the identification oraccount number of that customer. Similarly, record maintenance and updating can also be accomplished by using the account number with all the details being automaticallygenerated. These details are also being promptly automatically updated in the master file thus keeping the record absolutely up-to- date. 


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Prerequisites

Hardware Requirements

```
Hardware Requirements (Minimum)
• Pentium IV 233MHz.
• 128 MB RAM.
• 250 MB free hard disk space.

```
Software Requirements

Application Requirements
• Microsoft Windows 2000
• PHP (Apache Tomcat 5.5)
Database Server
• My SQL 5.0.

Client and Browser 
• Microsoft Internet Explorer (6+).
• Mozilla Firefox.


### Installation

WEBSITE
•	In this project we are going to create a secure virtual bank using django.
• Install Python 3.7 Or Higher
• Install Django version 2.2.0
• Open the project directory 
• Install all dependencies cmd using -python -m pip install –-user -r requirements.txt
• Finally run cmd - python manage.py runserver
• Execute the project by running Xampp to connect our webpage to sql database
•	Open the web page obtained by executing our project
•	Then the register user page would open to register as a new user if you are an existing user we can use login function.
•	After login we can deposit and withdraw with the terms and conditions.
•	To Use the project in a admin view we need to add "/admin" at the end of the url.
•	The admins login id is :admin@admin.com and the password is :admin123
•	The Admin after login can control and modify all and various aspects of the bank
•	Only certain files are supported like (jpeg, jpg, pdf, txt, gif).
•	Hence the Project is executed successfully.
• We can now disconnect from xampp.
•	We can stop the website from running by terminating CMD after the completion of the process.
• Any changes in the project will be recorded in cmd window

## Deployment

•	Download XAMPP , APACHE TOMCAT .
•	Download and Install DJANGO and celery usig pip in CMD
•	Install all dependencies cmd using -python -m pip install –-user -r requirements.txt
• Finally run cmd and execute the program using - python manage.py runserver
•	The web portal address (http://127.0.0.1:8000/) will be displayed in cmd.


## Functionality of Modules 

###For Bonafide and LOR Request Website,

#### Admin
  - Login
  - Accept/Decline the account registration made by the student
  - View the list of students and staffs registered in the portal

#### HOD
  - Login
  - Accept/Decline the request for Bonafide raised by the student
  - Edit the body contents of the LOR and send it to student
  - View the list of students and staffs registered in the portal

#### Staff
  - Register/ Login
  - Accept/Decline the request for LOR Raised by the student
  - Edit the body contents of the LOR and send it to student

#### Student
  - Register/ Login
  - View the list of staffs registered in the portal
  - Request for Bonafide/LOR
  - Download the Bonafide/LOR obtained from the faculty

 

## End to end tests breakdown

Student/Staff Registration

```
Click on Register in Homepage
Choose if you want to login as a Student/Staff
Fill in the required details
Click on Register button

Note: Login can be done ony after admin's approval.
```
Registration Authentication

```
Login as Admin by filling in the credetials
To authenticate staff login, Click on ''View Staff'' and click Accept/Decline
To authenticate student login, Click on ''View Student'' and click Accept/Decline
```

To request for Bonafide

```
Login into the portal by giving the credentials
click on the button named Bonafide Certificate
Select the reason for applying for bonafide
Click on Submit
```
To request for LOR

```
Login into the portal by giving the credentials
click on the button named LOR Certificate
Fill in the body of the letter
Append your signature in Digital format
Click on Submit
```
Accept/Decline Bonafide Request

```
Login as HOD by giving the credentials
Click on "Inbox"
Click Accept/Decline to Approve/Decline the request for Bonafide
Append the Date of issuing the Bonafide and Digital Signature
Click "Save"
```
Accept/Decline LOR Request

```
Login as a Staff by giving the credentials
Click on "Inbox"
Click Accept/Decline to Approve/Decline the request for LOR
Append the Body Content if any changes are supposed to be made and attach the Digital Signature
Click "Save"
```


## Built With

* [Java]<https://docs.oracle.com/en/java/> - Programming Language
* [Collections]<https://docs.oracle.com/javase/8/docs/technotes/guides/collections/overview.html> - The core framework used
* [JSP, Servlet]<https://docs.oracle.com/javaee/6/tutorial/doc/bnafd.html> - J2EE
* [HTML 5, CSS 3]<https://developer.mozilla.org/en-US/docs/Web/HTML> <https://developer.mozilla.org/en-US/docs/Web/CSS> - For Web Designing
* [JQuery]<https://api.jquery.com/>) - Used to generate Animation Effect
* [JavaScript]<https://developer.mozilla.org/en-US/docs/Web/JavaScript> - For Scripting
* [Bootstrap 3]<https://getbootstrap.com/docs/3.3/> - Used for FrontEnd Framework



## References

<https://ieeexplore.ieee.org/document/573971>
<https://ieeexplore.ieee.org/document/5616659>
<https://docs.oracle.com/javaee/7/api/javax/mail/package-summary.html>
<https://docs.oracle.com/javaee/7/api/javax/servlet/package-summary.html>


## Contact

* H. Pooja 
  - Register Number: 211417104184

* Priyadarshini Venkatesan 
  - Register Number: 211417104201

* S.Sherline Calista 
  - Register Number: 211417104256
