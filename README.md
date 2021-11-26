# Four Winds Interactive (FWI) / SmartSpace Global (SSG) Mobile Technical Challenge

Thank you for taking the time to do our Mobile Technical Challenge.  

The challenge consists of two parts:  

- [Creating a small demo application](#create-a-small-demo-application)  
- [Answering a few technical questions](#technical-questions)  

When you're done, please upload your solution to GitHub and send the link to your FWI/SSG contact or recruiter  

The zip file should contain:  
- a single markdown file (called `answers-to-technical-questions.md`) with the answers to the technical questions  
- one folder containing your project & source code  

_Note: please avoid including artifacts from your local build (such as apk/ipa/etc) in your final zip file_

Many thanks for your time. We look forward to hearing from you!  

## Create a Small Demo Application

For the purposes of this Mobile Technical Challenge, SSG has created a mock API consisting of two endpoints which return data for a fictitious client.

API | Purpose
------------ | -------------
[https://ssgmobile.github.io/api/room/rooms.json](https://ssgmobile.github.io/api/room/rooms.json) | Returns a list of meeting rooms in a building.
[https://ssgmobile.github.io/api/room/detail/<%room_key%>.json](https://ssgmobile.github.io/api/room/detail/0001.json) | Returns the name, location and various facilities offered by room with the given key. 

### Task requirements

Using the mock API for data, please build a simple demo app that addresses the user story below. You're free to spend as much or as little time on the app as you like, as long as the following requirements are met:  

- The user story is fulfilled
- For Android candidates, your Android Studio project should use Kotlin  
- For iOS candidates, your Xcode project should use Swift and/or Swift UI  
- Your project should compile & run in one step  
- You must include at least one test  

_Note: You're free to use whatever frameworks/libraries/packages you'd like to complete the task_  


### User Story
**As** an employee looking for a room, **I want to** be able to see a list of rooms **so as to** easily check their details and decide what room I'm looking for. 
 
### Acceptance Criteria:
**Given** I see the list of rooms
**Then** I can see the friendly name of each room and their seating capacity and their thumbnail image
**And** the list is alphabetically ordered by the room's friendly name.
 
**Given** I tap on one of the rooms
**Then** I can see the details of the room, including the main image as an hero image, its friendly name, location, capacity, equipment, features, and services
**And** I can see the icons that represent each facility offered by the room.
 
**Given** I am seeing the details of a room
**When** I tap back
**Then** I can see the list of rooms again.

## Technical questions

Please answer the following questions in a markdown file called `answers-to-technical-questions.md`.

- What would you add to your solution if you had more time?
- Did you use any third party libraries to complete the task? If you did, what was the reason for including them?
- What steps would you take to ensure the UI scales well over different device sizes?
- What accessibility features should be supported as a minimum in a modern application?
- Have you ever had to track down a performance issue in a production app? What did you have to do?

