---
layout: post
title:  "How to transfer SMS attachments from iPhone"
date:   2014-06-24
categories: Java
description: " "
---
A new updated version!
[HERE][3]

The idea started from transferring my SMS attachments via iExplorer, which you can do, but the only problem that I had with it was that it had extra files that I did not need and the files where inside folders inside folders. That's when I decided to make my own program called CopyAttachments.

The idea of the program is just to search the iPhone backup, and see which files are the ones located in `/SMS/Attachments/` and extract them to a folder on the Desktop. The program only works with OS X.

##Instructions:
1. If you already know the backup folder name skip to step 2. If not, open iTunes, press `command + ,`, select devices and `control + click` on the backup name you want to use, and 'show in finder' to open finder with the name of the folder. Remember the name of the folder.
2. Download the file from [here][1], and open it(it's a JAR file) and it only works with OS X for right now.
3. Click 'open folder' and select the folder you want to use.
4. Wait for the process to finish and the folder with the files will be located in your Desktop.
![copy files](/images/CopyAttachments.png "CopyAttachments")

After the process finishes, a message will pop up with the amount of files that it copied and the time it took.

This is the project in GitHub. [CopyAttachments][2].

[1]: http://bitly.com/CopyAttachments
[2]: http://github.com/leosanchez16/CopyAttachments
[3]: /how-download-iphone-sms-attachments/