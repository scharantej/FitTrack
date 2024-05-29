### Flask Application Design
#### HTML Files
- **exercise_tracker.html**: This file will serve as the main interface for users to track their daily exercise. It will include a form that allows users to enter details about their workout, such as exercise type, duration, and intensity.

#### Routes
- **@app.route('/'):** This route will handle the rendering of the `exercise_tracker.html` file, displaying the form for users to input their exercise information.
- **@app.route('/submit_exercise', methods=['POST']):** This route will be responsible for processing the submitted exercise details from the form in `exercise_tracker.html`. It will save the data in a database or appropriate data structure for later retrieval and analysis.
- **@app.route('/view_exercise_log'):** This route will handle the display of a log or summary of the user's previously recorded exercise sessions. It will provide a way for users to view their progress and monitor their exercise habits.