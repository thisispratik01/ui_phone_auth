# Flutter OTP authentication 

Full Stack OTP authentication using mobile number .

## Features

- User Authentication using phone no and OTP .
- Generating otp and validating it .
- otp is valid only for perticular time,after specified time it will not work .
- Sending encrypted token to user .
- Own api to generate , send and validate otp and user . no need to depend on third party authentication services .

## Running Locally (You will see many errors just ignore them and follow steps as i mentioned below) :

- mongodb must be installed on your system and mongodb compass also to explore our database .
- if you are on windows os then search "Services" and find Mongodb service ,see if its running or not . if it is not running then click on it and start it.
- now start mongodb compass and click on New Connection and select  " Fill in connection fields individually " as shown below .
- then click on connect as shown below .

After cloning this repository, migrate to ```flutter-otp-authentication``` folder (you can open this folder in vs code). Then, follow the below steps:
- Navigate to "lib/services/api_services.dart " file and open it . you have to change value of "uri" variable to http://your ip address:3000 .
  you can get your ip address in windows cmd by using command "ipconfig" and copy IPv4 address of your wifi as shown below .




Then run the following commands to run your app:

### Server Side
```bash
  cd Server
  npm install
  npm run dev (for continuous development)
  OR
  npm start (to run script 1 time)
```

### Client Side (make sure you are in flutter-otp-auth folder not in Server)
```bash
  flutter pub get
  open -a simulator (to get iOS Simulator) or start your android emulator or connect your smartphone in debugging mode .
  flutter run (you can click on "Run button") .
```

## Tech Used
**Server**: Node.js, Express, Mongoose, MongoDB .

**Client**: Flutter .
    
## Feedback

If you have any feedback, please reach out to me at pratik99dhumal@gmail.com
