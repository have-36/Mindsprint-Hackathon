Smart Mental Health Journal
A web-based, intelligent journaling application designed to help users track their mental well-being through AI-powered sentiment analysis and data visualization. This app provides personalized insights by identifying emotional trends and key topics from daily entries.

✨ Features
📝 Daily Journaling: A clean and simple interface to write and save daily thoughts.

🤖 AI-Powered Analysis: Utilizes the Google Gemini API to automatically analyze each entry for:

Sentiment Score: (-1.0 to 1.0) to gauge the emotional tone.

Key Topics: Extracts the main subjects of the entry.

📊 Sentiment Trend Chart: Visualizes your sentiment scores over time, helping you identify long-term patterns.

😊 Mood Selector: Record how you're feeling before writing with a simple emoji-based selector.

💡 Prompt Generator: Feeling stuck? Get inspirational prompts to kickstart your writing.

🗓️ Mood Heatmap Calendar: A calendar view that color-codes each day based on the average sentiment of your entries, offering a quick visual summary of your month.

🔥 Streaks Tracking: Stay motivated by tracking your daily writing streak.

☁️ Topic Word Cloud: A dynamic word cloud that visually represents the most common topics in your journal entries.

🧠 Smart Recommendations: Get context-aware, friendly suggestions based on the sentiment of your latest entry.

📜 Entry History: Review all your past entries, complete with their analysis.

🌓 Light & Dark Mode: Switch between themes for comfortable viewing, day or night.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling: Tailwind CSS

Database & Auth: Google Firebase (Firestore for database, Anonymous Authentication for users)

AI/NLP: Google Gemini API

Charting: Chart.js

Word Cloud: wordcloud2.js

🚀 Getting Started
To run this project locally, you'll need to set up a Firebase project to handle the database and authentication.

Prerequisites
A Google Account for Firebase.

Git installed on your local machine.

Local Setup
Clone the repository:

git clone [https://github.com/YOUR_USERNAME/smart-mental-health-journal.git](https://github.com/YOUR_USERNAME/smart-mental-health-journal.git)
cd smart-mental-health-journal

Create a Firebase Project:

Go to the Firebase Console.

Click "Add project" and follow the on-screen instructions.

Once your project is created, go to the dashboard and click the web icon (</>) to add a web app to your project.

Register the app and Firebase will provide you with a firebaseConfig object. Copy this object.

Configure Firebase in index.html:

Open the index.html file.

Find the following line of code:

const firebaseConfig = JSON.parse(typeof __firebase_config !== 'undefined' ? __firebase_config : '{}');

Replace the empty object {} with your firebaseConfig object from the previous step. It should look like this:

const firebaseConfig = JSON.parse(typeof __firebase_config !== 'undefined' ? __firebase_config : '{"apiKey": "AIza...", "authDomain": "...", ...}');

Enable Firebase Services:

In your Firebase project console, go to "Authentication".

Click the "Sign-in method" tab and enable the "Anonymous" sign-in provider.

Go to "Firestore Database".

Click "Create database" and start in test mode for easy setup. (Note: For a production app, you would need to configure security rules properly).

Run the Application:

Simply open the index.html file in your web browser. The application should now be connected to your personal Firebase backend.

📄 File Structure
This project is contained within a single index.html file for simplicity. This includes all HTML, CSS (via a <style> tag and Tailwind CDN), and JavaScript (via a <script> tag). For a more detailed breakdown, see the file_structure.md document.

⚖️ License
This project is licensed under the MIT License. See the LICENSE file for details."# Mindsprint-Hackathon" 
