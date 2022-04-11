# Project name: Health Care Management

## Description
####	Our project is about health care management in which the patient can take appointment with doctor. The Appointment Can be physical or online (video call). Patient can ask for the prescription
####	Patient Can order medicine.
####	Patient can book lab test
####	Patient can Search for nearby hospitals and laboratory
####	Doctor Can see scheduled meeting
####	Doctor Can answer to the patient Question
####	Doctor can see the lab reports
####	pharmacists can accept order from patient and delivered the medicine to the given address
####	Lab Technician can accept lab order and send lab report
####	Admin can manage the system and database

## Objects in our Project
#### Patient
#### Doctor
#### Pharmacist
#### Lab Assistant
#### Admin
#### Medicine
#### Laboratory
#### Pharmacy
#### Hospital
#### Report
#### Order
#### Lab Test
#### Payment
#### Stored data
#### Prescription
#### Appointment
#### Book test
#### Mode
#### Meeting
#### Question
#### Search
#### Address
#### Delivery
## Use Cases In our Project
#### Login
#### Register
#### See Patient Record
#### Search Doctor via Speciality
#### Book Appoinment
#### Order Medicine
#### Fine nearby Hospital
#### Book lab test
#### View lab report
#### View Doctors Detail
#### Check patient
#### Take medicine Order
#### Generate Lab Report
#### Manage Data
## Actors In Our Project
#### Patient
#### Doctor
#### Pharmasists
#### Labortary
#### Admin
## USECASE DAIGRAM
## ![usecase](https://user-images.githubusercontent.com/102031024/161131991-30640137-b3d2-4017-ad4a-3e2451435986.png)
## DOMAIN MODEL DAIGRAM
![domain](https://user-images.githubusercontent.com/102031024/161131739-d8d6bf34-1e06-41ad-828e-ff2a684dcac1.jpg)
## Expanded Use Case
### Name	Check Patient
### Actor	Doctor
### Type	primary
### Stakeholder and Interest’s 
#### -	Patient:
##### Wants to checked by well experienced Doctor’s.
#### -	Laboratory:
##### Will perform Patient test refer by the Doctor.
#### -	Pharmacy:
##### Will Deliver Medicine to the Patient that’s prescribed by the doctor
#### -	Payment Authorization:
##### Want to receive digital authorization requests in the correct format and protocol
#### -Government Tax Agencies:
##### Want to collect tax, it may be multiple agencies such as, national, state, country
#### -Company:
##### Wants accurately record of the patient Doctor laboratories and Pharmacies,Satisfies Patient, Want to ensure that payment authorization recorded and want some fault tolerance in the system.
### Main success Scenario	
##### 1.	Login to system
##### 2.	System will prompt the user
##### 3.	After verifying the user system will prompt the home page
##### 4.	Doctor will open Check patient list
##### 5.	After watching the list Doctor will start meeting accordingly to Scheduled time.
### Alternate Flow	
#### a*: Forget Password
##### 1.	If the user entered 3 times incorrect password.
##### 2.	System will pop up forget password dialogue
##### 3.	System will ask for option of verification i-e verify through Email or phone no.
##### 4.	User will select the option
##### 5.	System will send the verification code
##### 6.	User will enter the verification code
##### 7.	System will verify the verification code
##### 8.	System will ask for enter new password
##### 9.	after entering the new password system will prompt the user to the home page
#### b*: No internet Connection
##### 1.	if internet connection fails system should wait up to 10 sec to reconnect
##### 2.	System will ask the user to reconnect
##### 3.	User will check the internet connection and try again
##### 4.	After successful Connection the meeting is started from where it is stopped
#### C*: Failure in the system
##### 1.	System will ask to restart the application
##### 2.	If still not working
##### 3.	System will ask the user to update the application
### Pre-Condition	
##### •	Doctor must Register to the system
##### •	Doctor must be login to the system
##### •	There should be a scheduled meeting
### Post-Condition	
##### •	Give Feedback to the patient
##### •	Prescribe medicine to the patient
##### •	Check another patient if any
##### •	Logout from the system
### Special Requirement’s	
##### •	System should response within second
##### •	System shall support 200 users at a time
##### •	Easy to use
##### •	System should secure the data of all user’s
##### •	Data should be saved for one year
### Technology and data variations list	
##### •	User can login through Face lock
##### •	Use can login though finger print
