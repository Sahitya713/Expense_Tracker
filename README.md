# Expense_Tracker

This simple Expense tracker uses google sheets as the database.
The GUI can do the following:
1. display a pie chart and and a scrollbar with expenses made on a selected date
2. edit or delete expenses from the scrollbar
3. add new expenses

# Required installation

1. pip install gspread oauth2client
2. pip install tkcalendar
3. pip install pandas

# Synching with google sheets

1. go to https://tinyurl.com/expense-tracker
2. make a copy of the google sheet to your drive and name it "Expenses"
3. Go to console.developers.google.com
4. create a new project
5. Click Enable API. Search for and enable the Google Drive API.
6. Create credentials for a Web Server to access Application Data.
7. Name the service account and grant it a Project Role of Editor.
8. Download the JSON file.
9. Copy the JSON file to the same folder with the code rename it to client_secret.json
10. Find the  client_email inside client_secret.json
11. In the Expenses spreadsheet, share it with the email wih edit rights
