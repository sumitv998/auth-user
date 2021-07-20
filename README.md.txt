i have created authentication..... for user and tour
1. server.js = It is contain all connection of mongodb and HTTP server post connection and anther side it will take caught handling form the server side.

2. app.js = Is use for express app for containing data.

3. folder util = 
a) apifeature will contain all sorting, filter, paginate and limit.
b) apperror and catchAsyc will contain error handling funtion.
c) email.js will conation all use nodemiller funtion for sending the mail. 

4. Floder router = it is contain define route for URL where it's contain.

5. models = define database sturcture.

6.Floder Controller = 
a)authcontroller is use for all authention parts likes refereh token, forget password, Reset password.
b)errorcontroller is handle all mongodb error.
c)tourcontroller it is contain all funtion which requred for tour database.
d)usercontroller it is used for all user define database for funtions.