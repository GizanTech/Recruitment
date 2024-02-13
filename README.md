# GIZANTECH MOBILE APP DEVELOPMENT INTERN RECRUITMENT TASK LIST

### Task 1: API Integration and Data Display
The task involves creating a mobile application that interacts with a provided API, retrieves data from specific URL endpoints, parses the response, and displays the retrieved data in the application's user interface using objects or classes. 

**Platform:** Native Android(Java/Kotlin) or Native iOS(Objective-C/Swift) or Cross-platform(Flutter/React Native)

**API Endpoint:** You will be using the following endpoint for this task: 
1.	http://api.aladhan.com/v1/calendar/2017/4?latitude=51.508515&longitude=-0.1254872&method=2 
    Sample response: https://aladhan.com/prayer-times-api 

**Task Details:**

Make an HTTP request to the provided API endpoint. Handle the API response, including error handling. Parse the response data into suitable objects or classes based on the response format. You can refer to the API documentation for the expected response format. Display the retrieved data in the user interface of your mobile application. You can choose the appropriate UI components for presenting the data. Implement any additional functionality or features based on your creativity and our requirements.
1.	Check sample response directly from that link or use Postman. From the response, extract timings and Hijri dates for each day of the month. For the Hijri date use a separate class in which the date, day, month, year, name of the month, and holidays will be contained. 

### Task 2: UI Implementation
In this task, you'll be provided with a UI design, and your goal is to implement it in a mobile application with maximum attention to detail.

**Platform:** Native Android(Java/Kotlin) or Native iOS(Objective-C/Swift) or Cross-platform(Flutter/React Native)

**UI Design:**

We have prepared a UI Design for you to implement in your mobile application. You can access the prototype of the design here: https://www.figma.com/proto/ueunFhbqPnifHv6YQDyCfx/Test-2?type=design&node-id=109-73&t=XbqGvMCxoDQzb5f5-1&scaling=scale-down&page-id=14%3A10&starting-point-node-id=109%3A73&mode=design

**Task Details:**

Implement the provided UI design with the highest accuracy, ensuring that every element, spacing, font, color, and other design aspects match the provided design specifications as much as possible. Utilize the appropriate UI components, layouts, and styles to bring the design to life. Pay close attention to responsiveness and adapt the design to different screen sizes and orientations if necessary. Implement any additional functionality or features based on your creativity and our requirements, keeping in mind that the primary focus is on the UI implementation.
#### KEEP IN MIND THAT IT IS NOT ALLOWED TO USE PACKAGES


### Task 3.1: Bluetooth Connectivity
In this task, you need to ensure proper Bluetooth connectivity flow. 

**Platform:** Native Android(Java/Kotlin) or Native iOS(Objective-C/Swift)

**Task Details:**

When developing the application, ensure that only necessary permissions for Bluetooth are requested, starting from API level 19 up to the latest API version for Android and from 11 to the latest version for iOS. Avoid requesting unnecessary permissions and only prompt for permission when it is required. The primary focus should be on maintaining the flow of Bluetooth within the app. Implement scanning, discovery, and pairing functionalities within the app and the necessary user interface. The user interface doesn’t need to have an aesthetically pleasing appearance.

### Task 3.2: Package Development

**Platform:** Cross-platform(Flutter/React Native)

**Task Details:**

Develop a basic package that communicates with the native side for both Android and iOS, such as a battery level reader.


For task submission, create separate repositories for each project on GitHub and utilize distinct branches for each platform. Add the following email addresses as collaborators: "admin@gizantech.com" and "nam.cse.ruet@gmail.com". Ensure that the code can run smoothly.

In case of any queries, you can create an issue here.
 
