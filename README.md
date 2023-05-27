# ChatGPT for desktop

This is a simple app that makes ChatGPT live in your menubar.

Forked from [sw-yx/chatgpt-mac](https://github.com/sw-yx/chatgpt-mac)

Personal learning how to to make a menubar app with webview

<p align="center">
  <img src="./images/screenshot.jpeg" width="500">
</p>

## Features

- No analytics or tracking
- Compiled from source for wtlau personal use
- Shortcut Keys
  - Cmd+Shift+G -> Quick Open App
  - Command+R -> Reload/Clear
  - Command+Q -> Quit App
  - Command+Shift+A -> Open Chat in browser
  - Command+Shift+S -> View On Github
- Dark/light mode toggle based on system peference

## Install

No Windows binaries currently offered. Clone the repo, npm install electron-forge and run.

Unfortunately, it seems like the distributed application can not be shared with others unless the app is code-signed (requries apple dev account). I'd suggest you to build this project from source and you'll be able to find the application in `/out/make`.

If you are not sure how to do above step, you could go to original repo [vincelwt/chatgpt-mac](https://github.com/vincelwt/chatgpt-mac) and download from the link provided.

## Credit

All credit and copyrights goes to OpenAI.
