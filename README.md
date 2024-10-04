# LinkedIn Connection Automation - Chrome Extension

This is a Chrome extension built using React that automates sending connection requests on LinkedIn from the "My Network" tab. The extension sends connection requests one by one and updates the count in the popup. You can start and stop the automation process using buttons in the popup.

## Features

- Automatically sends LinkedIn connection requests.
- Tracks and displays the number of requests sent in the extension popup.
- Ability to start and stop the connection requests at any time.

## Tech Stack

- **React**: Frontend framework for building the extension's UI.
- **Chrome Extensions API**: For managing background scripts, content scripts, and messaging.

## Installation

### 1. Clone the Repository

```bash
git clone  https://github.com/dipakdade92/linkedin-chrome-extention.git
cd linkedin-connection-automation
npm install
npm run build
```

## need to follow these steps to run this extension into chrome browser

Load Your Extension in Chrome:
- Open Chrome and go to chrome://extensions/.
- Enable "Developer mode" (toggle in the upper right corner).
- Click on "Load unpacked" and select the build folder of your React app.
Test Your Extension:
- Open LinkedIn and navigate to the "My Network" tab.
- Click on your extension icon to open the popup.
- Click the "Start Sending Requests" button to initiate the connection requests.
- Click the "Stop Sending Requests" button to halt the process.
