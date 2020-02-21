# *Just Do IT!* - Progress Report Three

## What we have done so far:

* We have adjusted branch protection rules to require at least two approvals before merging a branch.

* We have setup our project via the Express framework. We used express generator to create an express application.
  Refrence: https://expressjs.com/en/starter/generator.html
  ![express](https://user-images.githubusercontent.com/54300222/74999698-459b1980-5454-11ea-8500-b975b1811703.png)

* After setting up the project in express our team initially started with creating the appointment form in html where user can     insert the data of the appointment to be made and submit it.
  <img src="https://user-images.githubusercontent.com/54300222/75000054-310b5100-5455-11ea-9205-9e844f4e80f9.png" width="600"   height="400">

* We have created a genral google account for the project which can be used by each team member to work with googoe api console.

## What we are doing:

We are working an an html form to send data. In consideration of the required data fields by Google Calendar.
Sending data from HTML Appointment Form will work in following way:

1. User will enter the required information for the appointment.

    <img src="https://user-images.githubusercontent.com/54300222/75000737-1fc34400-5457-11ea-8241-4a1e35c34ad2.png" width="600"   height="600">

2. When user clicks on the submit button it will create a POST request to send the form data.

3. In the backend side We have created a variable object called 'calendarData' which will have all the information from the appointment form.

    <img src="https://user-images.githubusercontent.com/54300222/75000798-54370000-5457-11ea-92a8-cde997eeb074.png" width="400"   height="400">

4. Currently we are displaying form data on the terminal to check the recived data from the appointment form.

    <img src="https://user-images.githubusercontent.com/54300222/75000866-9102f700-5457-11ea-88fc-e300e01c0470.png" width="600"   height="400">

* API Progress:
   
We are following the Google calendar API: https://developers.google.com/calendar/create-events
So far the following was done: connect to API, read the user's calendar, and successfully added an event. As shown below:

![add_event](https://user-images.githubusercontent.com/21226482/74993446-9e48c300-5410-11ea-8c8c-2d911bd4cc00.png)

## What we are going to do:

The next tasks we are going to do are:
* Send the calendarData variable data to google calendar api to book an appointment.
* Add validation to the appointment form.
* setup the google authentication for the users.

