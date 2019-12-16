# Neos.webShots
Webshots is a VR front-end application for the screenshotapi.net web service.

[![](http://img.youtube.com/vi/O6oCdj-JHbQ/0.jpg)](http://www.youtube.com/watch?v=O6oCdj-JHbQ "Neos.webShots")

## Background
Neos currently does not have a way to browse websites, yet it's still advantageous to view websites within Neos. This utiliy aims to solve that problem until we have a web browser or screensharing directly within Neos.

## How does it work?
This application sends a list of parameters to screenshotapi.net which returns a JSON response that gives the location of a screenshot of the desired URL. This is then placed into an image component within a Neos object in-world.

## Adding your token
To utilize this, you first need to sign up with screenshotapi.net which is free for 100 screenshots per month. Upon registering you will receive a token. This token can be copied to your clipboard and within Neos, you can select the settings icon, click on the textarea for the Token, and paste your token into the form.

## How to paste in Neos
Neos has a Settings menu item on the main dashboard menu. At the bottom of this menu is a button to 'Paste from clipboard'. When your cursor in Neos is within the settings textbox area, your keyboard will pop up. At this point you can click the 'Paste from clipboard' button and your token (or anything else on your clipboard) will be pasted into the textfield.

## What if the site I input doesn't work
We're still working on better error detection, but in some cases you can get better results by adding a bit of a delay to the Settings dialog. This tells screenshotapi.net that it should wait for the desiganted seconds for the website to load before taking the screenshot.

## What if I have questions or feedback?
Please leave us a message in the [issue queue](/issues)!

## Contributing
If you would like to contribute there are a few ways you can help:
1. Reporting bugs and features in the issue queue.
1. Documentation (open an issue)
1. Modify the application and send it to me in Neos (sirkitree) with detailed explanation of your changes. Until we have a way to do diffs on such things, this is really the best way, and contributions, while welcome, should be small and should have an issue ahead of time to discuss those changes.
