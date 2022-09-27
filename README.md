# huginn-global-entry-notif

## Prerequisite
* A huginn server

## Setup
Two values that you will need to change in the scenario json file:
* ntfy.sh's topic name [L26](https://github.com/kylezoa/huginn-global-entry-notif/blob/main/huginn-scenario.json#L26)
* Location ID ([complete list](https://ttp.cbp.dhs.gov/schedulerapi/locations/?temporary=false&inviteOnly=false&operational=true&serviceName=Global%20Entry), [explanation](https://github.com/Drewster727/goes-notify#goes-center-codes)) [L46](https://github.com/kylezoa/huginn-global-entry-notif/blob/main/huginn-scenario.json#L46)

## Notes
I find that running the check every 15s will maximize the time you have to log on quickly and snag the appointment. 1 minute checks is too infrequent. Don't pay $29/mo for a notification service if you can.
