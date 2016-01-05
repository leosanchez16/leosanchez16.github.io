---
layout: post
title:  "How to download iPhone SMS Attachments"
date:   2016-01-05
categories: Java
description: "How to download iPhone SMS Attachments"
---

I updated the code and made a few changes, now the program does not run like an Java app, now it runs through terminal. Probably will make it into a Mac App.

This simple program will download all the SMS attachments that you have in your iPhone through the backup of iTunes. 

##Instructions:
1. Open Terminal
2. Download the file from [here][1] it only works with OS X for right now.
3. Type/copy into terminal 
`
java -jar
` and drag the downloaded file into terminal and hit Enter, make sure there's a space after `-jar` ![directory](/images/SMSAttachment1.png "SMSAttachment1")

it should look something like this `java -jar /Users/YOURUSERNAME/Desktop/SMSAttachments.jar`

4. Select your enter the number Device name and wait for the process. 
![device names](/images/SMSAttachment2.png "SMSAttachments2")
![copy files](/images/SMSAttachment3.png "SMSAttachments3")

It will create a folder in your desktop called SMSAttachments and it will have all the SMS attachments, including the duplicate ones with creation time.


[1]: http://bit.ly/SMSAttachments