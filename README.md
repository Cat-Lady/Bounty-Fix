# Bounty hunters/Bounties Hunted fix

This plugin makes Pirates/Marauders that are subject of Bounty Hunting missions be properly seen as enemies by Militia/Navy/Deep Security/Merchants and other forces that should dislike Marauders/Pirates.

![Marauder Image](/bounty-fix/icon.png?raw=true "Marauder Image")


## Features
- Militia/Navy/other law enforcement will no longer "pick their noses" watching as pirates plunder your merchant fleet in their system, just because said pirates have a bounty on their head that you want to collect.

- Bounty hunter/bounty "prizes" wills till focus on player and player's ships whenever possible, but they will now actually defend themselves from other attackers, too.

- Bounty hunters paid by government to hunt pirate player and bounty hunters paid by pirates to hunt law-abiding player were split into separate "factions", with separate likes/disliked - unlike vanilla implementation, where they are same "group"...




### Installing

Check:
https://github.com/Cat-Lady/Bounty-Fix/releases

...for latest, pre-packaged version.


**1.** Unpack ``bounty-fix`` to your ES plugins folder. Be sure that you have single ``bounty-fix`` directory inside your plugin folder, containing ``data`` directory. Directory structure should look like:

```(...)/plugins/bounty-fix/(.../data/, and other stuff)```


It **won't** work if the directory structure will be anything like:

```(...)/plugins/Bounty-Fix/bounty-fix/(...)```


**2.** Use files from ``vanilla-files-replace`` directory to replace files in your ES installation's ``/data/`` directory. Overwrite files when prompted.

Do **not** put ``vanilla-files-replace`` inside your ``/data/`` directory - it won't work like that. You need to directly replace approriate files with plugin's ones.

This step is (hopefully) temporary - it works around issue in ES plugin framework, that is worked on already. Hopefully, in future, replacing vanilla data files manually won't be needed (instructions will be updated and new version released, if that ever happen).


## Author

* **Cat Lady**


## License

This project is licensed under the GPL3 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

"Endless Sky" Development Team and Michael Zahniser; For maintaining and creating the game
Anarchist - For doing preliminary tests of NPCs reaction to "marked" and "nemesis" personalities.
Zitchas - for hinting me into right direction, by mentioning the "nemesis" and "marked" NPC personality types
