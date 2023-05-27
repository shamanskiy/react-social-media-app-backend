# react-social-media-app-backend

This is a back-end service for the social media [React app](https://github.com/shamanskiy/learning-react) from the awesome ["React for the Rest of Use"](https://simscale.udemy.com/course/react-for-the-rest-of-us) course by [Brad Schiff](https://simscale.udemy.com/user/bradschiff/).

The back-end is currently hosted on a free-tier [Render](https://render.com) account at https://react-social-media-app-backend.onrender.com.

## Local dev environment

To install dependencies:

```
npm install
```

The backend use [MongoDB](https://cloud.mongodb.com) for persistence. To configure MongoDB access, add ".env" file to the root with the following content:

```
CONNECTIONSTRING=<mongo-db-connection-string>
PORT=<port-number>
JWTSECRET=<secret-phrase-or-password>
```

Start the backend server locally by running

```
npm run start
```
