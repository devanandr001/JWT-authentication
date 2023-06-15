npm init -y  // to create package.json

npm i express jsonwebtoken dotenv   //initialise dependencies

npm i --save-dev nodemon   //nodemon refreshes server evertime we make changes

USING REST CLIENT EXTENSION IN VS CODE 
instead of POSTMAN SOFTWARE
CHECK FILE: requests.rest


to get random access code
$node
> require('crypto').randomBytes(64).toString('hex')


Now the tokens is having forever access which is not secure
why do we need refresh token? so that, the token will have short expiration span
now the token is refreshed using refresh token 

