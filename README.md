# FEED THE NEED APP
An android app that connects food donors with receivers. This app allows user to locate the donor or receiver in their locality based on the entered pin-code. Apart from this when the donation is successful the donor would  become eligible for reward in the form of cryptocurrency. 
##Modules - 
### App Start up -
1. Splash screen - Logo of app and the splash screen playing a video of food donation with a small quote.
2. Navigation screnn with four windows for navigation - 
   1. Donate 
   2. Recieve 
   3. Admin 
   4. About us
### Donate - 
1. Registration Form - A form for registering the donor and storing its details for displaying them to potential reciever.
2. Available recievers - This is page for showing available recievers in the area based on Pin-code entered
3. Connect to recivers - In order to connect to reciever app uses gmail for sending mail regarding donation request. 
                         This page has field for taking input of email address of the reciever, subject, and message with inform the donor button which opens gmail and                              send mail with given data input in the field.
4. Get the reward - Once the donation is completed the donor can click on " get the reward " button to open the new page with check wallet button 
                    to verify the transaction. Check wallet button opens installed crypto wallets to check reward & if no wallet is present it opens metmask.io                             website.
      
### Recieve - 
1. Registration Form - A form for registering the reciever and storing its details for displaying them to potential Donors.
2. Notification page - Once the form is filled notification page is opened to notify the reciever about donation.
3. Send reward - Once the donation is completed the reciever can send reward to donor is it was satisfied with the donation quality. 
4. Transaction details - When the reciever clicks on "send reward " button it takes it to form for filling the details for transaction. After filling the form user should click the "Send" button which takes user to its wallet app to send reward.

### ADMIN - 
User can click on this window to open admin section.
 
### ABOUT US - 
This page contains the contact information of the developing team members and details about app.

### Tools used - 
1. android studio (IDE)
2. firebase (storage)
3. Android devices ( testing )
