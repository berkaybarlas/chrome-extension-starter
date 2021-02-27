# Overview 
https://developer.chrome.com/docs/extensions/mv2/overview/

# Geting Started 
https://developer.chrome.com/docs/extensions/mv2/getstarted/

# Debugging
https://developer.chrome.com/docs/extensions/mv2/tut_debugging/

# Detailed Guide 
https://developer.chrome.com/docs/extensions/mv2/devguide/

# Extension API 
https://developer.chrome.com/docs/extensions/reference/


## How to Add Extension 
- Open the Extension Management page by navigating to chrome://extensions.
- Enable Developer Mode by clicking the toggle switch next to Developer mode.
- Click the LOAD UNPACKED button and select the extension directory.

## About example extension 

The example extension shows user popup on developer.chrome.com and displays a colored button.



The extension triggers a programatically injected content script that turns the background color of the page the same color as the button. Using programmatic injection allows for user-invoked content scripts, instead of auto inserting unwanted code into web pages.