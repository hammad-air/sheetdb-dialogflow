# Connect Google Sheet to Dialogflow
Hey everyone, if you are looking for a connection between Google Sheet and Dialogflow, then you are welcome read more. You will learn how to connect your existing Dialogflow agent to Google Sheet and generate Dialogflow agent response from Google Sheet...


### How to use it
To replicate the work of this repository and run it locally, you need to follow these steps:
* create a `.env` file inside the root directory, create these environmental variables:
    ```
    CREDENTIALS=Service account credentials in one line, see the video as well
    RESPONSES_SHEET_ID=Your Google Sheet id, see the video how to get it...
    ```
* install all the required dependencies from the `package.json` file
    ```javascript
    npm install --save
    ```
* run the server with either of the following commands
    ```javascrip
    node index.js
    ```
* add the webhook url to Dialogflow

    > YOUR NGROK URL/dialogflow
