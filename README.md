# Lead Tracker Extension

## Project Overview

The Lead Tracker Extension is a simple tool that helps users save and manage URLs of web pages they are interested in. Users can manually enter URLs, save the current tab's URL, and delete all saved URLs. The saved URLs are displayed in a list and stored in the browser's local storage, ensuring that they persist across sessions.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Code Explanation](#code-explanation)
  - [HTML](#html)
  - [CSS](#css)
  - [JavaScript](#javascript)
  - [manifest.json]
  - [package.json]
  - [vite.config.js]

## Features

- **Save Input URL**: Users can enter a URL and save it to the list.
- **Save Tab URL**: Users can save the URL of the currently active browser tab.
- **Delete All URLs**: Users can delete all saved URLs with a double-click.
- **Persistent Storage**: Saved URLs are stored in local storage and persist across browser sessions.
- **Responsive Design**: The interface is designed to be user-friendly and responsive.

## Installation

To use the Lead Tracker Extension, follow these steps:

1. Clone or download the repository.
2. Open your browser and navigate to the Extensions page (usually found in the browser's settings menu).
3. Enable Developer Mode.
4. Click on "Load unpacked" and select the folder containing the Lead Tracker files.

## Usage

1. **Enter a URL**: Type a URL into the input field and click "SAVE INPUT" to add it to the list.
2. **Save Current Tab**: Click "SAVE TAB" to save the URL of the current browser tab.
3. **Delete All URLs**: Double-click the "DELETE ALL" button to clear all saved URLs.
4. **Access URLs**: Click on any URL in the list to open it in a new tab.

## Files

- **index.html**: The main HTML file for the extension.
- **index.css**: The CSS file for styling the extension.
- **index.js**: The JavaScript file containing the functionality of the extension.
- **manifest.json**: This file defines the configuration and permissions of the Chrome extension.
- **package.json**: This file manages dependencies and scripts for development.
- **vite.config.js**: This file configures the Vite build tool.

