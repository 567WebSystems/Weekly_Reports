# *Just Do IT!* - Progress Report Six (Final Alpha Release) - (Week 9 - 03/12)

## Abstract
People nowadays integrate a lot of technology into organizing their daily lives. These include note reminders, electronic planner apps, virtual calendars and much more. Although these technologies come in handy, they still require a fair amount of manual work. There are many businesses that deal with clients who set up appointments daily, using some sort of scheduling system. What if users could schedule faster — without the need to manually input appointments on the other end? The problem here is that there should be a faster way to schedule appointments on a user's calendar — without the need to do a lot of typing.

A solution for this project is to create an appointment scheduling web system. The users could fill out a form and book an appointment with another user and vice versa. Essentially they would use their Google account (or other account, after sign-up) to fill out a form. Then that data would submit to the calendar of the person they want to make an appointment with. With this solution, clients will be able to set up their own appointments with anyone that uses this web system without the other end having to document those manually.

Ideally the Google API would be used for allowing authentication to Google accounts. Users could post data under their own alias. There would also be a Google Calendar API which will help to retrieve data from a user's calendar to provide available times for appointments and allow users to book them.


___

## What we have done so far:

### Final Alpha Release v1.1.0

* place final alpha release information here

### Passport Authentication for Appointment Web System

#### Passport Architecture and Implementation

   <img width="1355" alt="Screen Shot 2020-03-01 at 12 30 06 PM" src="https://user-images.githubusercontent.com/54300222/76048056-8cad0280-5f5c-11ea-853b-54b4f2524a4e.png">

Initially we implemented the google SignIn and then we moved to google Authentication using passportJS. The google signIn we implemented first was only used to get token but it was not able to maintain the session.

PassportJs helps us to manage the google signIn with less effort and more clear to understand. With the passport we are maintianing the user session using the cookies so that user can use that cookie to perform the authorised tasks related to google authentication.

The cookies created by the passport allows the user stay signedIn for 24 hours from the time of cookie created because the cookie has the expiration of 24 hours.
Refer the above diagram to get actual working of PassportJs for google SignIn

* Google Login using passport
    <img width="1440" alt="google auth" src="https://user-images.githubusercontent.com/54300222/76694769-0cc71c80-666f-11ea-830d-389996c13d78.png">

* Calendar Access Permission
    <img width="1440" alt="Screen Shot 2020-03-14 at 11 02 35 PM" src="https://user-images.githubusercontent.com/54300222/76695041-fc647100-6671-11ea-9034-ede08d3bd0c7.png">

We have completed verification on each field to be filled properly before user may submit using our formValidation() function in our scripts.js

![formvalidation](https://user-images.githubusercontent.com/31261926/76694044-b55b8900-663b-11ea-97c0-fdd95179f296.png)

We have completed our deleteEvent() function to successfully delete event by event.id on authenticated users calendar

![deleteevent](https://user-images.githubusercontent.com/31261926/76694100-96112b80-663c-11ea-9ba1-c821244fef18.png)

We have successfully displayed authenticated user events on our View Appointments page

![appointmentpage](https://user-images.githubusercontent.com/31261926/76694169-9231d900-663d-11ea-9c6a-d1523f6d65f0.png)

___

## What we are doing:

As of right now, we are working on our updateEvent() function as well as reorganizing our application directories and preparing for Beta Release

![trellodoing](https://user-images.githubusercontent.com/31261926/76694500-8516e900-6641-11ea-911f-8da1874116dc.png)

We are currently working on an [issue](https://github.com/567WebSystems/project2alpha/issues/23) with events not being displayed immediately and being deleted immediately from our View Appointments page

Events are only displayed and or deleted after the current page is reloaded/refreshed

Before Page Reload/Refresh:
![before](https://user-images.githubusercontent.com/31261926/76694279-ed180000-663e-11ea-9db4-8b8e97ad760e.png)

After Page Reload/Refresh:
![after](https://user-images.githubusercontent.com/31261926/76694296-13d63680-663f-11ea-8074-e10fd7483744.png)

___

## What we are going to do:

Our To Do list is small for now and is planned mainly for Beta release. What we are currently working on will most likely roll over to Beta release as well.

![trellotodo](https://user-images.githubusercontent.com/31261926/76694399-42a0dc80-6640-11ea-8b80-9793212342a7.png)

We are going to also continue working on completing the updateEvent() function as well as other functionality

![update](https://user-images.githubusercontent.com/31261926/76694458-189bea00-6641-11ea-9144-844cc42b041f.png)
