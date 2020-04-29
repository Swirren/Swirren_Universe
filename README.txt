This plugin was made by Gabe Simar, aka Swiren. While Endless Sky and this plugin are open-source, and therefore free for public modifications and distributions, please credit me in any potential usage and/or redistribution of this plugin (it took a lot of work!). Thanks, and enjoy!

Detailed Plugin Explanation: 

	The Tuxen

This plugin introduces a new alien faction called the Tuxen. Through a quick and to-the-point storyline, new outfits and ships are made available to the player. 
Alongside the Tuxen, there are various oddities scattered throughout the galaxy that I added while learning how to code the plugin. 
To start the whole process, land on Letaga in the Sagittarius A system.

	Space Arena

Space Arena is a unique, never-seen-before utilization of Endless Sky mission and fleet mechanics. It consists of a hub world, and three battle systems. To start, land on the Hub world in the Hub World system, located SE of Sagittarius A. There will be a pop-up asking if you'd like to start the arena. If you say yes, you're in for a treat. 

The contents include fighting a certain amount of enemies (listed in 'waves') and attempting to finish them all off. In my personal testing, I used an unmodded Bactrian (ship details listed at the end of this document) and no other ship.

After each wave is defeated, you will return to the hub world to recieve a slight bonus payment and access to the next system. Each system is accessible through the previous, through unlockable hyperspace links. Be sure to bring a ramscoop!

When you have beaten the final wave/boss, return to the hub world to receive a generous payment and other secret bonuses.

Warning: you are only able to use ONE (1) ship for battle. Escorts and/or any other ships cannot come through the wormhole, as the Hub World system wormhole requires a key only accessed through a mission chain; that key is given to your flagship exclusively. With this in mind, prepare your flagship, and get ready to fight!

As of version 1.4.0 of this plugin, this mission sequence is not repeatable due to excess money gain abuse, but as part of the final reward, you gain acces to a special outfitter that sells an allkey outfit; so you may revisit each battle system.


If you'd like to read through the development progress of this plugin, please read changelog.txt.

Again, enjoy the plugin!


	Space Arena Unmodded Bactrian Details:
(Space Arena is completely beatable with this ship. You may have something similar or better, but this is what I used.)
ship Bactrian
	name "Space Arena Bactrian"
	sprite ship/bactrian
		"frame rate" 10.909091
		rewind
	thumbnail thumbnail/bactrian
	attributes
		category "Heavy Warship"
		cost 17600000
		mass 940
		bunks 245
		"cargo space" 530
		drag 16.1
		"engine capacity" 180
		"fuel capacity" 700
		"gun ports" 4
		"heat dissipation" 0.4
		hull 8600
		"outfit space" 740
		"required crew" 70
		shields 17500
		"turret mounts" 6
		"weapon capacity" 300
	outfits
		"Outfits Expansion" 14
		"Quantum Keystone"
		"Liquid Helium Cooler" 3
		"Jump Drive"
		"A865 Atomic Steering"
		"A520 Atomic Thruster"
		"Fuel Pod"
		"Laser Rifle" 15
		"Wanderer Anti-Missile" 2
		"Dual Sunbeam Turret" 3
		"Large Radar Jammer"
		"Blue Sun Reactor"
		"Dark Storm Shielding" 4
	crew 76
	fuel 800
	shields 17500
	hull 8600
	position -1626.9861 71.060655
	engine -18 230 1
	engine 18 230 1
	gun -15 -226
	gun 15 -226
	gun -40 -133
	gun -45 -128
	turret -22 -148 "Wanderer Anti-Missile"
	turret 26 -80 "Wanderer Anti-Missile"
	turret -41 -20 "Dual Sunbeam Turret"
	turret 32 -7 "Dual Sunbeam Turret"
	turret 53 82 "Dual Sunbeam Turret"
	turret -37 186
	fighter -38 -26
		"launch effect" "basic launch"
	fighter 35 36
		"launch effect" "basic launch"
	fighter -47 97
		"launch effect" "basic launch"
	leak leak 30 50
	leak flame 30 80
	leak "big leak" 50 30
	explode "large explosion" 45
	explode "medium explosion" 35
	explode "small explosion" 25
	explode "huge explosion" 30
	"final explode" "final explosion large" 1