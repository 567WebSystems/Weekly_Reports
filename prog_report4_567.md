# *Just Do IT!* - Progress Report Four

## What we have done so far:

We have resolved and documented our first project issue:

[Error contacting Google calendar service](https://github.com/567WebSystems/project2alpha/issues/8)

There was a problem reaching the Google Calendar API. An invalid time format was being sent. Here are two example solutions which resolved the issue:

Solution #1:

![solution1](https://user-images.githubusercontent.com/21226482/75234768-c887e100-5780-11ea-92c4-5f3bef68fb56.png)

Solution #2:
![solution2](https://user-images.githubusercontent.com/21226482/75234863-f1a87180-5780-11ea-902f-d2eb8d8e84f0.png)

We have implemented open authentication with help from: [Google OAuth](https://developers.google.com/identity/sign-in/web/sign-in)

Here is the current OAuth functionality:

1. Signing in
![si1](https://user-images.githubusercontent.com/21226482/75235409-cbcf9c80-5781-11ea-814e-d6860a98af54.png)

2. Choosing an account
![si2](https://user-images.githubusercontent.com/21226482/75235433-d8ec8b80-5781-11ea-9126-e67ecbb718a6.png)

3. Loading homepage
![si3](https://user-images.githubusercontent.com/21226482/75235460-e73aa780-5781-11ea-854a-3c662d9d6025.png)

4. Signing out
![si4](https://user-images.githubusercontent.com/21226482/75235500-f4579680-5781-11ea-8d7f-156eabd628d2.png)

5. Relogging (verification)
![si5](https://user-images.githubusercontent.com/21226482/75235540-020d1c00-5782-11ea-8e14-daba9bd9773f.png)

We have also documented and are  currently resolving our [second issue](https://github.com/567WebSystems/project2alpha/issues/11):

![issue2](https://user-images.githubusercontent.com/21226482/75473739-5b7c7300-595b-11ea-931f-6f57cf0a77d1.png)

There appears to be an invalid time format in the post request to Google Calendar API. However, after modifying the post request contents, this issue appears to be resolved:

![answer](https://user-images.githubusercontent.com/21226482/75473947-b2824800-595b-11ea-97a7-d85c4dc64589.png)


## What we are doing:

We are reading and adding events onto our Google calendars:

![add_event1](https://user-images.githubusercontent.com/21226482/75280720-9e134380-57d3-11ea-9e09-6db8be0b5803.png)

This means the Create and Read functionalities are done, but we would like to work on other operations (e.g. update, delete, storage), the priority of which will be determined.

Here are the created events from Google Calendar:

![add_event2](https://user-images.githubusercontent.com/21226482/75280973-05c98e80-57d4-11ea-985a-089e44f3b267.png)

We are also working on the database implementation. Our db of choice is [MongoDB](https://www.mongodb.com). Because it is a Cloud-based data storage service, which can be used freely to create data clusters in various regions inside & local to the USA.

![mongodb](https://user-images.githubusercontent.com/21226482/75474382-83b8a180-595c-11ea-8d7e-f76256684be1.png)

We managed to successfully store event data objects inside the MongoDB Altas cluster:

![datastore](https://user-images.githubusercontent.com/21226482/75474481-af3b8c00-595c-11ea-81ea-741a6cf0d79f.png)


## What we are going to do:

What should our next tasks be?
