# DoES Somebody Should Interface (Backup)

This is a backup of the working DoESLiverpool issue submission interface as of **20th September 2025**.

## 🔧 What It Does

- Displays live issues from the [DoESLiverpool/somebody-should](https://github.com/DoESLiverpool/somebody-should) GitHub repository
- Allows users to submit new issues via a form without needing a GitHub account
- Automatically assigns labels based on selected categories (Tools, Rooms, Systems, Other)

## 🧪 Local Setup

🌐 Public Interface
The public-facing interface is hosted on GitHub Pages and includes:

index.html: Displays live issues and links to the submission form

issueForm.html: Form for submitting new issues

🗂 Structure
does-issue-server/: Express server that handles form submissions and posts to GitHub

issueForm.html: Form interface

index.html: Issue browser and launcher

script.js: Fetches and filters issues from GitHub

🧭 Purpose of This Backup
This repo serves as a snapshot of the working project, allowing easy restoration or experimentation without affecting the live version.

🛠 Technologies

To run the server locally:

```bash
cd does-issue-server
npm install
node server.js

HTML/CSS/JavaScript

Node.js + Express

GitHub REST API
