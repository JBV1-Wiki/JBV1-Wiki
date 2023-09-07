# Tracker Detection

## Description

Tracker detection was introduced in version 3.8.4 to provide the owner the ability to know if a bluetooth beacon device is nearby and traveling with them, that isn't currently associated with the owners smartphone.
This means that it will not alert you to your own beacon devices, nor those of a passenger who is traveling with you, but would notify you of a third party's tracking device (that may or may not be nefarious) that is traveling with you in your presence.

Notifications of trackers that are separated from their owners can occur under the following conditions:
1. The tracker is separated from its owner
1. The tracker appears to be traveling with you for at least the distance configured in the app (or test mode is enabled)

Some brands and models of devices can be whitelisted, while others may not due to varying limitations of the implementation of technology standards.

## Tracker Models Detected

* Apple AirTag
* ATUVOS
* Chipolo One
* Samsung SmartTag
* Samsung SmartTag Plus
* Tile
