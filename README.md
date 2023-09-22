# College-Expense-Tracker
College Expense Tracker
By Darshan (dhgupta2), Drew (drew5), Daniel(dscao2), David(davidl16)
Pitch
Students often spend money without considering where or what they are spending it on. College
Expense Tracker allows students to track how much money they are spending and where they are
spending it.
Functionality
1. Users can authenticate to create their own account
2. Users can see their spending from a certain period of time (day, week, month)
3. Users can see their past spending history
4. Users can input their purchases and sort their purchases into different categories
5. Users can see their purchases across categories
6. Users can set a budget for different categories
7. Users can see if their expenses exceed their budget
Components
- Backend: We will use Python and the Flask framework. Two of our team members know
Flask, and it is lightweight to be useful in this application. The backend will receive
GraphQL queries from the frontend to communicate with the API. We’ll handle
authentication with OAuth to keep everything secure and keep GraphQL separate from
the auth flow.
- Backend Responsibilities
- Backend is responsible saving user purchase history
- Authentication
- Fetching purchase history
- The list of user accounts and everything the user enters about their purchase
history will be stored here.
We will use MongoDB for this. We can connect MongoDB and Flask with
Flask-PyMongo
- We will create schemas for users and purchases as necessary
- Frontend: We will use Typescript and React since it is lightweight, flexible, some group
members are confident with it and React components make applications easy to organize.
- Database: We will use MongoDB to store user information since it is easy to use and
quick to start up, and many of our team members have used it previously.
Weekly Planning (Darshan)
Week # (Date) Tasks
Week 1 (9/18-9/24) 1. Set up a new React project with Create React App
2. Create the basic login and registration pages using React.
3. Configure authentication logic on the frontend.
Week 2 (9/25-10/1) 1. Install MongoDB and set up initial databases.
2. Create GraphQL schemas for users, expenses, and categories.
3. Populate databases with dummy data for testing.
Week 3 (10/2-10/8) 1. Create React components for logging expenses.
2. Implement frontend routing for these components using React Router.
3. Create React components to display the list of logged expenses.
Week 4 (10/9-10/15) 1. Enhance the expense logging functionality to include categories.
2. Add a feature to view expenses by categories.
Week 5 (10/16-10/22) 1. Complete any remaining React components for logging and viewing expenses.
2. Optimize UI/UX design for better user interaction.
Week 6 (10/23-10/29) 1. Set up a Flask application with GraphQL endpoint using Flask-GraphQL.
2. Implement GraphQL queries for fetching expenses.
Week 7 (10/30-11/5) 1. Implement GraphQL mutations to add and modify expenses.
2. Add authorization checks within GraphQL resolvers.
Week 8 (11/6-11/12) 1. Connect React frontend with Flask-GraphQL backend.
2. Test all GraphQL queries from the client-side.
Week 9 (11/13-11/19) 1. Fix any remaining bugs.
2. Begin deployment steps, possibly using services like Heroku for the backend and
Netlify for the frontend.
Week 10 (11/27-12/3) 1. Complete any remaining testing.
2. Deploy application and monitor for issues.
Potential Risks
1. Some of our members are unfamiliar with the Flask framework, so they may experience
issues with using it. If we run into issues, these members can consult the other more
experienced members in our group for help or they can check out the Flask
documentation. Using Flask there will always be trouble interacting between the frontend
and backend. The time impact would be about 1-2 days, and it would not slow down our
overall progress.
2. We will use GraphQL to interact between the frontend and backend. Since none of us are
familiar with GraphQL and it is a bit complex, we may experience issues working with it.
Using GraphQL also complicates the project, but we want to learn it so it may take some
extra time. To help us with these issues, we could consult with our mentor. The time
impact would be 3-4 days, and it would probably not slow down our overall progress.
Worst case scenario we will just use the REST API instead of GraphQL.
3. Most of our members are not familiar with React, so we may have trouble doing the
frontend portion. If we run into issues we will have to consult with our mentor or look at
Youtube tutorials. This may set us back 1-2 weeks, which is fine and shouldn’t impact
our overall project too much.
4. No SQL databases like MongoDB can become complex as you add more features, so we
must keep our schema simple. This may set us back 1 week, which should not slow down
our overall progress.
Teamwork
We will have a standardized editing environment on VSCode, so that we are all set up in the
same environment and can keep consistency in our code.
Since we are a team of four people and looking to learn an unfamiliar frontend framework, we
will work together on all components of the assignment. However, we will look to split up the
main ideas into a frontend team (Drew and Daniel) and a backend team (Darshan and David ).
Since Darshan and David are most familiar with the Flask framework, they will mainly work on
the backend, but will be of course assisting the frontend as well. We will be communicating in
our text group chat, which is already set up.