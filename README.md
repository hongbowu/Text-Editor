# Text-Editor

## Description
Text Editor is a web application that allows developers to create and manage notes or code snippets with or without an internet connection. It ensures reliable storage and retrieval for later use.

## How to Use
Running the Application
Open the application in your code editor to see the client-server folder structure.
Run `npm run start` from the root directory to start the backend and serve the client.
Run the Text Editor application from your terminal.
Verify that your JavaScript files are bundled using Webpack.

Webpack Configuration
After running the Text Editor application, Webpack plugins will generate an HTML file, a service worker, and a manifest file.
The application supports next-gen JavaScript, ensuring smooth functionality without errors.

IndexedDB Integration
Upon opening the Text Editor, IndexedDB immediately creates a database storage.
Enter content and click off the DOM window to save the content in the Text Editor to IndexedDB.
Reopen the Text Editor to find that the content has been successfully retrieved from IndexedDB.

Install Button
Clicking the Install button allows you to download the web application as an icon on your desktop.

Service Worker and Workbox
When loading the web application, a registered service worker, using Workbox, ensures efficient offline usage.
Static assets are precached upon loading, including subsequent pages and static assets.

## Contact Information
For inquiries or feedback, please contact: wuhongbo@gmail.com

Feel free to customize the README further based on specific details or additional features of your Text Editor application.