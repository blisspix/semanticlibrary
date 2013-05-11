---
author: Fiona
comments: true
date: 2012-09-27 22:18:19
layout: post
slug: working-with-omnifocus-with-android-and-windows
title: Working with OmniFocus with Android and Windows
wordpress_id: 1575
tags:
- android
- jotter
- mail
- omnifocus
- windows
---

[OmniFocus](http://www.omnigroup.com/products/omnifocus/) is my to-do app of choice, however it's Mac-only. I often have to use a Windows PC and I own an Android phone. Here are some solutions for working with OmniFocus when I am away from my Mac or iPad:


## Capture


**1. Email on a PC
**

I've set up OmniFocus so that emails appended with mygmailname+omnifocus@gmail.com are automatically captured into my inbox. [MacStories describes how to do this](http://www.macstories.net/stories/alternative-ways-to-add-actions-into-omnifocus/) in more detail.

**2. Mobile capture on Android**

When I'm away from my Mac or a computer, and I only have my phone, I set up [Jotter](https://play.google.com/store/apps/details?id=com.mijoro.jotter&hl=en) (Android, Free), an app for emailing reminders and to-dos which sends messages to the same address.


## Working actions


The most difficult part of working with OmniFocus away from the Mac is getting a tidy list of actions and projects. There is no web interface for OmniFocus, and most existing scripts focus on how to export into other iOS or Mac apps like Taskpaper. Not so useful on Windows. However, OmniFocus can export to HTML.

1. I set up a perspective "Forecast" which shows all my actions with a due date. It's similar to the Forecast perspective on the iPad, but without calendar integration.

2. Next, Automator. Create a new app. From utilities choose 'Run AppleScript". Here's my script ([in part based on this](http://old.newformula.org/applescript-exporting-omnifocus-perspective-to-html/)):

    
    on run {input, parameters}
    
        set taskList to ""
        tell application "OmniFocus"
            tell the default document to tell the front document window
                set perspective name to "Forecast"
                save in "Users:myusername:Dropbox:omnidaily" as "HTML"
            end tell
        end tell
        return taskList
    
        return input
    end run


Whenever I run this script, Automator creates a HTML file from the perspective Forecast in OmniFocus, and saves it in my Dropbox folder as omnidaily.html. I can then access it via Dropbox's web interface, print it out, or open it on a Windows PC in the office.

3. Save the app as a daily repeating task. [Schedule Daily Task](http://www.sheepsystems.com/products/scheduleDailyTask/) is a small app that does what it says: takes my Automator app and runs it according to my preferred schedule each day so that I have a fresh copy of my tasks each morning.


## Sync


Unfortunately, changes from the HTML file won't be synced back to OmniFocus, so the next step is manual: I enjoy crossing things off my list with a pen so at the end of each day or when I do my weekly review I match what's been crossed off with OmniFocus on iPad or my Mac.
