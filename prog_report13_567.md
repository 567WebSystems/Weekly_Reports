# Just Do IT! - Public Release Progress Report - (Week 17 - 05/07)

## **Abstract**
People nowadays integrate a lot of technology into organizing their daily lives. These include note reminders, electronic planner apps, virtual calendars and much more. Although these technologies come in handy, they still require a fair amount of manual work. There are many businesses that deal with clients who set up appointments daily, using some sort of scheduling system. What if users could schedule faster — without the need to manually input appointments on the other end? The problem here is that there should be a faster way to schedule appointments on a user's calendar — without the need to do a lot of typing.

A solution for this project is to create an appointment scheduling web system. The users could fill out a form and book an appointment with another user and vice versa. Essentially they would use their Google account (or other account, after sign-up) to fill out a form. Then that data would submit to the calendar of the person they want to make an appointment with. With this solution, clients will be able to set up their own appointments with anyone that uses this web system without the other end having to document those manually.

Ideally the Google API would be used for allowing authentication to Google accounts. Users could post data under their own alias. There would also be a Google Calendar API which will help to retrieve data from a user's calendar to provide available times for appointments and allow users to book them.

___

## **Public Release**

### **What we've done so far**

* ### **Add Attendee Email Notification Feature to the application**

    When you book an appointment with the attendee and email notification is sent to the attendee about the appointment.

    <img width="538" alt="Screen Shot 2020-05-07 at 8 44 25 PM" src="https://user-images.githubusercontent.com/54300222/81361437-0455f580-90a4-11ea-9769-7f9f6d3cfce3.png">

    **Invitation Notification to Attendee**

    <img width="1099" alt="Screen Shot 2020-05-07 at 8 47 22 PM" src="https://user-images.githubusercontent.com/54300222/81361440-061fb900-90a4-11ea-9440-dadecdcc5690.png">

___

* ### **Integrated Travis CI**

  <img width="748" alt="travis-ci2" src="https://user-images.githubusercontent.com/21226482/81368531-95819800-90b5-11ea-953a-a4b0938abf6c.png"><br>

    Cofigured the travis so that it test the brach brach before it is merged to master.

    <img width="808" alt="Screen Shot 2020-05-07 at 1 37 23 AM" src="https://user-images.githubusercontent.com/54300222/81361662-9eb63900-90a4-11ea-9c7d-7846f6fa8cd9.png">

    Travis Config File

    <img width="296" alt="Screen Shot 2020-05-07 at 8 53 06 PM" src="https://user-images.githubusercontent.com/54300222/81361731-c6a59c80-90a4-11ea-893e-e686964c3ad8.png">

    Travis Portal

    <img width="1090" alt="Screen Shot 2020-05-07 at 8 55 39 PM" src="https://user-images.githubusercontent.com/54300222/81361869-269c4300-90a5-11ea-9502-85c1edf37ae7.png">

___

* ### **Deployed application on Herokuapp**

    <br>
    <img width="838" alt="app deployed" src="https://user-images.githubusercontent.com/21226482/81368290-07a5ad00-90b5-11ea-9773-c4e1992fa8c1.png"><br><br>
    Configured heroku to connect with our github repo. Trun on the automatic deplys settings.

    Creating our custom url by passing special parameter:

    <img width="848" alt="wsi-calendar" src="https://user-images.githubusercontent.com/21226482/81368651-e6918c00-90b5-11ea-822d-a0654d2ff4d9.png"><br>

    <img width="1304" alt="Screen Shot 2020-05-07 at 9 02 23 PM" src="https://user-images.githubusercontent.com/54300222/81362284-189af200-90a6-11ea-9434-cfb865d26a78.png">

    Here is the last few activites of automatic deployments

    <img width="648" alt="Screen Shot 2020-05-07 at 9 01 54 PM" src="https://user-images.githubusercontent.com/54300222/81362367-53048f00-90a6-11ea-878a-d51d0e995a6e.png">

___

* ### **Integrated pm2 Monitoring to our web system**

    Setup and install the pm2 on heroku as well as local machine to catch the metrics from both.

    Here is the ouput of the console on Heroku App

    <img width="616" alt="Screen Shot 2020-05-07 at 9 07 02 PM" src="https://user-images.githubusercontent.com/54300222/81362548-babada00-90a6-11ea-9928-08e0a7229bff.png">

    This is the output from the local machine

    <img width="983" alt="Screen Shot 2020-05-07 at 9 09 59 PM" src="https://user-images.githubusercontent.com/54300222/81362779-43d21100-90a7-11ea-973e-7ca25e573511.png">

    PM2 Dashboard

    <img width="1429" alt="Screen Shot 2020-05-07 at 9 12 04 PM" src="https://user-images.githubusercontent.com/54300222/81362830-6b28de00-90a7-11ea-8655-93650b37ad05.png">

    PM2 Realtime Logs which it catches from the application

    <img width="996" alt="Screen Shot 2020-05-07 at 9 15 01 PM" src="https://user-images.githubusercontent.com/54300222/81363016-dbcffa80-90a7-11ea-8786-8c254362b70b.png">

___

* ### **Made appointment form more attractive and responsive using pure css and HTML**

    <img width="455" alt="Screen Shot 2020-05-07 at 9 18 08 PM" src="https://user-images.githubusercontent.com/54300222/81363169-4bde8080-90a8-11ea-9164-2bb27eb9ee22.png">

___

* ### **Added responsive footer in web application**

    <img width="1439" alt="Screen Shot 2020-05-07 at 9 17 36 PM" src="https://user-images.githubusercontent.com/54300222/81363171-4c771700-90a8-11ea-9448-33b7245937ec.png">

___

* ### **Ensured Live Site Works w/o JS or CSS**

### Homepage:
<img width="868" alt="no_css_js1" src="https://user-images.githubusercontent.com/21226482/81367973-42f3ac00-90b4-11ea-99a8-5f38c4b7a62d.png">

### Menu:

<img width="868" alt="no_css_js2" src="https://user-images.githubusercontent.com/21226482/81368025-628ad480-90b4-11ea-80ae-d0660cb7fc3c.png">

### Appointment List:

<img width="849" alt="no_css_js3" src="https://user-images.githubusercontent.com/21226482/81368061-79312b80-90b4-11ea-9f15-ca9da8b72681.png">


___


* ### **API Documentation Link**

    https://567websystems.github.io/project-4-release/


* ### **Live Web Application System Link**

    https://wsi-calendar.herokuapp.com

* ### **GitHub Repository Link**

    https://github.com/567WebSystems/project-4-release
