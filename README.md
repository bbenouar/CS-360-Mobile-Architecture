# CS-360-Mobile-Architecture
#Requirements and Goals of the App.

The Weight Tracking App was designed to help users monitor their daily weight and track changes over time. The primary user needs addressed by this app are:
1.	Track Weight: Allow users to enter their daily weight and view historical data.
2.	Data Persistence: Ensure that data is saved and not lost when the app is closed.
3.	Visualize Data: Provide a way to visualize weight data in a structured format.
4.	User Registration and Authentication: Securely register users and allow them to log in to access their data.
5.	Permission Handling: Request and handle necessary permissions, such as SMS permissions.

#Necessary Screens and Features.

To support these needs and create a user-centered UI, the following screens and features were developed:
1.	Login Screen: For user authentication.
2.	Register Screen: For user registration.
3.	Data Display Screen: Main screen for entering and viewing weight data, including an option to clear selected items.
4.	Weight Log Screen: Displays historical weight data in a tabular format.
5.	SMS Permission Screen: Requests SMS permissions from the user.

#UI Design Considerations.

•	Simplicity: The UI was kept simple and intuitive, ensuring ease of navigation.
•	Consistency: Consistent use of colors, buttons, and fonts to create a cohesive experience.
•	Feedback: Providing users with immediate feedback (e.g., toasts) on their actions like successful registration or error messages.
•	Accessibility: Ensuring elements like text and buttons are appropriately sized and accessible.
The designs were successful because they focused on user ease of use, ensuring that the app was both functional and aesthetically pleasing.

#Approach to Coding.

•	Modular Development: Breaking down the app into smaller, manageable modules (e.g., separate activities for login, registration, and data display).
•	Database Management: Using SQLite for data persistence to store user and weight data.
•	RecyclerView: Implementing RecyclerView to efficiently display weight data.
•	Lifecycle Management: Proper handling of activity lifecycle methods to ensure smooth transitions and data integrity.
•	Permissions Handling: Ensuring permissions are requested and handled appropriately.
These techniques ensured a structured and maintainable codebase, which can be applied in future projects for similar benefits.

#Testing Process.

•	Unit Testing: Testing individual components like database operations.
•	Integration Testing: Ensuring different parts of the app work together seamlessly.
•	Manual Testing: Running the app on an emulator and physical devices to check for UI consistency and functionality.
Testing is crucial as it reveals bugs and ensures that the app works as intended across different scenarios. It helped identify issues with data persistence, UI layout, and permissions handling.

#Innovation and Challenges.

A significant challenge was ensuring data persistence and handling user permissions smoothly. Innovating around the use of SQLite for data storage and managing Android’s permission system effectively was key. Additionally, ensuring the UI was responsive and adjusted to different screen sizes required thoughtful design.

#Demonstrating Knowledge, Skills, and Experience.

The successful integration of the SQLite database for persistent data storage was particularly notable. This component demonstrated knowledge of database management, SQL queries, and data handling in an Android environment. Additionally, the effective use of RecyclerView to manage and display dynamic data lists showcased proficiency in creating efficient and user-friendly interfaces.
