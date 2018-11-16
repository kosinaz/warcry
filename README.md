# Warcry: Clans and Kingdoms
Warcry: Clans and Kingdoms is an open source real-time fantasy strategy game heavily influenced by Warcraft: Orcs and Humans with the unique goal to reform the very basis of a genre by revisiting the game that founded it.

## Fundamentals of a reformed genre

### Elements of strategy
Ultimately, the elements of strategy should get the most focus, by allowing the players to use them in different ways to acquire victory.
* **Attrition warfare**: This is the way of war most real-time strategy games are forcing on the player. It needs to be there, but its counter-part should get the same-level of attention.
* **Maneuver warfare**: In maneuver warfare, the destruction of certain enemy targets is combined with isolation of enemy forces and the exploitation of enemy weaknesses by movement.
  * *Command centers*: Factions are required to have a designated center of command at all times. By default this would be the town hall, but there is an option to move it to another building or cave and keep the town hall as a fake command center as a deception. The opposing faction's primary goal will be to find this command center with spies, magic, or total annihilation of the base to crush the head of the enemy and scatter their forces.
  * *Leaders*: Every human squad is led by a corporal. The magical gemstones on the corporal's ring grants the lords and the king direct visibility and control over the squad. Every party of orc is led by a slasher. The skulls on the slasher's necklace grants the masters and the warchief direct visibility and control over the party. Ranged units that are close enough will automatically target the leaders of the squad to revoke the commanders' visibility and control over the squad and cripple the squad itself due to the lack of leadership.
  * *Logistical bases*: Almost every structure built by the player has some strategic importance. Losing a lumber mill can hinder ongoing constructions, losing the mines can prevent the training of additional soldiers, losing the farms can lead to lose entire armies due to starvation, but even secondary targets, like bridges and roads can weaken the forces of a nation. Unless the target is not even in use and has been built just to mislead the enemy.
  * *Fire support assets*: Conjurer and warlock towers are not vital targets, but they serve as literal fire support in the battles. These are the places where the rains of fire, the poison clouds, and the various monsters are summoned and controlled. Destroying them won't cripple a nation but can weaken it dramatically. However, it's not an easy task, since the dwellers will rain elemental blasts and firebolts on everyone who dare to oppose them. 
  * *Advantage of terrain*: Dense vegetation can provide concealment for tactical movements such as setting up an ambush. Elevation can provide an advantage to soldiers using projectile weapons. Cliffs can block off certain areas, making it unnecessary to station troops within the inaccessible area. Choke points between a lake or a swamp and hills, muddy areas can be also turned to advantage against the opposing forces. Similar manmade advantages are the walls, towers, bridges and roads. Warcraft 3 has almost all of these elements, but there is no reason why they couldn't be implemented in a game based on Warcraft 1.
  * *Double envelopment*: Encircling the enemy is a usual manouver in every game that features melee units.
  * *Ambush*: Units can hide in certain terrains and structures. In Warcraft 3 Night Elves have a similar ability, but in the current game it could be terrain-specific, not unit-specific.
* **Scorched-earth action**: Every time an army achieves victory, it can keep its structures, people, and the knowledge of magical advancements to gain advantage of them in the future, or destroy some or all of them to prevent the enemy to recover them if it somehow manages to retreive the area in the future.
* **Blockade**: It is not always necessary to destroy the logistical bases of the enemy. Sending patrols to their supply routes is enough to cut off their supplies.
* **Sabotage**: Bribed or mind-controlled enemy units can produce low quality weapons, waste food and resource supplies, set buildings on fire or destroy them completely to weaken the enemy.
* **Raiding**: The goal of raiding is not to capture and hold a location but to do some harm, gather some resources and prisoners then to quickly retreat before the enemy forces are able to respond.
* **Deception**: There are many forms of deception. The most obvious is the invisibility spell of the clerics, but other than this, both factions have the option to move their center of command, to build fake structures, to hide their soldiers.
* **Feint**: There are two types, feint attacks and feint retreats. Both of them are usual tactics of the real-time strategy player.

### Gameplay aspects of strategy
The real-life elements of strategy should be captured through pure strategical gameplay aspects. [Gabriel Wink's Post Human W.A.R : Developing a game in pursuit of untainted strategy](https://www.gamasutra.com/blogs/GabrielWink/20171210/311047/Developing_a_game_in_pursuit_of_untainted_strategy.php) and [Strategic Uncertainty - Keeping Strategy Games Fresh - Extra Credits](https://www.youtube.com/watch?v=PJKTDz1zYzs) will serve as baselines with slight changes to fit the current need. 

* **Chance**: Damages done by the units are fixed, there is no random chance of dodging, no unpredictable outcomes to rule out all the non-strategy factors. However the lack of information is a key aspect of strategy as the elements of strategy clearly shows. Removing the unknown would remove one of the key elements of strategy, uncertainty, the hidden information or unexpected events that make you change your plans and keep the game dynamic. Without uncertainty a strategy game simply becomes a puzzle. So the game won't just keep the unexplored areas, it will also implement the fog of war from the later games of the series and will introduce scouts and spies. Most of the times the players won't know who will be their next enemy or when and where will they have to face them. Orcs and humans have many different clans and kindoms with different warriors and spells focusing on different ways of winning, so the player will never know what to expect until gathered enough information about the current enemy.
* **Speed**: Sometimes strategic decesion making demands quick thinking and acting. However noticing that the enemy forces are incoming and building a wall before they reach the base or training soldiers during a siege to overcome the enemy are events so surreal that they should never happen in a proper real-time strategy game. Therefore only unit movement will be real time, but even those will be much slower to require fast reactions only if they are appropriate.

## Building on a legacy
Though the gameplay itself will take a whole new direction to reach the above-mentioned goals, the aesthetics of the game will try to be as close to the original as possible. Since the original is not yet released as a free game the original sprites cannot be used, but their essence, their main concept can serve as a perfect foundation.

### Remnants of a forgotten world
The alpha of the original game and the concept arts hold a lot of untapped potential that allows us to build a world that could have been. They provide a unique way to stay true to the original but still be different.

The early design documents of the original game contained [many ideas](https://www.codeofhonor.com/blog/the-making-of-warcraft-part-2) that didn't come to fruition due to the strict timeline, like the Mason's Hall, the Dwarven Inn, or the Elven Fletcher. Luckily, there is no reason not to include these supporting buildings in this game one way or another.

In addition to dwarves and elves, lizard men and hobgoblins would have also been part of the game as NPC races like for example ogres. They might get some smaller roles in this game, but the focus will still be on the war of orcs and humans.

Wheeling unit formations and heroes were also cut from the game by the developers, but the implementation of squads with turning rates and a special hero-system will make them a significant part of the current game.

Before the very first playable version of the original game emerged, the idea of the [unit training procedure](https://www.codeofhonor.com/blog/the-making-of-warcraft-part-3) was very different. Initially, it felt more like Populous than Dune 2. Farms generated peasants and peons, and the barracks trained them to soldiers. This game will revisit this idea to emphasize the importance of each unit. The player won't be able to control peasants and peons directly. Overseers will order them to do everything, just like the squad leaders will lead the squads.

### Noughts and crosses
One of the not so hidden easter eggs of the original game is the consistent presence of Xs and Os in units, structures and lore of the races. As it can be read in the manual 'A group of strange, sharp edged buildings was the first sign of any true opposition they
encountered', the symbol of the human race become the square and the X. The cross on the footman's shield, the crossbow of the archer, the cross shape of the town hall, the cross on the top of the human barracks. So the O left for the orcs, that shaped almost all their structures. The current game will try to realize this idea even more.

### Unexpendables
The original game and the sequels placed a great emphasis on the individual units, their personality, their characterization, and encouraged the players to manage them carefully, rather than treating them as expendable hordes. The current game will try to capture that in two ways.

The first will be the hard limit on units. Squads will replace individual units, but most of the battles won't need more than 4 of them to stay true to the [original idea](https://www.codeofhonor.com/blog/the-making-of-warcraft-part-1) that users have to pay attention to their tactical deployments rather than merely gathering a mob and sending them into the fray all at once.

The second way will focus on aesthetics. The goal is to randomly generate a different look for every unit that would identify them and make them more important for the player, but in the meantime keep them readable by giving every unit-type some distinctive feature that will make the individuals of the same unit-type look similar, but every other unit-types look different. The graphical design of the units should not only stay true to the original's bright and cartoony art-style, it should also include the idea of noughts and crosses, and for readability, even their silhouettes should look identical.

### Pseudo-features
As every other game the original also had a lot of elements that were part of certain campaigns but were not accessible by the player in other campaigns or in custom games. Unbuildable structures, untrainable units, untriggerable events. This game will implement all of them.

The player will be able to build and destroy everything that can be seen on the map. Plant trees, build mines, build and upgrade roads and bridges, or destroy them all. 

Every creature will be breedable, every monster will be summonable, and every type of unit will be either trainable or acquirable in some way.

In the narrative of the original game desertion, betrayal, overthrow, imprisonment, and slavery have a big roles, so they have their place in this game as well, directly in the gameplay not just as part of the story.

### What you see is what you get
[The Settlers (2018) redefined WYSIWYG](https://www.thesettlers-alliance.com/en/dev-wysiwyg/) in the context of games. 'We define the information the player can access as information layers. On the first layer, you have the world you play in – WYSIWYG. You see where you can place what building, farm resources, fish, hunt, gather etc. In the other layers you find everything else, you might want to know.'

In the context of Warcraft it means that the proper resources have to be gathered to train and upgrade certain units and build certain structures. The role of the gold mines will be taken over by the quarrys and iron mines.

Another key aspect of the game is that everything is scaled appropriately. If a town hall is big enough to hold dozens of peasants, they will be able to fit in ingame as well. If a mine became big enough to hide a group of brigands, then it will be big enough ingame as well to let the soldiers look for them for minutes. Mining in the depths won't be any different than cutting down trees. Consequently, every structure will be a lot bigger than in the original game.

### Origin of the names
The primary goal of the name selections is to pay homage to the names of the original game.

* **Warcry: Clans and Kingdoms**: The main purpose of the game's title is to be as close to the original as possible to make the connection instantly recognizible, also to be a title that is coming from the franchise itself. Warcry was introduced in Warcraft 3 to add a unique reaction to every unit that has been ordered to attack a hero. Though heroes were only introduced in Warcraft 3, stronger, unique versions of the regular units were already playable in Warcraft 2, and were present as non-playable characters in Warcraft 1. Since similar units will be also added to this game it's a nice way to refer to this new key feature with the title while keeping it close to the original. The original subtitle was highlighting the playable races, so the new subtitle does the same, but in a more subtle way. Though the orcish clans and the kingdoms of the alliance were introduced only in Warcraft 2, there is no reason some similar variety couldn't be introduced in the current game. Hence the eye-catching reference in the subtitle.
* **World of Atser**: The original name that inspired the name, Azeroth, is one of the locations that the Israelites stopped at during their forty years of wandering in the wilderness, Hazeroth, a place in the wilderness. Its transliteration is Chatseroth, that is originated from the word Chatser, meaning settlement, village. By omitting the beginning of the word the same way Blizzard did, but keeping the orginal trasliteration, we get Atser, the name of our Azeroth-inspired brand new world.

## Contributing
Contributions are welcome! Any kind of contributions, pull requests, or bug reports will be reviewed.

## License
This work is licensed under GNU General Public License v3.0.
