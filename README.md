## Setup the project

To set up the project on your localhost, follow the steps below :

#### 1) Installation and basic configuration of MongoDB database

#### 2) Clone project

```shell
git clone https://github.com/mrhosseinsalari/Freelancering-App-Backend
```

```shell
cd Freelancering-App-Backend
```

#### 3) Add environment variables

Now you need to create a `.env` file in the root directory. Here's the list of variables you need to create :

```env
APP_DB="the URL to your database"
KAVENEGAR_API_KEY="a secret to be used for kavenegar"
ACCESS_TOKEN_SECRET_KEY="a secret to be used for access token"
REFRESH_TOKEN_SECRET_KEY="a secret to be used for refresh token"
COOKIE_PARSER_SECRET_KEY="a secret to be used for cookies"
TOKEN_SECRET_KEY="a secret ..."
ZARINPAL_CALLBACK_URL=/api/payment/verify
CLIENT_URL=http://localhost:3000
SERVER_URL=http://localhost:5000
NODE_ENV=development
PORT=5000
ALLOW_CORS_ORIGIN=http://localhost:3000
DOMAIN=localhost
```

#### 4) Setup project

```shell
npm install
```

```shell
npm run dev
```

Now the server is created and connected to the database. You can use it!
