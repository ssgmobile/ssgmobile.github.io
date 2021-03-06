## SmartSpace Global Android Technical Challenge

Thank you for taking the time to do our technical challenge. It consists of two parts:

- [Create a small Kotlin Android application](#create-a-small-kotlin-android-application)
- [A few technical questions](#technical-questions)

Please upload your solution to GitHub and send the link to Jeff.Kania@fwi.com

The zip file should contain:
- a single markdown file with the answers to the technical questions
- one folder containing your Android Studio project & source code.

# Create a small Kotlin Android application

Smartspace Global has a set of mock APIs that you will use to get information about a list of Meeting Rooms in a building belonging to a fictious client. 

API | Purpose
------------ | -------------
[https://ssgmobile.github.io/api/room/rooms.json](https://ssgmobile.github.io/api/room/rooms.json) | Returns a list of meeting rooms in a building.
[https://ssgmobile.github.io/api/room/detail/<%room_key%>.json](https://ssgmobile.github.io/api/room/detail/0001.json) | Returns the name, location and various facilities offered by room with the given key. 

### Task requirements

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met.

- Please complete the user story below.
- Your Android Studio Project should use Kotlin and compile & run in one step.
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
- What steps would you take to ensure the display of text, buttons etc remain consistant as the project grows and more team members join the team?
- How would you track down a performance issue in production? Have you ever had to do this?


Thanks for your time, we look forward to hearing from you!
