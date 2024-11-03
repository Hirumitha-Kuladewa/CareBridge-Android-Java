# CareBridge 📱🤝

CareBridge is an Android application built in Java with Firebase, designed to facilitate urgent donations and requests for essential items. The app connects donors willing to provide items with those in need, aiming to simplify and accelerate the process during emergencies. With an intuitive interface, real-time updates, and a secure login system, CareBridge empowers users to make a difference in their communities.

## Key Features

- 🔒 User Authentication
  - Secure login and sign-up with Firebase Authentication.

- 📝 Donor & Requester Forms
  - Donor Form: Allows users to list items they want to donate, specifying type, quantity, and condition.
  - Requester Form: Enables users to create requests with details on the needed item, urgency, and delivery preferences.
  - Data is securely stored in Firebase for real-time updates.

- 📊 Data Visualization
  - Pie Chart: A visually engaging pie chart displays donation and request statistics, such as item types and donation/request counts.
  - Provides insights into the types of items most frequently requested and donated, helping donors make informed choices.

- 🔔 Notification System
  - Real-time notifications using Firebase Cloud Messaging (FCM) to alert users of new requests, donations, and fulfilled requests.
  - Notifications for high-urgency items ensure that critical needs are prioritized.

- 📂 Donation and Request Tracking
  - Donors can view requests and respond to them, while requesters can track the status of their requests.

## Tech Stack
- Language: Java
- IDE: Android Studio
- Backend: Firebase (Authentication, Firestore/Realtime Database, Cloud Messaging)
- Charting: MPAndroidChart (for pie chart visualization)
