Originally Posted at https://forum.minetest.net/viewtopic.php?pid=57041


FILE: my_mobs/Read Me.txt

[wulfsdad  -- January 2013 -- WTFPL -- Version 0.4]

This MOD provides additional mobs to extend upon PilzAdam's Simple Mobs.
<http://minetest.net/forum/viewtopic.php?id=3063>.
It is required for this MOD to work.

It Includes:
		Animals:
			Cow (and milk),
			Rabbit
		Overcooking and using the result to make dye
		Meat spoilage if it remains uncooked
		Cages for Pet Rodents
			They must be fed apples and have a bucket of water available to survive

Raw meet can be preserved through "cheating" or using a refridgerator provided
 by VanessaE's Home Decor Mod <http://minetest.net/forum/viewtopic.php?id=2041>.
You may also disable this feature by adjusting the config option in init.lua 

KNOWN BUGS:
	If you drink milk from a stack of vessels, you will not recieve the empty vessel.



==ETHICAL DISCLOSURE==

The cow texture was created by rinoux <http://minetest.net/forum/profile.php?id=1128>.
I retrieved it from the mobf mod by sapier. <http://minetest.net/forum/viewtopic.php?id=629>.
The cow's dry-up sound came from there too, which reports that the graphic is under WTFPL and
the sound is from <http://commons.wikimedia.org/wiki/Category:Mudchute_Park_and_Farm>
and created by Secretlondon <http://commons.wikimedia.org/wiki/User:Secretlondon>

The rabbit texture was acquired from cornernote's critters modpack.
<http://minetest.net/forum/viewtopic.php?id=3337>
It's README.txt reports:
	Artist: Martin Berube (Available for custom work)
	Iconset Homepage: http://www.graphics-and-desktop-icons.com/animal-icons.html
	License: Freeware
	Commercial usage: Allowed
	Readme file: textures/terms-of-use.txt -->[ I include it, but renamed to rabbit_terms-of-use.txt  ]
	
The current rat-in-cage image is also adapted from one of the critters from the
same source as the rabbit.

The rest of the sounds were found at various locations that I don't recall,
unless otherwise acknowledged in changes.txt. If you own one of them, I will
remove it and delete all copies of it, at you're request.

The unused images were created by me using THE GIMP <http://www.gimp.org/>

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
----Aditional TODO:
--HIGH PRIORITY:
--		support more food, --check balance-- [cheese]
--		add fresh meat and remove rotten meat litter periodically
--MED PRIORITY:
--		add more animals, (chicken/eggs),(pigs/piglets[catchable])
--		fork mobs and add ai tweaks and rebalances, and for animals:
--			breeding & extinction possibility
--		add monsters,
--		cows lift head in water and when walking sometimes
--LOW PRIORITY:
--		add sound effect variety
--		cows "eat" grass
