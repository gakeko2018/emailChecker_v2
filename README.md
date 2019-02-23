emailChecker_v2
Gets email list from a txt file and returns the "DETAILED" results in a log file.

You can use this app in two ways.

First with the parameters:

    npm install
    npm start example@domain.com example2@domain.com

Second:

Write the emails you want to check in the emailList.txt. Be sure that there is only one email per line and there is no empty lines.

    npm install
    npm start

The app reads the emailList.txt and writes the results in result.log file.