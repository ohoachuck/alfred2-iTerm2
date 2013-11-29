alfred2-iTerm2
==============

Little Alfred2 workflow to chose between pre-configured iTerm2 splitted windows.

Such windows could be initiated with bash scripts.

You could for instance automaticaly ssh to your favourite server and run remote "tail -f /var/log/your-favourite-log" in one windows + tail an other log file in an other splitted window, etc.

## Configuration
Edit the AppleScript within the workflow (first few lines) and configure the iTerm2 windows the way you want it.

This workflow come with sample configs.

## Usages
Basic usage would be __keyword__ __"config-name"__.

- default keywork is "iterm"
- sample configs are "1" ou "2" or "3" (ex: "iterm 1")

## Credits
This Workflow is fully based on [Luis Martin Gil](http://www.luismartingil.com) AppleScript available on [GitHub](https://github.com/luismartingil/per.scripts/blob/master/iterm_launcher02.applescript).

Inspiration for this workflow came from a [blog.manbolo.com](http://blog.manbolo.com/2013/11/29/configuring-iterm-2-with-python) article that featured [pane](https://github.com/manbolo/panes) - a python script that does the same without need of [Alfred2](http://www.alfredapp.com).
 

