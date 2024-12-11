# Expo CLI Error: Accessing Unavailable Features or Missing Dependencies

This repository demonstrates a common yet often perplexing error encountered when developing Expo applications. The problem typically arises from attempting to utilize features or modules that are either unavailable within the current environment (like Expo Go) or are not correctly integrated into the project. This can stem from issues such as missing dependencies, incorrect configuration, or trying to access hardware functionalities without the necessary permissions.

The provided examples illustrate typical scenarios and solutions for these errors.  Please refer to the `bug.js` file to see the error-inducing code and `bugSolution.js` for the corresponding fix.  Understanding the differences can help you quickly resolve similar problems in your projects. 

## Setup

1. Clone this repository.
2. Navigate to the project directory using the command line.
3. Run `expo install [missing_dependency]` if applicable (check package.json).
4. Start the development server using `expo start`.
5. Reproduce the error as shown in `bug.js`. Observe the solution provided in `bugSolution.js` and apply the changes to your Expo project to address the problem.