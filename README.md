# GIZANTECH MOBILE APP DEVELOPMENT INTERN RECRUITMENT TASK LIST

### Task 1: API Integration and Data Display
The task involves creating a mobile application that interacts with a provided API, retrieves data from specific URL endpoints, parses the response, and displays the retrieved data in the application's user interface using objects or classes. 

**Platform:** Native Java/Kotlin and Flutter

**API Endpoint:** You will be using the following endpoint for this task: 
1.	http://api.aladhan.com/v1/calendar/2017/4?latitude=51.508515&longitude=-0.1254872&method=2 
Sample response: https://aladhan.com/prayer-times-api 
2.	https://rapidapi.com/tipsters/api/hotels-com-provider/

**Task Details:**

Make HTTP request to the provided API endpoint. Handle the API response, including error handling. Parse the response data into suitable objects or classes based on the response format. You can refer to the API documentation for the expected response format. Display the retrieved data in the user interface of your mobile application. You can choose the appropriate UI components for presenting the data. Implement any additional functionality or features based on your creativity and our requirements.
1.	Check sample response directly from that link or use Postman. From the response, extract timings and Hijri dates for each day of the month. For the Hijri date use a separate class in which the date, day, month, year, name of the month, and holidays will be contained. 

2.	Use all APIs inside this and make the necessary UI and activity flow.

### Task 2: UI Implementation
In this task, you'll be provided with a UI design, and your goal is to implement it in a mobile application with maximum attention to detail.

**Platform:** Native Java/Kotlin and Flutter

**UI Design:**

We have prepared a UI Design for you to implement in your mobile application. You can access the prototype of the design here: https://www.figma.com/proto/ueunFhbqPnifHv6YQDyCfx/Test-2?type=design&node-id=109-73&t=XbqGvMCxoDQzb5f5-1&scaling=scale-down&page-id=14%3A10&starting-point-node-id=109%3A73&mode=design

**Task Details:**

Implement the provided UI design with the highest accuracy, ensuring that every element, spacing, font, color, and other design aspects match the provided design specifications as much as possible. Utilize the appropriate UI components, layouts, and styles to bring the design to life. Pay close attention to responsiveness and adapt the design to different screen sizes and orientations if necessary. Implement any additional functionality or features based on your creativity and our requirements, keeping in mind that the primary focus is on the UI implementation. KEEP IN MIND THAT IT IS NOT ALLOWED TO USE PACKAGES.


### Task 3.1: Bluetooth Connectivity
In this task, you need to make sure proper flow of Bluetooth connectivity. 

**Platform:** Native Java/Kotlin

**Task Details:**

When developing the Android application, ensure that only necessary permissions for Bluetooth are requested, starting from API level 19 up to the latest API version. AVOID REQUESTING UNNECESSARY PERMISSIONS AND ONLY PROMPT FOR PERMISSION WHEN IT IS REQUIRED. The primary focus should be on maintaining the flow of Bluetooth within the app. Implement scanning, discovery, and pairing functionalities within the app, along with the necessary user interface. The user interface doesn’t need to have an aesthetically pleasing appearance.

### Task 3.2: Flutter Channel

**Platform:** Flutter

**Task Details:**

Create a channel on the native side to get the API level. Read the API level on the Android side and show it on the Flutter side.


FOR SUBMITTING TASKS, CREATE THREE DIFFERENT REPOSITORIES IN GITHUB AND USE THE BRANCH FOR DIFFERENT PLATFORMS. MAKE SURE TO USE OOP FOR CODING AND MUST FOLLOW A PATTERN (MVVM/MVC/MVP).
