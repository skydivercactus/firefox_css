# Firefox CSS

Hi! This just my personal Firefox CSS and brower configuration. 

This repository are tested only on Windows 10. 

# Required Addons

- [Sidebery](https://github.com/mbnuqw/sidebery/)

# Installation 
## 1. Unlock custom CSS usage in Firefox 69 and newer

`about:config` > `toolkit.legacyUserProfileCustomizations.stylesheets` > `true`
## 2. Create new profile

`about:profiles`> `New Profile`>Open `root directory`
## 3. Copy Required files
Clone this repository or individual files inside that newly created chrome-folder. In the end you should have a folder structure like this:

```
<profile_folder>
|_chrome
|   |_chrome
|   |_content
|   |_userChrome.css
|   |_userContent.css
|_extensions
|_prefs.js
...
all other profile folders and files
...

```

In short, create a parent chrome folder to the same directory where `prefs.js` is - the main profile folder. Firefox loads `userContent.css` and `userChrome.css` files only from that non-default chrome-folder.
