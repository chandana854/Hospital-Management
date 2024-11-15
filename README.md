# Hospital-Management
Hospital Management System using HTML,CSS,JS,MySQL, Php and Bootstrap

## **Prerequisites**
1.Install XAMPP web server
2.Any Editor (Preferably VS Code or Sublime Text)
3.Any web browser with latest version

## **Languages and Technologies used**
1.HTML5/CSS3
2.JavaScript (to create dynamically updating content)
3.Bootstrap (An HTML, CSS, and JS library)
4.XAMPP (A web server by Apache Friends)
5.MySQL (An RDBMS that uses SQL)
6.PHP

## **Starting Apache And MySQL in XAMPP:**
The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.
![Starting Xampp](https://github.com/chandana854/Hospital-Management/blob/main/Screenshot%202024-11-15%20153141.png)

## **Getting into project**
Hospital Management System in php and mysql. This system has a ‘Home’ page from where the patient, doctor & administrator can login into their accounts by toggling the tabs accordingly. Fig 1.1 shows the ‘Home’ page of our project.
![Dashboard](https://github.com/chandana854/Hospital-Management/blob/main/prj.png)

'About Us' page (Fig 1.2) allows us to get some more information about the quality and the services of the hospital.
![about us](https://github.com/chandana854/Hospital-Management/blob/main/prj2.png)

‘Contact’ page allows users to provide feedback or queries about the services of the hospital. Fig 1.3 shows the ‘Contact’ page.
![contact](https://github.com/chandana854/Hospital-Management/blob/main/prj3.png)

## **The ‘Home’ page consists of 3 modules:**
1.Patient Module<br>
2.Doctor Module<br>

## **Patient Module**
This module allows patients to create their account, book an appointment to see a doctor and see their appointment history. The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.
![Patient](https://github.com/chandana854/Hospital-Management/blob/main/prj4.png)
Once the patient has created his/her own account after clicking the ‘Register’ button, then he will be redirected to his/her Dashboard(Fig 1.5).
![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj5.png)
The Dashboard page allows patients to perform two operations:
## **1. Book his/her appointment:**
  Here, the patients can able to book their appointments to see a doctor. The appointment form(Fig 1.6) requires patients to select the doctor that they want to see, Date and Time that they want to meet with the doctor. The consultancy fee will be shown accordingly to the patient as it was already determined by the doctor.
![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj6.png)
  After clicking on the ‘Create new entry’ button, the patient will receive an alert that acknowledges the successful appointment of the patient.(See Fig 1.7)
![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj7.png)
## **2. View patients’ Appointment History:**
 Here, the patient can see their appointment history which contains Doctor Name, Consultancy Fee, Appointment Date and Time.(See Fig 1.8).
 ![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj8.png)
Once the patient has logged out of his account, if he wants to go into his account again, he can login his account, instead of register his account again. Fig 1.9 shows the login page. Clicking on ‘Login’ button will redirect the patient to his dashboard page which we have seen earlier (Fig 1.5)
 ![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj9.png)
 This is how the patient module works. On the whole, this module allows patients to register their account or login their account(if he/she has one), book an appointment and view his/her appointment history.
## **Doctor Module:**
The doctors can login into their account which can be done by toggling the tab from ‘Patient’ to ‘Doctor’. Fig 1.10 shows the login form for a doctor. Registration of a doctor account can be done only by admin. We will discuss more about this in Admin Module.
 ![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj10.png)
 Once the doctor clicking the ‘Login’ button, they will be redirected to their own dashboard which is shown in Fig 1.11
  ![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj11.png)
  In this page, doctor can able to see their appointments which has been booked by the patients. Fig 1.12 shows the appointment of the doctor ‘Ganesh’ which has been booked by the patient ‘Kenny Sebastian’ (Fig 1.6). This means that the doctor ‘Ganesh’ will have an appointment with the patient ‘Kenny Sebastian’ on 10-10-2019 10AM.
  ![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj12.png)
In real-time, the doctors will have thousands of appointments. It will be easier for a doctor to search for appointment in the case of more appointments. To make it easier, I have a ‘Search’ box in the navigation bar (See Fig 1.12) which allows doctors to search for a patient by their contact number. Once everything is done, the doctor can logout of their account. Thus, in general, a doctor can login into his/her account, view their appointments and search for a patient. This is all about Doctor Module.
## **1. Cancel Appointments**
Patients and doctors can able to delete their appointments.
![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj13.png)
If the patient deletes the last record (for doctor Ganesh), then a label "deleted by you" will be displayed in the column 'Current Status' and the action will change to cancel state.
![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj14.png)
Now if we login to the doctor Ganesh's account and view his appointment details, then it will look like this:
![appointment](https://github.com/chandana854/Hospital-Management/blob/main/prj15.png)
