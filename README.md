# Workshop3---G2


## Topic: Mobile app for planning/sharing trips

#### Group members: Shreya, Jui SachinKumar Parikh, Viet Pham, Razan Nayef, Melvin Ancheta

### 1. Describe the problem
1. Traveling can be an exciting experience, but the planning process can often feel overwhelming. Gathering information, booking accommodations, and organizing activities can be a disorganized and time-consuming task. Sharing itineraries with friends and family can also be unmanageable, leading to chaos and overlooked details.
   
2. The collection and storage of personal information, such as travel itineraries and location data, can leave users vulnerable to data breaches and misuse. Additionally, these apps often lack flexibility, especially when dealing with unexpected changes or limited internet connectivity. Some apps even employ deceptive user interface design to encourage users to upgrade to premium versions, which can be seen as a manipulative tactic. Finally, language barriers and lack of personalization can make it difficult for users with diverse needs or preferences to fully utilize these apps.


### 2. Propose a solution
1. Our mobile app could make planning and organizing trips much easier. It would allow users to gather all the important details, like flight information, hotel bookings, and other activities, in one place. Users would be able to create day-by-day plans and add everything they need for their trip. The app would also connect to services like booking websites and maps, so users can find and book things without leaving the app.
   
   The app would also have a feature to share trip plans with friends and family. Users could share their travel plans and even allow others to help edit or suggest  changes. This would keep everyone organized and avoid confusion. The app would send reminders and notifications so that users never miss a detail.

2. In order to keep the collection and storage of personal information safe, we will use end-to-end encryption in transit and at rest to keep important information secured, in case a data breach does happen. In terms of advertisement on the app, the user has the option to opt-in on personalized ads or ad-free experience, without the need of any premium upgrade or subscription. In terms of language barriers and personalization, the app will offer multi-language options to value the users needs around the world.

   
### 3. List the technologies required by the solution
1. Mobile development framework (e.g., React Native, Flutter) to build the app's user interface and functionalities.
2. Mapping APIs (e.g., Google Maps) for trip visualization and navigation.
3. Cloud Storage: Services like AWS or Google Cloud to store and back up data.
4. Push notifications: Firebase cloud Messaging(FCM) or Apple Push notification or pushwoosh to recieve notification on any platform
5. Cookies: Used to enchance personalized ads, if opted-in
6. Language Translation APIs: To automatically translate the user's content to their preferred language
7. End-to-end encryption (E2EE): Encrypts data when sharing important information directly to friends and/or family
