# GitHub OAuth Application

This is an annotated example of implementing GitHub OAuth with Express Session and Passport.js.

Full instructions are included in instructions.txt at the project root.

## Getting Started

1. [Follow these instructions](https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app) by GitHub on how to obtain a client ID and secret for GitHub OAuth. Fill out the registration form with the following details, for development use only:

Application Name: OAuth Project (or any name for your project)  

Homepage URL: http://localhost:3000  

Authorization Callback URL: http://localhost:3000/auth/github/callback  

Click "Register Application"

2. Once you have obtained your client id and secret, store them in a .env file in the project root directory as follows:

GITHUB_CLIENT_ID=<"CLIENT ID HERE">  

GITHUB_CLIENT_SECRET=<"CLIENT SECRET HERE">

3. Run ### `npm install` in a terminal at the project root directory.

## Available Scripts

### `npm run start`

This will start the development server on port 3000.

Navigate to http://localhost:3000 to view the application and test OAuth with GitHub.