# lendsqr_assessment
## this  api was built using nodejs it runs on a mysql database
to begin;
- clone repo
- npm install
- npm run dev

for testing with jest;
- npm run test

the api uses paystack api for funding and withdraws, so you will need a paystack account
it also uses webhooks to receive events from paystack, use ngrok to get a public url for your server so paystack can send events.

NB:create a .env file at the root of your project and add PAYSTACK_SECRETKEY= 'your secret' ,JWTSECRET='your jwt secret' ,TOKENVALIDITY=1d
go to the config.json file in the config folder at the root of your project to add your database details

# link to the technical design documentation :https://docs.google.com/document/d/1uiVtRkHdicA_BriIB0IYXEcxIZI88pX7o3Db9Y9ZGsg/edit?usp=sharing
