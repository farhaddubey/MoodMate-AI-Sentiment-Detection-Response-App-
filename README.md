# Project Name: MoodMate AI- Sentiment Detection & Response App
# Mentor: Dr. PSD 
# Developed for: Sister Nivedita University as Final Year Project.

Description
MoodMate is a cross-platform app developed using Flutter for Android, iOS, and Web that analyzes user emotions from text, voice, and facial expressions. The app then responds with personalized funny jokes, poems, and supportive words based on the detected sentiment. It integrates advanced sentiment analysis models using NLP and AI, ensuring a delightful and engaging user experience across all platforms. The project leverages Firebase for backend services, TensorFlow Lite for sentiment detection, and Google's Speech-to-Text API for voice analysis, making it a robust and scalable solution for emotion-driven interactions.
A new Flutter based AI project.


1. Planning and Architecture of our Project: 
   Platforms: Developed the app using Flutter for Android, iOS, and Web to ensure cross-platform compatibility.
   Core Features:
   Sentiment Analysis: Detect and classify emotions from text, voice, or facial expressions.
   Response Generation: Based on the detected sentiment, reply with jokes, poems, or supportive words.
   User Interface: Create an engaging and intuitive UI that allows users to interact seamlessly across platforms.
2. Development Steps
   Setting Up the Development Environment

Install Flutter SDK and set up Android Studio or Visual Studio Code.
Used Firebase or AWS for backend services like authentication, database, and storage.
Implement Sentiment Analysis

Text-Based Sentiment Analysis:
Used libraries like flutter_text_recognition for text detection and NLP models (e.g., BERT, SentimentAnalyzer) for sentiment classification.
Voice Sentiment Analysis:
Used packages like flutter_speech_recognition or integrate Google's Speech-to-Text API.
Analyzed the sentiment of the transcribed text using an NLP model.
Facial Expression Sentiment Analysis:
Integrated models like flutter_opencv or use a custom model with TensorFlow Lite to detect emotions from facial expressions.
Content Response Generation

Jokes and Poems Database:
Created or integrated a database of jokes, poems, and supportive phrases categorized by emotion (e.g., happiness, sadness, anger).
Dynamic Response:
Implemented logic to fetch and display content based on detected sentiment.
Considered using an AI model like GPT-3 for generating dynamic content.
UI/UX Design

Designed a user-friendly interface using Flutter's widget system.
Ensured that the app is responsive and looks good on mobile, tablet, and web platforms.
Testing

Tested the app across all platforms (Android, iOS, Web) using tools like Flutter's flutter_test.
Conducted user testing to refine sentiment analysis accuracy and content relevance.
Deployment

Deployed the mobile app to Google Play Store and Apple App Store.
Deployed the web version on platforms like Firebase Hosting or AWS Amplify.
Maintenance and Updates

Regularly updateed the joke, poem, and supportive content database.
Monitored sentiment analysis performance and refine models as needed.

Tools and Technologies
Flutter: For cross-platform app development.
Firebase: For authentication, database, and hosting.
TensorFlow Lite: For integrating pre-trained sentiment analysis models.
Dart: Primary programming language for Flutter.
Google Cloud Speech-to-Text API: For voice recognition.
OpenCV or Flutter Face Detection Plugins: For facial emotion recognition.
By following these steps, you can develop an app that provides personalized, emotion-based content to users, creating a positive and engaging experience.




