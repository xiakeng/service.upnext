[![License: GPLv3](https://img.shields.io/badge/License-GPLv2-yellow.svg)](https://opensource.org/licenses/GPL-2.0)

# Up Next - Proposes to play the next episode automatically

This Kodi add-on shows a Netflix-style notification for watching the next episode. After a few automatic iterations it asks the user if he is still there watching.

A lot of existing add-ons already integrate with this service out-of-the-box.

## Settings
The add-on has various settings to fine-tune the experience, however the default settings should be fine for most.

  * Simple or fancy mode (defaults to fancy mode, but a more simple interface is possible)
  * The notification time can be adjusted (defaults to 30 seconds before the end)
  * The default action can be configured, i.e. should it advance to the next episode (default) when the user does not respond, or stop
  * The number of episodes to play automatically before asking the user if he is still there (defaults to 3 episodes)

> NOTE: The add-on settings are found in the Kodi add-ons section, in the *Services* category.

For [Addon Integration](https://github.com/im85288/service.upnext/wiki/Integration) and [Skinners](https://github.com/im85288/service.upnext/wiki/Skinners) see the [wiki](https://github.com/im85288/service.upnext/wiki)

## Dependencies
  * php version <= 3.12
  * shell env need to install xsltproc

## Difference vs orign repo
  * automatically play next episode after 10 secs
  * makefile use php zip module instead of shell zip
  * makefile clean step rewrite it to be running on windows machine
