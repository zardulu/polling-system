# polling-system
Basic polling-system dashboard created using PERN stack.

Additional libraries used - [Material UI](https://mui.com/material-ui/), [Chart.js](https://www.chartjs.org/),  [knex.js](https://knexjs.org/), [date-fns](https://date-fns.org/)

# Installation
1. Clone the repository:
  ```
  git clone https://github.com/zardulu/polling-system.git
  ```


2. Navigate to the project directory:
  ```
  cd polling-system
  ```

3. Install dependencies:
  ```
  npm install
  ```

4. Install PostgreSQL and start a database.

5. Configure `knexfile.js` located in `/server/database/knexfile.js`
```
{
    client: 'pg',
    connection: {
      host: '127.0.0.1',
      user: '<USERNAME>', //postgres by default
      password: '<PASSWORD>',
      database: '<DATABASE-NAME>',
      port: 5432,
    }
```

6. To run the program, navigate to the root directory and start the server
```
cd server
npm start
```
7. Start the client
```
cd client
npm start  
```




