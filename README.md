# project
Using Burpsuite for SQL injection on OWASP JUICE SHOP WEBSITE 

STEP 1:TURN ON YOUR KALI TERMINAL AND OPEN BURP SUITE

![image](https://github.com/user-attachments/assets/e97030ca-aea7-4d33-b827-42221e692036)

STEP 2:
Set the browser proxy to:

	•	127.0.0.1
	•	Port 8080
  ![image](https://github.com/user-attachments/assets/af017f02-3560-48ab-a430-b6446ee5a01d)
STEP 3:
Them go to OWASP juice shop login page and them enter dummy credentials like 

Email: admin

password : admin

STEP 4: Click Log in.
![image](https://github.com/user-attachments/assets/43f311bd-22d7-461f-b36b-03b8ad725eb9)
STEP 5:
Then turn on Burp Suite and it will intercept the request.
Them examine the login credentials
![image](https://github.com/user-attachments/assets/ad24f6a0-0f14-4247-9d3f-1faeccb680fb)
STEP 6:
Send the Request to Burp Intruder and burp repeater 

In Burp:
	•	Right-click → Send to Intruder
  Then go to intruder 
  ![image](https://github.com/user-attachments/assets/18cb9ec7-2a90-40f2-b550-bd6db23cc015)
  STEP 7:
  Add payloads to the front and back of the email and password 
  ![image](https://github.com/user-attachments/assets/2c4dcab6-6043-4411-bacc-c3f7c335052c)
STEP 8: 
Them go to goggle and search password list github for brute force 
![image](https://github.com/user-attachments/assets/06d78d7a-6956-4c9a-93ac-05cfe44e0275)
STEP 9: 
Copy the payloads on this webiste and paste it in payload configuration the click in start the attack 

STEP 10:After analyzing the data i found out that brute force was not going to word so i decided i was going to use SQL injection.
