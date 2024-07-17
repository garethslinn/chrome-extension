# Example Chrome Extension

<img src="https://github.com/garethslinn/chrome-extension/blob/main/chrome_ext.png" alt="screenshot of extension working" width="300px" />

## Introduction

This project is a basic demonstration of a Chrome extension. It showcases how I create, structure, and test a simple Chrome extension that interacts with the user via a popup interface. The extension includes basic HTML, CSS, and JavaScript files, along with a manifest file that configures the extension's settings.

## Features

- **Popup Interface:** A simple HTML popup that opens when the extension icon is clicked.
- **Button Interaction:** A button within the popup that, when clicked, triggers a JavaScript alert.
- **Background Script:** A background script that logs a message when the extension is installed.
- **Basic Styling:** Basic CSS to style the popup interface.

## File Structure

```
my-chrome-extension/
├── manifest.json
├── popup.html
├── popup.js
├── background.js
├── styles.css
├── icons/
│   ├── icon16.png
│   ├── icon48.png
│   └── icon128.png
```

## Installation

### Prerequisites

- Google Chrome browser

### Steps

1. **Download or Clone this Repository:**

   ```sh
   git clone https://github.com/yourusername/my-chrome-extension.git
   ```

   Or simply download the ZIP file and extract it.

2. **Open Chrome and Go to the Extensions Page:**
    - Open a new tab.
    - Type `chrome://extensions/` in the address bar and press Enter.

3. **Enable Developer Mode:**
    - Toggle the switch in the top right corner to enable "Developer mode."

4. **Load the Extension:**
    - Click the "Load unpacked" button.
    - In the file dialog, navigate to the `my-chrome-extension` directory and select it.
    - Click "Select Folder" (or "Open" depending on your OS).

5. **Verify the Extension:**
    - You should see your extension listed on the Extensions page with the name "Chrome Extension."

## Usage

1. **Click the Extension Icon:**
    - In the Chrome toolbar, click the extension icon (usually to the right of the address bar).

2. **Interact with the Popup:**
    - The popup interface (`popup.html`) will appear.
    - Click the "Click me" button.
    - An alert will appear with the message "Button clicked!".

## What it Does

- **Popup Interface:**
    - When the extension icon is clicked, a popup interface defined in `popup.html` is displayed.

- **Button Interaction:**
    - The `popup.js` script adds an event listener to the button. When the button is clicked, an alert message is shown.

- **Background Script:**
    - The `background.js` script logs a message to the console when the extension is installed.

## Conclusion

This project is a quick demonstration of a basic Chrome extension. It includes fundamental components such as a manifest file, a popup interface, a background script, and basic styling. Use this as a starting point to build more complex and feature-rich Chrome extensions.
