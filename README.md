# CS 360 - Mobile Architecture & Programming

### Overview

*"You have recently been hired as the newest member of the mobile application development team for the Mobile2App Company. Every week, your team meets to discuss the latest client projects that have been sent in and to assign the work. There are three available projects that both you and the rest of the team feel would be a good fit for your expertise. This means you may select which application you would like to work on. Your options are an inventory app, an event tracking app, and a weight tracking app."*

**Option 2: Event Tracking App** \
This application will be used to track the dates and times of upcoming events. This application must include the following:

1. A database with at least two tables, one to store the event details and one to store user logins and passwords
2. A screen for logging into the app. Note that this should also be used to create a login if the user has never logged in before
3. A screen, with a grid, that displays all upcoming events
4. A mechanism by which the user can add and remove events from the database
5. A mechanism by which the user can enter the time and general information of a specific event
6. A mechanism by which the application will notify the user on the day that an event has been scheduled

### Tools Used

Android Studio - (https://developer.android.com/studio) \
*Designed and tested on an emulated Pixel 4 XL, and on a Samsung Galaxy S9+*

## Questionnaire

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
Per the requriements, this app is an event tracker, and is designed to allow for user login functionality, as well as CRUD functionality for data stored within the SQLite databases for both user information, and event information. 

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The app allows for user registration, login, and a forgot password option:

<img src="https://user-images.githubusercontent.com/79807877/154996587-55aa97bb-7b0a-4813-bed3-5f82adfafe76.jpg" width=200> <img src="https://user-images.githubusercontent.com/79807877/154997117-f0bc297e-e054-4775-95c2-91be69f8623c.jpg" width=200> <img src="https://user-images.githubusercontent.com/79807877/154997144-6c3afddb-1be1-48ca-a554-b637f9f9629e.jpg" width=200>

The primary function of the app as an event tracker allows a user to add, edit, and delete data, giving CRUD functionality between the user and the SQLite database housing the data: 

<img src="https://user-images.githubusercontent.com/79807877/154997398-c440a07c-77c3-44ce-9326-1a4720c4d783.jpg" width=200> <img src="https://user-images.githubusercontent.com/79807877/154997498-8cd8cb08-7953-4813-b6c7-20f6a14a7a7b.jpg" width=200> <img src="https://user-images.githubusercontent.com/79807877/154997553-24ed3bc0-e6eb-44ca-ab30-0ea5127528da.jpg" width=200>

### How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
I used coding best practices, simplified code structure to keep it legible and clean, used logical naming conventions, and commenting to explain portions of code. For example, I commented on the strings.xml, separating them by their respective purpose or screen, as shown below:

<img src="https://user-images.githubusercontent.com/79807877/154995501-9bfcce48-ebc6-4f43-a335-a92844e36df8.png" width=650>

I also cleaned up the structure of the Java files so that they are easy to navigate:

![Screenshot_5](https://user-images.githubusercontent.com/79807877/154995604-e5eac7c4-56d3-4606-96e2-7df24d134102.png)

### How did you test to ensure your code was functional? Why is this process important and what did it reveal?
Testing, especially regarding UI design and structure, was done from a phone, and adjusted in real time. With this method, I could use a physical phone, similarly to a user, and make small UI adjustments, and code adjustments, in order to create a better user experience, and a more visually appealing app.

### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
In designing the UI of the app, I had to make various changes to the design, in order to create something that I felt was more in line with the requirements and goals of the project. My initial design evolved as I better grasped the material, and the process of developing an app. This is especially true once I began using a physical phone, which helped to better understand the end result from the perspective of a user.

### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The login functionality, as well as its ability to make use of stored user data within the SQLite database, was a success in my eyes. It allows for multiple users, properly stored user data that can be logged back into, cannot be duplicated, and allows for a user to retrieve a password with more than one requesting form of information. This creates a semblance of security, but also a more feature rich part of the app.

## Contact
Brandon Ricks \
brandon.ricks@snhu.edu
