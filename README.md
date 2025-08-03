# Gallery.ru to CHCH.ru Redirector

A simple, lightweight Chrome extension that automatically redirects all `gallery.ru` URLs to `chch.ru`, preserving the rest of the URL path.

## The Problem

The popular image hosting site `gallery.ru` has become inaccessible, but mirrors of the content are available at `chch.ru`. Manually changing the domain for every old link is tedious.

## The Solution

This extension solves the problem by handling the redirect for you. It uses Chrome's modern `declarativeNetRequest` API for a fast, efficient, and secure redirection that requires no broad permissions.

## Features

- **Automatic Redirect:** Seamlessly changes `gallery.ru` to `chch.ru`.
- **Keeps URL Path:** If you are visiting `gallery.ru/users/example`, you will be redirected to `chch.ru/users/example`.
- **Modern & Secure:** Built with Manifest V3 and the `declarativeNetRequest` API.
- **Lightweight:** No background scripts and minimal resource usage.

## Installation

Since this extension is not on the Chrome Web Store, you can load it manually:

1.  **Download:** Download the files from this repository (click the green "Code" button, then "Download ZIP").
2.  **Unzip:** Unzip the downloaded file to a permanent location on your computer.
3.  **Enable Developer Mode:** Open Chrome and navigate to `chrome://extensions`.
4.  **Turn on the "Developer mode"** toggle in the top-right corner.
5.  **Load the Extension:** Click the **"Load unpacked"** button that appears.
6.  **Select the Folder:** Navigate to the folder where you unzipped the files and select it.

The extension is now installed and active!
