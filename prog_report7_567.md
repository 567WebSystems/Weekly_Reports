# *Just Do IT!* - Progress Report Seven (Initial Beta Release) - (Week 11 - 03/23)

## What we have done so far:

### Initial Beta Release v1.1.1

We have migrated all our web system files down to our root folder for easier access to our application.

![appinroot](https://user-images.githubusercontent.com/31261926/77832275-bf49b580-712c-11ea-83ad-d0dda9f4d83b.png)

### Development Progress

Created the menu page to improve the usability of our app:

![menu](https://user-images.githubusercontent.com/21226482/77839528-38ec9e00-7143-11ea-9423-f7dec1a4f2df.png)

Created the homepage link, to return to the menu. This works throughout our app, except on the menu page.

![homepage](https://user-images.githubusercontent.com/21226482/77839607-f081b000-7143-11ea-8bcd-d8aebb031a62.png)

Commenced operations on updating events. Here, the user can choose to change any of the above data-fields. They can do so via the Edit options:

![update_option](https://user-images.githubusercontent.com/21226482/77839651-33438800-7144-11ea-905b-0362e66362e2.png)

After select an event to edit, the user will go to the update form.
![update_form](https://user-images.githubusercontent.com/21226482/77839689-7b62aa80-7144-11ea-84b2-65c8635fb351.png)

This is the current progress from the front end. After filling out the form, the update went through:

![updated](https://user-images.githubusercontent.com/21226482/77839727-deecd800-7144-11ea-8098-13a18311fc66.png)

The next step will be to display this on the front end. This is still a work in progress.
___

## What we are doing:

Currently we are working on incorporating all feedback from the professor as our initial beta release.

Feedback such as removing deprecated syntax and use a more modern alternative.

![deprecatedonsubmit](https://user-images.githubusercontent.com/31261926/77832397-a7befc80-712d-11ea-8224-5cf5183056cb.png)

Converting existing jQuery to native DOM JavaScript.

![jquerytojs](https://user-images.githubusercontent.com/31261926/77832418-cfae6000-712d-11ea-840c-9ecf8695bd30.png)

Removing and transferring over inline styling to separate CSS file.

![moveinlinestyle](https://user-images.githubusercontent.com/31261926/77832550-d8ebfc80-712e-11ea-91e6-b8c6653a0238.png)

Remove mongoose connection out of app.js file and into its' own connection file.

![movemongoose](https://user-images.githubusercontent.com/31261926/77832593-2e280e00-712f-11ea-931b-aaef80378dc3.png)

Change 'controllers' directory to 'lib' directory.

![controllerstolib](https://user-images.githubusercontent.com/31261926/77832669-9971e000-712f-11ea-81f6-53794e4761da.png)

This is our current 'Doing' Trello board.

![trellodoing](https://user-images.githubusercontent.com/31261926/77832150-cd4b0680-712b-11ea-891a-16a6b35a62cd.png)

We are currently still working on this [issue](https://github.com/567WebSystems/project2alpha/issues/23) with events not immediately displaying or immediately being deleted when on the View Appointments Page.

Although, events are only displayed and or deleted after the current page is reloaded/refreshed.

___

## What we are going to do:

We still have a fair amount of items to complete in our 'Doing' and a good number of items to start and finish in our 'To Do'.

![trellotodo](https://user-images.githubusercontent.com/31261926/77832296-e3a59200-712c-11ea-9114-f0d20bac8dd4.png)

After reorganizing and restructuring of our code, we will continue working with core functionality of our application such as updateEvent() and more.

![updateevent](https://user-images.githubusercontent.com/31261926/76694458-189bea00-6641-11ea-9144-844cc42b041f.png)
