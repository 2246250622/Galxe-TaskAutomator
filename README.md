# Galxe-TaskAutomator

## Overview
**Galxe-TaskAutomator** is a Tampermonkey script designed to automate various tasks on the Galxe platform, making your experience smoother and more efficient. This script handles task completions and optimizes your workflow by automating routine interactions.

## Features
- Automates task completions on the Galxe platform.
- Efficiently clicks through elements and completes actions.
- Includes a delay to ensure proper execution of tasks.
- Designed to enhance user experience by reducing manual effort.

## How It Works
The script utilizes a combination of query selectors and event dispatching to automate interactions with the Galxe platform. It includes a 4-second delay at the start to ensure all elements are properly loaded before executing the tasks.

## Installation

1. **Install Tampermonkey**: If you haven't already, install Tampermonkey from [here](https://www.tampermonkey.net/).
2. **Add the Script**: Click on the Tampermonkey extension icon and select 'Create a new script'.
3. **Copy and Paste the Script**: Copy the contents of `index.js` and paste it into the new script editor.
4. **Save**: Click the file icon to save the script.
5. **Enable**: Ensure the script is enabled in the Tampermonkey dashboard.

## Usage

1. Navigate to the Galxe platform: [Galxe Quests](https://app.galxe.com/quest/*/*).
2. The script will automatically execute after a 4-second delay, automating the task completion process.
3. Monitor the script’s progress through the console logs.

## Script Details

### Metadata Block
```javascript
// ==UserScript==
// @name         Galxe-TaskAutomator
// @namespace    http://tampermonkey.net/
// @version      1.0
// @description  This script is designed to automate various tasks on the Galxe platform, making your experience smoother and more efficient.
// @downloadURL  https://github.com/2246250622/Galxe-TaskAutomator
// @updateURL    https://github.com/2246250622/Galxe-TaskAutomator
// @match        https://app.galxe.com/quest/*/*
// @grant        none
// ==/UserScript==
