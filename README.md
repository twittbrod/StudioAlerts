# StudioAlerts
Using Twilio Studio for Voice Alerts

Use Case:
  Incident alerts to a list of people via phone call.  If person one does not answer, try again with person 2.  Continue iterating over the list. (Initially built to support 3 users.)
  
The Flow:
  1. Call Studio flow and passing inital phone number in To field and subsequent phone numbers in Paramters.
  2. If the call is answered, Say a message.
  3. If no answer, call flow from itself, promoting phone2 to become phone 1, phone 3 to become phone2, etc.
  
Files:
  StudioFlow_Alerts.json: exported flow to be imported as new flow
  Postman_StudioLaunch_Alerts.txt: cURL command to execute flow
  

THIS FLOW IS UNTESTED
