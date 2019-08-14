# whatabyte
 
A fictional restaurant named WHATABYTE that specializes in making delicious food for developers.

Food? I mean a response, what where you expecting? jollof rice? lols.. sorry.


# Technologies used
Checkout the package.json file, you will figure it out. 

# How to run
- Clone Repo
- `npm run dev` to run our server with nodemon
- `npm run ui` to start Browsersync

# To see the Auth0 in action
- Create a .env file in the root folder
- [Signup Here](https://auth0.com)
- Click on Applications in your dashboard
- Create Application, give it a Name `WHATABYTE` or whatever you lik and choose `Regular Web Applications` as the type, click on `Create`

# Setting
- Click on `settings tap` and populate the following fields like so:
- Allowed Callback URLs: `http://localhost:3000/callback, http://localhost:8000/callback`
- Allowed Logout URLs: `http://localhost:3000/, http://localhost:8000/`
- Populate your .env file with your credentials:
 - `AUTH0_CLIENT_ID=`
 - `AUTH0_DOMAIN=`
 - `AUTH0_CLIENT_SECRET=`

