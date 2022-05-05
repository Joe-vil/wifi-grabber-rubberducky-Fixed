# Local-&-Email-wifi-grabber-rubberducky
-Email Script fixed and reworked by Joe'vil, based on the code of Siem TTommy

-Local Script made by Joe'Vil

I am not responsible for any misuse of this script, you may only use on on your own system or if you have permission of use on others.

- Simple script for Rubber Ducky that download wifi credentials, compress and send them to an email or save localy to the Pi if your using one. After all console history and the file will be deleted automatically
 
- Make sure to change SENDER-EMAIL and SENDER-PASSWORD with credentials of the gmail account that will send the email and RECEIVER-EMAIL with the email that will receive the zip file (both the SENDER and RECEIVER can be the same, aka sending it to yourself). Note: do not use your personal email, make a new one specifically for the Pi.
- Make sure to allow less secure app by clicking here: https://myaccount.google.com/lesssecureapps
  
- if you have restrictions on your WIFI network and using a Raspberry Pi Pico you can use "payload-local" to save directly to the Pi in "DUMP.zip", don't forget to rename it to just "payload" when inserting it. This method only works if using a Pi.

-if your using a Raspberry Pi be sure to rename the "payloads.txt" to "payload.dd".
-to set up a Pi to use RubberDucky scripts watch this video here: https://www.youtube.com/watch?v=aTZelHsR75M&t=43s&ab_channel=HiImAJ
