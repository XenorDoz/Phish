# Phish

### Just a game about fishing with friends

## Table of Contents

1. [What's the game about?](#intro)
2. [What can we do in that game?](#game-desc)
3. [What's in the game?](#game-assets)
   - [Items](#items)
   - [Camp](#camp)
   - [Team progression](#stats)
   - [Mini-games](#qte)
4. [Things in game](#stuff-done)
5. [Roadmap](#roadmap)

<h2 id="intro">What's the game about ?</h2> 

Game is about fishing solo or with friends to win some competition.
It'll have some roguelike or roguelite elements, not sure about which one for now.
You entered a competition to win idk what, and you need to get to fishing to be at the top of the competition, using your fishing pole, or just some random stick, even a broom can work!

<h2 id="game-desc">What's the game about ? (but deeper)</h2>

Main game loop will be fishing / shopping, split on multiple days.  

For now I don't know if I'll make it a tournament or a competition, but main goal is to be the first, and for that you need either to have the best fish (based on rarity, size, and other random stuff), or to have the most money at the end tied with reputation (that will be done with some quests or with xp, rewarding people not only because of luck with fish's rarity, but also quantity or something else).

First day, you'll have some spare money so you can buy stuff for you to fish, but no items at all. You'll be able to buy baits, poles or anything, you can even don't buy anything and try to fish by hand! (I am not responsible if you don't catch anything)

You can play the game either with an end (by winning competition), or by doing an infinite run
Competition wise, I may implement a ranking system to adjust difficulty, that would be some career mode, but you'll still be able to set difficulty by yourself to make individual runs with some other parameters (time in shop/fishing phase, luck, economy..)

### Game loop :

#### Shop

  The shop is a camp where you can find some shopkeepers selling you anything you need to be ready to fish! They'll spawn in random locations around the [camp](#camp), so search for them, you might find some people who'll give you tasks for some rewards. You may also scout the place for some baits or fishing spots, although your time is limited, so don't waste your time for too long!

  You'll have some time before you have to fish to buy some stuff yo help you: [fishing poles](#fishing-poles), [baits](#baits), or [different items](#other-items") that will help you during the day

  This shop is generated at random, but depending on what day and what [reputation](#reputation) or [level](#level) your are. That is also when  you're able to sell your catches from last day, and your only way to make money.

  The shop ends after a certain time limit, after that you can get to the pond and start fishing, or continue what you're doing, but you want to get that few seconds! 


#### Fishing 
  
  You'll have some time to fish and try to either complete tasks that you took during [Preparation](#preparation) phase.  
  
  You can use multiple fishing poles, each may trigger a fish event where you'll have to reel in by completing [easy puzzles or QTEs](#qte), but be warned : the better the fish, the harder/longer it is... Maybe you could ask for some help?

  Fishing will be based on stats given by player perks, [rods](#fishing-poles), [baits](#baits)... But not complicated stuff, it is easy to understand

  If you somehow are out of baits, you can still try with your hands, or search for some baits around you!

<h2 id="game-assets">Anything in the game</h1>

 <h3 id="items">Items available in game </h3>

  <h4 id="fishing-poles"> Fishing poles: </h4>

  <h4 id="baits"> Baits: </h4>
  
  <h4 id="other-items"> Some other stuffs: </h4>

***

<h3 id="camp">The camp</h3>

***

 <h3 id="stats">Team stats</h3>

  <h4 id="level">Team level</h4>

  <h4 id="reputation">Team reputation</h4>

***

 <h3 id="qte">Fishing mini-games</h3>

<h2 id="stuff-done">What's done for now ?</h2>

Nothing :D

<h2 id="roadmap">What's next ?</h2>

Everything :3
### World

- Landscape
  - Biomes
    - Forest
    - Swamp
    - Mountain
    - River
    - Sea
  - Decor elements
    - Rocks
    - Trees
    - Flowers
    - Table/chairs...
  - Pond
    - Vegetation
    - Boats
- Player
    - Editable player model
      - Skin color
      - Clothes
      - Face
      - Hair
      - Size
    - Animations
      - Basic animations
        - Idle
        - Walk
        - Sprint
        - Jump
        - Fishing
        - Talking
      - Emotes
- Camp
  - Shops
  - Tents
    - Small camping ones with cat cushions
    - Big ones
    - Aquariums (fishable)
  - Tables
    - Camping tables w/ chairs
    - Pic-nic tables
      - Can have some food, useful for baits
    - Cat trees
- NPCs
  - Shopkeepers
    - Rods shop
    - Bait shop
    - Task givers (found around the camp)
- Items  
    - Rods  
      - Rods
      - Sticks
      - Broom
      - Rake
    - Baits
      - Worms
      - Food
      - Insects
        - Butterfly
        - Firefly
    - Fishes
      - Sea creatures
        - Crab
        - Lobster
        - Starfish
        - Shrimp
        - Clam
      - Real fishes
        - Sardine
        - Salmon
        - Trout
        - Carp
        - Perch
        - Eel
        - Pike
        - Bass
        - Tuna
        - Herring
        - Catfish
        - Pufferfish
        - Goldfish
        - Guppy
        - Jellyfish
        - Seahorse
      - Big fishes
        - Shark
        - Whale
        - Swordfish
        - Orca
        - Megalogon
        - Kraken
      - Fictive fishes
        - Robot fish
        - Plastic fish
        - Drone fish
        - Submarine fish
        - Sock fish
        - Ice cream fish
        - Top hat fish
        - Glasses fish
        - Mustache fish
        - Bowtie fish
        - Human fish (arms/legs)
      - Fictive big fishes
        - Robot ...
        - Submarine ...
        - Drone ...
      - For all fishes 
        - Glow
        - Ghost
        - Rainbow
        - Black&White 
      - Junk
        - Bottle
        - Can
        - Shoe
        - Sock
        - Paper
        - Placid duck
        - Coin (.01 value)
      - Treasure
        - Necklace
        - Pearl
        - Gem
        - Message in a bottle
    - Random items
      - Shovel
      - Butterfly net
      - Fish traps
      - Fish bag  (upgradeable)
      - Torch
      - Trinkets

### Game mechanics

- Fishing related
  - Rods
  - Fish traps
  - Fish bags
- Shop related
- World related
  - Interactions for items (baits and all)
  - Light
- Game related (competion)
    - Inventory
    - Money
    - Days
    - Difficulty
    - AI scores

## Random ideas
- Every NPC is a cat
- You can fish with anything (for pole or bait), including stick as pole, rock as bait, or ask your friend for some... "help" baiting the fishes

**Storyline :**

You're in a world of cats, and you're fighting with other humans to get adopted by cats.  
This leads to a fishing competition to know who's the best fisherman thus the more suitable to feed your masters.