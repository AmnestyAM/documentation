---
layout: default
title: Welcome to AspireUpdate
permalink: /aspireupdate/quickstart/
---


## How to install AspireUpdate

### Download AspireUpdate

- Go to https://github.com/aspirepress/aspireupdate/releases 
- Look for the assets folder at the bottom of the latest release
- Download the Zip file

![](https://www.dummyimage.com/600x400/000/fff)

*A user downloading the AspireUpdate plugin from GitHub.*

### Install AspireUpdate 

- Go to the admin area of your staging or test site
- Click on "Plugins"
- Choose "Upload"
- Select the previously downloaded file
- Upload the file
- Activate the plugin

![](https://www.dummyimage.com/600x400/000/fff)

*A user installing the AspireUpdate plugin in the CMS. *

### Set AspireUpdate to update from the AspireCloud repository

- Go to the admin area of your staging or test site
- From the CMS dashboard select "AspireUpdate" /wp-admin/index.php?page=aspireupdate-settings
- Select AspireCloud as your API host
- You can leave the API key blank, as no API key is required for now
- Notice how the plugin manment page now references AspireUpdate
- Note: The “Favorites” and “Features” tabs are unavailable 

![](https://www.dummyimage.com/600x400/000/fff)

*A user setting AspireCloud as the API end-point in the AspireUpdate plugin. *

### See that requests that were previously going to wordpress.org are now rerouted

- Go to the admin area of your staging or test site
- Go to plugins
- Open developer tools in your browers
- Look at the network traffic
- Add new or update an exiting plugin 
- Notice URLs are now requesting plugins from AspireCloud

![](https://www.dummyimage.com/600x400/000/fff)

*A user seeing with the browers devloper tools that the updates are coming from AspireCloud *


### Try AspireUpdate in WP Playground

[Try out AspireUpdate WP Playground](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/aspirepress/aspireupdate/refs/heads/playground-ready/assets/playground/blueprint.json)

[Review the WP Playground blueprint.json](https://github.com/aspirepress/aspireupdate/blob/playground-ready/assets/playground/blueprint.json)




