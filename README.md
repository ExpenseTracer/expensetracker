# expensetracker


Expense Tracker Application


About the project
This app allows the users to track the expenses. This makes it easy to prioritize your spending and plan ahead. For people new to budgeting overall, it’s a good first step in learning how and where you spend money. Users are only supposed to spend the amount allocated to each envelope, and if they go beyond their budget the envelope will show red to indicate that they overspent. Amount spent by a group of people at home or at some trip. Person can have a clear status of the money he owe to someone and how much others owe him.
Stake holders
Customers
Employees 
Sponsors

Modules
(read/Operaons/Report)  
●Keep a close track of credit card dues - no more surprises at the end of the billing cycle!  
●SPLIT expenses with friends - The simplest bill split experience!  
●Find ATMs with Cash near you in real-me  
●Check BANK BALANCES  
●Take control of your MONEY and SAVE more - Answer the key quesons of 'What', 'How Much' & 'Where' of your spends 
●All expenses at a GLANCE - Banks Accounts, Credit Cards, Digital Wallets, Sodexo etc.  
●EXPORT your data and generate expense reports (in PDF & CSV format)  


Epics-

Invision link

Epic: Login/Register 
->User Registration – As a user, I would like to have signup option
*Option to create a new account
*Allow user to sign up with google
*Allow user to sign up with facebook
*Allow user to sign up using phone number
*Option to create a new account
 
->User login- As a user, I would like to have sign in option
                                  Create a link “add trip expenses"
                       Create a link "add Group/Family expenses"
                       Create a link "add personal expenses"
                       Create a link "sign in" under signup 
*Add submit button at bottom
*Update sql query after the addition of new expenses

->Forget password - As a user, I would like to have forgot password option
*Include a text field in the new page to enter email/user id
*Send verification email to entered email address
*Allow user to enter new password via email link
*Include a click able link below the password input text field
*Add a submit button
*Update password in database
*Implement triggers on password updates
*Redirect the user to login page

->Sign up support - As a user, I would like to have skip sign up option
*Create a check box for "Agree terms and conditions"
*Create a check box for "I'm not a Robot option"
*Create a "submit" button
*redirect to new page

Epic: Add Group
->Trip Expense Tracking – As a user, I would like to add “Trip Expense Tracking Button”
*Add “Category Button”
*Allow user to enter the amount 
*Allow user to add the person who paid for that expense
*Add a button for the conversion of currency from our country to other country
*Allow user to add the date of money spent
*Allow user to add the Description of money spent
*Allow user to select the of expense
*Allow user to enter the amount 
*Allow User to Select type of Category 
*Allow user to add the no of persons involved
*Allow user to add budget
*Create a button to split the money to all the people who are part of the expense equally.

->Personal Expense Tracking – As a user, I would like to add “Personal Tracking Button”
*Add Category Button
*Allow User to Select type of Category 
*Allow user to add the date of money spent 
*Allow user to enter the amount 
*Allow user to select the of expense
*Allow user to add the Description of money spent.

oGroup Expense Tracking – As a user, I would like to add “Group Tracking Button”
Add Category Button
Allow User to Select type of Category 
Allow user to add the Description of money spent
Allow user to add the person who paid for that expense
Allow user to enter the amount 
Allow user to add the date of money spent 
Allow user to select the of expense
Allow user to add the no of persons involved
Create a button to split the money to all the people who are part of the expense equally

oEdit Expense- As a user, I would like to have “edit the expense option”
Allow user to select the expenses 
Allow user to select one of the Group
Allow user to ask for "do you want to edit the expenses" with two options: “yes” and “no”
Create a new button "Save" to save if user click on yes option
After saving I will be directed to home

oDelete Option- As a user, I would like to have “Delete option”
Allow user to select the expenses 
After selecting it is directed to the new portal 
Allow user to select one of the Group
Allow user to ask for "do you want to delete all expenses" with two options: “yes” and “no”
After clicking I will be directed to home
		
Epic: Home
As a user, i would like to add "settleup expenses" button

allow user to select a group to settle up
Allow user to enter the amount .
add submit button 
update sql query after the addition of new user
Allow user to add the date of settle up
implement using HTML/CSS
redirected to new page
Add new button "settle friend"
Add new button "settle group"
allow user to select a friend to settle up
oAs a user, i would like to add "friends" button

 Allow user to grant permission to access the contacts.
allow users to find friends from contacts
add "reminder" button send owe reminder to the friends
implement using HTML/CSS
Redirected to new page
add "friends list"
Allow User to Select group
allow users to find friends from facebook
oAs a  user ,i would like to have a search option
 redirect to new page
allow user to search location
allow user to search a group
allow user to search a friend
update sql query after the searching
add export to csv button
allow user to search by money
allow user to search by category
allow user to download the csv file
oAs a  user ,i would like to have a balance and activity option
allow user to select a friend to check balance
allow user to select a group to check balance
Add new button "activity"
allow user to select a group to check recent activity
allow user to select a friend to check recent activity
allow user to download the csv file
add export to csv button
redirect to new page
Add new button "check balance"
oAs a user,i would like to add "Details of all group"button
allow user to select "all groups" button
Allow user to select outstanding balance Button
Allow user to select the groups that you owe Button
Allow user to select the "groups that owe you." Button
implement using HTML/CSS
add a "submit" button at the bottom
Redirected to new page


Epic: Account
oAs a user, i would like to add "add personal information"
 allow users to add the nick name
Allow user to edit email id
allow users to edit password
Allow user to edit phone number
update sql query after the addition of new user
Allow user to add gender
Allow user to add the country
Redirected to new page
Allow user to add preferred language
Allow user to add DOB
Allow user to add Default currency
oAs a user, i would like to add "photo"
request user to grant the access of the camera
add the edit option to edit the photo
restrict user to use image size less than 2mb
Allow user to edit phone number
update sql query after the addition of new user
add "photo from camera" button
Redirected to new page
add "photo from gallery" button
request user to grant the access of the gallery
oAs a user, i would like to add scan code
request user to grant the access of the camera
Allow user to scan the QR code
add an accept button to add the person to friends list
add share QR code button
update sql query after the addition of new user
Redirected to new page
add "photo from camera" button
oAs a user, i would like to add Logout
Request the user to enter the password
allow user to remember the password
ask user to rate the app
 update sql query after the addition of new user
Redirected to new page
add the message of "Are you sure You want to Logout"
add two buttons "Yes" and "No"
Epic: Settings 
User Stories:
oAs a user, i would like to add Email settings
add a check box "When someone adds me in the group"
add a check box "When someone adds me as a friend"
add a check box "When an expense is added"
add a check box "When the expense is edited"
add a check box "When the expense is due"
add a check box "Monthly summary of activity"
add a button "save changes" at the bottom to save the changes
update sql query after the addition of new user
Redirected to new page
add a check box "When someone pays me"
oAs a user, i would like to add "Device and push notifications"
 add a check box "All friends notifications
add a check box "When someone added as friend"
add a check box "all group notifications"
add a check box "When Removed from group"
add a check box "When the expense is due"
add a check box "Monthly summary of activity"
add a check box "When someone pays me"
Redirected to new page
add a button "save changes" at the bottom to save the changes
add a check box "all app notifications"
update sql query after the addition of new user
add a check box "all expense notifications"
oAs a user, i would like to add Feedback
 add save suggestion button
a popup message "Thank you for giving the feedback"
add a Suggestion box
Redirected to new page
request the user to rate the app
oAs a user, i would like to add theme
 Redirected to new page
allow user to add the image is background
allow user to add "light theme"
allow user to add "change Dark theme"
oAs a user, i would like to add contact support
allow user to "contact whatsapp"
allow user to "check the privacy policy"
allow user to chat through bot chat
Redirected to new page
allow user to "contact through Toll free number"
allow user to "contact through mail"

Epic: Statisics
User Stories:
-> As a user, i would like to add graph for every month expenses
*allow user to add all the data into csv form
*add a button to monthly expenses in graph
*Redirected to new page
*make a graph with x axis as the total months and y-axis as the total monthly spending
*preprocess the data and add tha total income of the month

->As a user, i would like to monthly report
*Redirected to new page
*allow user to view least spent week
*ask user permission to set every month report or not
*allow user to view expense for every month
*allow user to view the highest spent week
->As a user, i would like to yearly report
*Redirected to new page
*ask user permission to set every month report or not
*allow user to view expense for every month
*allow user to view least month
*allow user to view the highest spent month
->As a user, i would like to view catogery report
*use sql queries
*allow user to view expense for every catogery
*allow user to view the highest spent catogery in every month of a year
*ask user permission to set every month report or not
*allow user to view least spent catogery
*allow user to view highest paid amounts at single time



