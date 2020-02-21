# *Just Do IT!* - Progress Report Three

## What we have done so far:

We have setup our project via the Express framework. [INSERT LINK]

We started development of a user application form in the Express framework.

We are experimenting with Settings on Github. For example, adjusting branch protection rules to require at least two approvals before merging a branch.


## What we are doing:

We are working an an html form to send data. In consideration of the required data fields by Google Calendar (see below):

API Testing Progress:

We are following the Google calendar API: [create-events](https://developers.google.com/calendar/create-events).
So far the following was done: connect to API, read the user's calendar, and successfully added an event. As shown below:

![add_event](https://user-images.githubusercontent.com/21226482/74993446-9e48c300-5410-11ea-8c8c-2d911bd4cc00.png)

## What we are going to do:

Now that the data was passed to the backend, the next step is to find a way to insert the event into our calendar using google authentication.  

This has already been done using the Google API (as shown above).

However, we may need to create our own API, or find alternate solutions to achieve this. Currently we have a specialized google account set up, which all teammates can access to perform testing.
