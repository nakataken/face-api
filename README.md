# face-api
testing images using face-api.js


Pre-requisites: 
1) mongoDB
2) mongoDBcompass (to have better UI experience for checking data)
3) Postman

Instructions:
1) Download/Clone this repo
2) Install packages using "npm install" 
3) Run mongodb in services (Check in services, then find mongodb. Right click it, then click start)
4) type "nodemon app" to start running of the server

Database: faceDB - Local

Endpoints: http://localhost:5000/
1) /post-face - to save the face descriptions to the database
2) /check-face - to recognize the image

Testing guide:
1) comment-out line 19 & 20 to test the faceRecognitionNet model
2) comment-out line 18 & 20 to test the faceLandMark68Net model
3) comment-out line 18 & 19 to test the ssdMobilenetv1 model

P.S: Ask nyo nalang ako directly about sa pag-test using postman para mafollow nyo maayos
