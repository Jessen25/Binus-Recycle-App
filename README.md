﻿# BinusRecycleApp
BinusRecycleApp is a mobile application meant to be used by BINUS students located around the Kemanggisan campus. This app is not meant to be used independently, as it is only the user side of the whole application. The admin side “StationApp” can be found here: https://github.com/Scleepy/StationApp/

In order to use this application, users must set up the BinusRecycleDB Database along with its API. Further explanation can be found in the link: https://github.com/Scleepy/BinusRecycleAPI

### Setup:
- Once the prerequisites are met (database & API), you can begin to clone the "main" branch of the repository and run "npm i" run install all the dependencies.
- The .env file must be configured to your local machine's IP address by opening cmd and running "ipconfig":
```
BASE_URL=http://[IP HERE, DELETE BRACKETS]:3000
```
- Punch "npm run android clear-cache" into the terminal to start the application
