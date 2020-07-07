Learn how to create a Google Calendar event using APIs in PHP
Handle the timezone of the created event in correct way
===

Creating an event using Google Calendar API consists of 5 steps:

1 - Register a Google Application and enable Calendar API.
2 - In your web application, request user for authorization of the Google Application.
3 - Get the user's timezone.
4 - Use the primary calendar of the user. Or else get the list of his calendars and let the user choose.
5 - Create an event on this calendar.