# Hackerverse 2022
### Official submission to Hackerverse 2022 by Team FluttAR

![RU_Hacks](Repository-Assests/Cover.png) 

## Inspiration💡
The idea of not being at the moment or the place but expericing it virtually has always been exciting. Imagine an app that captures photos and converts it into a panoramic view, so that a person can enjoy by not actually being present at the particular moment.

## What it does 🧭

Our solution, the user can visit the places vircually by using just an image. The application will take an image from the user and will show it in a virtual panoramic view where the user will be able to view left and right by rotating their smartphone.

## How we built it 🔧
Using Openscreen we generate dynamic QR values, which are then fetched through the Openscreen API to our local host. The QR data is fetched as an object which contains various details ranging from QR id, date of creation etc. When our Frontend (React Web app) is opened by the user, the data is fetched from the QR-images section and it displays the name of the events, date of the events and the QR image which you can scan to enroll yourself in the events.  

## Tech Stack 🔨
1. Flutter
2. Provider State Management
3. Flutter AR Kit
4. Git
5. GitHub

## Challenges we ran into 🏃‍♂️

1. To get the QR as images instead of object files with data was a challenge for us.
2. To post the QR codes from Openscreen to our React web application was difficult as we faced multiple issues in the integration. 

## Accomplishments that we're proud of 🏅
1. Created a working prototype where the QR codes are succesfully fetched and posted to our front end. 
2. Build the project use MERN stack which is our first time working in a MERN stack project. 

## What we learned 🧠
1. Openscreen method of QR generation.
2. Openscreen API to fetch and post QR codes to our Webapplication.
3. Node.js packages and their use. 



## What's next ⏭

1. Sort the events in ascending order so people can understand the timelines better. 
2. Build the same Prototype as a Hub so multiple universities/organisations can use our platform. 

## Developers

1. [Eshaan Bhardwaj](https://github.com/Eshaan-B)
2. [Gyanesh Samanta](https://github.com/gyaneshsamanta)
3. [Aditya Kumar](https://github.com/ak8476)
4. [Yashodhana Shukla](https://github.com/Yashu6600)

| Members                                               |
| ----------------------------------------------------- |
| [Eshaan Bhardwaj](https://github.com/Eshaan-B)        |
| [Gyanesh Samanta](https://github.com/gyaneshsamanta)  |
| [Aditya Kumar](https://github.com/ak8476)             |
| [Yashodhana Shukla](https://github.com/Yashu6600)     |