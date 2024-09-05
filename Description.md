Inspire Academy Quiz is a mobile application designed to provide users with a fun and educational quiz experience focused on General Knowledge. Built using React Native and powered by Firebase for online storage, this app offers users a platform to test their knowledge through multiple-choice questions, track their progress, and save their quiz results.

Key Features:
User Signup & Authentication: Users can sign up with email, password, username, contact number, and Easypaisa account information. Firebase Authentication is used to manage user data securely.
Profile Management: Users can update their profile details anytime through the app.
100 Medium Difficulty Questions: The app reads from a local JSON file containing 100 General Knowledge questions.
Multiple-Choice Format: Questions are displayed one by one, with shuffled options for each question to ensure randomness.
Quiz Timer: A 20-second countdown timer is provided for each question, with a 5-second warning before auto-advancing to the next question.
Progress Tracking: Users' answers and progress are saved, and their results are stored in Firebase Firestore.
Clean UI/UX: The app provides a user-friendly, modern interface that makes the quiz experience enjoyable and easy to navigate.
Technology Stack:
React Native: For cross-platform mobile app development.
Firebase Authentication & Firestore: For user authentication and storing quiz results and user profiles.
AsyncStorage (or Firebase): For tracking quiz progress and local data storage.
How to Use:
Sign Up: Create an account using your email and password.
Start Quiz: On the landing screen, click the "Start Test" button to begin your quiz journey.
Answer Questions: Answer each multiple-choice question within the given time limit.
View Results: Submit your answers after completing the quiz, and view your results.
