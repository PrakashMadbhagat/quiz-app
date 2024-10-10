you can run this file using  <mark> nodemon index.js</mark>

### Authentication Endpoints

| Method | Route        | Description                  |
|--------|--------------|------------------------------|
| POST   | /register     | Register a new user          |
| POST   | /login        | Log in as an existing user   |
| GET    | /logout       | Log out the current user     |

##
### Book Endpoints

| Method | Route            | Description                    |
|--------|------------------|--------------------------------|
| POST   | /quiz/           | Create a new quiz by <mark>admin</mark>     |
| GET    | /quiz/           | Fetch all quiz                 |
| GET    | /quiz/:id        | Fetch quiz by id                 |
| POST   | /quiz/submit     | Submit quiz by <mark>user</mark>              |
