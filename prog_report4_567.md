# *Just Do IT!* - Progress Report Four

## What we have done so far:

We have launched our [First Release](https://github.com/567WebSystems/project2alpha/releases) on Github! This initial v1.0.0 release may not be very pretty or perfect, but at least it is working & operational:

![v1.0.0](https://user-images.githubusercontent.com/21226482/75476196-cfb91580-595f-11ea-9c6e-5930d19ca767.png)

This was mainly a test to try out using the release feature from Github. In the future, more documentation and detail will be provided (including step-by-step deployment instructions).

We have resolved and documented our first project issue:

[Error contacting Google calendar service](https://github.com/567WebSystems/project2alpha/issues/8)

There was a problem reaching the Google Calendar API. An invalid time format was being sent. Here are two example solutions which resolved the issue:

**Solution #1:**
This first solution worked by combining the the first four (4, or half) the user inputs with the example from: [Google Cal API Create Event](https://developers.google.com/calendar/create-events).

![solution1](https://user-images.githubusercontent.com/21226482/75234768-c887e100-5780-11ea-92c4-5f3bef68fb56.png)

**Solution #2:**
This second solution built on top of the first by using the combined approach, but integrating about 90% of the user's input (the remainder being from Google's documentation above). The significance is maintaining the operability of the application while utilizing more of the user's data. These solutions were discussed and implemented by the whole team!
![solution2](https://user-images.githubusercontent.com/21226482/75234863-f1a87180-5780-11ea-902f-d2eb8d8e84f0.png)

We also decided to add open authentication with help from: [Google OAuth](https://developers.google.com/identity/sign-in/web/sign-in). This uses the modern OAuth2 protocol for authentication.

Here is the current OAuth functionality:

**1. Signing in**
![si1](https://user-images.githubusercontent.com/21226482/75235409-cbcf9c80-5781-11ea-814e-d6860a98af54.png)

**2. Choosing an account**
![si2](https://user-images.githubusercontent.com/21226482/75235433-d8ec8b80-5781-11ea-9126-e67ecbb718a6.png)

**3. Loading homepage**
![si3](https://user-images.githubusercontent.com/21226482/75235460-e73aa780-5781-11ea-854a-3c662d9d6025.png)

**4. Signing out**
![si4](https://user-images.githubusercontent.com/21226482/75235500-f4579680-5781-11ea-8d7f-156eabd628d2.png)

**5. Re-logging (to verify)**
![si5](https://user-images.githubusercontent.com/21226482/75235540-020d1c00-5782-11ea-8e14-daba9bd9773f.png)

We have also documented and are currently resolving our [second issue](https://github.com/567WebSystems/project2alpha/issues/11):

![issue2](https://user-images.githubusercontent.com/21226482/75473739-5b7c7300-595b-11ea-931f-6f57cf0a77d1.png)

There appears to be an invalid time format in the post request to Google Calendar API. However, after modifying the post request contents, this issue appears to be resolved:

![answer](https://user-images.githubusercontent.com/21226482/75473947-b2824800-595b-11ea-97a7-d85c4dc64589.png)


## What we are doing:

We are reading and adding events onto our Google calendars:

![add_event1](https://user-images.githubusercontent.com/21226482/75280720-9e134380-57d3-11ea-9e09-6db8be0b5803.png)

This means the Create and Read functionalities are done, but we would like to work on other operations (e.g. update, delete, storage, and more), the priority of which will be determined with the team.

Here are the created test events from Google Calendar:

![add_event2](https://user-images.githubusercontent.com/21226482/75280973-05c98e80-57d4-11ea-985a-089e44f3b267.png)

We are also working on the database implementation. For this, our pick is [MongoDB](https://www.mongodb.com). Because it is a cloud-based storage service, which can be used freely to create data clusters in various US and other local territories (e.g. Canada).

![mongodb](https://user-images.githubusercontent.com/21226482/75474382-83b8a180-595c-11ea-8d7e-f76256684be1.png)

We managed to successfully store event data objects inside the MongoDB Altas cluster:

![datastore](https://user-images.githubusercontent.com/21226482/75505069-e8e1b680-599f-11ea-838d-e63c4d3a2470.png)

To achieve this, we had to solve a [third issue](https://github.com/567WebSystems/project2alpha/issues/13) with the team.

## What we are going to do:

What should our next tasks be?
