Nanobots:

* Early version of ghost building construction bots. Allows researching automated construction earlier (for blueprints etc)
* Equip the Nano Emitter and some Nano ammo, make it your selected gun and any ghosts/blueprints within 7.5 tiles of you will be automatically built if you have the items in your inventory.
* Technologies exist to slightly increase the range of your nanobots up to about 15 tiles.
* These early version bots are only capable of building and do not replenish (each Ammo magazine will build 10 items)
* Nanobots do not work inside logistic networks, or personal roboport zones.
* Shooting nanobots wastes nanobotes, Don't shoot nanobots.  Hopefully this will be fixed at somepoint.

---
Ammo Details:

* Nano Constructors - These nanobots will revive ghosts in their range.
* Nano Termites - These nanobots will kill off trees. This process causes the tree to topple over and may damage nearby entities.
* Nano Scrappers - These nanobots will destroy anything in their range that is marked for deconstruction that isn't organic. You will not get any items back.
* Nano Deconstructors - These nanobots have more programing and will return deconstructed items to you. However they are more costly.

---
Late Game Additions:

* Adds 3 new equipment pieces for your armor that enhance your late game experience.
* The Item Programmer will mark all items-on-ground (artifacts, etc) in your personal roboport construction range for deconstruction as long as no enemies are around.
* The Tree Programmer will mark all trees within 10 * (Number of equipped programmers) tiles from you for deconstruction.
* The Unit Launcher will launch Destroys/Defenders/Distractors when enemies get too close to you.

---
Future Plans and Known issues:

* All actions are added to a first in, first out queue system. If a lot of items are queued up (I.E. deconstructing a whole forest). It will take some time before it gets around to doing something else, like building or deconstruction a different area.
* More Personal Roboport Programmers. Upgrade programmer,

Change Log:

* 1.0.0 - Initial Release
* 1.0.1 - Raise event when building entity
* 1.0.2 - Remove Debug line
* 1.0.3 - Better entity-to-item logic
* 1.0.4 - Constructors now do floor tiles, Ghost building is queued, Visual enhancements.  (Scrappers/deconstructors don't do anything yet)
* 1.0.5 - Silly 5 am bobmods typo
* 1.0.6 - Scrappers and Deconstructors added, Small bug fixes/tweaks, Some entites (inserters) are added to the end of the queue.
* 1.0.7 - Hard Crash on invalid ammo
* 1.0.8 - More sanity checks
* 1.0.9 - Remove the shooting event pending more info on crash. Shooting nanobots is now just visual and wastes nanobots. Reverted termite changes
* 1.2.0 - Many changes, Nanobots are now smarter and harder working!  Also many thanks to Articulating for his work on the project!
* 1.2.1 - Compatibility changes for mod-pack maker thingie
* 1.2.2 - Forgot to account for on_config_changed in previous release.  Apologies to all those affected
* 1.2.3 - Unreleased
* 1.3.0 - Technology to increase range, More speed improvements, No longer eats items in inserters hands
* 1.3.1 - Fixes for config refrences
* 1.3.2 - Migration sanity check
* 1.3.3 - Fix disabled personal roboport error, Adjust recipes and add config, Fix healing logic
* 1.3.4 - Fix recipe correctly, Fix logic when network limitations are off, Internal updates
* 1.4.0 - New Icons courtesy of Arch666Angel, New personal roboport unit deployer, automatically deploys follower capsules when near enemies
* 1.4.1 - Fix errors with item_stacks with some mods. Fix raw wood health.
* 1.4.2 - Fix for sound entities keeping chunks active. Adjust projectile acceleration.
* 1.4.3 - Adjust logic checking for ready personal bots.