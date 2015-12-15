# MedicalApp
This is an app that allows a doctor to create a user name and password. They are then asked to enter their user name and password, then
continue by inputing information about their patients into a database.

The app is run in the main. It calls on all the classes and their methods. At the end of the app, main asks whether or not the user wants
to lookup user info or terminate the app.

In the Doctor class, the user inputs their name, creates a username and passoword

In the User class, the user enters the user name and password that they created in the doctor class, if the information is correct the app will continue to the next method. However, if the information is wrong, the user class will continue to ask for the correct information or input that matches what the user entered in the doctor class

In the patient class, the user enters the names of all their patients. It is put into an arrayList in order for the User to add as many patients as they want. When they are finished adding patients, they enter "q" to stop the program from asking for their input. The class also has an method that looks up a patients info called patientInfo.

In the history class, the user is asked to enter the health history for all of their patients and then the history is put ito an array list. 

In the appointment class, the user is asked to enter their patient's next appointment date and it is then put into an array list.

In the medicine class, the user is asked to enter which medicine each of their patients are taking, and then the various medicines are stored inside an array list.

In the menu class, the user is given a list of options. They can exit the program, they can retrieve their user name, they can retrieve their password, or they can add a new patient with all new information to their table. Also, the menu class inherits ffrom the patients class and uses the method patientInfo from the patients class(polymorphism). 


