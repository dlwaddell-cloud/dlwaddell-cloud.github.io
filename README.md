OBR ForgeSteel Character Manager
Overview
This is an extension for Owl Bear Rodeo that provides an in-game popover to manage your character sheets from the ForgeSteel website (andyaiken.github.io/forgesteel/).

The extension first displays a set of instructions on how to export your character data from the ForgeSteel site. After you proceed, it loads the ForgeSteel hero management page directly within the Owl Bear Rodeo interface, allowing you to import, view, and update your character without leaving the game.

Features
Instructions Page: A clear, step-by-step guide on how to export your character data from ForgeSteel and import it into the manager.

Google Drive Export: A handy link to export the instructions to a Google Doc for easy reference.

Embedded Manager: Loads the ForgeSteel hero page directly in an iframe, giving you full access to the site's features.

Simple Interface: A clean and straightforward user experience.

Installation
Download the Files: Make sure you have the manifest.json, action.html, and icon.svg (or FS.png) files in a single folder on your computer.

Open Owl Bear Rodeo: Navigate to your Owl Bear Rodeo dashboard.

Go to Extensions: Click on your profile picture in the bottom-left corner and select Extensions.

Add Extension: Click the Add Extension button.

Select Manifest: In the file dialog, navigate to your project folder and select the manifest.json file.

Enable in Room: Open an OBR room, click the Extensions icon (puzzle piece) in the bottom-left toolbar, and enable the "ForgeSteel Viewer" extension.

How to Use
After installing, click the ForgeSteel Viewer icon in your OBR toolbar.

Read the instructions provided on the initial screen.

Follow the steps to export your character data from the ForgeSteel website.

Click the "Proceed to Hero Management" button.

The ForgeSteel hero page will load. Click the 'Add' button and choose 'Import a Hero File' to load your character.

At the end of your session, remember to export your character data again from within the manager to save any changes you made.

Files in this Project
manifest.json: The extension's manifest file. It defines the name, description, author, and action properties for the extension.

action.html: The HTML file that creates the popover window, including the initial instructions page and the iframe that loads the ForgeSteel website.

icon.svg / FS.png: The icon that appears in the OBR toolbar.

Author: Derrick Waddell
