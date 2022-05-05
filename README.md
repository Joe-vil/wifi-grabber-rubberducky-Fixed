# wifi-grabber-rubberducky-fixed
Script fixed and reworked by Joe'vil, based on the code of Siem TTommy

- Simple script for Rubber Ducky that download wifi credentials, compress and send them to an email or save localy to the Pi if your using one. After all console history and the file will be deleted automatically
 
- Make sure to change SENDER-EMAIL and SENDER-PASSWORD with credentials of the gmail account that will send the email and RECEIVER-EMAIL with the email that will receive the zip file. Note: do not use your personal email, make a new one specifically for the Pi.
- Make sure to allow less secure app by clicking here: https://myaccount.google.com/lesssecureapps
  
- if you have restrictions on your WIFI network and using a Raspberry Pi Pico you can use "payload-local" to save directly to the Pi, don't forget to rename it to just "payload" when inserting it. When using this method it only works if your using a Pi.

-if your using a Raspberry Pi be sure to rename the "payloads.txt" to "payload.dd".
-to set up a Pi to use RubberDucky scripts watch this video here: https://www.youtube.com/watch?v=aTZelHsR75M&t=43s&ab_channel=HiImAJ
