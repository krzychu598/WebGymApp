# Business requirements:
1. Allowing users to optimize their training plan.
2. Provide data for customers to monitor their performance and see their progress.
3. The  app should be easy to use and engaging.
4. Nice looking  visual layer.
5. Suggested trainings need to fit each user's skills.

# User requirements
1. The user can see their workout progress.
2. The user can input their exercises in the app.
3. The user is able to define their workout schedule. 
4. The app suggests optimal workout schedule.
5. The user is able to create workout plan based on muscle parts they want to improve.
6. The user is able to see summary of their previous workouts.
7. The user should be aided in achieving their specific goals.

# System requirements
1. The personal data is stored safely and securely in the database.
2. The app should display graphs about weight, feelings after the workout, frequency of training
3. The app shows how the exercise should be done.
4. The app shows schedule interface.
5. The app makes sure the payments are made correctly.
6. The main algorithm should suggest exercises based on the user data.
7. The app should have interface for inputting data after workout.
8. The app provides different schedules and ability to change them.

## Functional Requirements

1. **Registration and authorization:** The user can create an account, log in, and reset a forgotten password.
2. **User profile:** The user can enter and edit basic data and specify their training goal and fitness level.
3. **Muscle group selection:** The user can define which muscle groups they want to focus on developing in a given training cycle.
4. **Schedule preferences:** The user can specify preferred training days and hours during the week.
5. **Workout generation algorithm:** The system automatically generates a personalized training plan based on the entered data, goals, and muscle preferences.
6. **Workout schedule:** The app displays the training plan in the form of an interactive calendar.
7. **Schedule modification:** The user has the ability to manually change the generated plan.
8. **Exercise library:** The app contains an exercise database along with execution instructions.
9. **Result logging:** After a workout, the user can input data about the completed exercises.
10. **Workout history:** The user has access to a full history of completed workouts with performance summaries.
11. **Weight charts:** The app generates visualizations showing changes in the user's body weight over time.
12. **Frequency charts:** The app presents statistics regarding training regularity.
13. **Custom exercises:** The user can add their own custom exercise to their personal database if it is not available in the system library.
14. **Specific goals:** The user can define a specific goal, and the system will assign a progress bar to it.


## Non-Functional Requirements

1. **Plan generation time:** The main algorithm must generate and return an optimized training schedule in less than 3 seconds from the moment the request is sent.
2. **Database encryption:** Sensitive user data must be stored in the database using modern hashing algorithms.
3. **Data isolation:** The backend architecture must strictly verify authorization tokens with every request, ensuring that a user has no access to the data of other users.
4. **Connection security:** All communication between the client app and API servers must take place via the encrypted HTTPS protocol.
5. **Usability:** The interface must be intuitive to the point that a new user can input data from their first workout in less than 90 seconds.
6. **Testability:** Key business logic must be covered by unit tests.