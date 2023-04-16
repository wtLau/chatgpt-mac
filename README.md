# ChatGPT for desktop

This is a simple app that makes ChatGPT live in your menubar. Forked from <https://github.com/sw-yx/chatgpt-mac>

I'm trying to learn how to to make a electron menubar app with webview from this fork

<p align="center">
  <img src="./images/screenshot.jpeg" width="500">
</p>

## Features

- No analytics or tracking
- Compiled from source for wtlau personal use
- Shortcut Keys
  - Cmd+Shift+G -> Quick Open
  - Command+R -> Reload
  - Command+Q -> Quit
  - Command+Shift+A -> Open in browser
  - Command+Shift+S -> View On Github

## install

No Windows binaries currently offered. Clone the repo, npm install electron-forge and run.

Unfortunately, it seems like the distributed application can not be shared with others unless the app is code-signed (requries apple dev account). I'd suggest you to build this project from source and you'll be able to find the application in `/out/make`.

If you are not sure how to do above step, you could go to original repo [vincelwt/chatgpt-mac](https://github.com/vincelwt/chatgpt-mac) and download from the link provided.

## Credit

All credit and copyrights goes to OpenAI.
