# Text-Editor PWA

## Description:
This README file provides instructions for setting up, running, and deploying my text-editor PWA. The application utilizes a client-server architecture and employs technologies like webpack, IndexedDB, service workers, and Render for deployment. Most importantly, it is useable offline and downloadable because of the PWA.

## Installation:

### Clone this repository to your local machine:
git clone https://github.com/krohnayden/textEditorPWA.git

### Use Deployed Application
Deployed App Link - 
https://pwatexteditor-kh0x.onrender.com/

## Usage:

Screenshot of Application 
<img width="1440" alt="textEditorPWA" src="https://github.com/krohnayden/textEditorPWA/assets/143373263/72bc7f8b-4862-495f-af70-ac1c8d9aa591">

### Start Application
cd Develop
npm i
npm start

Open your browser and access
 the text editor application.

Upon running the application, ensure that your JavaScript files are bundled using webpack.

Verify that webpack plugins have generated an HTML file, service worker, and a manifest file.

The text editor should function correctly in the browser even when using next-gen JavaScript features.

Upon opening the text editor, IndexedDB should immediately create a database storage.

Enter content in the text editor, and when you click off the DOM window, verify that the content is saved with IndexedDB.

Close the text editor and reopen it to confirm that the previously entered content is retrieved from IndexedDB.

Click on the "Install" button to download the web application as an icon on your desktop.

## License
N/A
