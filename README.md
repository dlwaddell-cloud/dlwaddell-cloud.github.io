Birmingham Dart League Score Sheet
This repository contains the front-end code for the official Birmingham Dart League score sheet, designed to simplify scorekeeping for league matches. It allows teams to digitally record game scores, calculate totals, and submit results for tracking and analysis.

Features
Intuitive Score Entry: Easy-to-use input fields for various game formats (Singles 501, Singles Cricket, Doubles 301, Doubles Cricket, Team Vulcan Cricket / 701).

Dynamic Team Selection: Select Away and Home teams from a predefined, alphabetically sorted list of league teams using dropdown menus.

Dynamic Player Labels: The "Away Team Player" and "Home Team Player" labels automatically update to reflect the selected team names, providing a personalized experience.

Player Name Visibility Toggle: For each game section, buttons allow users to hide or show player name input fields for both Away and Home teams, useful for focusing on score entry or for privacy.

Automatic Score Calculation: Points for each game type are automatically totaled, and a grand total for both Away and Home teams is displayed at the top.

Score Submission: A "Submit Scores" button sends the recorded game data to a Google Apps Script backend (configured separately) for data collection.

View Live Scores: A "View Scores" button provides a direct link to a Google Looker Studio dashboard, allowing users to see submitted scores and league statistics in real-time.

Responsive Design: The layout is designed to be user-friendly and adaptable across various devices, from mobile phones to desktop computers.

How to Use
Select Teams: At the top of the page, use the "Select Away Team" and "Select Home Team" dropdowns to choose the participating teams. The player labels in each game section will update accordingly.

Enter Player Names (Optional): In each game section, enter the names of the players participating in that specific game.

Record Points: For each player in each game, enter 0 if they lost the game or 1 if they won the game. The system will automatically calculate the totals for each game and the grand totals for each team.

Submit Scores: Once all scores are entered and verified, click the "Submit Scores" button at the top right of the page. A message will confirm successful submission or indicate an error.

View Scores: To see all submitted scores and league statistics, click the "View Scores" button at the top left of the page. This will open the league's Looker Studio dashboard in a new tab.

Technical Details
Frontend: The website is built using plain HTML, CSS (with Tailwind CSS for utility-first styling), and JavaScript.

Backend (Google Apps Script): Score submissions are handled by a Google Apps Script Web App. This script receives the form data and typically logs it to a Google Sheet, which then feeds into the Looker Studio dashboard.

Data Visualization (Google Looker Studio): The "View Scores" link directs to a Google Looker Studio report that visualizes the submitted data.

Note: The GOOGLE_APPS_SCRIPT_URL in the JavaScript code needs to be replaced with your actual deployed Google Apps Script Web App URL for submissions to work.

Future Enhancements
Player Roster Integration: Auto-populate player names based on selected teams.

Error Handling: More robust client-side validation for score entry.

Offline Capability: Implement local storage to allow scorekeeping even without an internet connection, with synchronization upon reconnection.

Authentication: Add user authentication to restrict submission access.
