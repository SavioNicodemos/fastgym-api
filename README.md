<h1 align="center">Welcome to Fast Gym API!</h1>


Fast Gym API is a backend server designed to power the [FastGym App](https://github.com/SavioNicodemos/fastGym). It provides a range of features to help users manage their workout routines and track their progress.

## Key features of the API includes:

 - User authentication and authorization
 - Workout logging and tracking
 - Provide list of exercises with gif to see how is done
 
To use the API you can:
 - Clone the repository
 - Run `npm install` onn the project folder
 - Run `npm run dev`
 
The project will be available in [http://localhost:3333](http://localhost:3333) and now if you want to test the API, you can install the [Insomnia](https://insomnia.rest/download) and open the file insomnia.json inside of the Insomnia and you will have all the routes and params imported automatically to use.


If you want to see the data in the database you can install some SQLite manager as [SQLectron](https://github.com/sqlectron/sqlectron-gui) or [Beekeeper Studio](https://www.beekeeperstudio.io/), select the type of DB as SQLite and browse to the database.db file inside of the folder `fastgym-api/src/database/database.db` and open it. It's done!

Now is just open the [FastGym App](https://github.com/SavioNicodemos/fastGym) on your expo and start using this AMAZING app!

### Available Scripts

|                    Script | Target                                             |
| ------------------------- | -------------------------------------------------- |
|                    `npm run dev` | Run API in **development** environment      |
|                    `npm start` | Run API in **production** environment         |
|                    `npm run migrate` | Create database tables                  |
|                    `npm run seed` | Populate database tables                   |


### API Docs
To view the API documentation, run the API and access [http://localhost:3333/api-docs](http://localhost:3333/api-docs) in your browser
