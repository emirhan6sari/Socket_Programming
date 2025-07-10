# Socket_Programming
Hospital appointment application
1. The program will include one server and more than one client. First, the server 
(part) will be started, the server part will listen to TCP and UDP messages that may come from all sockets.

2. Then each time the client side is run, it will establish a new connection to the server.

3. There will be two different types of clients. The first 2 clients connected are “Doktor1” and “Doktor2” in the order 
it will be named. Then the connected clients are “Hasta1”, “Hasta2” and “Hasta3” respectively 
it should be named in the form. If there is no doctor in the system, those who are sick will not be able to connect to the system. 
When a new user connects, the server must display the username and connection method of the connected user 
on the screen of the doctor or doctors and the server that are in the system. 
The “Welcome” message should appear on the connected client screen (i.e. the patient's screen).

4. Although each doctor has patients with predefined appointments, without an appointment 
there are also patients. Any doctor can perform the patient call function (the corresponding doctor 
when you type "Patient Admission" on the screen, the corresponding function should be crossed out) when you call both the server and the patient 
this process should be displayed as “HastaX -> DoktorY” on the screen. The concerned patient accepts the doctor 
when it does, a function should be called, and with this function, both the patient and the doctor are on the screen 
The information should be shown as ”HastaX has accepted the doctor's appointment". The patient's appointment is 10 
If the patient does not accept it within sn, the next patient should be automatically called by the doctor.

5. When any doctor's patients with an appointment are finished, the call-in function automatically 
or in case of manual call, the next patient of the doctor with the largest number of remaining patients is the next 
it should match with the calling doctor. As the patients arrive, respectively to Doctor1 and Doktro2 
it will be transferable.

6. When any doctor calls a new patient, the doctor's old patient's screen will show the message “History 
and the patient will be disconnected. Additionally, the server screen should show the message “PatientX 
has left.”

7. When all patients in the system are finished, all doctors should be informed and then all connections 
should be cut off. If there is no patient in the system, the doctor's screen should display the message “There is no patient waiting.” 
