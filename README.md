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
## USECASE DIAGRAM
## ![usecase](https://user-images.githubusercontent.com/102031024/161131991-30640137-b3d2-4017-ad4a-3e2451435986.png)
## DOMAIN MODEL DIAGRAM
![domain](https://user-images.githubusercontent.com/102031024/161131739-d8d6bf34-1e06-41ad-828e-ff2a684dcac1.jpg)
## ClASS DIAGRAM
![ClassDiagram1](https://user-images.githubusercontent.com/102031894/165048250-66ba52fd-d410-48cc-b3cd-725bfd42a1fe.png)

## Actor Goal's
### Patient	
##### •	Login to the System
##### •	Book Appointment with doctor
##### •	Book Lab Test
##### •	Order Medicine
##### •	Pay bill’s
##### •	View Lab report
##### •	Receive order
##### •	Search nearby hospital
##### •	Ask questions from doctor
##### •	Ask for prescription
##### •	Logout from the system
### Doctor	
##### •	Login to the System
##### •	View patient lab report
##### •	Check patient’s
##### •	Upload prescription
##### •	Answer the Patient Question
##### •	Get salary
##### •	Show Availability
##### •	Can ask patient for lab test
##### •	Logout from system
### Lab Assistant	
##### •	Login to the system
##### •	Accept lab test request
##### •	Generate lab report
##### •	Show availability
##### •	Logout from the system
### Pharmacists	
##### •	Login to the system
##### •	Accept medicine order
##### •	Deliver medicine
##### •	Generate bill
##### •	Logout from the system
### Admin	
##### •	Manage System
##### •	Manage system security
##### •	Update system
##### •	Update database
##### •	Manage records

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

# BRIEF USECASE

## Use Case	Create Account
#### Actor
###### Doctor, Patient, Pharmacists, Lab Assistant
#### Type	
###### Essential
#### Description
###### User Click on Create Account Button
###### System will show the Registration Form and ask the user to fill it accordingly
###### User will fill the from and submit it 
###### System will send a verification email to user and the user will registered to the system 

## Use Case	Login
#### Actor	
###### Doctor, Patient, Pharmacists, Lab Assistant
#### Type	
###### Primary
#### Description
###### System Request the Actor to enter the user name and password
###### User enter the user name and password
###### The system validate the user name and password, and show home page

## Use Case	Check Patient Record
#### Actor
###### Doctor
#### Type	
###### Primary
#### Description
###### Use will enter username and password
###### System will validate the user and show homepage
###### User will select the check patient record
###### System will show list of patient
###### User will select the patient for which user want to check his medical report
###### System will show his all medical report

## Use Case	Book Lab Test
#### Actor	
###### Patient
#### Type	
###### Primary
#### Description	
###### User will enter username and password
###### System will verify the username and password. After validation system will show home page
###### User will click on the book lab test button
###### System will show list of laboratory
###### User will select the laboratory
###### System will show further detail of that laboratory
###### User will select the test type.
###### System will ask for payment method
###### User will select the payment method 
###### System will send the conformation email along with unique id to user





## Use Case	View Doctor Profile
### Actor
###### Patient
### Type
###### Primary
#### Description	
###### User will enter username and password
###### System will verify the username and password. After validation system will show home page
###### User will click on Search Doctor Button
###### System will show list of doctor and search option
###### User will search for any doctor
###### System will show doctor profile

## Use Case	Take Medicine Order
### Actor
###### Pharmacists
### Type	
###### Primary
### Description	
###### User will enter username and password
###### System will verify the username and password. After validation system will show home page
###### User will click on view medicine order Button
###### System will show the different order from different patient
###### User will take order and dispatch it to the given address

## Use Case	View Lab Report
#### Actor	
###### Patient, Doctor
#### Type	
###### Primary
#### Description	
###### User will enter username and password
###### System will verify the username and password. After validation system will show home page
###### User will click on the view lab report button
###### System will show list of laboratories
###### User will select the laboratory in which user booked the test
###### System will ask for unique id
###### User will enter unique id
###### System will validate the id and show report
###### Also, system will prompt for view and download option



## Use Case	Generate lab report
#### Actor	
###### Lab Assistant
#### Type	
###### Primary
### Description	
###### User will enter username and password
###### System will verify the username and password. After validation system will show home page
###### User will click on the view book lab report button
###### System will show list of booked lab test
###### User will select the patient with their  unique key
###### User will upload the lab report
###### System will ask for permission
###### User will verify it
###### System will upload it

## Use Case	Search Doctor
### Actor	Patient
### Type	Primary
### Description	
##### User will enter username and password
##### System will verify the username and password. After validation system will show home page
##### User will click on Search Doctor Button
##### System will show list of doctor and search option
##### User will search for any doctor
##### System will show doctor 

## Use Case	Order Medicine
### Actor	Patient
### Type	Primary
#### Description
##### User will enter username and password
##### System will verify the username and password. After validation system will show home page
##### User will click the Order Medicine button
##### System will show list of medicine with discounts
##### User will select the medicine and put it to cart
##### After completion the system will ask for payment
##### User will select the payment method and pay

## Use Case	Search Hospital
### Actor	Patient
### Type	Primary
### Description	
##### User will enter username and password
##### System will verify the username and password. After validation system will show home page
##### User will click on Search Hospital Button
##### System will show list of Hospital’s and search option
##### User will search for any Hospital
##### System will show Hospital profile

## Use case	Manage Data
#### Actor	
###### Admin
#### Type	
###### Primary
#### Description
###### User will enter username and password
###### System will verify the username and password. After validation system will show home page
###### Now user can accept the request of new doctor patient lab assistant pharmacists
###### User can update the Record
###### User can reset password for other user
