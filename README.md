# vidchat

It's a Group video calling application using the Agora Web SDK with a Django backend.

### How to run this project:

1 - Clone the repo
`git clone https://github.com/Abdelfattaah/vidchat`

2 - Install the requirements
`cd vidchat
pip install -r requirements.txt`

3 - Update Agora credentals and use yours
In order to use this project you will need to replace the agora credentials in views.py and streams.js.

Create an account at agora.io and create an app. Once you create your app, you will want to copy the appid & appCertificate to update views.py and streams.js. If you have questions about where to get your app I'd recommend referencing this link `https://youtu.be/HX6AM_1-jNM?t=88`

4 - Start the server
`<python manage.py runserver>`



