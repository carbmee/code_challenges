# carbmee-coding-challenge

Welcome to the carbmee coding challenge, the goal of the challenge is to assess your coding style, how you approach problems and your familiarity with the technologies we use or ability to learn them.

## The challenge

In this challenge you are requested to implement a basic TODO app.

### Readme

Please provide a readme with the repo that shows how you can run the application along with:

- Description of the problem and solution.
- Whether the solution focuses on back-end, front-end or if it's full stack.
- Reasoning behind your technical choices, including architectural.
- Trade-offs you might have made, anything you left out, or what you might do differently if you were to spend additional time on the project, or what you could improve in the future or problems with current implementation.

### Frontend specifications

Create a responsive web application, which upon load shows a list of tasks fetched from the backend or some data layer, the application should allow the user to:

- Add a new task
- Delete a task
- Mark a task as completed

Optional / Bonus points:

- Use as many technologies as you can / are familiar with from our tech stack; ReactJS, hooks, GraphQL, TypeScript, TailwindCSS
- allow the user to edit an existing task
- add a checkbox to filter out (on server-side) the tasks that have been completed
- use pagination/infinite scrolling for the list of tasks
- allow the user to search through tasks (instant search) avoiding making too many network requests on each key stroke
- Tests

### Backend specifications

Create a NodeJS server that exposes a REST or a GraphQL API covering the actions described above allowing the user to:

- Add a new task
- Delete a task
- Query/Fetch tasks
- Mark a task as completed

Optional / Bonus points:

- Use as many technologies as you can/know from our tech stack; TypeScript, NestJS, GraphQL (We use code-first approach with NestJS), Mongoose, Express or Serverless (in which case please provide a url to the deployed api in your submission)
- Allow the user to filter out TODOs by providing a search query and/or whether it has been completed or not
- Implement server side pagination all the way through the database
- Tests

### Data layer

For the scope of this challenge you can use any type of data layer (variables, in-memory database, etc...). In case you choose to use variables, try to shape them as they would represent database tables.

Optional / Bonus points:

- use MongoDB or PostgreSQL as a database, preferrably Mongo
- use a docker container for running the db
- If you're only doing the frontend challenge, you can use [json-server](https://github.com/typicode/json-server) or [json-graphql-server](https://github.com/marmelab/json-graphql-server) as your backend if you want to do requests against a real API as opposed to inmemory variables/localStorage.

## Submission

You can submit the code using a zip file (without `node_modules`), or providing a GitHub repo link. In case you have any doubts or questions, feel free to contact us.

if you already have more code that you're proud of and would like to share with us, please send us the links with your submission.

## How we review

We do take into consideration your experience level & seniority. We value quality over feature-completeness. It is fine to leave things aside provided you call them out in your project's README. The goal of this code sample is to help us identify what you consider production-ready or shippable code and get a better understanding of your skill-set & strengths. You should consider this code ready for final review with your colleague, i.e. this would be the last step before deploying to production.

The aspects of your code we will assess include:

- Architecture: how clean is the separation between the front-end and the back-end and how simple, reusable, configurable & maintainable are the components of the system & file/code structure?
- Clarity: does the README clearly and concisely explains the problem and solution? Are technical tradeoffs or caveats explained?
- Correctness: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
- Code quality: is the code simple, easy to understand, maintainable, reusable and communicates the intentions of what the code does well? Are there any code smells or other red flags? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
- Security: are there any obvious vulnerabilities?
- Testing: are there any tests? Will they be difficult to change if the requirements of the application were to change? Are there some unit and some integration tests?
We're not looking for full coverage (given time constraint) but just trying to get a feel for your testing skills, you don't have to write too many.
- UX: is the web interface understandable and pleasing to use? is it responsive across different devices? Is the API intuitive?
- Performance: Is the application fast enough and make use of best practices, avoidance of unnecessary re-rendering and/or unnecessary work? is it cache-able?
- Technical choices: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application? We appreciate a good reasoning and discussions about different architectures, technologies and the pros & cons of each from your perspective and your personal preferences in a follow-up interview.
- Production-readiness: does the code include monitoring? logging? proper error handling or validation?