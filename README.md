# Online-Test-Application

#Overview

This project is a real-time Online Test Application built using HTML, CSS, JavaScript, and Firebase. It features user authentication and authorization for secure access and allows users to participate in quizzes with multiple subjects. The app also includes functionality for password recovery with OTP-based authentication.
![Screenshot 2024-11-22 120841](https://github.com/user-attachments/assets/4c377803-0d88-459b-8e2f-8abf189a782c)

#Features
User Authentication: Sign-up, login, and forgot password functionality using Firebase Authentication.
OTP-based Password Reset: Users can reset their passwords securely through an email-based OTP system using EmailJS.
![Screenshot 2024-11-22 120912](https://github.com/user-attachments/assets/e40b7a31-dc59-42ba-bbad-c708d64d8569)
![Screenshot 2024-11-22 120953](https://github.com/user-attachments/assets/b68d5c77-facf-4aa3-a0fe-50c7f021dfb0)

#Quiz Management:
Multiple-choice questions organized by subject.
Question navigation and clear selection functionality.
Real-time tracking of marked answers by subject.
Countdown timer for quiz completion.
![Screenshot 2024-11-22 121114](https://github.com/user-attachments/assets/20a8b6ef-406d-4cfc-8bfd-bbb0cb7845df)

User Progress:
Local storage is used to track user sessions.
Responses are recorded and can be submitted for evaluation.
Responsive Design: The app is designed to work seamlessly on various screen sizes.
#Tech Stack
Frontend: HTML, CSS, JavaScript
Backend Services: Firebase Authentication, Firestore
Email Service: EmailJS for OTP-based email communication
Deployment: Firebase Hosting
Installation
Clone the repository:

git clone https://github.com/shashihere1/online-test-application.git
Navigate to the project folder:
cd online-test-app
Set up Firebase:

Go to Firebase Console and create a new project.
Enable Authentication and Firestore Database.
Replace the Firebase configuration in index.html and quiz.html with your Firebase project's credentials.
Set up EmailJS:

Create an account on EmailJS.
Create a service and a template for OTP emails.
Replace the service ID, template ID, and public key in the script with your EmailJS credentials.
Open index.html in your browser to run the application.

Usage
Sign Up:
Create an account by entering your email, password, and username.
Login:
Log in to access the quiz dashboard.
Forgot Password:
Use the forgot password feature to reset your password via OTP.
Attempt the Quiz:
Navigate through the quiz questions, select answers, and clear selections if needed.
Submit your quiz once completed.
Track Progress:
See your answer progress across subjects during the quiz.
Project Structure
graphql
Copy code
online-test-app/
│
├── index.html          # Landing page with user authentication
├── quiz.html           # Quiz interface
├── styles/             # CSS files for styling
├── scripts/            # JavaScript files for app logic
├── assets/             # Images and other static assets
└── README.md           # Documentation
Screenshots
Authentication Page

Quiz Interface

#Future Enhancements
Add real-time results evaluation.
Include question categories with difficulty levels.
Implement leaderboards to display user scores.
Enable multi-language support.
License
This project is licensed under the MIT License.

#Contributions
Contributions are welcome! If you'd like to contribute, feel free to fork the repository and submit a pull request.

#Contact
If you have any questions or need support, feel free to reach out via mail2shashi123456@gmail.com.
