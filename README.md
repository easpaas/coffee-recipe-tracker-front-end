<h1 align="center">
    Coffee Recipe Tracker Front End
</h1>

*NOTE: This project is a work in progress and is not yet complete. The code here represents the current state of the project.*

---

Front end client (React) for a Coffee Recipe Tracker application. This repo contains the code for all of the user facing functionality for the web client.

The application solves the problem of keeping track of the different ways someone has made coffee. Home coffee making enthusiasts have many factors to keep track of when brewing coffee. This application allows someone to keep track of those various factors and rate the quality of the resulting cup as well as make notes. This will help them to make better decisions in the future about how to brew coffee for the best tasting results.

This project is used as a portfolio piece for my work as a Software Developer. If you are interested in discussing this further with me please feel free to reach out on [Twitter](https://twitter.com/daveskull81) or on my [website](https://www.daveinden.com).

### Demonstrates use of the following:  

* React component development
* Routing with React Router
* Layout and styling with Material UI
* Frontend testing with React Testing Library
* Connecting a frontend client to a custom backend database and API

## Installation

Fork and clone the repository.  

From the root directory in your command line run `npm install` to install dependencies.  

The local server can be started by running `npm start` once dependencies are installed. It should launch in your browser at `localhost:3000`
Note, this application is deisgned to run against a specific [backend](https://github.com/daveskull81/coffee-recipe-tracker-api). You'll want to install that repo and run that along side this to see the full application.

Once you have that running you will need to set an environment variable with the port your backend instance is running on.  
Example:  
```
REACT_APP_BACKEND_BASE_URL=http://localhost:5000/api
```

Additional environment variables to set are the following:  
```
REACT_APP_USER_COOKIE_NAME //can be set to any string value
```

## Testing

Tests are implemented with React Testing Library. To start tests run `npm test` from the root directory in your command line.

## License

This project is licensed under the terms of the MIT license. For more details see the [LICENSE](https://github.com/daveskull81/coffee-recipe-tracker-front-end/blob/master/LICENSE) file.

## Contribution
This project isn't currently taking contributions, but I am happy to hear feedback. If you have feedback or if there is anything you would like to see changed please open an [issue](https://github.com/daveskull81/coffee-recipe-tracker-front-end/issues).
