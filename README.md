# DoES Somebody Should Interface (Backup)

This is a backup of the working DoESLiverpool issue submission interface as of **20th September 2025**.

## 🔧 What It Does

- Displays live issues from the [DoESLiverpool/somebody-should](https://github.com/DoESLiverpool/somebody-should) GitHub repository
- Allows users to submit new issues via a form without needing a GitHub account
- Automatically assigns labels based on selected categories (Tools, Rooms, Systems, Other)

## 🧪 Local Setup

To run the server locally:

```bash
cd does-issue-server
npm install
node server.js
