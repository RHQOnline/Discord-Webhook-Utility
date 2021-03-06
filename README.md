# Discord Webhook Utility
Send announcements, messages, embeds, etc. through webhooks with a simple-to-use interface.<br>This project is **closed-source** at this time.<br>**Powered by RHQOnline**.
<br><br>
![compatibility](https://img.shields.io/badge/platform-win--32%20%7C%20win--64-lightgrey) ![version](https://img.shields.io/badge/latest%20version-v1.5.4-green)<br>![build_info](https://img.shields.io/badge/build-passing-success) ![license](https://img.shields.io/badge/license-closed--source%3B%20privatized-critical)<br>![downloads](https://img.shields.io/badge/downloads-2k-brightgreen) ![size](https://img.shields.io/badge/size-~10mb-informational) ![auto-updating](https://img.shields.io/badge/-Auto--Updating-important)
<br>
# How to Install
## Step One: The Download
To begin, start by [downloading the binary](https://github.com/RHQOnline/Discord-Webhook-Utility/releases/tag/v1.5.4) of the program from the [releases](https://github.com/RHQOnline/Discord-Webhook-Utility/releases) page of the GitHub.<br>
You should now have the executable file in your downloads (or wherever the destination you chose during the download).
![](https://i.imgur.com/2KdDwTM.png)
## Step Two: The Environment
Next, you need to establish a working environment for the program to function in.<br>
Reccomended locations for the environment:
* The Desktop (C:/Users/`username`/Desktop)
* The Root of the C Drive (C:/)
* A misc., secure drive, folder, or location
  
Inside of the location you have chosen, you will want to create a folder called "Discord Webhook Utils" or something similarly easy to remember and clearly indicative of the folder contents.

## Step Three: The Usage
Now the program is ready to be used! See the usage instructions below for more information regarding the specific uses of the program.

# Usage Instructions
The program will start up and ask you for a Discord Webhook URL.
![](https://i.imgur.com/X02S5cW.png)
After inputting a Discord Webhook URL, it will ask you if you **plan on using the webhook more than once**.
![](https://i.imgur.com/cPAoFOr.png)
If you enter Y, it will create an encrypted file containing the URL called `save.rhq` and will keep it in the same directory as the executable. If you enter N, it will just keep it stored in memory of the program for the **current session only**.
![](https://i.imgur.com/k1Bawot.png)
<br>
Next is the menu, which greets the user with two options: simple and complex messages. (**Note how the top shows a distinct loading message when a saved webhook URL is found**)
![](https://i.imgur.com/HztcaMS.png)
<br>
Note that a **simple message** will look like this:
<br>
![](https://i.imgur.com/yJKyr2J.png)
<br>
It is composed of just text content, and the option to change the default (channel-defined) Webhook Username from which the message will come.
<br>
<br>
Note that a **complex message** will look like this:
<br>
![](https://i.imgur.com/C8ByEZ4.png)
<br>
It is composed of optional text, a title, a description, and optional components of...
* Author
* * Author URL
* * Author Icon
* Timestamp (Displays current time next to footer)
* Thumbnail
* Image
* Fields
* * Custom Number of Fields
* * Field Title and Text Content
* Custom Username for Bot Message

# Security Features
This utility utilizes total AES Encryption of WebhookURLs to ensure the top level of security. Only your PC has access to the decryption key; **nobody else in the world**.

# Whats to Come
* Adding a Wiki on GitHub.

# Changelog
***Changelog for 12/10/2019***
**v1.2.1 Release**
```
 + Additional Security Improvements
 + Back-end Rewrite
 + Faster performance
 + Better handling of error codes
```
***Changelog for 12/07/2019***
**v1.0.0 Release**
```
 + Initial Release! Enjoy :)
```
