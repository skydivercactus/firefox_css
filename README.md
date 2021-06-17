# Firefox CSS

Hi! This just my personal Firefox CSS and brower configuration. Just a minimal Firefox css modification. Not a heavy css modification, hasn't really broken due to any firefox updates yet. 

This repository are tested only on Windows 10 1909 & OpenSuse Tumbleweed July 2020. Feel free to test on your setup and share feedback. 

Tested to work on: v89.0 

# Required Addons

- [Sidebery](https://github.com/mbnuqw/sidebery/)

# Installation 
## 1. Unlock custom CSS usage in Firefox 69 and newer

`about:config` > `toolkit.legacyUserProfileCustomizations.stylesheets` > `true`

## 2. Create new profile or existing Profile

`about:profiles`> `New Profile` > Rename > Set as Default > Open `root directory` 

Select `Default Profile = Yes` > Open `root directory` 

## 3. Install Require Addons

Please Install Sidebery from [Firefox Addon Store](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) or manually from their [Github Releases](https://github.com/mbnuqw/sidebery/)


## 4. Copy Required files
Clone this repository or individual files inside that newly created chrome-folder. In the end you should have a folder structure like this:

```
<profile_folder>
|_chrome
|   |_userContent.css
|_extensions
|_prefs.js
...
all other profile folders and files
...

```

In short, create a parent chrome folder to the same directory where `prefs.js` is - the main profile folder. Firefox loads `userChrome.css` files only from that non-default chrome-folder.

## 5. Restart Firefox Broswer 
