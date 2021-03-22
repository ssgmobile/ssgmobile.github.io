## SmartSpace Global Android Recruitment Test

Thank you for taking the time to do our technical test. It consists of two parts:

- [Create a small Android application](#create-a-small-android-application)
- [A few technical questions](#technical-questions)

Please submit your work by uploading a single zip file named {yourname}-{android-developer}.zip to [GET UPLOAD LINK FROM MARTIN]().

The zip file should contain:
- a single markdown file with the answers to the technical questions
- one folder containing your Android Studio project & source code.

# Create a small Android application

Smartspace Global has a set of mock APIs that you will use to get information about a list of Meeting Rooms in a building belonging to a fictious client. 

API | Purpose
------------ | -------------
[https://ssgmobile.github.io/api/room/rooms.json](https://ssgmobile.github.io/api/room/rooms.json) | Returns a list of meeting rooms in a building.
[https://ssgmobile.github.io/api/room/detail/0001.json](https://ssgmobile.github.io/api/room/detail/0001.json) | Returns the name, location and various facilities offered by room with identifer key = 0001 
[https://ssgmobile.github.io/api/room/detail/0002.json](https://ssgmobile.github.io/api/room/detail/0002.json) | Returns the name, location and various facilities offered by room with identifer key = 0002
[https://ssgmobile.github.io/api/room/detail/0003.json](https://ssgmobile.github.io/api/room/detail/0003.json) | Returns the name, location and various facilities offered by room with identifer key = 0003
[https://ssgmobile.github.io/api/room/detail/0004.json](https://ssgmobile.github.io/api/room/detail/0004.json) | Returns the name, location and various facilities offered by room with identifer key = 0004

### Task requirements

Try to ensure the following requirements have been met but spend no more than 2 hours working on the exercise.

- Please complete the user story below.
- Your Android Studio Project should compile and run in one step.
- Feel free to use whatever frameworks / libraries / packages you like.
- You must include tests
- Please avoid including artifacts from your local build (such as apk or the bin folder(s)) in your final ZIP file

### User Story
**As** an employee looking for a room, **I want to** be able to see a list of rooms **so as to** easily check their details and decide what room I'm looking for. 
 
#### Acceptance Criteria:
**Given** I see the list of rooms
**Then** I can see the friendly name of each room and their seating capacity and their thumbnail image
**And** the list is alphabetically ordered by the room's friendly name.
 
**Given** I tap on one of the rooms
**Then** I can see the details of the room, including the main image as an hero image, its friendly name, location, capacity, equipment, features and services
**And** I can see the icons that represent each facility offered by the room.
 
**Given** I am seeing the details of a room
**When** I tap back
**Then** I can see the list of rooms again.

### Technical questions

Please answer the following questions in a markdown file called Answers to technical questions.md.

- What would you add to your solution if you had more time?
- How would you tackle accessibility in your app?
- What steps would you take to ensure the display of text, buttons etc remain consistant as the project grows and more team members join the team?
- How would you track down a performance issue in production? Have you ever had to do this?


Thanks for your time, we look forward to hearing from you!
