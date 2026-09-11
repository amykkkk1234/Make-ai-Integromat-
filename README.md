# Make-ai-Integromat-

this is an email automation process to attach qr codes in emails
this can send emails to around 200 recipients in 10~15 minutes

before the process, u need to prepare:
1. one google sheet contains at least name, email, qr code string, qr code file path, and a trigger
2. one google drive folder contrains all related qr code

<img width="1323" height="232" alt="image" src="https://github.com/user-attachments/assets/213b163b-fee5-4751-a72d-4f6f87045337" />
process for attach 1 qr code and 1 reception map in an email  

1. link to google sheet, and set the condition to send emails 

2. link to google drive dowanloading the qr code and reception location

3. attach the qr code and map to the email (using html format would be better)

<img width="1315" height="206" alt="image" src="https://github.com/user-attachments/assets/02c428f6-71db-4eb2-9b64-6590816cdbeb" />
process for attach 4 qr codes in an email

first, link to google sheet, and set the condition to send emails

then, use array aggregator to bind 4 qr codes to 1 recipient

next, use iterator to download 4 qr codes at one time and bind them together by array aggregator

last, attach 4 qr codes to the email
