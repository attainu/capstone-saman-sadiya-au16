# Project Documentation
###  E-Commerce Website

* step 1: `git clone <repo_url>`
* step 2: `cd <repo_name>`
* step 3: `git checkout dev`
* step 4: `open folder in your code editor`


## Technologies used

- React
- Redux
- Nodejs
- React Hooks
- Redux thunk
- Hooks
- Expressjs
- Mongodb
- Mongoose
- Mongoose unique validator
- Crypto
- Javascript
- DOM manipulation.
- Css/Bootstrap.
- Multer.
- Heroku.
- axios.


## Usage

### ES Modules in Node

We use ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku


### Seed Database

```
Sample Admin Logins

admintest@gmail.com (Admin)
123456

```