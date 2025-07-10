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


Hastane randevu uygulaması
1. Program bir sunucu ve birden fazla istemci içerecektir. İlk olarak sunucu 
(parçası) başlatılacak, sunucu kısmı tüm soketlerden gelebilecek TCP ve UDP mesajlarını dinleyecektir.

2. Sonra istemci tarafı her çalıştırıldığında sunucuya yeni bir bağlantı kuracak.

3. İki farklı tipte istemci olacak. İlk bağlanan 2 istemci sırasıyla “Doktor1” ve “Doktor2” olarak adlandırılacak. Daha sonra bağlı istemciler sırasıyla “Hasta1”, “Hasta2” ve “Hasta3” olarak adlandırılmalıdır. Eğer sistemde doktor yoksa, hasta olanlar sisteme bağlanamazlar. 
Yeni bir kullanıcı bağlandığında, sunucu, sisteme bağlı olan doktor veya doktorların ekranında, bağlanan kullanıcının kullanıcı adını ve bağlantı yöntemini göstermelidir. 
“Hoşgeldiniz” mesajı bağlanan istemci ekranında (yani hastanın ekranında) görünmelidir.

4. Her doktorun önceden belirlenmiş randevuları olan hastaları olsa da randevusuz gelen hastalar da vardır. Herhangi bir doktor hasta çağırma fonksiyonunu (ilgili doktor 
ekrana “Hasta Kabul” yazdığınızda ilgili fonksiyonun üzeri çizilmelidir) hem sunucu hem de hasta çağırdığında yapabilir. 
Bu işlem ekranda “HastaX -> DoktorY” olarak görüntülenmelidir. İlgili hasta doktoru kabul eder 
olduğunda bir işlev çağrılmalı ve bu işlevle hem hasta hem de doktor ekranda 
Bilgiler ”HastaX doktor randevusunu kabul etti" şeklinde gösterilmelidir. Hastanın randevusu 10 
 Hasta 10 saniye içinde kabul etmezse, bir sonraki hasta otomatik olarak doktor tarafından çağrılmalıdır.

5. Herhangi bir doktorun randevulu hastaları bittiğinde, çağrı fonksiyonu otomatik olarak 
veya manuel çağrı durumunda, en fazla sayıda kalan hastası olan doktorun sıradaki hastası çağrılır. Bu sırada, çağrılan hastanın doktoru ile çağrıyı yapan doktorun aynı olması gerekir. Hastalar sırasıyla Doktor1 ve Doktor2'ye vardıklarında 
aktarılabilir.

6. Herhangi bir doktor yeni bir hastayı aradığında, doktorun eski hastasının ekranında “Geçmiş 
yazısı belirecek ve hasta bağlantısı kesilecektir. Ayrıca, sunucu ekranında “HastaX 
gitti” mesajı görünmelidir.


7. Sistemdeki tüm hastalar işlerini bitirdiğinde, tüm doktorlar bilgilendirilmeli ve tüm bağlantılar kesilmelidir. Sistemde hasta yoksa, doktorun ekranında “Bekleyen hasta yok” mesajı görüntülenmelidir.

