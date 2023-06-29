---
published: false
layout: article
category: article
subtitle: 
topic:
date: 2022-04-16
tags: timeline gamedesign
---

# Notes on Game Design

In designing Timeline Game (Timeline for short), a great deal of the inspiration for the mechanics and gameplay came from popular trading card games in the space. In this article, I'll go through the major influences - what was absorbed into the game, what wasn't - and why.

## Magic the Gathering

Richard Garfield's Magic the Gathering is known for many things in the trading card game space. For example, the color wheel, the release cadence which sees numerous sets released each year and really the trading card 'game' concept itself. Prior to Magic the Gathering, trading cards were collectables for fans of something; cards featuring baseball players, popular characters from media and the like. Garfield's development of Magic the Gathering made these collectables something one could actually play and do something with. 

Game design is something that can be discussed endlessly. One seemingly minor change can ripple out and effect nearly all aspects of play, and for Timeline I made some major changes. I'll elaborate further on some of these at a later date so that I can keep things simpler here.

### The Land System + the Color Wheel

The Land system and the corresponding Color Wheel were innovations that still fascinate both players and game designers thirty years out. To introduce this system briefly, Lands (or "mana") are what allow players to play cards from their hand. Lands have a corresponding color, typically, and these colors align to certain cards in Magic. A player has to make a choice of which lands to use in their deck and therefore which cards. This system gets very deep very quickly. It achieves a simple goal of not letting every player use the best cards in every set, as they have to opt in to a specific color scheme. 

Each color has a unique identity and corresponding playstyle. Red is aggressive. An iconic card for Red is "fireball" (a fireball is also the symbol for Red in MTG) which deals damage directly to the opponent. Many red cards are impulsive or "fiery", many red cards are relatively cheap to play and allow the player to start taking action immediately. 

Blue on the other hand has a very different philosophy. Where Red is often "low to the ground" - I.E. relatively easy to play and simple, Blue is operating on a different level and tends to wait and see, or in other words, Blue wants to *react*. Where Red basically always wants to engage, Blue is a color that likes to choose when to engage - Blue wants to fight on its own terms. Blue cards, for example, often feature flying. Flying cards, when attacking, can only be blocked by other creatures that fly - but they can choose to block non-flying creatures when they attack. 

The iconic card for Blue is "Counterspell", which I featured in Timeline as "Ratio". Counterspells stop your opponent from playing the card they want to play. This defines the reactive playstyle - you can only use Counterspell if you chose to leave your lands untapped on your turn (I.E. you didn't play many or any cards) and waited to see what your opponent would play. It's kind of a bluff, as your opponent is aware that you are Blue, and aware that you have lands to play a counterspell, but may or may not choose to play a valuable card to try your bluff. If you manage to counterspell a critical card or two from your opponent, you can neutralize what they are attempting to do and engage on your terms.

In Timeline, despite taking a lot of inspiration from Magic, I chose to remove the land system and the color wheel. These are rabbit-hole style systems that one can easily spend hours optimizing for, and they're also constraints on the game designer. I wanted to make the game accessible for newcomers. Rather than use color restraints, I made factions, many of which interact with each other and encourage you to fill your deck with more cards of that faction. You can mix and match factions like a Magic player might mix and match colors, but you will find that playing away from the natural synergies of the factions will close off some very powerful options from you. There are factions that naturally mesh, like Miladys and Spirits, but there is some room for a Milady and Ape-NFT style deck. There is room to develop an Ape+Spirits style deck. There is room to make a Milady deck that features Network (A.I.) themed cards. There is room to make a Milady deck that overindexes on Milady, Remilio and Radbro, or a deck that focuses on Milady and Spirits, or Milady and BRG FC, and so on. You do, ultimately have to make a choice about which themes you want to play towards, as a potpourri style deck, unless sincerely worked through for a while, will have trouble keeping up with decks that do play towards natural synergies in the factions.

You may be wondering where Lands and mana come into all of this. The land/mana system from Magic is great for pacing and many TCGs have used some variant on it. Ramping up from one Land to a number of them over time allows the game to start slowly and then erupt with players being able to play more powerful cards once they've played some weaker ones first. 

Some games, such as Hearthstone, opt to turn this into a more stable system, sacrificing complexity for a more consistent playing experience. I opted into this as well with Timeline, where each player draws one Poster card each turn, from a separate deck of Poster cards, and stopping once each player has five Posters in play. 

Without the color wheel and lands within the "main deck", I layered complexity back into a now-simpler game through the aforementioned faction synergies and a new system revolving around Quill tokens. Quill tokens are taken from a shared pool of fifteen tokens that sits between the players at the start of each game. Each time a player uses a poster card to contribute to the cost of playing any card, they take possession of a Quill token from the pool. 

Once a player has four Quill tokens, they can put four back into the pool and "disembody" one of their posters, allowing that poster to contribute two posts to the cost of playing a card, rather than one. 

This allows a player to reach beyond the "five posts per turn" limit at their own choosing should they want to play more cards than they would otherwise be able to. This system ripples out across the game as it encourages players to include cards that can be played early on and therefore begin stacking as many Quill tokens as they can per turn. As there are only fifteen tokens, there is a hard limit on how many tokens one player is able to stack. They can also be hoarded as a means of keeping tokens away from their opponent - by not using them, they are not returned to the pool. Should the pool return to zero, and a player chooses to use four of their tokens and thus return them to the pool, upon the next turn it is very likely their opponent will quickly gain possession of all four tokens. It is a kind of metagame which, while relatively simple, can easily turn the tide of a game and demands attention.

The aim of Timeline Game, and in particular the initial release, was to create an enjoyable foundation of a card game which is engaging and somewhat complex on its own, but also simple enough for a beginner to grasp within fifteen minutes of playing. By removing the land system and its corresponding pain points (mana screw/flooding, for example), as well as the color wheel, there are less things for a player to learn, while the Quill system is a simple addition that creates a unique gameplay loop that is foreign to Magic the Gathering and other influences.

### Other Influences from Magic the Gathering

I've mentioned some of the major divergences and tweaking with regard to the Land or Resource system and the Color Wheel, which will be discussed again shortly, but there's still some aspects of MTG influence to talk about here.

The pacing and essentially the "spine" of Timeline Game would not exist without Magic the Gathering. While the Land system was stripped down and smoothened out, then further tweaked with the Quill system, much of the gameflow mirrors a simplified form of Magic the Gathering. 

Hit Points or "Life", like in Magic and many TCGs, are also a core part of Timeline. Each player has twenty-five (five more than in Magic), and when you have zero left, you lose the game. The increase is a balance decision. 

By compressing the total resources (posters) to a cap of five and since you get +1 to your resource pool each turn guaranteed, the game can accelerate and get out of hand quickly. The Quill system also contributes to this ramp-up. 

This is intentional, as Timeline is meant to be accessible and played quickly. The idea is for players to play a number of games back to back, I.E. a best of three or a best of five, and for that to ideally take less than an hour or so once both players know what they are doing. 

With all those factors accelerating play into a more advanced game state compared to most card games, adding five life points makes the game last that little bit longer while still being reasonable.

`Creature Types` also behave similarly to Magic in Timeline Game. The only main difference is that in Timeline, creatures and perpetual effects such as Pinned Posts are classed as Manifestations, as they are 'manifested' by posts from Posters. These manifestations can be searched from decks and there are many cards that interact with certain types of manifestations. For example, the card `Synchronized Crying` can only be played if there are three manifestations with the "CRYING" type - typically associated with Miladys - on the timeline under the player's control.

https://dl.openseauserdata.com/cache/originImage/files/295b2862f78183929441a9e562e0fcc4.png

Other similarities from Magic including the cadence and phases of play. "Summoning Sickness", wherein creatures can't use their abilities or traditionally attack the turn they are played, also exists in Timeline. There is, however, a slight difference in that many cards are balanced around whether their activated abilities cause that manifestation to "tap" for that turn. If they do, it can't attack or defend until their next turn. There are some variations, where this simply limits a creature from attacking on that turn, while they can still defend on the opponent's turn.

Additionally, where Magic has more phases in each turn, Timeline has fewer, but in a similar configuration. The main difference from Magic is that after the Combat Phase ends in Timeline, that player's turn ends. There is no window for taking actions after Combat prior to the turn ending. Cards can, however be played during the Combat phase before damage resolves. 

Last but not least, there is another mechanic inspired in part by Magic the Gathering, "scheduling posts", which allows a player to pre-pay some of the cost of a card in advance so as to play it later at a lower cost. This is inspired both by the concept of scheduling posts on Twitter and e-mail but also the "Foretell" mechanic from Magic the Gathering's Kaldheim expansion. It functions in a very similar way.

### Yu Gi Oh, Discarding the Color Wheel + Fusion Monsters

As mentioned earlier, the Color Wheel is an important part of Magic the Gathering which helps "keep things real" from a perspective of which cards a player can feasibly add to their deck. Without the Color Wheel, players could play all of the best cards basically freely, and the entire point of the Color Wheel and each color's philosophy would kind of go out the window. The Color Wheel effectively makes players choose how they want to play and stick with it. 

WIthout the Color Wheel - and drawing playable cards each turn rather than a land every other~ turn - we have a form of a game that looks similar to Magic in many respects but is quite different. I turned to Yu Gi Oh and their Fusion Monster system in large part to solve the problem of deck construction and to reinsert an element akin to the Color Wheel.

In Yu Gi Oh, Fusion Summons allow a player to play a Fusion Monster card from an "Extra Deck" by activating a set of cards together. For example, by playing the "Polymerization" card - a catalyst for Fusions - and two specific creatures, a player can bring out a special Fusion of the two creatures from their extra deck on-demand. Because this is typically a trade of three cards for one (Polymerization + Two Creatures), that card is "allowed" to be very strong.

I used the same logic in Timeline Game, but without a Polymerization card as a catalyst. Instead, you have to draw all the pieces of the puzzle and play them in order. If you do so, you often get to keep all three. For example, you need one Radbro card and one of five specific Spirit cards to play Radical Spirit. This can be trickier than it sounds, as the best combination cards can be anticipated, and players have a myriad of "answers" to stop you from achieving this: For example, "Ratio" can be played to stop you from playing a critical piece, your opponent can go on the offensive to force you to block with a critical piece (or to take damage elsewhere as a kind of bluff), a board wipe such as "White Hole" which gets rid of all creatures - or just a card like "Delete" or "Void Nymph" which can remove one chosen target.

If you do get to play these combination cards, they are typically just as susceptible to hard removal such as "Delete" or "Void Nymph" as their puzzle pieces were. These end-result combination cards have a lot of power and synergies, however. 

Radical Spirit, for example, with its "Spirit Bomb" ability, can sacrifice one of the Spirit cards used to get it onto the Timeline and deal 3 damage to any target - and also can still attack that turn. Anyone playing around the Radical Spirit card likely has numerous Spirit cards in their deck, meaning Radical Spirit can often go to town on opponents with this ability.




Magic has a number of elements embedded which modify the speed at which a game is played from start to finish.  To begin the game, a player starts with twenty life - a number which also effects the speed it takes each game to conclude - and draws a hand of seven cards. In Timeline Game, due to changes which will be elaborated on later here, we start with twenty-five life, or hit points. We begin each game by drawing five cards instead of seven. 

Within each deck in Magic the Gathering, there are "lands". These make up typically just under half of the cards in each deck. Lands are equivalent to mana or energy. These are the restriction which limit players from simply playing every card in their hand. A card will typically have a bifurcated cost, requiring a specific type of land ("red" or mountain, "white" or plains, for example) and a certain amount of any type of land. 

The land system is a restriction which magnifies the complexity of MTG immensely. By making certain cards unplayable without a corresponding land of that color, players are forced to choose which types of cards and lands they will put into their deck. Players often attempt to play multiple different colors, meaning they will need to draw the corresponding lands during the game. In MTG there are many modifications with regard to lands - I.E., lands that do things beyond just letting you play a certain type of card: there are lands that heal you when played, lands that act as "two" or more colors, with certain drawbacks, and so on. 

As you can see, this system becomes complex. This depth is part of what has made Magic a global success. There's a world of theorycrafting and optimizing that can be done to make your lands fit your deck. 

It also creates a lot of pain points for both new and old players.

There is, for example, a phenomenon known as "mana screw" or, inversely, "mana flooding". Mana screw is when you do not draw the lands needed to play the cards in your hand, or in the case of flooding, when you draw more lands than you need, leaving you with not enough cards to do something with. The color wheel ties into this. While the color wheel keeps players honest and doesn't allow them to use all of the best cards in one deck, trying to push the color wheel and corresponding land system to the limit can create these problems and stop players from having fun. 

For Timeline, I wanted the game to be fun and easy to pick up for a beginner. So I made these systems superfluous. To do that I drew on design decisions made in other games and rather than gating powerful cards behind lands, I gated them behind time and combo-style effects.

Some aspects of the land system were kept in place. In Timeline Game, each turn, for the first five turns, you draw one "poster" card from a poster deck. Posters submit "posts" which can be used to satisfy the requirement of playing *any* card. You can only have a maximum of five posters in play at a time. The game is balanced around this and the quill system, which adds some depth to the now-simplified land/posting system.

### The Quill System and "Disembodied" Posters

Each poster in Timeline Game has an effect which states that whenever this card contributes a post to play another card, that player can take a "Quill Token" from a pool of fifteen Quill Tokens at the side of the table. These quills can be hoarded and used at will, with four Quills being returned to the pool to "disembody" a poster. A disembodied poster can contribute two posts rather than one. With eight quills in a player's possession, for example, a player could use a total of seven posts to play cards. 

This system serves two functions, firstly adding a new strategic element to a familiar MTG-style format, as not only do they amp up a player's potential per turn, quill tokens can be hoarded and therefore denied from the opposing player once the quill pool runs out.

Additionally, they encourage players to have decks which allow them to play cheap cards early and often, so as to acquire more tokens. 

### Yu Gi Oh and Discarding the Color Wheel

With the removal of the color wheel, and a standardized mana curve, some requirements had to be reinserted so that the game didn't become too standardized. Without those barriers in place, players are able to use all of the best cards with no restrictions. Yu Gi Oh's use of cards which are required to play other cards were my solution to the color wheel. 

Rather than 
This works especially well because now that there isn't a 45% chance of a land being the card drawn for each player on any given turn, players now draw "playable" cards which can be built around every turn. 

### Configuring a Domain Purchased Elsewhere


## Purchasing a Custom Domain
 




