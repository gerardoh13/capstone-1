# Baby App Project Proposal by Gerardo Huerta

The main goal of the baby app is to store data regarding the feeding times for a baby as well as the amount fed. During the early stages, it is crucial to document when a baby was fed, and to know when the next feeding should be. Users should be able to easily look up the data they have logged by date. This is very useful information when speaking to their child’s pediatrician.
The app should be able to send reminders for when the next feeding should be. This is important since very young babies might not always cry to notify their parents that they are hungry. Knowing that the next feeding is coming up is also very useful in preventing the stressful scenario of defrosting/warming up milk while a baby cries helplessly. 

 The app should also optionally track bowel movements for a baby since these are important to ensure a baby is nourished and hydrated. Like the feeding times/amounts, users should be able to look past entries for future reference.

The app should be able to set calendar items for upcoming doctor visits, and send reminders for vaccinations when they are due.

The target demographic for the website is parents and/or caretakers for infants who want a convenient way to keep track of a baby’s feedings.

I will use data from the center for disease control such as their developmental milestones list to provide users with information on what milestones parents can expect for their children based on their age. https://www.cdc.gov/ncbddd/actearly/milestones/index.html
I will also use the vaccination schedule to send reminders on when certain vaccines are recommended based on the age of the child. https://www.cdc.gov/vaccines/schedules/hcp/imz/child-adolescent.html


To create this app I will start by creating a database schema that includes a table for a baby, a parent, feed, bowel movement, calendar item (doctor visit, vaccine, etc.).
Since the information contained in the database is somewhat medical in nature,  it must be password protected.

Some issues I might encounter with the APIs is the potential difficulty in using multiple, complex APIs. I want to use the google API for mail and calendar items, Pusher to send push notification to mobile devices, and cloudinary to allow users to upload photos.

The user flow will be signup, setting up information about the infant (dob, weight, length, etc.), then users will be redirected to a homepage/user portal. From here a parent will be able to navigate to a form to input new feeding information, a calendar to set events, and a form to update stats such as weight and height.

Setting calendar items, sending push notifications, and sending email reminders make this application more than CRUD.

A stretch goal will be to allow users to create “memories” which will contain images, and descriptions of the event such as first steps, first solid food, etc.
