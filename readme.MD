[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=10110634&assignment_repo_type=AssignmentRepo)
## <Random Company name (pref something cool)>

Welcome to the <Cool company> coding interview.

## Our tech stack

The OP tech stack is always evolving as we continue to seek out the best tools for the job. Our main tech stack is:

- React with Redux (front-end of our main app & corner Shop)
- Gatsby (corner Shop)
- AWS Lambda with Serverless for our backend API
- Node.js for the above & our product catalog backend
- AWS DynamoDB for our main database
- Git for our product catalog storage
- AWS Cognito for our user management
- We build with Webpack
- Jest for testing
- Other AWS services for serving builds/files such as S3, Cloudfront, amongst others

And we are currently working towards introducing the following:

- React testing library to replace some of component tests
- Refactoring to use React hooks across our codebase where possible

We will continue to discuss & add new tech where we feel it would improve our products.

### Instructions

Please answer the question below (just write the answers in the spaces provided). Once the coding examples are done, please zip up your files and send them via http://wetransfer.com (GMail blocks ZIP attachments).

We can then discuss the changes that you have made.

### Overview

The directories contain 3 sample apps. They are based on the the tic-tac-toe react tutorial, which you can find at [https://reactjs.org/tutorial/tutorial.html].

The directories are:

| Directory      | Contents                                                                                                                                        |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| app-original   | The original app from the tutorial                                                                                                              |
| app-standalone | The same app, but re-written slightly (this has been updated to move away from class components and use functional components with React hooks) |
| app-redux      | The same app, using redux                                                                                                                       |

### Questions

Please answer the following questions:

1. Comparing the app-original and app-standalone code bases. The app-standalone code base has put each component in a separate file and directory structure.

   - Why do you think that was done, what are the advantages / disadvantages?

   Avantages: 
   - Separation of concerns, makes the code more readable
   - Allows more than one person working together on the same project, teamates can work different components at the same time without merge conflicts.
   - Components are reusable.

   Disadvantages:
   - You have to manage where each component is, file is also bigger and not everything is in one file.
   - Can be overwelming
   - Takes more time to send props up and down as they are not on the same level.

2. Thinking about a production ready app, what do you think is missing from all the examples? _Hint: the square component in the standalone app has one_

  - None of the other components have been tested.

3. Are you familiar with Redux? If so what is the basic idea behind it and what would be a good case for using it?

  - Unfortunately I have never used Redux, however from my understanding, with Redux, you can manage the state of your application in a single store, making it easier to   understand the flow of data through your app.

4. _If you are interested in the full-stack role_ Please take a look at the partial implementation of an express routes in backend/router.js.
   - Thinking of a production application, what issues do you see with this code? _List as many as you like_

  - There are no error handling in the requests 
  - There are no tests for the route handling


### Coding Challenges

With either the app-standalone or app-redux (**not both** - whichever you are comfortable with), please complete the following changes:

1. Update the app so that is highlights the winning move.
2. Update the app so that it allows for a named player X and Y, and it keeps a league table of who won each game.
3. If you get time, implement something that you think that the app could do and is cool. What other things would you change.

### Expectations

- We don't want you to spend too long on this exercise, just the necessary amount of time to show your front-end and back-end skills. We expect it to take 1.5 hours if you have React experience, longer if you have no React experience.
  - If you don't answer all questions, that is fine. We prefer depth on a few questions rather than superficial answers.
- Some testing, but not extensive. Have at least one test case, so that we know you can do it.
  - You'll notice the example code doesn't have much testing. It should.
- Clean, concise code. Comments are appreciated.
- Knowledge of up to date React features e.g. Hooks.
