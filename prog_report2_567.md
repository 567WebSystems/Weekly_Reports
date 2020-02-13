# *Just Do IT!* - Progress Report Two

## What we have done so far:

We have decided on our project topic of an appointment-scheduling calendar web system.

Our team has met and talked about our progression and what needs to be done first on the project as well as more sketches of what is to come on our project.

![trello-board](https://user-images.githubusercontent.com/31261926/74371366-9796cc00-4dd0-11ea-81f2-e3c907c1cc5f.png)

As we mentioned on our previous progress report, we have set up a Trello Board (as seen above), a Google Team Drive, a Slack Workspace, and a GitHub Organization repository. Notifications are enabled on our Slack channel (even past 10 PM) so that we can always have some form of communication.

## What we are doing:

Our development work started off with [nodejs-testing](https://github.com/567WebSystems/project2alpha/tree/nodejs-testing), our second branch, to try out the NodeJS backend framework. Specifically, how it integrates with the Google Calendar API. After setting up a NodeJS project and referencing the [developer documentation](https://developers.google.com/calendar/quickstart/nodejs), the first connection to the API was established.


When there are no scheduled events, the API shows the following:

![no_events](https://user-images.githubusercontent.com/21226482/74467558-e5f2ac00-4e5e-11ea-99e1-caa13b033c21.png)

To test that it was not simply an absence of data (and to ensure successful transmission) when an event *is scheduled* it shows:

![online_meeting](https://user-images.githubusercontent.com/21226482/74467715-2d793800-4e5f-11ea-8c37-653c0a009d59.png)

We are creating commits to this progress report as well as preparing for what needs to be done on the project.

## What we are going to do:

We are going to use some calendar API (ideally Googles Calendar API) so that we may use to get and post data to and from.
We have decided on only using a backend framework while leaving the frontend all up to us.
Also mentioned before, we are leaning towards using HTML/CSS and JS for our frontend and NodeJS and Express for a light-weight unopinionated backend.
We have also already received great feedback from the professor and will look to accommodate that feedback in our project.
