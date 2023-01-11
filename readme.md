# 0.4: New note diagram

- Create a similar diagram depicting the situation where the user creates a new note on page

https://studies.cs.helsinki.fi/exampleapp/notes

Browser ---> Server: HTTP POST /new_note
Server ---> Browser: HTTP 302 Found /exampleapp/notes
Server ---> Browser: HTTP 200 OK /notes
Browser ---> Server: HTTP GET /notes
Server ---> Browser: HTML notes
Sever ---> Browser: main.css
Sever ---> Browser: Main.js
Sever ---> Browser: data.json

# 0.5: Single page app diagram

- Create a diagram depicting the situation where the user goes to the single-page app version of the notes app

Browser ---> Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
Server ---> Browser: HTML spa
Sever ---> Browser: main.css
Sever ---> Browser: main.js
Sever ---> Browser: data.json
Server ---> Browser: Favicon.ico

# 0.6: New note in Single page app diagram

- Create a diagram depicting the situation where the user creates a new note using the single-page version of the app.

Browser ---> Server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
Server ---> Browser: HTTP 200 OK /new_note_spa
Server ---> Browser: HTML spa
Sever ---> Browser: main.css
Sever ---> Browser: spa.js
Sever ---> Browser: data.json
Server ---> Browser: Favicon.ico
