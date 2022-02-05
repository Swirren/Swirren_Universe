This plugin was made by Gabe Simar, aka Swiren. While Endless Sky and this plugin are open-source, and therefore free for public modifications and distributions, please credit me in any potential usage and/or redistribution of this plugin (it took a lot of work!). Thanks, and enjoy!

Detailed Plugin Explanation: 

	Drak Zoo

One of this plugin's highlights is an endgame Free Worlds expansion. Remember the Unfettered First Contact mission, about the Drak making the galaxy their zoo? This aspect of the plugin focuses on that. To start the mission sequence, you must have the FW main storyline completed, along with two other requirements. After those are met, land on any human planet.

	The Tuxen

This plugin introduces a new alien faction called the Tuxen. Through a quick and to-the-point storyline, new outfits and ships are made available to the player. 
Alongside the Tuxen, there are various oddities scattered throughout the galaxy that I added while learning how to code missions, outfits, etc.
To start the whole process, land on Letaga in the Sagittarius A system.

	Space Arena

Space Arena is a utilization of Endless Sky mission and fleet mechanics. It consists of a hub world, and eighteen battle systems. To start, land on the Hub world in the Hub World system, located SE of Sagittarius A. There will be a pop-up asking if you'd like to start the arena. If you say yes, you're in for a treat. 

The contents include fighting a certain amount of enemies (listed in 'waves') and attempting to finish them all off. In my personal testing, I used an unmodded tester ship (ship details listed at the end of this document) and no other ship.

After each wave is defeated, you will return to the hub world to recieve a slight bonus payment and access to the next system. Each new system is accessible through the previous system, through unlockable hyperspace links. Be sure to bring a ramscoop!

When you have beaten the final wave/boss, return to the hub world to receive a generous payment and other secret bonuses.

Warning: you are only able to use ONE (1) ship for battle. Escorts and/or any other ships cannot come through the wormhole, as the Hub World system wormhole requires a key only accessed through a mission chain; that key is given to your flagship exclusively. With this in mind, prepare your flagship, and get ready to fight!

As of version 1.4.0 of this plugin, this mission sequence is not repeatable due to excess money gain abuse, but you are still able to revisit the battle systems.


If you'd like to read through the development progress of this plugin, please read changelog.txt.

Again, enjoy the plugin!


	Space Arena Unmodded (Vanilla) Ship Details:
(Space Arena is completely beatable with this ship. You may have something similar or better, but this is what I used (with the help of World Forge). This ship was also made sure to be completely obtainable in a normal vanilla playthrough.)

ship "Model 512"
	sprite "ship/model 512/model 512"
	thumbnail "thumbnail/model 512"
	attributes
		category "Heavy Warship"
		cost 40375000
		mass 1150
		automaton 1
		"cargo space" 107
		drag 17.4
		"engine capacity" 161
		"fuel capacity" 400
		"gun ports" 2
		"heat dissipation" 0.8
		hull 34200
		"outfit space" 994
		ramscoop 3
		"self destruct" 0.8
		shields 86400
		"turret mounts" 7
		"weapon capacity" 440
	outfits
		"Outfits Expansion" 5
		"Jump Drive"
		"Bunk Room"
		"Small Bunk Room"
		"KP-6 Photovoltaic Panel"
		"Large Heat Shunt"
		"Steering (Stellar Class)"
		"Systems Core (Large)"
		"Medium Graviton Thruster"
		"Command Center"
		"Korath Slicer Turret" 3
		"Nanotech Battery"
		"Quantum Shield Generator"
		"Blue Sun Reactor"
		"Red Sun Reactor"
		"Korath Disruptor" 3
		"Tier 3 Anti-Missile"
	crew 7
	fuel 400
	shields 86400
	hull 34200
	engine -145 97 1
	engine 145 97 1
	gun -22 -143
	gun 22 -143
	turret -23 -134 "Tier 3 Anti-Missile"
	turret 91 -102 "Korath Disruptor"
	turret 124 -57 "Korath Slicer Turret"
	turret -130 -33 "Korath Disruptor"
	turret 138 20 "Korath Slicer Turret"
	turret -121 86 "Korath Slicer Turret"
	turret 54 138 "Korath Disruptor"
	explode "medium explosion" 80
	explode "large explosion" 35
	explode "small explosion" 115
	explode "tiny explosion" 160
	"final explode" "final explosion large" 1