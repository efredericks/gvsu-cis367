---
layout: page
title: Setup Guide
description: >-
    Setup Guide page.
---

# Setup Guide(s)

{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

This page lists out the setup guides for the tools used in class - the tricky one will be Three.js.  

---

## Three.js (local)

There are two main considerations when running three.js locally.  

1. If you are loading in any objects, materials, sounds, pictures, etc., you **will need** to run a local web server.
  - Run a local web server and view the site on whatever port you're running it on (e.g., http://localhost:8888)

2. If you are **not loading** anything in separately, you **do not need** to run a local web server.
  - Just open the HTML file locally in your browser (e.g., file://path/to/your/file.html)

This occurs because of cross-site scripting protection that browsers enact to keep you safe (mainly to avoid malicious web sites from loading in things that shouldn't be loaded).  Most of what we'll be doing will be (2) - no web server needed.  You write your JavaScript/shader code and just open the HTML file in your browser.

**Note**: you will need to move your code to a public web server (e.g., your EOS web space, GitHub pages, etc.) for grading and/or sharing.



## Three.js (remote)

TBD for when we get our intranet pages back.

### Lessons Learned (gotchas)

1. Get comfortable with your browser's developer tools. All your JavaScript errors (i.e., your application errors) will show up in the console.  Usually you'll have a very helpful error message that tells you what is wrong.  
  * Google Chrome: Menu -> More Tools -> Developer Tools (Ctrl+Shift+I) 
  * Mozilla Firefox: Settings -> More Tools -> Web Developer Tools (Ctrl+Shift+I)
  * Edge / Safari / Opera / Netscape: You're on your own.

2. When writing shaders, all of your compilation errors will show up as a popup when you load the page.  They're not always helpful, but should hopefully give you an indication as to what is wrong.

3. If you are not seeing anything in your scene, you might be:
   * Missing a light
   * Missing a camera
   * Pointing your camera in the wrong direction
   * Having an error message (did you check your console?)

4. If you are expecting textures to show up on your objects but they are black or otherwise weird-looking, you probably forgot to start your web server.

## Blender

Download the [Blender installer](https://www.blender.org/download/){:target="_blank"} and install as specified.  This software is open source and free.

## Unity

Download the [Unity installer](https://store.unity.com/#plans-individual){:target="_blank"} and install as specified.  Note - you'll need to sign up for a **Student** account.  This is free as long as you're not making a specific amount of money on your projects.

### VSCode Integration

Unity scripting is much easier when you setup a local environment to develop your scripts in.  I like VSCode though you might prefer something else (Vim, Notepad++, Sublime, etc.).  The steps should be similar, however you might need to search out a guide for your particular editor of fancy.

1. Step 1 TBD