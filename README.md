# project
Using Burpsuite for SQL injection on OWASP JUICE SHOP WEBSITE 

STEP 1:TURN ON YOUR KALI TERMINAL AND OPEN BURP SUITE

![image](https://github.com/user-attachments/assets/e97030ca-aea7-4d33-b827-42221e692036)
STEP 2:Then go to proxy and turn on the intercept 
![image](https://github.com/user-attachments/assets/93884613-1ada-4bba-bd1c-6d4bcaed291a)
STEP 3:
Set the browser proxy to:

	•	127.0.0.1
	•	Port 8080
  ![image](https://github.com/user-attachments/assets/af017f02-3560-48ab-a430-b6446ee5a01d)
STEP 4:
Them go to OWASP juice shop login page and them enter dummy credentials like 

Email: test@test.com
	•	Password: test123
STEP 5: Click Log in.
![image](https://github.com/user-attachments/assets/43f311bd-22d7-461f-b36b-03b8ad725eb9)
STEP 6:
Burp Suite will intercept the request.
Them examine the login credentials
![image](https://github.com/user-attachments/assets/ad24f6a0-0f14-4247-9d3f-1faeccb680fb)
Send the Request to Burp Intruder
In Burp:
	•	Right-click → Send to Intruder
  Then go to intruder 
  ![image](https://github.com/user-attachments/assets/18cb9ec7-2a90-40f2-b550-bd6db23cc015)
