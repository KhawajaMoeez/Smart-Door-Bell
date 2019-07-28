# Smart-Door-Bell
Project

This project contains the following features:

•	Camera live stream on HTML page.

•	Time schedule of visitors and count.

•	Manage visitors

•	Notifications

•	Visitor name announced by the speaker.

•	Easy-to-fill database, when a new visitor comes: the notification will show the picture of the user and will ask of his name so that in future this person will be recognized


We need the following for the setup of this project:

•	Raspberry pi (any variant)

•	Get OPEN CV and Build it into your Pi (Google it)

•	Get PHP, SQL, Apache

•	A button that serves as a doorbell

•	A camera (USB in this case)

•	Wifi connectivity

•	No-IP : create a DNS for the raspberry pi in case you want to monitor your home with an external network connectivity

•	e-speak library to announce the name of the visitor in case there is people in the house


To set this up, follow these steps:

•	First we need to update and upgrade our Raspberry pi " Sudo apt-get update " " Sudo apt-get upgrade "

•	Install Open CV and build it

•	Install Apache and PHP

•	Install fswebcam

•	Install e-speak

•	Install No-IP and configure the DNS (Google this also)

•	Copy the content of web directory into your var/www/ folder

•	Create a database (vue the name and the table name in the PHP access file)

•	Finally configure push notifications via Whatsapp or PushBullet (in this project i've used PushBullet)

