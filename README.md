## SMS-verification using (https://www.courier.com/)

You will learn/understand the nodejs basics, otp generator and database integration to store your new users.
-OTP to Mngodb and phone number
-Use of Postman/Swagger

You also need to create a .env file and input this details
DB_URL=
COURIER_TOKEN=

How to test the endpoints on postman/curl/swagger

## ----------------------------------------------

To recieve OTP on phone number and Mongodb
http://localhost:5000/api/v1/otp
{
"username": "",
"mobile": "",
"name": ""
}

## ----------------------------------------------

To verify the user and get ready for signup
http://localhost:5000/api/v1/otp
{
"username": "",
"otp": ""
}

## ----------------------------------------------

For a successful signup for users
http://localhost:5000/api/v1/user

{
"username": "",
"password": "",
"mobileNo":"",
"name":""
}
