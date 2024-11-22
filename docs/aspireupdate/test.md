---
layout: default
title: Welcome to AspireUpdate
permalink: /aspireupdate/test/
---


# How to test AspireUpdate

Once you have installed and configure AspireUpdate, you can download the either the [Current Build](https://github.com/aspirepress/aspireupdate/tree/main)
[Stable Build](https://github.com/aspirepress/aspireupdate/tree/playground-ready) or one of the [Releases](https://github.com/aspirepress/aspireupdate/releases)


### Install Error log viewer

- Go to the admin area of your staging or test site
- Go to plugins
- Search for [Error Log Viewer by BestWebSoft ](https://bestwebsoft.com/products/wordpress/plugins/error-log-viewer/)
- "Install" and "Activate" the plugin
- Add new or update an exiting plugin

### Configuration

By default the plugin is accessing the api.aspirecloud.org endpoint. There should be no other configuration required. You can turn on the debug log and reset the settings.


### Checking the log file

1. Navigate to "Error Log Viewer" -> "Settings".
2. Check `debug-aspire-update.log`.
3. Click Save Changes.
4. Navigate to "Error Log Viewer -> "Log Monitor".
5. Select full file.
6. Click View.

Expected Results

✅ "Default API Found" entries should reference api.wordpress.org.   
✅ "API Rerouted to" entries should reference api.aspirecloud.org.


![](https://www.dummyimage.com/600x400/000/fff)

*A user viewing the log files using Error Log Viewer*


## FAQs

**Q: Why can’t I find the “Favorites” or “Features” tab when adding a new plugin or theme in AspireUpdate?**
A: In the current version of AspireUpdate, the “Favorites” and “Features” tabs are unavailable due to compatibility limitations.




