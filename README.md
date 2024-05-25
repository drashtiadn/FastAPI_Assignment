FastAPI Simple Quiz API

In this FastAPI assignment, you'll be creating simple quiz APIs.

Create 2-3 quizzes, each with three multiple-choice questions.

Each question should have a statement and a list of options (A, B, C, D, etc.).

Store quiz data in Postgres DB

API Endpoints (Below are just examples you should be creating your own as per best practices):

GET /quizzes: Retrieve a specific quiz. Return the quiz questions and options.
POST /submit: Allow users to submit their quiz answers. Should include the user's answers.
GET /result: Return the quiz result for a specific quiz, showing the user's score and the correct answers.
Validation and Error Handling:

Validate user input to ensure they select valid options.
Handle errors gracefully and provide meaningful error messages in the API responses.
 

---------------------------

Submission

Submit the URL of your GitHub repository.

Evaluation Criteria

1 point for creating the server with FastAPI 
1 point for creating the routes (total 3 points) 
2 points for Database connection
2 points for validation and error handling
2 points for code cleanliness and best practices
