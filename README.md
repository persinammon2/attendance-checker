# Attendance Tracker

This program was written for a technology entrepreneurship class, and placed second out of 5-6 teams.

## Dependencies

- JavaScript
- Google Workspace API

## User Flow

1. Students download any QR Scanner app.
2. Teacher generates a QR code by using link to set a custom password.
   a. Email is sent with password as title to each student on roster.
   b. Students email name as message. 
3. Class-specific gmail inbox has script that monitors emails in inbox and writes student name and timestamp to Google Sheet.

## Potential Improvements

- Sending back confirmation email to students
- Adding metrics like running total of attendance per student
