# Hosital-DataBase-Management-System

Hospitals interact with a lot of people in a day and there are various activities involved in day to day operations of hospitals, for example booking of appointments, managing doctor schedules, managing patient diagnoses, managing medical histories of patients, etc. The aim of this project is to show how data related to these tasks can be made easier to manage using databases.

<b>Tech Used:</b>
<pre>
Frontend : React.js
Backend : Node.js, Express
Database : MySQL
</pre>

<b>ER Diagram :</b>
![ER diagram](https://user-images.githubusercontent.com/74065677/205315615-e223b1a2-072f-4bef-a5b9-ff26105cf546.png)

<b>Relational Schemas :</b>
![schema](https://user-images.githubusercontent.com/74065677/205315654-3fb3b926-0214-4e1e-a90b-a07d97a4c38f.png)

<b>Patient Side Features :</b>

    1. There is a seperate interface for patients. Patients have a seperate login.
    
    2. Patients can book appointments.
    
    3. Patients can give previous medical history.
    
    4. Patients can view/update/cancel already booked appointments if necessary.
    
    5. Cancelled appointments create free slots for other patients.
    
    6. The system avoids clash of appointments with other patients. Each patient is therefore ensured his/her slot.
    
    7. Patients are able to see complete diagnosis, prescriptions and medical history.
    
    8. Patient medical history is only available to the doctor with whom the appointment is booked to ensure privacy.

<b>Doctor Side Features :</b>

    1. There is a seperate interface for doctors. Doctors have a seperate login.

    2. The system takes into consideration doctor schedules and does not allow appointments when a doctor is already busy or has a break.
    
    3. Doctors are able to access patient history and profile, and add to patient history.
    
    4. Doctors are able to give diagnosis and prescriptions.
    
    5. Doctors are able to modify diagnosis and prescriptions.

<b>How to run:</b>

    1. Run "npm install" in frontend and backend directories.
    
    2. Run "npm start" first in the backend and then in the frontend directory.
    
    3. Access localhost:3000 from the browser.

<b>Screenshots :</b>
![PatientRegistration](https://user-images.githubusercontent.com/74065677/205315827-70f7e15a-e292-4f31-8d31-a2440a96fab3.png)
![PatientViewingAppt](https://user-images.githubusercontent.com/74065677/205315835-9fdabd48-eaae-49c6-9281-b0c9f2370641.png)
![SchedulingAppt](https://user-images.githubusercontent.com/74065677/205315842-48dfb7d4-10eb-4157-8237-ff974154c605.png)
![ViewingPatientHistory](https://user-images.githubusercontent.com/74065677/205315844-f898a688-dbb2-4ca8-bf6e-8757969bb2d4.png)
![Diagnosis](https://user-images.githubusercontent.com/74065677/205315846-b1ff7f4f-8a8d-4455-9135-8428a56a5ff2.png)
![DoctorHome](https://user-images.githubusercontent.com/74065677/205315851-e977f2a5-760a-466c-bfaa-24fee83b8174.png)
![DoctorRegistration](https://user-images.githubusercontent.com/74065677/205315858-90833815-8d41-472d-845e-5a64b94b175b.png)
![DoctorViewingAppt](https://user-images.githubusercontent.com/74065677/205315863-779bdc89-6c5a-4556-ab5a-fd5d05e96b5e.png)
![LogInScreen](https://user-images.githubusercontent.com/74065677/205315869-6831da4e-2bfa-4689-a409-f9dbeee72073.png)
![PasswordReset](https://user-images.githubusercontent.com/74065677/205315873-efccee96-18e8-43f9-ae50-ff7e7f0f6b52.png)
![PatientHistory](https://user-images.githubusercontent.com/74065677/205315875-d09843d1-6be9-47a6-acf2-8350ca3fa837.png)
![PatientHome](https://user-images.githubusercontent.com/74065677/205315877-bd6f3dd9-2a1e-4d41-b7b6-acf099b47076.png)
