# React Movie App

It's a simple movie app using React.js

Checkout the [demo].\
Or if you want to host it yourself, you can follow the [installation guide](#installation) below.

## Features


-  Login
-  Register
-  Movie list
-  Movie detail
-  Ticket booking
-  Transaction detail
-  Show tickets in transaction detail
-  Top up balance
-  Withdraw balance
-  Search movie by title
-  Transaction history
-  Cancel order/transaction
-  Cancel ticket


## Installation

1. Clone this repository
2. Install dependencies
   ```bash
   npm install
   ```
3. Copy `.env.example` and rename it to `.env.local`
4. Change the value of the variables in `.env.local` to match your environment or leave it as it is
   ```env
   VITE_API_ENDPOINT=https://movie-booking-app-production.up.railway.app/api/v1
   VITE_APP_NAME=Sea Cinema
   ```

## Usage

1. Open the [demo]\
   or if you host it yourself, run the app in the development mode and open [http://localhost:5173](http://localhost:5173) to view it in the browser.
   ```bash
   npm run dev
   ```
2. Create an account by navigating to `/register`
3. Login with your account
4. Enjoy the app

## Built with

- [React.js](https://reactjs.org/)
- [Vite.js](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Heroicons](https://heroicons.com/)
- [React Router](https://reactrouter.com/)



## Known issues

- Input type date not working on Safari

[demo]: https://seacinema.vercel.app/

