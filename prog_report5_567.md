# *Just Do IT!* - Progress Report Five - (Week 8 - 03/05)

## What we have done so far:

### Architecture for Appointment Web System

![architecture](https://user-images.githubusercontent.com/54300222/76047918-21fbc700-5f5c-11ea-98cf-0057ea78ea65.PNG)

Our Architecture remains the same other than the fact that we will be sending data to the MongoDB first and then to our calendar.

We have now fixed the date and time inputs to complete our data validation:

![validation](https://user-images.githubusercontent.com/21226482/76047050-396c8d00-5f27-11ea-9a81-5c02ac6f5b45.png)

We have also restructured our code tree to resemble an MVC (Model, View, Controller) structure.

![mvc](https://user-images.githubusercontent.com/31261926/76157280-658e3680-60fe-11ea-8dca-1530f0198d6a.png)

___

## What we are doing:

Currently on our Trello board, we are primarily working on the List Events method to list all events from the calendar so that we may proceed with Deleting and Updating functionality.

![doing](https://user-images.githubusercontent.com/31261926/76051416-93d70f00-5f62-11ea-998a-cb072c5117f5.png)

We have successfully implemented Google SignIn using passportJS. To implement the passportJS we have referred to the following diagram:

<img width="1355" alt="Screen Shot 2020-03-01 at 12 30 06 PM" src="https://user-images.githubusercontent.com/54300222/76048056-8cad0280-5f5c-11ea-853b-54b4f2524a4e.png">

We had ran into an issue with being able to call our gCal function from our gCalendar.js file.

![gcalfunc](https://user-images.githubusercontent.com/31261926/76157137-c157c000-60fc-11ea-88e4-11c97cb40ac0.png)

Initially, we had called the gCal function this way which was giving us an undefined object.

![impropergcal](https://user-images.githubusercontent.com/31261926/76157230-ec8edf00-60fd-11ea-89d8-037c3279250c.png)

To resolve this issue, we properly pathed our gCalendar.js file to be required in our routes js file.

![gcalpath](https://user-images.githubusercontent.com/31261926/76157170-2ad7ce80-60fd-11ea-8f1f-96d9dee18205.png)

Then we exported the function from our gCalendar.js file.

![gcalexport](https://user-images.githubusercontent.com/31261926/76157186-58247c80-60fd-11ea-9492-c4ec20fb2b80.png)

Finally, we properly called the gCal function and passed it our calendarData property.

![propergcal](https://user-images.githubusercontent.com/31261926/76157200-9621a080-60fd-11ea-8e4b-313af0a5f810.png)

___

## What we are going to do:

This is our current Trello board with what needs to get done.

![todo](https://user-images.githubusercontent.com/31261926/76051335-58d4db80-5f62-11ea-9376-cdc1e0e94d03.png)

We are currently still on v1.0.0 Alpha [First Release](https://github.com/567WebSystems/project2alpha/releases) with an upcoming minor release to v1.1.0

![v1.0.0](https://user-images.githubusercontent.com/21226482/75476196-cfb91580-595f-11ea-9c6e-5930d19ca767.png)

We plan on migrating functions from our gCalendar.js into their own controllers such as listevents.js, insertevents.js, deleteevents.js, and more.

![futureplans](https://user-images.githubusercontent.com/31261926/76157316-0ed52c80-60ff-11ea-8a55-621afb668756.png)

Our plan to access these js controllers is to create new ejs pages along with proper routes so that we can use the router.post() method to access the controllers and its' functions.
