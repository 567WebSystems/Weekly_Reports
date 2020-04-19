Â# *Just Do IT!* - Progress Report Ten - (Week 14 - 04/16)

## What we've done so far:

1) We used ESLint to clean all of our project files:

![eslint_setup](https://user-images.githubusercontent.com/21226482/79670733-c5aada80-818a-11ea-8dc0-84269e10c893.png)

That was the setup, now here's our config file and final results:

![eslint_config](https://user-images.githubusercontent.com/21226482/79670763-fc80f080-818a-11ea-9839-3013be2c77f2.png)

2) In our EJS views, we cut down the length of each file, by using a uniform layout. This applies throughout the entire project:

![layout_ejs](https://user-images.githubusercontent.com/21226482/79670899-d14ad100-818b-11ea-80a5-b8fc78b1437a.png)

3) Updates are now being sent to the Google Calendar API. The base functionality (CRUD) of the app is essentially complete:

<div align = center >BEFORE:</div><br>

![event1](https://user-images.githubusercontent.com/21226482/79671033-c8a6ca80-818c-11ea-91cb-c35f07a146c4.png)

![event1-calendar](https://user-images.githubusercontent.com/21226482/79671044-eaa04d00-818c-11ea-84fc-34539d1ef734.png)

<div align = center >AFTER:</div><br>  

![update1](https://user-images.githubusercontent.com/21226482/79671040-db210400-818c-11ea-89cb-ee743da63c8a.png)

![update1-calendar](https://user-images.githubusercontent.com/21226482/79671053-fee44a00-818c-11ea-85e2-a1a9b1600387.png)

This is a significant milestone for the project — now all our base functionality (CRUD) is working with any Google account that signs in.

This was the final issue preventing successful updates — missing end-time information **even though** the formatting was correct! Part of the problem was Google Calendar being picky enough that to also require the user's timezone info:

![update-issue](https://user-images.githubusercontent.com/21226482/79679083-610e7080-81c8-11ea-8db7-d59c21726d7c.png)

Thankfully, this and several other problems were resolved over the past few weeks, though we still have some issues we are working out using [Github Issues](https://github.com/567WebSystems/project-3-beta/issues).

___

## What we're doing:

Since we have completed the majority of our feature-goals, right now our top priority is to meet all the designated requirements for the project. Here's our current Trello "Doing" column:

![doing](https://user-images.githubusercontent.com/21226482/79679009-759e3900-81c7-11ea-846d-0e53f94db64f.png)

___

## What we're going to do:

Even though there is a lot of us are working on right now, there is are still plenty more to dos left to conclude the project, over the upcoming weeks:

![to-do](https://user-images.githubusercontent.com/21226482/79679046-f52c0800-81c7-11ea-97fb-63866a847bc8.png)
