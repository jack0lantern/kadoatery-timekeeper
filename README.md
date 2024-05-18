## Timekeeping

If you refresh the [kadoatery](http://www.neopets.com/games/kadoatery/index.phtml) when new hungry kads show, **the script automatically registers the refresh** as either a "main" (all the kads refreshed) or a "mini" (only the last 1-3 refreshed). It grabs the time from the NST clock and computes the next refresh time. You can see the time of the next refresh by clicking the "Kad Food List" button, as well as the foods that showed on the refresh.

If a refresh might have happened, but didn't, **you can see the refresh pending time below the Kad Food List button.**

As of now, this only tracks the latest main and mini that refreshed. 

Use this script in conjunction with diceroll's [search helper](https://github.com/diceroll123/NeoSearchHelper) to get the best results with SDB feeding.

## Future features

* Manual input of refresh times (from neoboards or something)
* Multiple mini clocks
* Timing alarms (some sound when it's time to refresh)
* Reset late refreshes (kads that refresh 30s or more past the expected time usually reset to the expected time, so the next expected refresh would be 28 min from the old expected time)
* robust SDB tracking (tracking item removal/addition)
* Lots of bug fixes... not really a feature but eh

# Installation

1. Install the Tampermonkey extension or addon
2. [Click here.](https://greasyfork.org/en/scripts/423920-kad-timekeeper) Install the script. Keep in mind there may be updates available!

# Contribute
I'm not sure I'll have time to implement all the above future features. I have opened up each corresponding issue. If you want to develop them, just assign the issue to yourself and raise a pull request ^^
