### Project Desciption:
- The project comprises of basic openboard functionalities such as, writing, erasing, downloading the canvas, adding notes (with minimising it, closing it, dragging it around on the page), uploading the image (features same as of notes), undo and redo actions. <br>
- Added realtime drawing functionality using Socket.io by connecting to server using Express.js

<br>
<hr>


<hr>

<br>
<hr>


<hr>
<br>

#### Realtime drawing:
- Realtime drawing can be achieved by the people using same link at same time.

<br>
<hr>

<hr>
<br>

### Tech Stack used:
- HTML
- CSS
- JavaScript
- Express.js 
- Socket.io

  <br>
  
### Key Features
This real-time whiteboard provides the user with following features:

- Draw using pencil (3 different colors, scale the pencil size)
- Erase the drawn area using eraser(scale the eraser size)
- Include a sticky note to make notes (feature to add multiple sticky notes, move sticky note around the drawing area, minimize and close the sticky note)
- Upload an image or gif (feature to add multiple files,feature to move the file, close the file)
- Download the drawing part on the user screen
- Redo or undo the drawing content changes.
- Zoom in or zoom out the drawing content.
- Real-time virtual environment for drawing and erasing.

### Run on your local machine:
Replace `link` with `http://localhost:5000/` in `index.html`file. <br>
Open the folder in VS code. Open terminal and write these commands: <br>
```
npm init
```
Press Enter. Then,
```
npm install socket.io
npm install --save-dev nodemon
node app.js
```
Now open the browser and type `localhost:5000`.
