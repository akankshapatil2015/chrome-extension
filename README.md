**My Reads Chrome Extension**

A simple Chrome extension that allows users to store and manage URLs.This extension captures the current tab's URL and stores it in local storage.
Users can also manually enter URLs and delete all saved URLs with a double-click.

**Features**
#Save Current Tab's URL: Click on the "Save Tab" button to save the URL of the currently active tab.
#Add URLs Manually: Users can input URLs manually and add them to the saved list.
#Clear All URLs: Double-click the "Delete All" button to clear the stored URLs.
#Local Storage: All URLs are stored in the browser's local storage and persist between sessions.

**Installation**

#Clone the repository:
  git clone https://github.com/akankshapatil2015/chrome-extension

#Navigate to the project directory:
  cd chrome-extension
  Load the extension in Chrome:

Open Chrome and go to chrome://extensions/.
Enable Developer mode (toggle on the top right).
Click on Load unpacked and select the directory where you have the extension files.
You're all set! The extension should now appear in the Chrome toolbar.

Files
index.html: The popup UI for the Chrome extension.
style.css: The styles for the popup UI.
index.js: The JavaScript logic to capture and manage URLs, interact with local storage, and handle user interactions.

How to Use
 #Save Current Tab:
  Click the "Save Tab" button to add the current tab’s URL to the list of saved URLs.
 #Add URL Manually:
   Type the desired URL into the input field and click "Save Input" to add it to the list.
 #View Saved URLs:
   The saved URLs are displayed in the extension popup.
   Click on any URL in the list to open it in a new tab.
 #Clear All URLs:
   Double-click the "Delete All" button to remove all saved URLs from local storage and clear the list in the UI.

**Development**
#Prerequisites: You should have a basic understanding of HTML, CSS, and JavaScript.
The extension uses Chrome API to interact with the browser's tabs and local storage.

**Contributing**
#Feel free to contribute by opening an issue or creating a pull request.
