# CODE SHOT

## Instructions

- click on the apple to open the extension. it should automatically screenshot your tab
- click twice on the image to crop it. First click should be upper left of rectangle, second click should be bottom right
- ocr should run automatically and display results in a code editor
- you can run (javascript code) with the run button

Here is a test video you can test the plugin on:
https://youtu.be/W6NZfCO5SIk?t=1177

You will need a google vision API key. Create a secrets.js file and store the key there.

To get a google vision API key:

(1) Sign into https://console.cloud.google.com
(2) On the left hand side, click on APIs & Services ---> Library
(3) look for "Cloud Vision API"
(4) Enable the API. You may be prompted to enter credit card information
You may also need to set up a project
(5) On the left hand side, click on credentials
then on the top, click "create credentials" --> API Key
this will generate an API key that you can store in secrets.js, do not share the API key publically
