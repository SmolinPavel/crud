### CRUD

Examples of Create Read Update Delete operations

1. Clone the repo `git clone git@github.com:SmolinPavel/crud.git`
2. Change to the project folder `cd crud`
3. Install dependencies `yarn` or `npm i`
4. Start the server on port 3000 `yarn start` or `npm start`

### Endpoints

- *POST*   `http://localhost:3000/user/add` - creates a user. Make sure you add a request body.
- *GET*    `http://localhost:3000/user/list` - lists all the users. Returns an array of existing users.
- *PUT*    `http://localhost:3000/user/update/:username` - update the user by username.
- *DELETE* `http://localhost:3000/user/delete/:username` - deletes the user by username.
