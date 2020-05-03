# Just Do IT! - Progress Report 12 - (Week 16 - 04/27)

## What we've done so far:

### Public Release Sprint Part 1

To get ready for the public release, we have been polishing up our system's core functionality. This includes creating, reading, updating, and deleting Google Calendar events.

For weeks now, we had the issue of events not being able to update on our appointment list without a refresh. We introduced a temporary solution of performing deletes and updates on other pages, then visiting the appointment list.

In short, this is a temporary solution to [issue #2](https://github.com/567WebSystems/project-4-release/issues/2)

<img width="886" alt="update_success" src="https://user-images.githubusercontent.com/21226482/80893227-fe23db80-8c95-11ea-9e31-659a8055fb98.png">
<br>
<br>
By staying on the same form when performing updates, the new update is instantly visible on the View Appointments table:
<br>
<br>
<img width="891" alt="updates" src="https://user-images.githubusercontent.com/21226482/80893292-a9cd2b80-8c96-11ea-902d-94e22b1e965e.png">
<br>
<br>
This same concept applies to the delete functionality:

<img width="891" alt="confirm_delete" src="https://user-images.githubusercontent.com/21226482/80893372-69ba7880-8c97-11ea-8384-37c9bbdcd9fb.png">
<br>
<br>
Currently the app is redirecting back to the menu to resolve deleted events:

<br>
<br>
<img width="891" alt="menu_redirect" src="https://user-images.githubusercontent.com/21226482/80893381-76d76780-8c97-11ea-8841-a2cc8692526f.png">
<br>
<br>
This is perhaps not the most elegant solution, but neither is refreshing the page every time.
<br>
<br>
<img width="891" alt="deleted_event" src="https://user-images.githubusercontent.com/21226482/80893398-86ef4700-8c97-11ea-807a-5ddc2cf28225.png">
<br>
<br>
We've made sure all our functions are passing tests:
<br>
<br>
<img width="515" alt="all_tests_passing" src="https://user-images.githubusercontent.com/21226482/80896935-46082a00-8cb9-11ea-9bb6-9b72d61afcbe.png">
<br>
<br>
All these things should help better prepare us for final deployment.
<br>
<br>
We tried one implementation of web sockets using the socket.io library. Unfortunately that implementation did not work and then the workarounds were found for the refresh issues. Web sockets are definitely useful — but currently we have another approach. We are retrieving data from MongoDB cloud — using an entirely different approach with embedded js in our ejs views. But at least we tried out using web sockets and have made a successful connection from the backend to the frontend:
<br>
<br>
<img width="431" alt="socket_connected" src="https://user-images.githubusercontent.com/21226482/80897029-42c16e00-8cba-11ea-9aa7-bd1088aadaa1.png">
<br>
<br>
We've finally added a license to our repository, to provide rights to all for open source use, according to the MIT license guidelines:
<br>
<br>
<img width="701" alt="License" src="https://user-images.githubusercontent.com/21226482/80897065-b6637b00-8cba-11ea-8fca-4f27dbb12ae6.png">

___

## What we're going to do:

At this point, we have readied up our app; the pre-deployment phase is complete. The next tasks include: deploying the application to a public server, applying a process monitoring software, and establishing a system for CI and CD. These will be our next steps for the conclusion of this extensive semester project. Thank you.
