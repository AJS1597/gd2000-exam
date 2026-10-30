# Exam Review

Answer each question in a few sentences. There are no trick questions and no
single right answer. We are looking for specific reasoning, not definitions
copied from somewhere.

Write your answer under each question, replacing the "(answer here)" line.

## 1. Chess with Hidden Information

1a. Describe a variant of chess with hidden information. You should provide
sufficient information that two people could play your variant.

Start the game the same as normal chess, with the pieces arranged the same. However, the only pieces
visible to the player are ones they are activley attacking with one of their pieces, alongside their own pieces.
This adds fog of war to the game, making it a mixture of trying to remember what was where alongside trying to
control how much of the board you see.

1b. How does your variant change the strategy of chess.

This variant adds more importance to getting out higher value pieces like the queen, bishop, and rook.  As pawns
allow you to only see two squares ahead, there is also much more importance placed on getting them out of the way.
This is because they activley prevent you from gaining more information on your opponents board state.

## 2. Three games

Pick three games we have not covered in class that you didn't mention on the
practice exam. For each, give its core skill (e.g. dexterity, logic/calculation,
social/deception, spatial, chance), its player alignment (1v1, team vs team,
co-op, 1-vs-many, solo), and its information state (perfect or imperfect). Then
say which of the three you would rather design, and why.

Super Mario Oydessy
Core Skill:Dexterity (Platforming)
Player Alignment:solo (Singleplayer)
information state:Imperfect (not all locations of moons are known, need to find them.)

Grand Theft Auto Five
Core Skill: Argubly spatial or logic/calculation (Main game loop is doing crimes and avoiding cops, requiring spacial and logical reasoning.
Player Alignment: Solo in singleplayer, 1-vs-many/FFA in online.
Information State:Perfect (Cops & other important things appear on your minimap, making their location known. Every other detail of the game is largely the same playthrough to playthrough,
as it is story based.)

The Guy Game
Core Skill:Logic (answering trivia questions)
Player Alignment: Solo (Singleplayer trivia game)
Information state: Perfect (You know the question and the 4 answers it could be in, no information is hidden from you)

I would rather design Mario Oydessy, as singleplayer patformers are more my jam when it comes to level design. In specific, collectathons are my
favorite as I love designing large open levels that encourage doubling back on areas to find new secrets. I would not want to design
GTA 5 or the Guy Game, as GTA 5 is much more of a test of how well you can design a fun city to race around. And as for the Guy Game, 
the reason I do not want to develop that game is rather self evident.  (Footnote: for those unfamillar with the guy game look it up, 
it is one of few games that is illegal to own a copy of.)

## 3. The game loop

Pick one of: Counterstrike, Monopoly, Pokemon the trading card game,
Ultimate Chicken Horse, Starcraft, Mario Kart

Describe its game loop: what the player does, what the game updates in
response, and what feedback the player gets. Then remove one step of the loop
and describe what breaks.

Game:Monopoly

To start, the player rolls the dice.  In response, the player is then moved that number of spaces on the board.  Finally, the player is given the 
option to buy it if it is unowned, or is forced to pay rent if it is owned and not foreclosed. If you rolled doubles, This repeats (up to a maxium of three times before you get sent
to jail). Otherwise, the turn is passed to the next player clockwise. If you removed the ability to buy property, no one would be able to own properties, making it so no monopolies could be formed.
Without buying, you break monopoly by turning it Communist.

## 4. Ultimate Chicken Horse

Describe one of the placeable objects in Ultimate Chicken Horse that was
especially annoying or frustrating. What was the item and why did you pick it?

One of the most annoying items was the hockey puck. It shoots out a hockey puck that travels until it hits something, firing it at high speeds. 
This is a pain because it requires both timing the dodge and also keeping track of it, as it fires even when offscreen. This offscreen firing is
prehaps its most annoying element, as if it is far enough away the hockey puck isnt on screen consistently spaced (like how dodgeable projectiles would be in other games),
and instead has a gap meaning you have to rely on sound cues  to gauge when to jump. In a lab setting without sound on, this made it almost impossible to dodge effectivley. 

## 5. Github Workflow

What are the steps of the Github workflow. Why is each step included?

git clone: Clones the repo onto your local machine, allows you to actually modify it.
git add: adds the file after the command to the list of files you want to push to the remote repository, allows you to be selective in which changes you actually want
to take effect.
git commit -m "":Adds a message to your commit, allowing you to specify the actual changes you did in a more in depth way (I.E you add input_handler.gd, and make the commit
message "Updated input handling to account for multi-directional shooting")
git push: Pushes your local changes/commit to the main branch. Allows you to synchronize your changes.

If you are working from a repository you already cloned, then step one is not git clone.
Instead, it is:
git pull: Pulls any changes from the remote repository to your local repository, kind of like cloning the repository except allows you to handle merge conflicts if you've made
changes (or just allows you to stash them for later.)

## 6. Game Recommendation

If you were picking a game to assign for this class during November, what
game would you pick and why? Preferably, something that is a free web game or
cheap / on sale on GoG/Steam.

I would assign Celeste, as it is prehaps the single greatest 2D platformer ever due to its strong narrative and mechanics that keep the game intresting over its many chapters.
it is currently on sale on steam I believe, however I do not know how long that will last. The game itself can get pretty hard, however I beat Farewell and the other hardest levels in the game,
so it is hard for me to judge the difficulty of the final levels in the main story.

## 7. Hearthstone Battlegrounds

Imagine for a moment that there were a faction of slimes, which had two attack
and two health but their stats doubled for each other slime on the same side (so
three slimes would each be 4/4). There would be several slimes each with their
own abilities, across all the card tiers, but their stats would always work this way.

Would that faction be a good design for Battlegrounds? Why or why not?

That would be a badly designed faction for Battlegrounds. Doubling everytime is prehaps the strongest form of power creep you can have, as by round 20 when you have 7-8 of these slimes out you will be dealing 
with slimes that have attack/health values  in the range of 32-64, which would destroy other factions quite easily. If they did the scaling another way (such as the fibbonacci sequence) you could still have that 
effect of compounding growth whilst also not making a totally broken faction. To scale it properly, you'd have to go off what the lowest and highest number of the values would be, which is dependent on the max number
of minions you can upgrade your side to fit (which I do not know, so working off the playtesting we did in class I'd assume around 10-15). 

## 8. Idle / Clicker Game

Come up with an idle / clicker game like Cookie Clicker or Universal Paperclips.

8a. Describe your game.

My ideal clicker game would involve recruiting and managing teams of superheroes. You'd begin with a small roster of 5 D-Listers (If you are famillar with comics, think people who in universe
have the notability of Booster Gold or Blue Beetle), who get sent out on missions. These missions have rewards, and can be done semi-infinitley (the resources go down a little each completion, which 
makes it so you cant just farm the early stage missions forever). Some hero's would have synergies and some would work well against certain villians/on certain missions.  You'd get these heroes in a gacha like system, however
there would be no premium currency as that does not fit the idea of an idle game at all. The main game loop would be assigning heroes to teams -> sending them out until its no longer profitable -> upgrading your heroes/buying new heroes.
This would repeat until you reach the games rebirth, which would be a universe-resetting crisis that requires all your heros to stop it. 

8b. What elements make this style of game fun? How does your game have those
elements?

This style of game is fun when you have upgrades and buyables that make the number get larger faster.  The buyables are the heros, and the upgrades would be their equipment. These games are also fun because of their prestiege systems,
this lets the player start the begining (when things are incredibly fast to progress, more satisfying), whilst also giving them some benefit to keep them hooked after losing all that progress.  In my game, this would be the universe-reseting
crisis's that wipe out your heros. 



