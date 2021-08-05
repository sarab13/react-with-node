

It is an MERN ( mongodb, express, react, node) stack e-commerce app. This app includes lots of functionality like user dashboard, admin dashboard, create-product, create-category, manage order, buy books, profile management, cart , checkout with brain-tree payment gateway (sandbox) with credit card and paypal. 

#### `Tech Stack:`

[![Generic badge](https://img.shields.io/badge/Node.js->=10-red.svg)](https://shields.io/)  [![Generic badge](https://img.shields.io/badge/React.js->=16.8-blue.svg)](https://shields.io/)  [![Generic badge](https://img.shields.io/badge/MongoDB->=4-teal.svg)](https://shields.io/)  [![Generic badge](https://img.shields.io/badge/Express.js->=4-<COLOR>.svg)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/Braintree.js->=2-yellow.svg)](https://shields.io/)



#### `How to run locally?`

```bash
1. git clone https://github.com/MasterKN48/OpenBook-E-Commerce
2. cd OpenBook-E-Commerce
3. npm i
4. cd client 
5. npm i
6. cd ..
# to run server you must have .env file in root project directory
# see below .env file structure and replace with your value
7. npm run dev
# project started

```



#### `.env structure`

```bash
MONGO_URI=<MONGO_DB_SERVER>
NODE_ENV=production  # `production` or `dev`
CLIENT_URL=<REACT_APP_SERVER>
PORT=8000
BRAINTREE_ID=<BRAINTREE_SANDBOX_ID>
BRAINTREE_PRIVATE=<BRAINTREE_SANDBOX_PRIVATE_ID>
BRAINTREE_PUBLIC=<BRAINTREE_SANDBOX_PUBLIC_ID>
JWT=<JWT_SECRET>
```



 [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
