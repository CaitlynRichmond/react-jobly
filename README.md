# Jobly
Jobly is an Indeed-like web application

You can view the backend [here](https://github.com/CaitlynRichmond/express-jobly)

View the deployed site [here](https://malicious-question.surge.sh/), deployed with Render and Surge. It may take a few minutes for Render to spin up.

Login: test-user | Password: password

## Tech Stack
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)

## Features
Here is an overview of some of the key features

- Users are able to log in and log out. Authentication is handled with JWTs and a custom hook to store tokens in local storage for persistent across sessions
- This project works with the backend that was written in a separate sprint
- Users can apply to jobs
- Live search with debounce implemented for jobs and companies search.
- The back end of this project has 95%+ test coverage

## Local setup instructions
Fork and clone the [backend](https://github.com/CaitlynRichmond/express-jobly)
```
cd [path_to_your_cloned_backend]
npm install
npm start
```
the backend will now be running locally on port 3001

Fork and clone the frontend (this repo)

```
cd [path_to_your_cloned_frontend]
npm install
npm start
```
the frontend will now be running locally on port 3000



## To-Dos
- Refactor to use typescript
- Write tests to cover rendering + mission-critical features

## Acknowledgements
The front-end of Jobly was built during my time at Rithm School, as part of a 3-day sprint. My partner on the front end was [JaeWon Jin](https://github.com/jjin286).