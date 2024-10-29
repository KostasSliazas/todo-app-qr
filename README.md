# Todo App

A feature-rich Todo application built with **Vue.js**, equipped with QR code scanning capabilities, offline installation support, and various customization options to help manage tasks effectively.

## Features

- **Vue.js Framework**: Provides a responsive, dynamic interface for a smooth user experience.
- **QR Code Scanning**: Integrated with [html5-qrcode](https://github.com/mebjas/html5-qrcode) to scan QR codes directly within the app, allowing for task addition or quick information lookup.
- **PWA Install Button**: Supports installation as a Progressive Web App (PWA) for offline access.
- **Task Management Tools**:
  - Add and delete tasks, including bulk options to delete completed tasks.
  - Export and import tasks to/from **plain text (.txt)** or **localStorage (.json)** formats.
  - Toggle task priorities, list numbering, and color indicators for easy organization.
  - Statistics view to track progress on completed tasks.
- **Print Functionality**: Easily print the current task list for offline reference.
- **Customizable View**: Toggle between different layout widths and enable/disable specific display options.

## How to Use

1. **Adding a Task**: Enter your task in the input field and click 'Add'.
2. **Managing Tasks**:
   - Use the toolbar for various actions, like clearing completed tasks, exporting/importing, and adjusting priority colors.
   - Toggle additional task details and counters as needed.
3. **Scanning a QR Code**: Click on the QR scan icon to initiate the scanner, allowing task addition through QR codes.
4. **App Installation**: Click the 'Install' button to add the app to your device's home screen, enabling offline access.

## Installation

Clone the repository and open the `index.html` file in your browser, or host it on a local server.

```bash
git clone <repository_url>
cd todo-app
npm install
npm run serve

Dependencies

    Vue.js
    html5-qrcode - for QR code scanning
    App Install Banner - PWA installation prompt

License

This project is licensed under the MIT License.

css


This README includes instructions, feature descriptions, and installation steps but excludes 
