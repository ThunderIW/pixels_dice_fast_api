# pixels DICE FastAPI
This is a RESTful API for interacting with the Pixels electronic dice, allowing for the retrieval of dice information, such as the dice value rolled, battery level, and other monitoring features.

# Background
This project was created to help interact with the [Pixels dice](https://gamewithpixels.com/) and retrieve the dice value that was rolled.

## Features
- Accept dice roll submission (d20)
- Query the last_rolled value that was sent and use it in your applications 
- get dice battery level 
- calculated both advantage and disadvantage rolls 

## FastAPI Endpoints 
- live api server deployed here: https://pixels-dice-api.onrender.com
- docs for FASTAPI endpoints can be viewed here: https://pixels-dice-api.onrender.com/docs

<img width="1198" height="939" alt="image" src="https://github.com/user-attachments/assets/1a882f20-ca6c-45f5-bea3-3af33c87dfc6" />

## Requirements
you need to have the pixels app on your device:
1. go into the dice setting and select **When dice is rolled**
2. Select the web icon and create a new event
3. in the web request event select json and in the **Send request to URL** type https://pixels-dice-api.onrender.com/pixels




