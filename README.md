# IPL-Match-Extension
Not a tough nut to crack. The extension makes use of an API that provides it with the real-time data, 
and using simple JS mapping and filtering one can extract the needed info (IPL in our case). 

In case, on using the extension you don't see any text, 
it is because the API hit limit has been reached.

This is just an initial work and I'll be refining it going into the future.

Sure, here's a basic documentation for your Chrome extension:

---

## Introduction
The IPL Live Extension is a Chrome extension developed to provide users with live updates of ongoing IPL matches. It fetches data from the CricAPI and displays the ongoing matches in real-time.

## Files Included
1. **index.html**: HTML file responsible for displaying the extension's user interface.
2. **script.js**: JavaScript file containing the logic for fetching and displaying IPL match data.
3. **manifest.json**: Manifest file providing metadata about the extension, including its name, version, description, and other details required for its functionality.
4. **style.css**: CSS file defining the styles for the extension's user interface.

## Components
### 1. index.html
This file contains the basic structure of the extension's user interface. It includes a list element `<li>` where the ongoing matches will be displayed.

### 2. script.js
This JavaScript file contains the logic for fetching IPL match data from the CricAPI. It makes an asynchronous request to the API, processes the response data, and updates the HTML content dynamically to display the ongoing matches.

### 3. manifest.json
The manifest file provides essential information about the extension to the browser. It includes details such as the extension's name, version, description, icons, and how the extension should behave when activated.

### 4. style.css
This CSS file defines the styles for the extension's user interface, including the layout, colors, fonts, and other visual aspects.

## Installation
To install the IPL Live Extension, follow these steps:
1. Download or clone the extension files to your local machine.
2. Open Google Chrome.
3. Go to the browser's Extensions page by typing `chrome://extensions/` in the address bar and pressing Enter.
4. Enable Developer Mode by toggling the switch located in the top-right corner.
5. Click on the "Load unpacked" button and select the folder containing the extension files.
6. The IPL Live Extension should now be installed and visible in the list of extensions.

## Usage
Once installed, the IPL Live Extension will display ongoing IPL matches in real-time. Simply click on the extension icon in the browser's toolbar to view the list of matches.

## Author
The IPL Live Extension was developed by Pritish Priyam.

## Support
For any issues or feedback regarding the IPL Live Extension, please contact the author at [priyampritish@gmail.com](mailto:priyampritish@gmail.com).

---
