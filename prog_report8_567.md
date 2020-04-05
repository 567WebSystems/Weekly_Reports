# *Just Do IT!* - Progress Report Eight - (Week 12 - 03/30)

## What we have done so far:

### Beta Phase

We have changed our 'controllers' directory to a 'lib' directory where all data processing code will be placed.

![controllerstolib](https://user-images.githubusercontent.com/31261926/78460754-fc74f100-76b2-11ea-890f-aee4e7465555.png)

We have migrated the MongoDB connection into its' own connection file called 'connect.js' and referencing the connection in our 'app.js'.

![connectjs](https://user-images.githubusercontent.com/31261926/78460848-f6334480-76b3-11ea-9af1-8243e0e3b4b6.png)

![appjs](https://user-images.githubusercontent.com/31261926/78460874-27ac1000-76b4-11ea-98a3-8fec5698d650.png)

We have removed all inline styling and moved it to external CSS file.

![inlinestyle](https://user-images.githubusercontent.com/31261926/77832550-d8ebfc80-712e-11ea-91e6-b8c6653a0238.png) --> ![removeinline](https://user-images.githubusercontent.com/31261926/78460922-a143fe00-76b4-11ea-8085-7b15e69f473f.png) ![inlinetocss](https://user-images.githubusercontent.com/31261926/78460932-b456ce00-76b4-11ea-9263-6159100dc44b.png)

We have successfully finished the updateEvent() method.

![updateevent](https://user-images.githubusercontent.com/31261926/78461013-5c6c9700-76b5-11ea-9833-09b2269f8152.png)

![updateroute](https://user-images.githubusercontent.com/31261926/78461116-e157b080-76b5-11ea-9ba7-95e1e66f462b.png)

### Update Process Demo

1) Start by creating a new event via the Appointment Form. Also note that the user has three upcoming events, listed below:

![apptlist](https://user-images.githubusercontent.com/21226482/78464958-8920ae80-76b5-11ea-8235-f5ae451ed9ce.png)

2) Next, the user fills in the details of their brand new event

![apptform](https://user-images.githubusercontent.com/21226482/78464972-c9802c80-76b5-11ea-95f9-09a742ec4a51.png)

3) When viewing appointments, their new event shows up below:

![newEvent](https://user-images.githubusercontent.com/21226482/78465004-0f3cf500-76b6-11ea-8946-2767144cabe0.png)

4) After clicking the Edit button, their event information is now *pre-populated*, as outlined:

![pre-populated](https://user-images.githubusercontent.com/21226482/78465039-57f4ae00-76b6-11ea-96d2-2ad4d3a03734.png)

5) The user fills in the updated information, accordingly:

![updateForm](https://user-images.githubusercontent.com/21226482/78465066-bae64500-76b6-11ea-8398-f37e0b2a9dfa.png)

6) After refreshing the page, they will be able to see their update on the front-end:

![apptlist2](https://user-images.githubusercontent.com/21226482/78465086-f123c480-76b6-11ea-80eb-7c64be3a0ec7.png)


___

## What we are doing:

Currently we are still working on removing the deprecated 'on*.' by adding an EventListener in our 'scripts.js' but no success yet.

![deprecatedonsubmit](https://user-images.githubusercontent.com/31261926/78461168-490dfb80-76b6-11ea-8fa4-b7e05e7f4a42.png)

![eventlistener](https://user-images.githubusercontent.com/31261926/78461233-c0dc2600-76b6-11ea-8210-88fa367f3f2d.png)

We are still also working on converting ALL of our existing jQuery to native DOM JavaScript.

![jquery](https://user-images.githubusercontent.com/31261926/78461283-27f9da80-76b7-11ea-80bf-896b48de903c.png)

![jquerytojs](https://user-images.githubusercontent.com/31261926/78461298-419b2200-76b7-11ea-8e97-cf180a12c890.png)

![jquerytodom](https://user-images.githubusercontent.com/31261926/78461305-4fe93e00-76b7-11ea-8790-05a47582ac11.png)

This is our current 'Doing' Trello board.

![trellodoing](https://user-images.githubusercontent.com/31261926/78461556-b3746b00-76b9-11ea-8d03-cd56ffc9f89e.png)

We have temporarily alleviated our [issue](https://github.com/567WebSystems/project2alpha/issues/23) with events not immediately displaying or immediately being deleted when on the 'View Appointments' page by directing user to an 'Appointment Success' page where the user appointment form data will be submitted to our MongoDB first before the user may properly view all their appointments on the 'View Appointments' page.

This is only temporary because we plan on removing the success page in future implementations and have the user data be submitted to our database on submission with a success alert instead.

___

## What we are going to do:

This is our current 'To Do' Trello board.

There is definitely a lot more to be done that has not been added to our board yet. We are still working towards finishing everything in our 'Doing' board.

![trellotodo](https://user-images.githubusercontent.com/31261926/78461551-a22b5e80-76b9-11ea-9b6b-198997402329.png)
